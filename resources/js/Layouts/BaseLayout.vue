<template>
    <v-layout>
        <v-app-bar>
            <slot name="app-bar"></slot>
        </v-app-bar>

        <v-main>
            <v-container>
                <slot></slot>
            </v-container>
        </v-main>
    </v-layout>
</template>

<script setup>

</script>