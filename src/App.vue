<template>
  <div>
    <h1>Vue Router 테스트 (TS 버전)</h1>

    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>

    <router-view></router-view>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
nav {
  margin-bottom: 20px;
}
</style>
