<template>
  <div class="container">
    <div class="content-page">
      <div class="sidebar-header">
        <h4>Top 5 phòng khám nha khoa uy tín tỉnh Hòa Bình</h4>
      </div>
      <div class="sidebar-body">
        <div>
          <a href="#section1">
            <div class="content">
              <img src="https://toplist.vn/images/numbers/1.svg" />
              NHA KHOA PHA LÊ CƠ SỞ HÒA BÌNH
            </div>
          </a>
        </div>
        <div>
          <a href="#section2">
            <div class="content">
              <img src="https://toplist.vn/images/numbers/2.svg" />
              NHA KHOA24H
            </div>
          </a>
        </div>
        <div>
          <a href="#section3">
            <div class="content">
              <img src="https://toplist.vn/images/numbers/3.svg" />
              NHA KHOA VIỆT
            </div>
          </a>
        </div>
        <div>
          <a href="#section4">
            <div class="content">
              <img src="https://toplist.vn/images/numbers/4.svg" /> NHA KHOA
              THẨM MỸ VŨ KẾ
            </div>
          </a>
        </div>
        <div>
          <a href="#section5">
            <div class="content">
              <img src="https://toplist.vn/images/numbers/5.svg" />
              NHA KHOA HỮU NGHỊ
            </div>
          </a>
        </div>
      </div>
      <div class="sidebar-footer"></div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style scoped>
.container {
}
.content-page {
  margin-left: 10px;
}

img {
  width: 20px;
  margin-right: 5px;
  margin-bottom: auto;
  margin-top: auto;
}

a {
  text-decoration: none;
}

.content {
  display: flex;
  flex-direction: row;
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
