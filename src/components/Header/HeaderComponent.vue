<template>
    <header>
        <h1>This is the header component</h1>
        <div><NavbarComponent /></div>
        <ProfilePictureComponent />
    </header>
</template>

<script>
import NavbarComponent from './HeaderComponents/NavbarComponent.vue';
import ProfilePictureComponent from './HeaderComponents/ProfilePictureComponent.vue';

export default {
    name: 'HeaderComponent',
    components: {
        NavbarComponent,
        ProfilePictureComponent,
    }
}
</script>
