<template>
  <div class="flex justify-between p-4">
    <Nuxt class="w-1/2" />
    <ul class="w-1/3">
      <li>Bruno Gonzales</li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
    </ul>
  </div>
</template>
<style>
a[href] {
  text-decoration: underline;
  text-decoration-color: aqua;
}
</style>
