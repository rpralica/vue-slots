<template>
  <div>
    <my-buttons>
      <template v-slot:header>
        <h2>Header</h2>
      </template>

      <template v-slot:body>
        <div>
          <h2>Body</h2>
        </div>
      </template>

      <template v-slot:footer>
        <div>
          <h2>Footer</h2>
        </div>
      </template>
    </my-buttons>
  </div>
</template>

<script>
import MyButtons from './components/MyButtons.vue';
export default {
  components: {
    MyButtons,
  },
  data() {
    return {};
  },
};
</script>

<style scoped></style>
