<template>
  <Section title="Skills" class="mt-96">
    <div class="flex flex-wrap mt-12">
      <Skill title="PHP" description="Programming Language">
        <Php class="h-16 mb-4" />
      </Skill>

      <Skill title="Laravel" description="Web Framework">
        <Laravel class="h-16 mb-4" />
      </Skill>

      <Skill title="Javascript" description="Programming Language">
        <Javascript class="h-16 mb-4" />
      </Skill>

      <Skill title="Vue" description="Front End Framework">
        <Vue class="h-16 mb-4" />
      </Skill>

      <Skill title="Nuxt" description="SSR / SSG Vue Front End Framework">
        <Nuxt class="h-16 mb-4" />
      </Skill>

      <Skill title="Inertia" description="Front End / Back End SPA Adapter">
        <div class="h-16 mb-4">
          <Inertia class="w-40 mb-4 mt-3" />
        </div>
      </Skill>

      <Skill title="PostgreSQL" description="Relational Database">
        <Postgres class="h-16 mb-4" />
      </Skill>

      <Skill title="MySQL" description="Relational Database">
        <Mysql class="h-16 mb-4" />
      </Skill>

      <Skill title="HTML" description="Programming Language">
        <Html class="h-16 mb-4" />
      </Skill>

      <Skill title="CSS" description="Programming Language">
        <Css class="h-16 mb-4" />
      </Skill>

      <Skill title="Tailwind" description="CSS Framework">
        <Tailwind class="h-16 mb-4" />
      </Skill>
    </div>
  </Section>
</template>

<script>
import Javascript from '@/components/icons/javascript'
import Postgres from '@/components/icons/postgres'
import Laravel from '@/components/icons/laravel'
import Inertia from '@/components/icons/inertia'
import Tailwind from '@/components/icons/tailwind'
import Mysql from '@/components/icons/mysql'
import Section from '@/components/section'
import Skill from '@/components/skill'
import Nuxt from '@/components/icons/nuxt'
import Html from '@/components/icons/html'
import Php from '@/components/icons/php'
import Vue from '@/components/icons/vue'
import Css from '@/components/icons/css'

export default {
  components: {
    Javascript,
    Postgres,
    Tailwind,
    Section,
    Inertia,
    Laravel,
    Mysql,
    Skill,
    Nuxt,
    Html,
    Vue,
    Css,
    Php,
  },
}
</script>
