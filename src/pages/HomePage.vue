<template>
    <div>
        <BannerLarge/>
    </div>

  <img src="./maquette.png">
</template>

<script>
import BannerLarge from "@/components/BannerLarge";

export default {
    name: 'HomePage',
    components: {BannerLarge},
    mounted() {

    }
}


</script>

<style lang="scss">
img {
  max-width: 100%;
  height: auto;
}
</style>