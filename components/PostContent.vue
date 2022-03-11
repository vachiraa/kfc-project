<template>
  <b-col md="6">
    <b-card no-body class="mb-5 card-size">
      <b-row no-gutters>
        <!-- image -->
        <b-col md="5">
          <b-card-img fluid :src="image" class="image-size"></b-card-img>
        </b-col>

        <!-- details -->
        <b-col md="7">
          <b-card-body style="margin-left: 10px">
            <h5>{{ title }}</h5>
            <b-card-text>
              {{ content }}
            </b-card-text>
          </b-card-body>
        </b-col>
      </b-row>

      <!-- botton -->
      <b-row no-gutters>
        <b-col></b-col>
        <b-col no-gutters style="margin: 5px">
          <b-button block href="#" style="background-color: #e4002b">{{
            price
          }}</b-button>
        </b-col>
      </b-row>
    </b-card>
  </b-col>
</template>

<style>
h5 {
  color: #e4002b;
}
.card-size {
  max-width: 100%;
  height: auto;
  border-radius: 0%;
  box-shadow: 3px 3px 6px rgb(143, 142, 142);
}
.image-size {
  max-width: 15rem;
  height: auto;
  margin: 10px;
}
</style>

<script>
export default {
  props: ["title", "content", "image", "price"],
};
</script>