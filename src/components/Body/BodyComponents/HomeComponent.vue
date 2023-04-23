<template>
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hello, World!</div>
                <div class="text-2">THIAGO BARROS</div>
                <div class="text-3">I am <span ref="selfPromotionText"></span></div>
                <div> {{ texto1 }}</div>
                <a href="https://www.linkedin.com/in/thiagobarros95" target="_blank">Talk to me</a>
            </div>
        </div>
    </section>
</template>

<script>
import Typed from 'typed.js';

export default {
    mounted() {
        this.selfPromotionText();
    },
    methods: {
        selfPromotionText() {
            const options = {
                strings: ['Backend Developer', 'Web Developer',],
                typeSpeed: 50,
                backSpeed: 50,
                loop: true
            };
            new Typed(this.$refs.selfPromotionText, options);
        }
    }
}
</script>