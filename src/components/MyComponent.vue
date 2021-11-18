<template>
  <h1>Hello Vue CLI</h1>
  <input type="text" ref="name" />
  <button @click="handleClick">click me</button>
</template>

<script>
export default {
  methods: {
    handleClick() {
      this.$refs.name.classList.add("active");
      this.$refs.name.focus();
    },
  },
};
</script>