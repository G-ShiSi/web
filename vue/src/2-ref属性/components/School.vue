<template>
  <div class="school">
    <h2>学校名称：{{ name }}</h2>
    <h2>学校地址：{{ address }}</h2>
  </div>
</template>

<script>
export default {
  name: "School",
  data() {
    return {
      name: "湖南科技大学",
      address: "湖南湘潭",
    };
  },
};
</script>

<style>
.school {
  background-clip: black;
}
</style>