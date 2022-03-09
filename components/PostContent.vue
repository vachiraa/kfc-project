<template>
    <b-col md="6">
      <b-card no-body class="mb-4" style="max-width: 100; height: 100">
        <b-row no-gutters>
          <!-- image -->
          <b-col md="5">
            <b-card-img
              fluid
              :src="image"
              style="max-width: 100%; height: auto"
            ></b-card-img>
          </b-col>
          <!-- details -->
          <b-col md="7">
            <b-card-body>
              <h5>{{ title }}</h5>
              <b-card-text>
                {{ content }}
              </b-card-text>
              <b-button block href="#" style="background-color: #e4002b">{{
                price
              }}</b-button>
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
  props: ["title", "content", "image", "price"],
};
</script>