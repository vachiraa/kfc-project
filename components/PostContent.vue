<template>
  <b-col md="6">
    <b-card no-body class="overflow-hidden" style="max-width: 100%; max-high: 100%">
      <b-row no-gutters>
        <b-col md="5">
          <b-card-img :src=image alt="Image" ></b-card-img>
        </b-col>
        <b-col md="7">
          <b-card-body>
              <h5> {{title}} </h5>
            <b-card-text>
              {{ content }}
            </b-card-text>
            <b-button href="#" variant="danger">{{price}}</b-button>
          </b-card-body>
        </b-col>
      </b-row>
    </b-card>
  </b-col>
</template>

<style>
h5 {
    color: #e4002b;
}
</style>

<script>
export default {
  props: ["title", "content","image","price"],
};
</script>