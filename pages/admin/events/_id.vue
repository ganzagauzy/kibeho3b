<template>
 <div>
   <adminNav />
   <div class="container">

     {{ product.description }}
   </div>
 </div>
</template>

<script>
export default {
  computed: {
    product() {
      return this.$store.getters.getProductById(this.$route.params.id)
    }
  }

}
</script>

<style  scoped>
.container {
  padding-top: 100px;
}
</style>
