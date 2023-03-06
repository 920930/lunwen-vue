<template>
  <header class="fixed w-full h-16 shadow bg-slate-900">
    <section class="container mx-auto h-16 flex justify-between items-center text-slate-300">
      <NuxtLink to="/" class="font-bold text-4xl">Blog</NuxtLink>
      <nav class="space-x-10 flex">
        <div class="relative text-slate-600">
          <input type="text" class="rounded pl-3 pr-9 h-7 text-sm w-56" placeholder="搜索" />
          <aside class="absolute right-2 top-1/2 text-sm -translate-y-1/2">搜索</aside>
        </div>
        <NuxtLink to="/">首页</NuxtLink>
        <NuxtLink to="/">分类</NuxtLink>
        <NuxtLink to="/">留言</NuxtLink>
        <NuxtLink to="/">关于我</NuxtLink>
      </nav>
    </section>
  </header>
  <p class="h-16"></p>
</template>

<script lang='ts' setup>
import { ref } from 'vue'

</script>

<style lang='scss' scoped>

</style>