<template>
  <div>
    <h1>This is Home page</h1>
    <p>{{ name }}</p>
    <JaeWoo />
  </div>
</template>

<script>
import JaeWoo from '@/components/JaeWoo.vue';
export default {
  components: {
    JaeWoo,
  },
  data() {
    return {
      name: 'VueItem',
    };
  },
};
</script>
// scoped 넣어줘야됨.
<style scoped>
h1 {
  color: red;
  font-size: 20px;
}
</style>
