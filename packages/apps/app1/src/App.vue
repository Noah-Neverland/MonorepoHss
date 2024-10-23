<script setup lang="ts">
import {getAge} from '@vueapps/utils/getAge';
// import Button from '@vueapps/components/Button';
import {Button} from '@vueapps/components';

const age = getAge();
console.log('age===', age);
</script>

<template>
  <div>123</div>
  <Button>这是共享的按钮组件</Button>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
