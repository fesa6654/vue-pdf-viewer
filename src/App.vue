<template>
  <div id="app">
    <button @click="pdfler()">sefa</button>
  </div>
</template>

<script>
import { jsPDF } from "jspdf";

export default {
  mounted() {
    //this.pdfler();
  },
  methods: {
    pdfler() {
      const doc = new jsPDF();

      doc.text("Hello world!", 10, 10);
      doc.save("a4.pdf");
    },
  },
};
</script>

<style>
</style>
