<template>
  <div class="container">
    <div class="logo">
      <b>Review Nha Khoa</b>
      <input type="text" placeholder="Tìm nha khoa" />
    </div>
    <div class="content">
      <img class="nhakhoaphale" src="../assets/nhakhoaphale-logo.png" />
      <img class="nhakhoa24h" src="../assets/nhakhoa24h-logo.png" />
      <img class="nhakhoaviet" src="../assets/nhakhoaviet-logo.png" />
      <img class="nhakhoavuke" src="../assets/nhakhoavuke-logo.png" />
      <img class="nhakhoahuunghi" src="../assets/nhakhoahuunghi-logo.png" />
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  background-color: yellow;
  height: 50px;
  justify-content: space-between;
}

.nhakhoaphale {
  width: 60px;
  margin-top: auto;
  margin-bottom: auto;
  margin-right: 20px;
}

.nhakhoa24h {
  width: 50px;
  margin-bottom: 5px;
  margin-right: 20px;
}

.nhakhoaviet {
  width: 60px;
  margin-bottom: 13px;
  margin-right: 20px;
}

.nhakhoavuke {
  width: 60px;
  margin-bottom: 15px;
  margin-right: 20px;
}

.nhakhoahuunghi {
  width: 40px;
  margin-bottom: 13px;
  margin-right: 40px;
}

.logo {
  margin-left: 30px;
  margin-top: auto;
  margin-bottom: auto;
}

.logo b {
  font-size: 20px;
  font-family: Comic Sans MS;
}

input {
  width: 300px;
  border-radius: 20px;
  border: 1px solid #ccc;
  font-family: inherit;
  margin-left: 20px;
  height: 30px;
}

@media only screen and (max-width: 600px) {
  .content {
    display: none;
  }

  input {
    width: 150px;
    border-radius: 20px;
    border: 1px solid #ccc;
    font-family: inherit;
    margin-left: 20px;
    height: 30px;
  }
}

@media only screen and (max-width: 900px) {
  input {
    width: 150px;
    border-radius: 20px;
    border: 1px solid #ccc;
    font-family: inherit;
    margin-left: 20px;
    height: 30px;
  }
}
</style>
