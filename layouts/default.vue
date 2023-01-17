<template>
  <div class="flex flex-grow">
    <Navbar />

    <main class="w-11/12">
      <div class="container">
        <nuxt />
      </div>
    </main>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>


<style>
</style>
