<template>
  <img
    class="vuetify-logo"
    alt="Vuetify Logo"
    src="/vuetify-logo.svg"
    :height="_size"
  >
</template>

<script>

export default {
  props: {
    _size: {
      type: Number,
      require: false,
      default: 100,
    }
  },
  data() {
    return {
      
    }
  },
}
</script>


<style>
.vuetify-logo {
  transform: rotateY(560deg);
  animation: turn 3.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
