<template>
  <div id="app" :class="classList">
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>
<script>
export default {
  name: "app",
  computed: {
    classList() {
      // console.log(process.env);
      let classes = "";
      if (process.env.NODE_ENV == "development") {
        classes += " " + process.env.NODE_ENV;
      }
      return classes;
    }
  }
};
</script>
<style lang="scss">
#app {
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
