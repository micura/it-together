<template>
  <div class="container">
    <div class="flex-container mt-5 mb-5 justify-content-md-center">
      <ServiceCard serviceName='Weboldal készítés' imgName="service-1.png"/>
      <ServiceCard serviceName='Vállalatirányítási megoldások' imgName="service-2.png"/>
      <ServiceCard serviceName='Provisoning és számlázó rendszer' imgName="service-3.png"/>
      <ServiceCard serviceName='Alközponti megoldások' imgName="service-4.png"/>
      <ServiceCard serviceName='Call, contact center megoldás' imgName="service-5.png"/>
      <ServiceCard serviceName='IT Support' imgName="service-6.png"/>
      <ServiceCard serviceName='Kamerarendszer kiépítések' imgName="service-7.png"/>
      <ServiceCard serviceName='Hangrögzítő megoldások' imgName="service-8.png"/>
      <ServiceCard serviceName='Hálózati megoldások' imgName="service-9.png"/>
      <ServiceCard serviceName='Backup-rendszer kialakítása' imgName="service-10.png"/>
      <ServiceCard serviceName='Pályázati támogatás' imgName="service-11.png"/>
    </div>
  </div>
</template>

<script>
import ServiceCard from "@/components/ServiceCard.vue";

export default {
  name: "ServiceComponent",
  components: {
    ServiceCard
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.flex-container {
    display: inline-flex;
    flex-wrap: wrap;
    gap: 12px;
}

.card {
    border-radius: 10px;
    padding: 5px; 
    color: #203d67;
    cursor:pointer;
    width: 100%;
}

.card:hover {
    background-color: #21bf73;
    transition: all 0.6s ease;
    -webkit-transition: all 0.6s ease;
    color: white;
}
</style>
