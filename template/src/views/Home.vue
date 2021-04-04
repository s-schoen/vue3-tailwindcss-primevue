<template>
  <div class="">
    <span class="">Welcome to the Vue 3 Template</span>
    <div>
      <Button label="This is a PrimeVue button" />
    </div>
    <div>
      <span>This is a FontAwesome Icon: </span>
      <i class="fas fa-user" />
    </div>
  </div>
</template>

<script>
import Button from "primevue/button";

export default {
  components: { Button },
  setup() {
    return {};
  },
};
</script>

<style scoped></style>
