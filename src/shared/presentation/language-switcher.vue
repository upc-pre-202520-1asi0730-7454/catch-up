<script setup>

</script>

<template>
  <pv-select-button 
      v-model="$i18n.locale" 
      :options="$i18n.availableLocales.map(locale => ({ label: locale.toUpperCase(), value: locale }))" />
</template>

<style scoped>

</style>