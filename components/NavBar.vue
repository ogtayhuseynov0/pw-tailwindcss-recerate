<template>
<div class="flex flex-col h-screen min-h-screen">
  <div class="flex items-center justify-between px-4 bg-gray-900 text-gray-200 h-12">
      <div>
      </div>
      <div>
      </div>
  </div>
  <div class="flex  flex-1 overflow-y-hidden">
    <div class="flex w-64  overflow-y-auto border-r-2" :class="sidenav ? '': 'hidden'">
      
    </div>
    <div class=" flex-1 overflow-y-auto">
asd
    </div>
  </div>
</div>
</template>

<script>
export default {

data () {
  return {
    sidenav: true
  }
}
}
</script>

<style>

</style>