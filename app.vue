<!-- <script lang="ts" setup>
  useHead({
    title: 'Home',
    meta: [
      { 
        name: 'description', 
        content: 'Home Nuxt 3, IT Genius Engineering' 
      },
      {
        name: 'keywords',
        content: 'Home, Nuxt 3, Learning Nuxt 3'
      },
    ],
  })
</script>

<template>
  <div class="flex items-center justify-center h-screen">
    <h1 class="text-3xl font-bold text-purple-600 animate-bounce">
      <Icon name="icon-park:home-two"></Icon> 
      <Icon name="ic:twotone-wb-sunny"></Icon>
      Hello Nuxt 3
    </h1>
</div>
</template> -->


<template>
  <Head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Itim&family=Sarabun&display=swap" rel="stylesheet">
  </Head>

  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>

</template>
