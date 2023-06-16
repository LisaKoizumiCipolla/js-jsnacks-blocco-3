<template>
    <ul>
        <NavLink v-for=" linkObj in linksList"
            :linkElement="pastaObj" 
        />
    </ul>
</template>

<script>
import NavLink from './NavLink.vue';

    export default{
        data() {
            return{
            linksList : [
                "uno",
                "due",
                "tre",
                "quattro"
            ]

            }
        },
        components:{
            NavLink
        }
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