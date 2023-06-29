<template>
  <div>
    Hi Hi, 這邊有卡片元件!!
    <br>
    {{ text }}
  </div>
</template>

<script setup>
import { ref } from 'vue';

const text = '我是一段文字!!';

</script>