<template>
  <div>
    <Home />
    <About />
    <Work />
    <Skills />
    <Contact />
  </div>
</template>

<script>
import Contact from '@/components/contact'
import Skills from '@/components/skills'
import About from '@/components/about'
import Home from '@/components/home'
import Work from '@/components/work'

export default {
  components: {
    Contact,
    Skills,
    About,
    Home,
    Work,
  },
}
</script>
