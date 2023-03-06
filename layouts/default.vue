<template>
  <slot name="header"></slot>
  <main class="bg-slate-100">
    <section class="container mx-auto">
      <slot />
    </section>
  </main>
  <slot name="footer"></slot>
</template>

<script lang='ts' setup>

</script>

<style lang='less' scoped>

</style>