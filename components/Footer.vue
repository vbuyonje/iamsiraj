<template>
  <footer id="menu" class="mt-24 md:mt-32 bg-black h-screen md:h-auto md:py-24 flex items-center">
    <div class="container py-16">
      <div class="flex flex-wrap flex-col md:items-end md:flex-row justify-between">
        <div class="text-white">
          <p>Don’t be a stranger</p>
          <h3 class="text-4xl md:text-5xl font-extrabold leading-tight text-white">
            Lets Connect
          </h3>
        </div>
        <div>
          <a
            href="https://twitter.com/kimulisiraj"
            target="_blank"
            title="@kimulisiraj"
            class="opacity-75 hover:opacity-100 duration-300 block mr-6 md:inline-block mt-4 text-lg font-bold md:text-xl text-yellow"
          >
            Twitter
          </a>
          <a
            href="https://github.com/kimulisiraj/"
            target="_blank"
            title="@kimulisiraj"
            class="opacity-75 hover:opacity-100 duration-300 block mr-6 md:inline-block mt-4 text-lg font-bold md:text-xl text-yellow"
          >
            Github
          </a>
          <a
            href="https://dribbble.com/kimulisiraj"
            target="_blank"
            title="dribbble"
            class="opacity-75 hover:opacity-100 duration-300 block mr-6 md:inline-block mt-4 text-lg font-bold md:text-xl text-yellow"
          >
            Dribbble
          </a>
          <a
            href="https://linkedin.com/in/kimulisiraj"
            target="_blank"
            title="linkedin"
            class="opacity-75 hover:opacity-100 duration-300 block mr-6 md:inline-block mt-4 text-lg font-bold md:text-xl text-yellow"
          >
            LinkedIn
          </a>
        </div>
      </div>
      <hr class="border-t-2 border-white opacity-25 mt-10">
      <div class="flex flex-wrap justify-between py-8 md:py-6">
        <div class="w-full md:w-2/3">
          <nuxt-link to="/" class="hover:opacity-100 text-lg text-white opacity-50 block md:inline mt-4 md:mt-0 mr-6">
            Home
          </nuxt-link>
          <nuxt-link to="/about" class="hover:opacity-100 text-lg text-white opacity-50 block md:inline mt-4 md:mt-0 mr-6">
            About
          </nuxt-link>
          <nuxt-link to="/work" class="hover:opacity-100 text-lg text-white opacity-50 block md:inline mt-4 md:mt-0 mr-6">
            Work
          </nuxt-link>
          <nuxt-link to="/blog" class="hover:opacity-100 text-lg text-white opacity-50 block md:inline mt-4 md:mt-0 mr-6">
            Blog
          </nuxt-link>
        </div>
        <div class="opacity-50 mt-16 md:mt-0 text-white opacity-50 text-sm hidden md:block">
          All Rights Reserved 2020
        </div>
      </div>
    </div>
  </footer>
</template>
