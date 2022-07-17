<template>
    <div v-if="loading" class="top-0 left-0 flex items-center justify-center w-full h-full rounded flex-col z-40 fixed bg-black opacity-80">
        <div class="loading"></div>
    </div>
</template>

<script src="@/components/Spinner/script.js"></script>
<style scoped src="@/components/Spinner/style.css"></style>