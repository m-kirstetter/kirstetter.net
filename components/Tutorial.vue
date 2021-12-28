<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <h1
        class="flex justify-center pt-8 sm:pt-0 text-4xl leading-7 font-semibold"
      >
        Manuel Kirstetter
      </h1>
      <div class="mt-4 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <h2 class="text-2xl leading-7 font-semibold">👋 Welcome 👋</h2>
        <p class="mt-3 text-gray-600">
          I'm a Freelance Frontend/Blockchain Developer. <br />
          My preferred stack includes:
        </p>
        <p class="mt-3 text-gray-600">
          Ethereum, Truffle, Vue, Nuxt, TypeScript, Mongo, Express
        </p>
        <p class="mt-4 pt-4 text-gray-800 border-t border-dashed">
          Currently available. Contact me on
          <a
            class="link"
            href="https://www.linkedin.com/in/manuelkirstetter/"
            target="_blank"
          >
            LinkedIn
          </a>
        </p>
      </div>
      <div class="flex justify-center pt-4 space-x-2">
        <a class="link" href="https://github.com/maunoxyd" target="_blank">
          <Icon type="github" :style="{ fontSize: '21px' }" />
        </a>
        <a
          class="link"
          href="https://www.linkedin.com/in/manuelkirstetter/"
          target="_blank"
        >
          <Icon type="linkedin" :style="{ fontSize: '21px' }" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { Icon } from "ant-design-vue";

export default {
  name: "NuxtTutorial",
  components: { Icon },
};
</script>

<style>
.link:hover {
  color: #000;
}
</style>
