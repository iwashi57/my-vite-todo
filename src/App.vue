<script setup>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
</script>

<template>
  <div class="wrap">
    <TheHeader />
    <main class="main">メイン</main>
    <TheFooter />
  </div>
</template>

<style>
@import 'assets/css/destyle.css';

.wrap {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  width: 370px;
  margin: 0 auto;
  font-family: sans-serif;
}

.main {
  flex: 1;
  width: 100%;
}
</style>
