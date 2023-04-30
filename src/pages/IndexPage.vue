<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
  </q-page>
</template>

<script setup>
import {defineComponent, onMounted} from 'vue'

onMounted(() => {
  main()
})
async function main() {
// Fetch network info
  window.martian.connect();
  // const network = await window.martian.network();
  // console.log(network);
}
</script>
