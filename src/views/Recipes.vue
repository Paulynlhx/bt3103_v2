<template>
<div id="bg">
    <div data-app>
        <Recipe/>
    </div>
</div>
</template>

<script>
import Recipe from "@/components/Recipes.vue"
export default {
    name : "Recipes",
    components: {
        Recipe
    }
}
</script>

<style scoped>
#bg{
    background-color: #FFF8EF;
    width: 100%;
    height: 100vh;
}
</style>