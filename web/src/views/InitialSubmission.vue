<template>
  <div>
    <div class="head-bar d-flex ai-center">
      <router-link tag="div" :to="'./'">
        <i class="el-icon-arrow-left fs-xxxl"></i>
      </router-link>
      <span class="flex-1 pr-1">Initial Submission</span>
    </div>
    <div class="ql-container ql-snow">
      <h1 align="center">Coming Soon...</h1>
      <!-- <div
        class="ql-editor body-main px-3 bg-white fs-xxl"
        v-html="models[2].submenus[0].body"
      ></div> -->
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
        submenus: {},
      },
    };
  },
  methods: {
    async fetchArticles() {
      const res = await this.$http.get("articles");
      this.models = res.data;
    },
  },
  created() {
    this.fetchArticles();
  },
};
</script>

<style></style>
