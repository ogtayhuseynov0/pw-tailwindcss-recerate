<template>
  <div class="flex flex-col mr-4 ml-1 w-full mt-4 text-gray-600">
    <div
      class="flex items-center hover:bg-gray-800 rounded p-2 cursor-pointer hover:text-gray-300"
    >
      <div class="w-1/6 text-2xl ">
        <i class="fas fa-info-circle flex-grow"></i>
      </div>
      <div class="w-5/6 font-medium">
        <span>About</span>
      </div>
    </div>
    <div
      class="flex items-center hover:bg-gray-800 rounded p-2 cursor-pointer hover:text-gray-300"
    >
      <div class="w-1/6 text-xl">
        <i class="fas fa-briefcase flex-grow"></i>
      </div>
      <div class="w-5/6 font-medium">
        <span>Portfolio</span>
      </div>
    </div>
    <div
      class="flex items-center hover:bg-gray-800 rounded p-2 cursor-pointer hover:text-gray-300"
    >
      <div class="w-1/6 text-xl">
        <i class="fas fa-brain flex-grow"></i>
      </div>
      <div class="w-5/6 font-medium">
        <span>Skills</span>
      </div>
    </div>
    <div
      class="flex items-center hover:bg-gray-800 rounded p-2 cursor-pointer hover:text-gray-300"
    >
      <div class="w-1/6 text-xl">
        <i class="fas fa-id-card flex-grow"></i>
      </div>
      <div class="w-5/6 font-medium">
        <span>Contacts</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SideLinks'
}
</script>
