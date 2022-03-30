<script setup lang="ts">
</script>

<template>
  <div class="container px-10 pt-5 mx-auto">
    <header class="mb-10">
      <h1 class="font-serif text-3xl font-bold">Super Awesome App</h1>
    </header>
    <main>
      <div class="sm:justify-around sm:flex">
        <div class="w-full sm:w-auto">
          <img
            class="mx-auto border-2 border-pink-400 hover:animate-spin"
            src="http://placekitten.com/100/100"
          />
          <p class="text-center">Good cat</p>
        </div>
        <div class="w-full sm:w-auto">
          <img
            class="mx-auto mt-10 border-2 border-pink-400 sm:mt-auto hover:animate-ping"
            src="http://placekitten.com/100/100"
          />
          <p class="text-center">Okay cat</p>
        </div>
        <div class="w-full sm:w-auto">
          <img
            class="mx-auto mt-10 border-2 border-pink-400 sm:mt-auto hover:animate-bounce"
            src="http://placekitten.com/100/100"
          />
          <p class="text-center">Bad cat</p>
        </div>
      </div>
      <p class="mt-5 font-mono text-green-700">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex nisi cumque
        explicabo quam. Aliquam unde, magni ullam aperiam cumque at odit dolorem
        quis recusandae. Deserunt fuga ad mollitia aliquam. Consectetur.
      </p>
    </main>

    <footer
      class="fixed inset-x-0 bottom-0 w-full text-sm text-center border-0"
    >
      <p>© Kevin Griffin</p>
    </footer>
  </div>
</template>

<style>
</style>
