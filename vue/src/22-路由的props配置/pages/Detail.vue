<template>
  <ul>
    <li>消息编号:{{ id }}</li>
    <li>消息标题:{{ title }}</li>
    <li>a:{{ a }}</li>
    <li>b:{{ b }}</li>
  </ul>
</template>

<script>
export default {
  name: "Detail",
  props: ["id", "title"],
  mounted() {
    console.log(this.$route);
  },
};
</script>

<style>
</style>