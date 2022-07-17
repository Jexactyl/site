<template>
    <div class="
      ml-8 whitespace-nowrap inline-flex items-center justify-center px-2 py-1
      border border-transparent rounded-md shadow-sm text-base font-medium
      text-white bg-pink-700 hover:bg-pink-800 transition-colors
    ">
      <a :href="to">
        {{ title }}
      </a>
    </div>
</template>

<script>
export default {
  props: [
    'title',
    'to',
  ],
}
</script>