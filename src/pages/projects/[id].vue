<template>
  <h1>Project {{ projectId }}</h1>
</template>

<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
const projectId = route.params?.id
</script>

<style></style>
