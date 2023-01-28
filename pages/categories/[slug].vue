<script setup lang="ts">

    // รับค่า params จาก url
    const params = useRoute().params

    // call wp api
    const { data: categories } = await useWpApi().getCategory(params.slug as string)
    const category = categories.value?.[0]
    console.log(category)

    // read post in category
    // const { data: posts } = await useWpApi().getPosts(category.id)

    useHead({
        title: `Archive: ${category?.name}`,
        meta: [
            {
                name: "description",
                content: `Category ${params.slug}`,
            },
        ],
    })

</script>

<template>
    <div>

    </div>
</template>


<style scoped>

</style>