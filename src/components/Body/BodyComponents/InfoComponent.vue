<template>
    <div>
        <p v-if="workingWithVue">I'm working with Vue</p>
        <p v-else>Actually working with another JS framework</p>
        <div>
            <button @click="setShowMyFavoritesLanguages">{{ showMyFavoritesLanguagesButtonText
            }}</button>
        </div>
        <div v-show="showMyFavoritesLanguages">
            <ul>
                <li>JAVASCRIPT</li>
                <li>PHP</li>
                <li>CSHARP</li>
                <li>RUST</li>
            </ul>
        </div>
    </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

export default {

    name: 'InfoComponent',
    data() {
        return {
            workingWithVue: true,
            showMyFavoritesLanguages: true,
            showMyFavoritesLanguagesButtonText: 'Show my favorites languages'
        }
    },
    methods: {
        setShowMyFavoritesLanguages() {
            this.showMyFavoritesLanguages = !this.showMyFavoritesLanguages
            if (this.showMyFavoritesLanguages) {
                this.showMyFavoritesLanguagesButtonText = 'Show my favorites languages'
                die()
            }
            this.showMyFavoritesLanguagesButtonText = 'Hide my favorites languages'
        },
    }
}
</script>
