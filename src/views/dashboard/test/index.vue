<template>
  <div id="test">
    <Editor class="editos" :value="value" />
  </div>
</template>

<script setup lang="ts">
import 'bytemd/dist/index.css'
import { Editor, Viewer } from "@bytemd/vue-next";
import { ref } from "vue";

const value=ref("\n" +
  "> 智能科技学院\n")
</script>

<style scoped>

</style>
