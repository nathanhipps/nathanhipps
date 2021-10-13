<template>
  <Section title="Contact" class="mt-96">
    <form name="contact" method="POST" data-netlify="true">
      <div class="mt-4">
        <label for="email" class="block text-sm font-medium">Email</label>
        <div class="mt-1">
          <input
            id="email"
            type="text"
            name="email"
            class="
              shadow-sm
              focus:ring-blue-500 focus:border-blue-500
              block
              w-72
              sm:text-sm
              border-gray-300
              rounded-md
            "
            placeholder="you@example.com"
          />
        </div>
      </div>
      <div class="mt-4">
        <label for="name" class="block text-sm font-medium">Name</label>
        <div class="mt-1">
          <input
            id="name"
            type="text"
            name="name"
            class="
              shadow-sm
              focus:ring-blue-500 focus:border-blue-500
              block
              w-72
              sm:text-sm
              border-gray-300
              rounded-md
            "
            placeholder="Your Name"
          />
        </div>
      </div>

      <div class="mt-4">
        <label for="message" class="block text-sm font-medium">Message</label>
        <div class="mt-1">
          <textarea
            id="message"
            name="message"
            rows="3"
            class="
              max-w-lg
              shadow-sm
              block
              w-full
              focus:ring-blue-500 focus:border-blue-500
              sm:text-sm
              border border-gray-300
              rounded-md
            "
          ></textarea>
        </div>
      </div>

      <button
        type="submit"
        class="
          mt-4
          inline-flex
          items-center
          px-4
          py-2
          border border-transparent
          text-sm
          font-medium
          rounded-md
          shadow-sm
          text-white
          bg-blue-600
          hover:bg-blue-700
          focus:outline-none
          focus:ring-2
          focus:ring-offset-2
          focus:ring-blue-500
        "
      >
        Send
      </button>
    </form>
  </Section>
</template>

<script>
import Section from '@/components/section'

export default {
  components: { Section },
}
</script>
