<template>
    <div>
        <picture><img v-bind:src="avatar" v-bind:alt="description"></picture>
    </div>
</template>

<script>
export default {
    name: 'ProfilePictureComponent',
    data() {
        return {
            avatar: '/images/avatar.png',
            description: 'avatar profile image description',
        }
    },
}
</script>