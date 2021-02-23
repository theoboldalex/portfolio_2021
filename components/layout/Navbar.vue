<template>
  <nav class="w-full h-20 shadow">
    <div class="mx-6 md:mx-40 h-full flex justify-between items-center">
      <h1 class="font-semibold text-3xl">Alex Theobold</h1>
      <div>
        <NuxtLink to="/portfolio" class="ml-8">
          <button>Portfolio</button>
        </NuxtLink>
        <NuxtLink to="/cv" class="ml-8">
          <button>CV</button>
        </NuxtLink>
        <NuxtLink to="/blog" class="ml-8">
          <button>Blog</button>
        </NuxtLink>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
