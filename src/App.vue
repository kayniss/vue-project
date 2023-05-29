<template>
  <nav>
    <ul>
      <li><router-link :to="{name: 'home'}">Home</router-link></li>
      <li><router-link :to="{name: 'about'}">About</router-link></li>
      <li><router-link :to="{name: 'linktree'}">Linktree</router-link></li>
    </ul>
    </nav>
    <router-view />
</template>

<script setup>
import { RouterView, RouterLink } from 'vue-router'
</script>
