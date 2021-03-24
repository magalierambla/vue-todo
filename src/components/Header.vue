<template>
  <div>
    <img :alt="logoAlt" :src="logoSrc" />
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    logoSrc: {
      type: String,
      required: true,
    },
  },
  computed: {
    logoAlt() {
      return "Vue Alt";
    },
  },
};
</script>

<style></style>
