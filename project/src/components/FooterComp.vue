<template>
  <footer class="text-light p-5">
    <div class="row mx-3">
      <div class="col-sm-12 hidden-xs hide-whiteline">
        <div class="footer-desktop">
          <div class="footer-row">
            <div class="footer-col">
              <div class="row">
                <div class="col-md-2" v-for="i in names" :key="i.name">
                  <p class="font-weight-bold">{{i.name}}</p>
                  <p v-for="k in i.links" :key="k">{{k}}</p>
                </div>
              </div>
            </div>

            <div class="footer-copy mt-5">
              C1Smile-Dental-branded dental practices are independently owned and operated by licensed dentists.&nbsp;
              <br />For more information about the relationship between C1Smile-Dental Management, Inc. and the branded dental practices click
              <a
                href="/about"
              >
                <span style>here</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      names: [
        {
          name: "Dental services",
          links: [
            "Emergency dental care",
            "Check ups",
            "Treatment of periodontal disease",
            "Tooth extraction",
            "Fillings",
            "Root canal",
            "Dental crowns",
            "Dental implants"
          ]
        },
        {
          name: "Cosmetic dentistry",
          links: ["Teeth whitening", "Veneers", "Invisalign"]
        },
        {
          name: "Dentures",
          links: [
            "Dentures made affordable",
            "Compare dentures",
            "Denture quality",
            "Partial & flexible dentures",
            "Full dentures",
            "Denture repair & reline",
            "Denture advice",
            "Patient reviews",
            "Pricing and offers"
          ]
        },
        {
          name: "What to expect",
          links: [
            "Emergency and walk in dental treatment",
            "Peace of mind promise",
            "Tips for overcoming dental anxiety",
            "Your first dental visit",
            "Patient forms"
          ]
        },
        {
          name: "Oral health",
          links: [
            "Cavities",
            "Gum disease",
            "Mouth & throat cancer",
            "Mouth sores & spots",
            "Oral health & overall health",
            "Oral hygiene",
            "TMJ"
          ]
        },
        {
          name: "(800) 277-3633",
          links: [
            "Careers",
            "My account",
            "About",
            "FAQs",
            "Accessibility",
            "Privacy policy",
            "Terms of use",
            "Sitemap",
            "Dental office listing"
          ]
        }
      ]
    };
  }
};
</script>
<style scoped>
footer {
  background-color: #004f82;
}
p {
  font-size: 16px;
}
</style>