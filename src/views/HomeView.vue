<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <customInput @focus="onFocus" />
  </div>
</template>

<script>
import customInput from '@/components/customInput.vue';

export default {
  name: 'HomeView',
  components: {
    customInput,
  },
  methods: {
    onFocus() {
      console.log('focus');
    },
  },
};
</script>
