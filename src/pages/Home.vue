<template>
    <span>
        <AppNavigation />
        <HomeHero />
        <HomeDetails />
    </span>
</template>

<script>
    import AppNavigation from '../components/AppNavigation.vue'; // Component Navigation
    import HomeHero from '../components/HomeHero.vue';
    import HomeDetails from '../components/HomeDetails.vue'; 

    export default {
        name: 'Home',
        components: {
            AppNavigation,
            HomeHero,
            HomeDetails
        }
    };
</script>