<template>
  <div class="home">
    <Section></Section>
    <Services></Services>
    <Contents></Contents>
  </div>
</template>

<script>
// @ is an alias to /src
import Section from "@/components/Section.vue";
import Services from "@/components/Services.vue";
import Contents from "@/components/Contents.vue";
export default {
  components: {
    Section,
    Services,
    Contents
  },
  name: "Home"
};
</script>
