<template>
  <div :id="titleToLower" class="min-h-screen">
    <div class="border-b-2 border-gray-700 py-6 flex justify-between">
      <h2 class="text-3xl">{{ title }}</h2>
      <a v-scroll-to="{ el: '#header' }" class="mt-4" href="#">
        <div class="flex">
          <Up class="mr-2 w-6" />
          <span>back</span>
        </div>
      </a>
    </div>
    <slot />
  </div>
</template>

<script>
import Up from '@/components/icons/up'
export default {
  components: { Up },
  props: {
    title: {
      type: String,
      required: true,
    },
  },
  computed: {
    titleToLower() {
      return this.title.toLowerCase()
    },
  },
}
</script>
