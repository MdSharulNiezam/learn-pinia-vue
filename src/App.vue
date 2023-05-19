<template>
  <div class="app">
    <nav>
        <RouterLink to="/">Counter</RouterLink> |
        <RouterLink to="/TwoData">Two Data Binding</RouterLink>
      </nav> 
  </div>
  
  <RouterView />
</template>

<style>
  .app {
    text-align: center;
  }
</style>