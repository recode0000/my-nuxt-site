<template>
  <div class="wrapper">
    <layout-header class="wrapper_header" />
    <main class="wrapper_main">
      <Nuxt />
    </main>
  </div>
</template>
<style lang="scss" scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  min-height: 100%;

  &_header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: auto;
  }
  &_main {
    margin: 0 auto;
    width: 100%;
    max-width: 1000px;
    padding: 80px 40px;
    flex: 1 0 auto;
    @media #{sp} {
      margin-top: 104px;
      padding: 16px 4.3%;
    }

  }
}
</style>
