<template>
  <nav>
    <h1>Vuestagram</h1>
    <div>
      <router-link to="/">Home</router-link> | 
      <router-link to="/about">About</router-link>
    </div>
  </nav>
  <router-view/>
</template>

<style lang="scss">
body{
  background: gray;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 350px; height: 70vh;
  margin: 0 auto;
  background: white;
}

nav {
  padding: 30px;
  display: flex;
  align-items: center;
  justify-content: space-between;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
