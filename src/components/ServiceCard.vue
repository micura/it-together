<template>
    <div class="flex-item card text-center" data-aos="fade-right" data-aos-anchor-placement="bottom-bottom"
    onclick="location.href='services/1.html';">
        <div class="card-body">
            <p class="card-text">{{ serviceName }}</p>
        </div>
        <img class="card-img-bottom w-75 mx-auto" v-bind:src="getImgUrl(imgName)" />
        
    </div>
</template>

<script>
export default {
  name: "ServiceCard",
  props: ['serviceName', 'imgName'],
  methods:{
    getImgUrl(imgName) {
        return require('../assets/images/'+imgName)
    }
  }
};
</script>
