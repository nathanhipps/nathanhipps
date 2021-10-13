<template>
  <header id="header">
    <div class="flex justify-between items-center h-20">
      <div class="text-2xl text-blue-400 font-bold">
        <Logo class="h-12 fill-current" />
      </div>
      <div>
        <ul class="flex items-center space-x-6 text-blue-400">
          <li>
            <a
              v-scroll-to="{ el: '#about' }"
              class="hover:underline hover:text-blue-300"
              href="#"
              >About</a
            >
          </li>
          <li>
            <a
              v-scroll-to="{ el: '#work' }"
              class="hover:underline hover:text-blue-300"
              href="#"
              >Work</a
            >
          </li>
          <li>
            <a
              v-scroll-to="{ el: '#skills' }"
              class="hover:underline hover:text-blue-300"
              href="#"
              >Skills</a
            >
          </li>
          <li>
            <a
              v-scroll-to="{ el: '#contact' }"
              class="hover:underline hover:text-blue-300"
              href="#"
              >Contact</a
            >
          </li>
          <li>
            <a href="https://www.linkedin.com/in/nathan-hipps-97a814184/">
              <Linkedin class="w-4 fill-current" />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
import Logo from '@/components/icons/logo'
import Linkedin from '@/components/icons/linkedin'

export default {
  components: {
    Logo,
    Linkedin,
  },
}
</script>
