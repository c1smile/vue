<template>
  <header>
    <div class="row mx-md-1 px-md-5">
      <div class="col-md-12 mx-md-2">
        <nav class="navbar navbar-expand-lg navbar-light" id="headerid">
          <div class="row w-100">
            <div class="col-md-4 col-sm-10 col-10">
              <router-link to="/" class="navbar-brand">
                <h2>C1Smile-Dental</h2>
              </router-link>
              <!-- <a href="#">
                <img
                  src="https://www.aspendental.com/-/media/aspendentaldotcom/logos/aspendental_logo-sm-rgb-blue.svg?la=en&hash=91CD11563E43A17CF67A3FB902143701"
                  alt="image"
                  style="width:55%"
                />
              </a>-->
            </div>
            <div class="col-2 d-lg-none">
              <button
                class="border-0 mt-3 navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
            </div>
            <div class="col-md-8 col-sm-12 col-12 pl-md-5 pt-3">
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav d-flex justify-content-between mr-auto" style="width:90%">
                  <li class="nav-item active">
                    <router-link class="nav-link" to="/smilepage">
                      schedule appointment
                      <span class="sr-only">(current)</span>
                    </router-link>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">find office</a>
                  </li>

                  <li class="nav-item">
                    <a class="nav-link" href="#">my account</a>
                  </li>
                </ul>
                <div class="btn btn-sm rounded-circle">
                  <i class="fa fa-search text-primary" style="font-size: 25px;"></i>
                </div>
                <form class="form-inline my-2 my-lg-0 d-none">
                  <input
                    class="form-control mr-sm-2"
                    type="search"
                    placeholder="Search"
                    aria-label="Search"
                  />
                  <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                </form>
              </div>
            </div>
          </div>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-link {
  font-size: 18px;
}

.header {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  width: 100%;
  min-height: 100px;
  background: linear-gradient(red 100px, transparent 102px 100%) fixed no-repeat
    0 0;
  z-index: 99;
  border: 1px solid #000;
}
@supports (-webkit-overflow-scrolling: touch) {
  .header {
    background-attachment: scroll;
  }
}
</style>
