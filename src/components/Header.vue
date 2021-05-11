<template>
    <header class="flex mx-6 mt-4 text-lg lg:text-2xl">
      <p class="marginright">mendingrakitpc.id</p>
          <img class="w-10 lg:w-auto" src="../assets/profile.svg">
    </header>
</template>

<script setup>
import { reactive } from 'vue'

const state = reactive({ count: 0 })
</script>

<style scoped>
    .marginright{
        margin-right: auto;
    }
    header{
        color: #00B570;
    }

</style>