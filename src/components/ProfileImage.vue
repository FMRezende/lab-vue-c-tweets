<script>
export default {
    name: 'ProfileImage',
    props: {
        image: {
            type: String,
            required: true,
        },
    },
}
</script>

<template>
    <img :src="image" class="profile" alt="profile"/>
</template>
