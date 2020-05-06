<template>
  <div id="app">
    <div
      class="flex items-center justify-center mt-48 lg:mt-0 lg:min-h-screen text-center"
    >
      <div class="flex-initial">
        <img
          class="object-contain self-center mx-auto h-32"
          alt="Vue logo"
          src="./assets/logo.png"
        />
        <HelloWorld class="w-full" msg="Welcome to Your Vue.js App" />
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style></style>
