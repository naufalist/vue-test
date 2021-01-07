<template>
  <div id="app">
    <!--  -->
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/profile">Profile</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
    <!--  -->
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
// import ItemTugas from "@/components/ItemTugas.vue";

export default {
  name: "app",
  components: {},
};
</script>

<style>
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
</style>

<style>
.header {
  background: #1abc9c;
}

.header h2 {
  margin: 0;
}

.tugas .item {
  font-size: 20px;
}

.item-completed {
  color: #1abc9c;
}
</style>
