<template>
  <div class="flex items-center flex-col w-1/2 lg:w-1/3 xl:w-1/4 mb-12">
    <slot />
    <p class="text-sm text-center">
      <span class="block text-lg font-bold italic">{{ title }}</span>
      {{ description }}
    </p>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: '',
    },
    description: {
      type: String,
      default: '',
    },
  },
}
</script>
