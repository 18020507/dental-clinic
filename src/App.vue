<template>
  <div>
    <NavBar />
    <div class="content">
      <div class="side-bar">
        <SideBar />
      </div>
      <div class="content-page">
        <ContentPage />
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import SideBar from "./components/SideBar.vue";
import ContentPage from "./components/ContentPage.vue";

export default {
  name: "App",
  components: {
    NavBar,
    SideBar,
    ContentPage,
  },
};
</script>

<style scoped>
body {
  margin: 0;
  padding: 0;
}

nav {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1;
}

.content {
  display: flex;
  height: calc(100vh - 60px); /* subtract the height of the navbar */
  overflow: hidden;
}

.side-bar {
  position: fixed;
  top: 60px; /* align the top of the sidebar with the bottom of the navbar */
  bottom: 0;
  width: 25%;
  overflow-y: auto;
}

.content-page {
  margin-left: 25%; /* leave space for the sidebar */
  width: 75%;
  height: 100%;
  overflow-y: auto;
}

@media only screen and (max-width: 600px) {
  .content {
    display: block;
    height: auto;
  }

  .side-bar {
    display: none;
  }

  .content-page {
    margin-left: 0;
    width: 100%;
  }
}
</style>
