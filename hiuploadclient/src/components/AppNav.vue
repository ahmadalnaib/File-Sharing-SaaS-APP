<template>
  <header class="flex flex-wrap md:flex-nowrap items-center justify-between mt-6 ">
    <ul class="flex items-center">
      <li><router-link class="text-sm inline-block p-3 text-gray-800" :to="{name:'home'}">Home</router-link></li>
      <li><a class="text-sm inline-block p-3 text-gray-800"  href="">Your files</a></li>
    </ul>

    <ul class="flex items-center">
      <li><router-link class="text-sm inline-block p-3 text-gray-800" :to="{name:'login'}">Login</router-link></li>
      <li><a class="text-sm inline-block p-3 text-gray-800"  href="">Create account</a></li>
    </ul>
  </header>
</template>