<script setup lang="ts">
import { defineProps } from 'vue';

defineProps<{
  content: string;
}>();
</script>

<template>
  <!-- 画面下の中央に配置 -->
  <div class="text-xl font-bold absolute bottom-10 text-center">
    {{ content }}
  </div>
</template>