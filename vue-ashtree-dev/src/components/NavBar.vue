<template>
    <div class="NavBar fixed-top d-flex justify-content-between align-items-center p-3">
    <div>
        <h1 class="m-3 text-white">Ashtree Dev</h1>
    </div>
    <div class="d-flex">
        <RouterLink class="p-3 h2 nav-item" to="/">Home</RouterLink>
        <RouterLink class="p-3 h2 nav-item" to="/">Game Dev</RouterLink>
        <RouterLink class="p-3 h2 nav-item" to="/">Web Dev</RouterLink>
    </div>
</div>

</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { useRouter } from 'vue-router';

export default defineComponent({
name: 'Navbar',

data() {
    return {
    
    };
},
methods: {
    
},
});
</script>

<style scoped>

.nav-item {
    text-align: center;
    color: rgb(222, 230, 230);
    font-weight: 200;
    text-decoration: none;
}

.NavBar {
    background-color: rgb(38, 39, 53);
}

</style>
  