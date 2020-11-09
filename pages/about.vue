<template>
  <div>
    <PageBanner pageTitle="About Us" />
    <AboutAgency />
    <OurWork />
    <CallToAction />
  </div>
</template>
<script>
  import PageBanner from "~/components/pages/PageBanner";
  import AboutAgency from "~/components/home/AboutAgency";
  import OurWork from "~/components/pages/OurWork";
  import CallToAction from "~/components/home/CallToAction";
  export default {
    components: {
      PageBanner,
      AboutAgency,
      OurWork,
      CallToAction
    },
    head(){
      return {
        title: "cypher | About Us"
      }
    }
  }
</script>
