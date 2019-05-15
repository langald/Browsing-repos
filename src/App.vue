<template>
  <div id="app">
    <header class="app-header">
      <div class="container">
        <a class="github-icon" href="https://github.com/"></a>
        <span class="header-title">Github repository browsing tool</span>
      </div>
    </header>
    <div class="app-content">
      <router-view/>
    </div>
    <footer class="app-footer">
      Created by &nbsp;  <a href="https://github.com/langald" class="app-link">Larissa Angald</a>, 
      source code &nbsp;  <a href="https://github.com/langald/Browsing-repos" class="app-link">link</a>
    </footer>
  </div>
</template>


<style lang="sass">
  @import "@/assets/css/app.sass"
</style>
