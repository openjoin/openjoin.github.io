<template>
  <div>
    <b-navbar class="navbar docs-navbar is-spaced has-shadow">
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="assets/newlogo.png"
                    alt="OpenJoin"
                >
            </b-navbar-item>
        </template>
        <template slot="start">
            <b-navbar-item>
              <router-link to="/" active-class="active">Home</router-link>
            </b-navbar-item>
            <b-navbar-item>
                <router-link to="/about" exact-active-class="exact-active">About</router-link>
            </b-navbar-item>
            <b-navbar-item>
                <router-link to="/contact" exact-active-class="exact-active">Contact</router-link>
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item tag="div">
                <div class="buttons">
                  <router-link to="/join" class="button is-danger">
                    <strong>Join with us</strong>
                  </router-link>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
    <router-view/>
  </div>
</template>

<style scoped>
h1 {
  font-family: 'Lobster', cursive;
  color: black;
}
h4{
  font-family: 'Lobster', cursive;
  color: black;
}
p {
  color: maroon;
  font-family: 'Kaushan Script', cursive;
}
a {
  color: black;
}
.top-bar {
    width: 100%;
    height: 2em;
    background-color: gray;
}
.navbar {
    padding-left: 2rem;
    padding-right: 2rem;
}
nav a {
  color: black;
}
nav a:hover,
nav a.router-link-active,
nav a.router-link-exact-active {
  background-color: indianred;
  cursor: pointer;
  color: black;
}
</style>