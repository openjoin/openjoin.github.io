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
              <router-link to="/" class="is-danger">Home</router-link>
            </b-navbar-item>
            <b-navbar-item>
                <router-link to="/about">About</router-link>
            </b-navbar-item>
            <b-navbar-item>
                Contact
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a href="https://github.com/openjoin/support/issues" class="button is-danger">
                        <strong>Join with us</strong>
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
    <router-view/>
  </div>
</template>

<style scoped lang="scss">
.top-bar {
    width: 100%;
    height: 2em;
    background-color: gray;
}
.navbar {
    padding-left: 2rem;
    padding-right: 2rem;
}
</style>