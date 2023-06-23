<script setup>
  const config = useRuntimeConfig()
</script>

<template>
  <div>
    Revelo App, rodando em: {{ config.app.env }}
  </div>
</template>
