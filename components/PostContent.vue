<template>
  <b-col md="6">
    <b-card>
      <b-row no-gutters>
        <b-col md="6">
          <b-card-img alt="Image"> {{ image }} </b-card-img>
        </b-col>
        <b-col md="6">
          <b-card-body>
              <h5> {{title}} </h5>
            <b-card-text>
              {{ content }}
            </b-card-text>
            <b-button href="#" variant="danger">Go somewhere</b-button>
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
  props: ["title", "content", "image"],
};
</script>