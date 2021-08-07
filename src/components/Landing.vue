<script setup>
import { Head } from "@vueuse/head";
</script>

<template>
  <Head>
    <title>{{ title }}</title>
  </Head>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name: "Landing",
  props: { title: String },
};
</script>
