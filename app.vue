<script setup lang="ts">
useHead({ htmlAttrs: { lang: 'en' } });
</script>

<template>
    <NuxtLayout>
        <NuxtLoadingIndicator color="#000000" />
        <NuxtPage />
        <Toaster />
    </NuxtLayout>
</template>
