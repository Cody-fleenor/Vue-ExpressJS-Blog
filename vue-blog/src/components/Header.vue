<template>
  <div>
    <b-navbar toggleable style="background-color: #1D2D44;">
      <b-navbar-brand href="#">
        <b-iconstack style="margin: 5px;color: white;">
          <b-icon stacked icon="arrows-fullscreen" scale="1.5" animation="throb"></b-icon>
          <b-icon stacked icon="circle-fill" scale="1.5" style="color: #748CAB;"></b-icon>
          <b-icon stacked icon="code-slash" scale="1"></b-icon>
        </b-iconstack>
      </b-navbar-brand>
      <b-nav-text style="color: white;">
        My Internship Blog
      </b-nav-text>
      <b-navbar-toggle target="navbar-toggle-collapse">
        <template #default="{ expanded }">
          <b-icon v-if="expanded" icon="chevron-bar-up" style="color: white;"></b-icon>
          <b-icon v-else icon="chevron-bar-down" style="color: white;"></b-icon>
        </template>
      </b-navbar-toggle>

      <b-collapse id="navbar-toggle-collapse" is-nav>
        <b-navbar-nav>
          <b-button-group style="display: block; text-align: center;">
            <b-link href="http://caveprojects.link">
              <b-button title="Projects" size="sm" style="margin: 2px; opacity: 1;">
                <b-icon icon="files" aria-hidden="true"></b-icon>
                  Projects
              </b-button>
            </b-link>
            <b-link href="https://www.github.com/Cody-fleenor">
              <b-button title="Projects" size="sm" style="margin: 2px; opacity: 1;">
                <b-icon icon="github" aria-hidden="true"></b-icon>
                  GitHub
              </b-button>
            </b-link>
            <b-link href="https://www.linkedin.com/in/cody-fleenor">
              <b-button title="Projects" size="sm" style="margin: 2px; opacity: 1;">
                <b-icon icon="linkedin" aria-hidden="true"></b-icon>
                  LinkedIn
              </b-button>
            </b-link>
            <b-link to="/">
              <b-button title="Contact Me" size="sm" style="margin: 2px; opacity: 1;">
                  <b-icon icon="envelope-open" aria-hidden="true"></b-icon> Contact
              </b-button>
            </b-link>
          </b-button-group>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
