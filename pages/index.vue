<template>
  <div>
    <Home />
    <About />
    <Work />
    <Skills />
  </div>
</template>

<script>
import Skills from '@/components/skills'
import About from '@/components/about'
import Home from '@/components/home'
import Work from '@/components/work'

export default {
  components: {
    Skills,
    About,
    Home,
    Work,
  },
}
</script>
