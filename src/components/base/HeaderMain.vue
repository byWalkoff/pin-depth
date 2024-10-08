<template>
  <header class="header">
    <div class="header__logo">
      <img src="/logo.jpeg" alt="">
    </div>
    <div class="header__nav">
      <nav class="nav-list">
        <div class="nav-item">
          <span class="nav-item__link">Item 1</span>
          <div class="nav-list">
            <div class="nav-item"><span class="nav-item__link">Nested Item 1</span></div>
            <div class="nav-item"><span class="nav-item__link">Nested Item 2</span></div>
            <div class="nav-item"><span class="nav-item__link">Nested Item 3</span></div>
          </div>
        </div>
        <div class="nav-item">
          <span class="nav-item__link">Item 2</span>
          <div class="nav-list">
            <div class="nav-item"><span class="nav-item__link">Nested Item 1</span></div>
            <div class="nav-item"><span class="nav-item__link">Nested Item 2</span></div>
            <div class="nav-item"><span class="nav-item__link">Nested Item 3</span></div>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<script setup lang="ts">

</script>

<style lang="scss">
  @import "@/scss/layout/header/header";
  @import "@/scss/layout/nav/nav-list";
  @import "@/scss/layout/nav/nav-item";
</style>