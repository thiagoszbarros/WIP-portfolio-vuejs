<template>
    <HomeComponent />
    <AboutComponent />
    <ProjectsComponent />
    <SkillsComponent />
    <MastermindComponent />
</template>

<script>
import HomeComponent from './BodyComponents/HomeComponent.vue';
import AboutComponent from './BodyComponents/AboutComponent.vue';
import ProjectsComponent from './BodyComponents/ProjectsComponent.vue';
import SkillsComponent from './BodyComponents/SkillsComponent.vue';
import MastermindComponent from './BodyComponents/MastermindComponent.vue';
export default {
    components: {
        HomeComponent,
        AboutComponent,
        ProjectsComponent,
        SkillsComponent,
        MastermindComponent,
    }
}
</script>
