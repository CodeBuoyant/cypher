<template>
  <div>
    <PageBanner pageTitle="Services" />
    <Services />
    <Funfact />
    <Clients />
  </div>
</template>

<script>
  import PageBanner from "~/components/pages/PageBanner";
  import Services from "~/components/home/Services";
  import Funfact from "~/components/home/Funfact";
  import Clients from "~/components/home/Clients";
  export default {
    components: {
      PageBanner,
      Services,
      Funfact,
      Clients,
    },
    head(){
      return {
        title: "Cypher | Services"
      }
    }
  }
</script>
