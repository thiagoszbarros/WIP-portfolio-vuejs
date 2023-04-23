<template>
    <body>
        <div>
            <h1>This is the body component</h1>
        </div>
        <div>
            <InfoComponent />
        </div>
    </body>
</template>

<script>
import InfoComponent from './BodyComponents/InfoComponent.vue';
export default {
    name: 'BobyComponent',
    components: {
        InfoComponent,
    }
}
</script>