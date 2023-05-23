<script>
export default {
    name: "AppHeader",
}
</script>

<template>
    <header>
        <div class="container d-flex justify-between align-items-center m-auto">
            <div class="logo">
                Giovanni Bassani
                <div class="under-logo">
                    Jr Full Stack Developer
                </div>
            </div>

            <ul class="d-flex">
                <li>Portfolio</li>
                <li>Chi sono</li>
                <li>Blog</li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss">
@use "../styles/partials/variables" as *;

header {
    width: 100%;
    height: $header-height;
    background-color: $col-primary;
    color: $col-white;

    position: fixed;
}

.container {
    height: 100%;
}

.logo {
    font-size: 2.5rem;
    position: relative;

    text-shadow: 0 0 5px #ffffff50;

    .under-logo {
        font-size: 0.8rem;
        position: absolute;
        bottom: 0.2rem;
        right: -2rem;
        transform: rotate(-4deg);

        color: $col-secondary;
        text-shadow: none;
        border-bottom: 1px dotted $col-secondary;
    }
}

li {
    padding-left: 1rem;
}
</style>
