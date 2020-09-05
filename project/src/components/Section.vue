<template>
  <div class="row no-gutters my-5">
    <div class="col-md-11 mx-5 px-4">
      <div class="section">
        <div class="no-gutters px-5 py-4 row">
          <div class="col-md-6">
            <h1
              class="font-weight-bold text-hero text-light mb-0"
              tabindex="0"
            >Yes, we’re open for all care.</h1>
          </div>
        </div>
        <div class="row no-gutters">
          <div class="col-md-8 px-5">
            <p class="text-light text-24px">
              Many C1Smile-Dental practices are now open
              and taking appointments for all types of care.
              We’re also making your safety our priority with our
              <br />
              <a class="link" href="#">Smile Wide, Smile Safe Promise.</a>
            </p>
          </div>
        </div>
        <div class="row no-gutters">
          <div class="col-md-4 px-5">
            <div class="btn btn-yellow">Schedule Appointment</div>

            <p class="text-light text-see mt-3">SEE APPOINTMENT GUIDELINES</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return { name: "Zeeshan" };
  }
};
</script>
<style scoped>
.section {
  background: url("https://www.aspendental.com/-/media/hpdesktophero1170x5772x.png");
  width: 100%;
  height: 500px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
}
.text-hero {
  font-size: 64px;
  line-height: 64px;
  padding-right: 80px;
  margin-bottom: 30px;
  letter-spacing: -1.42px;
}
.text-24px {
  font-size: 30px;
  line-height: 38px;
  font-weight: 500;
}
.link {
  color: #337ab7;
  text-decoration: none;
}
.btn-yellow {
  color: #fff;
  background: #ff7900;
  border: 2px solid #ff7900;
  width: 265px;
}
.btn-yellow:hover {
  background: #cc6100;
}
.text-see {
  font-size: 18px;
  font-weight: 600;
}
</style>
