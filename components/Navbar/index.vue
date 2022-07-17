<template>
<div class="relative bg-black opacity-90 shadow-2xl sticky top-0 z-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6">
    <div class="flex justify-between items-center py-4 md:justify-start md:space-x-10">
      <div class="flex justify-start lg:w-0 lg:flex-1">
          <img src="https://www.jexactyl.com/assets/images/logo.png" width="32" height="32" />
          <p class="font-bold text-xl ml-1 text-pink-300">Jexactyl</p>
      </div>
      <nav class="flex space-x-5 md:space-x-10">
        <a href="https://docs.jexactyl.com" class="text-sm text-gray-200 hover:text-pink-300">Documentation</a>
        <a href="https://github.com/jexactyl" class="text-sm text-gray-200 hover:text-pink-300">GitHub</a>
        <a href="https://discord.gg/qttGR4Z5Pk" class="text-sm text-gray-200 hover:text-pink-300">Discord</a>
      </nav>
      <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
        <Button title="Get Started" to="https://docs.jexactyl.com" />
      </div>
    </div>
  </div>
</div>
</template>
