<template>
  <div>
    <div class="flex flex-col h-screen min-h-screen bg-gray-300">
      <NavBar @sidenavclick="sideClick" />
      <div class="flex  flex-1 overflow-y-hidden">
        <transition name="slide">
          <div
            v-if="sidenav"
            :class="sidenav ? 'block' : ''"
            class="flex w-64 hidden md:block overflow-y-auto border-r-2 bg-gray-900"
          >
            <SideLinks />
          </div>
        </transition>

        <div class=" flex-1 overflow-y-auto">
          <nuxt />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from '../components/NavBar'
import SideLinks from '../components/SideLinks'
export default {
  components: { SideLinks, NavBar },
  data() {
    return {
      sidenav: true
    }
  },
  methods: {
    sideClick() {
      this.sidenav = !this.sidenav
    }
  }
}
</script>
<style>
.slide-leave-active,
.slide-enter-active {
  transition: 0.3s;
}
.slide-enter {
  transform: translate(-100%, 0);
}
.slide-leave-to {
  transform: translate(-100%, 0);
}
</style>
