<template>
  <div>
    <b-navbar class="bg-white" toggleable="lg" type="light" variant="fade">
      <!-- kfc icon -->
      <b-navbar-brand href="#"
        ><img
          src="https://custom-images.strikinglycdn.com/res/hrscywv4p/image/upload/c_limit,fl_lossy,h_1440,w_720,f_auto,q_auto/4215606/133185_278332.jpeg"
          class="img-fluid"
        />
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">

            <b-tabs active-nav-item-class="font-weight-bold text-uppercase bg-danger text-white">
              <b-tab title="เดลิเวอรี" ></b-tab>
              <b-tab title="รับที่ร้าน/รถ" ></b-tab>
            </b-tabs>

          <b-navbar-brand>
            <img class="coupon-icon" src="@/assets/coupon.png" alt="" />
          </b-navbar-brand>

          <b-nav-item-dropdown text="ภาษา" right>
            <b-dropdown-item href="#">TH</b-dropdown-item>
            <b-dropdown-item href="#">EN</b-dropdown-item>
          </b-nav-item-dropdown>

          <b-nav-item> เข้าสู่ระบบ </b-nav-item>

          <b-nav-item>
            <b-icon icon="bell-fill" font-scale="1"></b-icon>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <!-- second navbar -->
    <b-navbar class="bg-white" type="light" variant="fade">
      <b-navbar-nav>
        <b-nav-item href="#">โปรโมชั่น</b-nav-item>
        <b-nav-item href="#">ชุดสุดคุ้ม</b-nav-item>
        <b-nav-item href="#">เมนูเพิ่มเติม</b-nav-item>
        <b-nav-item href="#">เมนูจัดเลี้ยง</b-nav-item>
      </b-navbar-nav>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item right>
            <b-button style="background-color: #e4002b"
              >เริ่มสั่งอาหาร</b-button
            >
          </b-nav-item>
          <b-nav-item> ฿0.00 </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style>
img {
  width: 80px;
  height: 80px;
}
.coupon-icon {
  width: 40px;
  height: 40px;
  margin-left: 5px;
}
</style>

<script>
export default {
  data() {
    return {
      selected: [],
      option: [{ text: "เดลิเวอรี" }],
    };
  },
};
</script>