<template>
    <div class="navbar">
        <v-app-bar color="red darken-3" dark>
            <v-app-bar-nav-icon dark></v-app-bar-nav-icon>
            <v-toolbar-title>Ladybug-landing</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn icon>
                <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-magnify</v-icon>
            </v-btn>
        </v-app-bar>
    </div>
</template>

<script>
export default {
    name: "Navbar",
    data(){
        return{

        }
    }
}
</script>

<style>

</style>
