<template>
  <div>
    <PageBanner pageTitle="Contact" />
    <Contact />
    <Map />
    <ClientsTwo />
  </div>
</template>

<script>
  import PageBanner from "~/components/pages/PageBanner";
  import Contact from "~/components/pages/Contact";
  export default {
    components: {
      Contact,
      PageBanner,
  
    },
    head(){
      return {
        title: "cypher | Contact"
      }
    }
  }
</script>
