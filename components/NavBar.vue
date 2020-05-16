<template>
  <div
    class="flex items-center justify-between px-4 bg-gray-900 text-gray-600 h-12 border-b-2 border-gray-800"
  >
    <div class="flex items-center">
      <button class="mr-3 text-2xl" @click="$emit('sidenavclick', true)">
        <i class="fas fa-bars text-2xl"></i>
      </button>
      <span class="font-medium text-gray-300">
        Ogtay Huseynov
      </span>
    </div>
    <div class="flex text-gray-300">
      <span
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          class="h-6 w-6 get fill-current mr-3"
        >
          <path
            class="heroicon-ui"
            d="M6.3 12.3l10-10a1 1 0 011.4 0l4 4a1 1 0 010 1.4l-10 10a1 1 0 01-.7.3H7a1 1 0 01-1-1v-4a1 1 0 01.3-.7zM8 16h2.59l9-9L17 4.41l-9 9V16zm10-2a1 1 0 012 0v6a2 2 0 01-2 2H4a2 2 0 01-2-2V6c0-1.1.9-2 2-2h6a1 1 0 010 2H4v14h14v-6z"
          /></svg
      ></span>
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
