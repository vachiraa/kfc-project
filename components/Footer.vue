<template>
  <div>
    <b-row no-gutters style="background-color: #e4002b; width: 100%;">
      <b-col><p class="redrow">บริการลูกค้า</p></b-col>
      <b-col><p class="redrow">นโยบาย</p></b-col>
    </b-row>

    <b-row no-gutters style="margin: 10px;">
      <b-col><a>คำถามที่พบบ่อย</a></b-col>
      <b-col><a>เงื่อนไขการใช้บริการ</a></b-col>
    </b-row>

    <b-row no-gutters style="margin: 10px;">
      <b-col><a>ติดตามคำสั่งซื้อ</a></b-col>
      <b-col><a>คำชี้แจงความเป็นส่วนตัว</a></b-col>
    </b-row>

    <b-row no-gutters style="margin: 10px;">
      <b-col><a>ติดต่อเรา</a></b-col>
    </b-row>

    <b-row>
        <b-icon class="icon" icon="youtube" font-scale="2"></b-icon>
        <b-icon class="icon" icon="instagram" font-scale="2"></b-icon>
        <b-icon class="icon" icon="facebook" font-scale="2"></b-icon>
    </b-row>
  </div>
</template>

<script>
export default {};
</script>

<style>
.redrow {
    color: white;
    margin: 10px;
}
a {
    font-weight: bold;
}
.icon {
    margin: 15px;
    color: #e4002b;
}
</style>