<script>
import BonusComponent from './components/BonusComponent.vue'

export default {
  data() {
    return {
      message: 'Hello world'
    }
  },
  components: {
    BonusComponent
  }
}
</script>

<template>
  <h2>{{ message }}</h2>
  <BonusComponent />
</template>

<style>
h2 {
  color: palevioletred;
  background-color: paleturquoise;
  padding: 1rem;
  width: fit-content;
}
</style>
