<template>
  <div class="body-main">
    <div class="server-articles">
      <h1 align="center">Coming Soon...</h1>
      <!-- <div class="px-3 bg-white fs-xxl" v-html="models[2].submenus[0].body"></div> -->
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {},
  },
  data() {
    return {
      models: {
        submenus: {}
      }
    };
  },
  methods: {
    async fetchArticles() {
      const res = await this.$http.get("articles");
      this.models = res.data;
      console.log(this.models);
    }
  },
  created() {
    this.fetchArticles();
  }
};
</script>

<style>
</style>