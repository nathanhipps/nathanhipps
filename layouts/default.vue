<template>
  <div class="w-full lg:w-8/12 mx-auto px-12 lg:px-0">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/header'
import Footer from '@/components/footer'

export default {
  components: {
    Header,
    Footer,
  },
}
</script>
