<template>
  <div id="app " class="h-100">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "@/styles/main.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
html,
body {
  height: 100%;
}
@font-face{
    font-family: "Prompt";
    src: local("Prompt"),
    url(./fonts/Prompt-Medium.woff) format("truetype") 
}
</style>
