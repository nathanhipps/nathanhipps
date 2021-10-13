<template>
  <Section title="Work">
    <div class="mt-12">
      <div>
        <h3 class="text-2xl">Mark C. Pope Associates, Inc.</h3>
        <h4 class="italic text-lg mt-1">Smyrna, Georgia</h4>
        <p class="text-xs">March 1997 - October 2021</p>
        <p class="mt-4 leading-8 lg:w-3/4">
          Most of my time was spent in management and sales related roles, but I
          was also the sole developer of some in-house web based applications
          that we utilized. I built an e-commerce system and marketing site that
          was used by two divisions of the company. I also developed a customer
          relationship management system that allowed us to manage long-running
          capital equipment sales projects.
        </p>
      </div>
    </div>
    <div class="mt-12">
      <div>
        <h3 class="text-2xl">Retail Insights, LLC</h3>
        <h4 class="italic text-lg mt-1">Colonia, NJ</h4>
        <p class="text-xs">October 2021 - Present</p>
        <p class="mt-4 leading-8 lg:w-3/4">
          Working as a web application developer building solutions for fortune
          500 companies.
        </p>
      </div>
    </div>
    <div class="pt-12">
      <h3 class="text-2xl block border-t border-dashed border-gray-700 py-6">
        Highlighted Projects
      </h3>
      <div>
        <h4 class="mb-2 text-xl flex">
          <a class="hover:underline" href="https://www.batterydate.com/"
            >batterydate.com</a
          >
          <a href="https://github.com/nathanhipps/battery-date-decoder">
            <Github class="w-10 fill-current pl-4" />
          </a>
        </h4>
      </div>
      <div class="flex">
        <a class="hover:underline" href="https://www.batterydate.com/">
          <img
            class="w-64"
            src="@/assets/images/batterydate.jpg"
            alt="Battery Date Decoder PWA"
        /></a>

        <p class="flex-1 ml-6 leading-8">
          This site takes a serial number and manufacturer name and will decode
          the date code. It is used by many service companies in the material
          handling industry. Forklift steel-case motive traction batteries
          typically have a warranty of 5 years and it is necessary to know the
          manufacturing date to properly service their customers. This site is a
          progressive web application so it can be used without data service.
        </p>
      </div>

      <div class="mt-10">
        <h4 class="mb-2 text-xl flex">
          <a class="hover:underline" href="https://www.mcpclean.com/"
            >mcpclean.com</a
          >
        </h4>
      </div>
      <div class="flex">
        <a class="hover:underline" href="https://www.mcpclean.com/">
          <img
            class="w-64"
            src="@/assets/images/mcpclean.jpg"
            alt="MCP Clean Marketing and E-Commerce Site"
        /></a>

        <p class="flex-1 ml-6 leading-8">
          MCP is a company that provides industrial cleaning equipment. I built
          their marketing site and incorporated e-commerce functionality that
          uses Stripe for the payment gateway and integrates with their internal
          accounting system software. They are able to market and sell
          replacment parts globaly and provide everything you would expect from
          a fully functional e-commerce product.
        </p>
      </div>

      <div class="mt-10">
        <h4 class="mb-2 text-xl flex">
          Funl - Customer Relationship Management Application
        </h4>
      </div>
      <div class="flex">
        <img
          class="w-64"
          src="@/assets/images/funl_app.jpg"
          alt="MCP Clean Marketing and E-Commerce Site"
        />

        <p class="flex-1 ml-6 leading-8">
          Funl is a CRM that was built to manage long running capital equipment
          sales projects. It includes all of the company's customers, contacts,
          products, images, documents and a fully featured quotation builder.
          Equipment availability and demonstration requests are also provided
          through this system.
        </p>
      </div>
    </div>
  </Section>
</template>

<script>
import Section from '@/components/section'
import Github from '@/components/icons/github'
export default {
  components: { Section, Github },
}
</script>
