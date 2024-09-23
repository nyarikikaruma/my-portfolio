<template>
    <div>
        <v-toolbar title="Karuma Resume" class="text-blue-darken-4 text-h4"
            style="background-color: hsl(247.2deg 51.02% 19.22%); position: sticky; top:0; z-index: 100;">
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
        <aboutme class="pa-2"></aboutme>
        <summary-section class=""></summary-section>
        <work-experience></work-experience>
        <my-education></my-education>
    </div>
</template>

<script setup>
import SummarySection from '~/components/SummarySection.vue';

</script>

<style></style>