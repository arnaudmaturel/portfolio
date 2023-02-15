<template>
  <v-col cols="12">
    <Skills />

    <v-row no-gutters align-content="center">
      <v-col>
        <Studies />
      </v-col>

      <v-col>
        <Experiences />
      </v-col>
    </v-row>

    <Realisations />
  </v-col>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import Skills from '../components/section/Skills.vue';
import Studies from '../components/section/Studies.vue';
import Experiences from '../components/section/Experiences.vue';
import Realisations from '../components/section/Realisations.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    Skills,
    Studies,
    Experiences,
    Realisations
  },
});
</script>
