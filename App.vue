<script setup>
import Card from "./components/Card.vue";

const Melihat = () => {
  alert("Berpindah ke halaman lain");
};
</script>

<template>
  <Card title="Project Baru" @lihat="Melihat" />
</template>
