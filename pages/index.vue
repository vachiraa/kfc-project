<template>
  <b-container fluid>
    <Header />
    <b-row class="py-2">
      <PostContent
        title="7 ฟรี 7"
        content="ไก่ทอด 7 ชิ้น ฟรี วิงซ์แซ่บ 7 ชิ้น"
        image="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Items/7Free7Y22.png"
      />
      <PostContent
        title="ไก่ทอดเนื้อล้วนสูตรผู้พัน 2 ชิ้น"
        content="ไก่ทอดเนื้อล้วนที่ทำการหมักด้วยสูตรลับของผู้พันด้วยเครื่องเทศ 11 ชนิด เสิร์ฟพร้อมซอสหอมกลิ่นรมควันสูตรพิเศษ ที่จะทำให้ทุกมื้อของคุณฟินกว่าเดิม"
      />
      <PostContent
        title="คอมโบไก่ทอดเนื้อล้วนสูตรผู้พัน"
        content="ไก่ทอดเนื้อล้วนสูตรผู้พัน 2 ชิ้นพร้อมซอสสูตรพิเศษ
เฟรนช์ฟรายส์ ปกติ 1 กล่อง
เป๊ปซี่ 1ที่"
      />
      <PostContent
        title="เดอะบอกซ์ไก่ทอดเนื้อล้วนสูตรผู้พัน"
        content="ไก่ทอดเนื้อล้วนสูตรผู้พัน 2 ชิ้นพร้อมซอสสูตรพิเศษ ไก่ทอด 1 ชิ้น ไก่วิงซ์แซ่บ 2 ชิ้น เฟรนช์ฟรายส์ ปกติ 1 ที่ เป๊ปซี่ 1ที่"
        image="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Items/lg2x/TB_Tender_DLV.png"
      />
    </b-row>
  </b-container>
</template>

<script>
import Header from "@/components/Header";
import PostContent from "@/components/PostContent";

export default {
  layout: "default",
  components: {
    Header,
    PostContent,
  },
};
</script>

<style>
html {
  align-content: center;
}
</style>