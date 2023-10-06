<template>
  <div>
    <p>{{ name }}</p>
    <button @click="updateName">이름 바꾸기</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Vue 익히기',
    };
  },

  methods: {
    updateName() {
      this.name = 'Vue 싱글파일 컴포넌트';
    },
  },
};
</script>

<style scoped>
h1 {
  color: red;
}
</style>
