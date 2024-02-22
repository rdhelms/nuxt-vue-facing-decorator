<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script lang="ts">
import { Component, Vue, toNative } from 'vue-facing-decorator';

@Component
class MainApp extends Vue {}

export default toNative(MainApp);
</script>
