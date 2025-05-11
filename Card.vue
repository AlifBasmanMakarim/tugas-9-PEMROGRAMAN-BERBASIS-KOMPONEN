<script setup>
defineProps({
  title: {
    type: String,
    default: "judul default",
  },
});

defineEmits(["lihat"]);
</script>

<template>
  <div class="card">
    <h2>{{ title }}</h2>
    <p>Menggunakan props, emits dan slot</p>
    <slot>Klik Tombol Disamping</slot>
    <button @click="$emit('lihat')">Lihat</button>
  </div>
</template>

<style></style>
