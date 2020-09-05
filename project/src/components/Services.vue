<template>
  <div class="row no-gutters my-5">
    <div class="col-md-11 mx-5 px-4">
      <div class="row no-gutters">
        <div class="col-md-4 pr-4" v-for="(item, index) in cols" :key="index">
          <div class="card w-100">
            <img class="card-img-top" :src="item.image" alt="Card image cap" />
            <div class="card-body">
              <h3 class="card-title p-2" tabindex="0">{{item.title}}</h3>
              <p class="card-text">{{item.text}}/p></p>
            </div>
            <div :class="item.class">
              <a href="#" class="card-link">{{item.btnText}}</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cols: [
        {
          title: "smile wide, smile safe Promise",
          image: "https://www.aspendental.com/-/media/smilesafe-odp-promo.png",
          text:
            "In these uncertain times, smiles connect us more than ever. We’re taking steps to ensure patients, care teams and communities have a safe, clean care environment for all their dental needs.",
          btnText: "Read our promise",
          class: "card-body"
        },
        {
          title: "What to know before you go",
          image: "https://www.aspendental.com/-/media/book_an_appointment.png",
          text:
            "As the COVID-19 pandemic continues to impact our lives, we continue to update our operations to keep you safe and smiling. Here are a few things to know as you plan for your treatment.",
          btnText: "Learn More",
          class: "card-body mt-3 pt-4"
        },
        {
          title: "We're #BetterTogether",
          image: "https://www.aspendental.com/-/media/thankyou_opt2.png",
          text:
            "Happiness. Hope. Joy. Confidence. A smile has the power to unleash these emotions and so many more.",
          btnText: "watch the video",
          class: "card-body mt-5 pt-5"
        }
      ]
    };
  }
};
</script>
<style scoped>
.card-img-top {
  border-top: 8px solid #afd1ed;
}
.card-title {
  font-size: 39px;
  min-height: 84px;
  line-height: 42px;
  color: #6d6e71;
  font-weight: 500;
  margin-bottom: 15px;
}
.card-text {
  font-size: 18px;
  line-height: 26px;
}
.card {
  box-shadow: 0 2px 30px 0 rgba(0, 0, 0, 0.04);
  border-radius: 2px;
  border: none;
}
</style>
