<template></template>

<script setup lang="ts">
import { Blog } from "~~/types/Blog";

const { data } = await useMicroCMSGetList<Blog>({
  endpoint: "blogs",
});
console.log(data);
</script>
