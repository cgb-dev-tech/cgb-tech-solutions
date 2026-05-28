<template>
    <UHeader>
    <template #title>
         <client-only>
            <img :src="isDark.value === 'dark' ? '/images/logo-dark.svg' : '/images/logo-light.svg'" alt="CGB Technical Solutions" class="h-12 w-auto cursor-pointer" @click="$router.push('/')" />
        </client-only>
    </template>
  </UHeader>
</template>
<script setup lang="ts">
const isDark = useColorMode()
</script>