<!-- TODO: Move attribution and contact link to TheFooter -->
<template>
  <DeviceGrid></DeviceGrid>
  <div>
    <RouterLink to="/contact">Contact Us</RouterLink>
    <div>Icons made by <a href="https://www.flaticon.com/authors/dinosoftlabs" title="DinosoftLabs">DinosoftLabs</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
    <div>Icons made by <a href="https://www.flaticon.com/authors/smashicons" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
  </div>
  <PasswordGenerator></PasswordGenerator>
</template>

<script setup lang="ts">
import DeviceGrid from '../components/DeviceGrid.vue'
import PasswordGenerator from "../components/PasswordGenerator.vue";
</script>

<style scoped>

</style>
