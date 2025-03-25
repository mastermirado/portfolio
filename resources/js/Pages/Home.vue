<template>
    <BaseLayout>
        <template #app-bar>
            <Header></Header>
        </template>

        <template #default>
            <TwoColumn></TwoColumn>
        </template>
    </BaseLayout>
</template>

<script setup>
import Header from '@/Components/Header.vue';
import TwoColumn from '@/Components/TwoColumn.vue';
import BaseLayout from '@/Layouts/BaseLayout.vue';
</script>