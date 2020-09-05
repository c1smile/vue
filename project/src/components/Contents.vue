<template>
  <div>
    <Content v-for="item in content" :key="item.title" :content="item"></Content>
  </div>
</template>

<script>
import Content from "./content";
export default {
  components: {
    Content
  },
  data() {
    return {
      content: [
        {
          title: "Introducing Virtual Care",
          image:
            "https://www.aspendental.com/-/media/aspendentaldotcom/covid-update-homepage/01virtualcarewhite2x.png",
          text:
            "Our process has changed, but our care for you hasn’t. For your health and safety, your care can now start with a virtual consultation. If you have a dental issue, just pick up the phone and a trusted member of the C1Smile-Dentalal team will help bring a doctor to you. ",
          btnText: "Learn More",
          class: "img-holder img-bg w-100",
          style: ""
        },
        {
          title: "Our response to COVID-19",
          image:
            "https://www.aspendental.com/-/media/aspendentaldotcom/covid-update-homepage/02covidresponse2x.png",
          text:
            "Many of our offices are now open. During your visit, we’re committed to protecting you, the doctors and our community. We’ve taken steps to put health and safety first while addressing your needs. See the latest on our response.",
          btnText: "Learn More",
          class: "img-holder img-bg w-75 rounded-circle",
          style: "padding-left: 115px;"
        },
        {
          title: "We are Aspen Strong",
          image: "https://www.aspendental.com/-/media/03_aspen-stories.png",
          text:
            "From selfless acts of kindness to shining moments of leadership, C1Smile-Dentalal team members show strength in times of adversity. Each week, we’re featuring a new face who is impacting their community and bringing hope to the patients they treat.",
          btnText: "Read their stories",
          class: "img-holder img-bg w-100",
          style: ""
        }
      ]
    };
  }
};
</script>