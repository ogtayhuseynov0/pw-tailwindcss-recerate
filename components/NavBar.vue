<template>
  <div
    class="flex items-center justify-between px-4 bg-gray-900 text-gray-600 h-12 border-b-2 border-gray-800"
  >
    <div class="flex items-center">
      <button class="mr-3 text-2xl" @click="$emit('sidenavclick', true)">
        <i class="fas fa-bars"></i>
      </button>
      <span class="font-medium text-gray-300">
        Ogtay Huseynov
      </span>
    </div>
    <div class="flex text-gray-300 flex items-center">
      <span class="mr-3 text-2xl">
        <i class="fas fa-code-branch"></i>
      </span>
      <span>
        10 days ago
      </span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      sidenav: true
    }
  }
}
</script>

<style></style>
