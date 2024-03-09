<template>
    <div class="navbar">
        <div class="logo">
            <h2>Vuebar</h2>
        </div>

        <div class="menu">
            menu
        </div>
        <ul>
            <li v-for="link in Links" :key="link.id">
                <a href={{link.link}}>{{ link.name }}</a>
            </li>
        </ul>
    </div>
</template>

<script>

export default {
    setup() {
        let Links = [
            { name: "Home", link: "#" },
            { name: "About", link: "#" },
            { name: "Work", link: "#" },
            { name: "Contact", link: "#" }
        ]

        return { Links }
    }
}


</script>