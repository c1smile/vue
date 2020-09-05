<template>
  <div class="row no-gutters my-5">
    <div class="col-md-11 mx-5 px-4">
      <div class="row">
        <div class="col-sm-6" :style="content.style">
          <img :class="content.class" :src="content.image" />
        </div>
        <div class="col-sm-6 pt-5">
          <h2 tabindex="0" class="title mt-4">{{content.title}}</h2>
          <p class="text">{{content.text}}&nbsp;</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["content"],
  data() {
    return { name: "Zeeshan" };
  },
  created() {
    console.log("shani", this.content);
  }
};
</script>
<style scoped>
.title {
  font-size: 60px;
}
.text {
  font-size: 24px;
}
.ctahome {
  background-color: #ff7900;
  border: none;
  color: #fff;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
</style>