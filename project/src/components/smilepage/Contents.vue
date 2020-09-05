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
          title: "Cleaning, Hygiene & Safety Standards",
          image:
            "https://www.aspendental.com/-/media/cleaning_safety_hygiene_no_icon.png",
          text:
            "We’ve always been committed to the highest safety standards—and now deep cleaning has a whole new meaning as we sanitize chairs and surfaces between visits. Masks are also required for everyone in the office, including team members and patients. If you don't have one, we'll provide you one at the front desk.",
          class: "img-holder img-bg w-100",
          style: ""
        },
        {
          title: "Symptom Screening",
          image:
            "https://www.aspendental.com/-/media/gettyimages-1219032362_f-temp.jpg",
          text:
            "We’re requiring wellness checks for care teams and patients alike. This means daily health check ins with staff and must-do temperature checks for everyone. We’ll make sure to check your temp before you start your care to keep everyone safe and healthy.",
          class: "img-holder img-bg w-100",
          style: ""
        },
        {
          title: "Social Distancing",
          image:
            "https://www.aspendental.com/-/media/social_distancing_no_icon.png",
          text:
            "In times like these, a little distance goes a long way. We're moving you in and out of treatment rooms quickly (and safely) and encouraging you to wait outside the office prior to your appointment. We'll text you when we're ready to see you—and don't forget to wear your mask.",
          class: "img-holder img-bg w-100",
          style: ""
        },
        {
          title: "Smarter Scheduling",
          image:
            "https://www.aspendental.com/-/media/smarter_scheduling_no_icon.png",
          text:
            "We’ve adjusted our operations to keep you and care teams safe. Staggered appointments limit the number of people arriving and give us plenty of time to clean in between. And if you’re an older adult or have underlying medical conditions, we’ll see during a slower time of day.",
          class: "img-holder img-bg w-100",
          style: ""
        },
        {
          title: "Virtual Visits",
          image:
            "https://www.aspendental.com/-/media/virtual_visits_no_icon.png",
          text:
            "Now we can bring C1Smile-Dental doctors to you with our new Virtual Care service. Get dental advice right from the safety of your own home. Free denture consultations are available by phone or online, too",
          class: "img-holder img-bg w-100",
          style: ""
        },
        {
          title: "Onsite Labs",
          image: "https://www.aspendental.com/-/media/onsite_lab_no-icon.png",
          text:
            "Did you know that your dentures never leave the safety of our office? They’re custom-crafted right in our own labs, where we follow the same protocols of our Smile Wide, Smile Safe Promise. You’ll know that your dentures are secure, from impression to insertion.",
          class: "img-holder img-bg w-100",
          style: ""
        }
      ]
    };
  }
};
</script>