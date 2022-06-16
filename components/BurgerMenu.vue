<template>
  <nav class="sm:hidden flex flex-col absolute w-full">
    <div class="flex justify-end w-full">
      <button
        class="flex flex-col space-y-1 w-[50px] h-[50px] justify-center items-center"
        @click="toggleMenu"
      >
        <div v-if="!isMenuOpen" class="w-7 h-1 bg-gray-600"></div>
        <div v-if="!isMenuOpen" class="w-7 h-1 bg-gray-600"></div>
        <div v-if="!isMenuOpen" class="w-7 h-1 bg-gray-600"></div>
        <svg
          v-else
          class="h-8 w-8 gray-600"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <line x1="18" y1="6" x2="6" y2="18" />
          <line x1="6" y1="6" x2="18" y2="18" />
        </svg>
      </button>
    </div>
    <ul
      v-if="isMenuOpen"
      class="w-screen h-screen bg-green-700 flex flex-col items-center p-9"
    >
      <li class="mb-6">
        <NuxtLink to="/work">Our work</NuxtLink>
      </li>
      <li class="mb-6"><NuxtLink to="/about">About</NuxtLink></li>
      <li class="mb-6"><NuxtLink to="/resources">Resources</NuxtLink></li>
      <li class="mb-6"><NuxtLink to="/blog">Blog</NuxtLink></li>
      <li class="mb-6"><NuxtLink to="/get-involved">Get involved</NuxtLink></li>
      <li class="mb-6"><NuxtLink to="/contact">Contact</NuxtLink></li>
      <li class="mb-6"><NuxtLink to="/donate">Donate</NuxtLink></li>
    </ul>
  </nav>
</template>

<script lang="ts">
export default defineComponent({
  setup() {},
  data() {
    return {
      isMenuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    },
  },
});
</script>
