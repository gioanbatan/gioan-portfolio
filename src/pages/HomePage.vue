<script>
export default {
    name: "HomePage",
}
</script>

<template>
    <main class="container m-auto">
        <h1>Bassani Giovanni - "forty-year-old" JUNIOR Web Developer</h1>
        <h3>
            Benvenut* sul mio sito!
        </h3>
        <div class="wip">WORK IN PROGRESS</div>
    </main>
</template>

<style lang="scss">
@use "../styles/partials/variables" as *;

main {
    padding-top: calc($header-height + 1rem);
}

.wip {
    text-align: center;
    color: $col-white;
    font-size: 3rem;
    font-family: 'Press Start 2P', cursive;
    border: 2px dotted $col-white;
    transform: rotate(-15deg);
    text-shadow: 0 0 30px #ffffff60;
}
</style>