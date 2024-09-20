<template>
    <div>
        <v-toolbar title="George Karuma">
            <v-btn color="blue-darken-4" class="ma-2 pa-2">
                About me
            </v-btn>
            <v-btn color="blue-darken-4" class="ma-2 pa-2">
                Skillset
            </v-btn>
            <v-btn color="blue-darken-4" class="ma-2 pa-2">
                Projects
            </v-btn>
            <v-btn color="blue-darken-4" class="ma-2 pa-2">
                Education
            </v-btn>
            <v-btn color="blue-darken-4" class="ma-2 pa-2">
                Experience
            </v-btn>
        </v-toolbar>
        <hero-section></hero-section>
        <aboutme></aboutme>
        <summary-section></summary-section>
    </div>
</template>

<script setup>
import SummarySection from '~/components/SummarySection.vue';

</script>

<style></style>