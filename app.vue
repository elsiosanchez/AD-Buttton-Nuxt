<template>
  <div>
    <!-- <NuxtWelcome /> -->
    <h1>
      <ADButton :txt="'alo'" />
    </h1>
  </div>
</template>

<script>
import ADButton from './components/ADButton.vue';

export default {
  name: 'App',
  components: {
    ADButton,
  },
};
</script>
