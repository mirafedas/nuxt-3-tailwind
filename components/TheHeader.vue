<template>
  <header class="flex items-center justify-between px-4 py-2 bg-green-700">
    <div class="flex items-center">
      <a href="/" class="inline-block mr-2">
        <img
          class="block"
          width="40"
          height="40"
          src="https://images.vectorhq.com/images/previews/a2e/food-not-bombs-logo-142141.png"
          alt="a hand holding a carrot"
        />
      </a>
      <p>Food Not Bombs Wrocław</p>
    </div>

    <ul class="hidden sm:flex items-center justify-between">
      <li class="mr-2">
        <NuxtLink to="/work">Our work</NuxtLink>
      </li>
      <li class="mr-2"><NuxtLink to="/about">About</NuxtLink></li>
      <li class="mr-2"><NuxtLink to="/resources">Resources</NuxtLink></li>
      <li class="mr-2"><NuxtLink to="/blog">Blog</NuxtLink></li>
      <li class="mr-2"><NuxtLink to="/get-involved">Get involved</NuxtLink></li>
      <li class="mr-2"><NuxtLink to="/contact">Contact</NuxtLink></li>
      <li><NuxtLink to="/donate">Donate</NuxtLink></li>
    </ul>
  </header>
</template>
