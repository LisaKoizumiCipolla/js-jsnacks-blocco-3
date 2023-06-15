<template>
    <ul>
        <li v-for="link in links">
            {{ link }}
        </li>
    </ul>
</template>

<script>
    export default{
        data() {
            return{
            links : [
                "uno",
                "due",
                "tre",
                "quattro"
            ]

            }
        },
    }
</script>

<style lang="scss">

ul{
    list-style-type: none;
    display: flex;

    li{
        margin-left: 2rem;
        color: black;
        font-size: 5rem;

        &:hover{
            color: magenta;
            cursor: pointer;
        }
    }
}

</style>