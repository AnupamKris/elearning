<template>
  <div
    class="flex justify-center items-center fixed top-0 w-full h-20 text-gray-100"
  >
    <div class="flex justify-between items-center max-w-[1200px] w-full px-10">
      <div class="left">
        <div class="logo text-2xl">Redlight</div>
      </div>
      <div class="center flex gap-5 text-md">
        <NuxtLink class="hover:text-red-600" to="/">Home</NuxtLink>
        <NuxtLink class="hover:text-red-600" to="/about">About</NuxtLink>
        <NuxtLink class="hover:text-red-600" to="/courses">Courses</NuxtLink>
        <NuxtLink class="hover:text-red-600" to="/contact">Contact Us</NuxtLink>
      </div>
      <div class="">
        <Button>
          <NuxtLink to="/login">Join Us</NuxtLink>
        </Button>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
