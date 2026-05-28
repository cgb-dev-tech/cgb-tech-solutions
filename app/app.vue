<template>
  <UApp>
    <UMain>
      <NuxtLayout>
        <Navbar />
        <NuxtPage />
        <Footer />
      </NuxtLayout>
    </UMain>
  </UApp>
</template>
<script setup lang="ts">
useSeoMeta({
  title: 'CGB Tech Solutions - Custom Software Development',
  ogTitle: 'CGB Tech Solutions - Custom Software Development',
  description: 'CGB Tech Solutions is a software development company specializing in custom web and mobile applications, cloud solutions, and IT consulting services. We help businesses leverage technology to achieve their goals.',
  ogDescription: 'CGB Tech Solutions is a software development company specializing in custom web and mobile applications, cloud solutions, and IT consulting services. We help businesses leverage technology to achieve their goals.',
  ogImage: '/cgb-logo-icon-only.png',
  twitterCard: 'summary_large_image',
})
</script>
