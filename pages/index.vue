<template>
  <b-container>
    <b-btn variant="primary" show>DEFAULT PRIMARY COLOR</b-btn>
    <b-btn variant="danger" show>DEFAULT DANGER COLOR</b-btn>
    <b-btn variant="custom">CUSTOM BOOTSTRAP THEME COLOR</b-btn>
    <b-btn variant="custom">CUSTOM SCSS VAR COLOR</b-btn>
  </b-container>
</template>

<script>
export default {}
</script>

<style lang="scss">
// Если нужно использовать SCSS-переменные в компонентах по всему проекту, надо добавить модуль
// npm i @nuxtjs/style-resources -S
// И закинуть его в nuxt.config.js
// .custom {
//   background-color: $custom-color;
// }
</style>
