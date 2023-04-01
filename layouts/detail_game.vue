<template>
    <header>
        <nav>
            <ul>
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><nuxt-link to="/about">About</nuxt-link></li>
                <li><nuxt-link to="/games">Games</nuxt-link></li>
            </ul>
        </nav>
    </header>

    <div>
        <slot />
    </div>
</template>



<style scoped>
    h2 {
        color: red;
    }
</style>