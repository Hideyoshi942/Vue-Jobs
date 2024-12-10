<script setup>
import Hero from "@/components/Hero.vue";
import HomeCars from "@/components/HomeCars.vue";
import JobListings from "@/components/JobListings.vue";
</script>

<template>
  <Hero/>
  <HomeCars />
  <JobListings :limit="3" :showButton="true"/>
</template>

<style scoped>

</style>