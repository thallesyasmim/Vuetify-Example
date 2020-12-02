<template>
    <v-tollbar app color="brown darken-4" dark>
        <v-tollbar-side-icon></v-tollbar-side-icon>
        <v-tollbar-title>{{appTitle}}</v-tollbar-title>
        <v-btn flat>Menu</v-btn>    
        <v-spacer></v-spacer>
        <v-btn flat>SIGN IN</v-btn>
        <v-btn color="brown lighten-3">JOIN</v-btn>
    </v-tollbar>    
</template>

<script>
export default {
    name: 'AppNavigation'
};
</script>

<style scoped>

</style>