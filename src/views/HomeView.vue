<script setup>
import { useStore } from '@/stores'

const { user } = useStore()

console.log(user)
</script>

<template>
  <div class="container mx-auto">
    <h1>Home Page</h1>
    <p class="mt-4 text-gray-600">{{ user?.name }}</p>
  </div>
</template>
@/stores
