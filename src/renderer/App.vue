<template>
  <div id="app">
        <VueDropdown label="Menu">
          <VueDropdownButton icon-left="edit">Edit</VueDropdownButton>
          <VueDropdownButton icon-left="delete">Delete</VueDropdownButton>
          <VueDropdownButton icon-left="lock" keep-open>Keep open</VueDropdownButton>
        </VueDropdown>
    <VueButton v-tooltip="`Detailed explanation here`">Hover me!</VueButton>
  </div>
</template>

<script>
  export default {
    name: 'test-proj'
  }
</script>
<style lang="stylus">
  @import "~@vue/ui/dist/vue-ui.css"

</style>
<style>
  /* CSS */
</style>
