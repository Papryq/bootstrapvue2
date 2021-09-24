<template>
  <div class="home">
    <TheNavbar />
    <TheShowcase />
    <TheBoxes />
    <HealthSection />
    <WorkoutSection />
    <TheQuestions />
    <TheTrainers />
    <TheNewsletter />
    <TheModal />
    <TheFooter />

  </div>
</template>

<script>
// @ is an alias to /src
import TheNavbar from '@/components/TheNavbar.vue'
import TheShowcase from '@/components/TheShowcase.vue'
import TheBoxes from '@/components/TheBoxes.vue'
import HealthSection from '@/components/HealthSection.vue'
import WorkoutSection from '@/components/WorkoutSection.vue'
import TheQuestions from '@/components/TheQuestions.vue'
import TheTrainers from '@/components/TheTrainers.vue'
import TheNewsletter from '@/components/TheNewsletter.vue'
import TheModal from '@/components/TheModal.vue'
import TheFooter from '@/components/TheFooter.vue'




export default {
  name: 'Home',
  components: {
    TheNavbar,
    TheShowcase,
    TheBoxes,
    HealthSection,
    WorkoutSection,
    TheQuestions,
    TheTrainers,
    TheNewsletter,
    TheModal,
    TheFooter
  },
}
</script>

<style>
body::before {
  display: block;
  content: '';
  height: 50px;
}


@media(min-width: 768px) {
  .news-input {
    width: 50%;
  }
}

</style>
