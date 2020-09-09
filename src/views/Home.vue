<template>
  <div class="home">
    <button @click="pdfac()">sefa</button>
  </div>
</template>

<script>
export default {
  methods: {
    pdfac() {
      this.$router.push("/about");
    },
  },
};
</script>
