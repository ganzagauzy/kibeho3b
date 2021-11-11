<template>
  <div>
    <adminNav />
    <div class="container">
      <div class="flex-head">
        <h4>Events 5</h4>
        <v-btn class="bg-primary text-light py-1 px-3 border-radius">+Event</v-btn>
      </div>
      <div>
        <NuxtLink to="/admin/events/_id" class="text-decoration-none text-dark ">
          <div  v-for="product in products" :key="product.id" class="border1 ">
            <div class="">
              <h5>{{product.title}}</h5>
              <br>
              <h6>{{product.snippet}}</h6>
              <br>
              <!-- <p>{{product.description | abbreviate}}</p> -->
            </div>
          </div>
        </NuxtLink>
      </div>

    </div>
  </div>
</template>

<script>
import { mapState } from "vuex"
export default {
  computed: {
    ...mapState([
      'products',
    ]),
    filters: {
      abbreviate(text) {
        if(text) {
          return text.slice(0, 10);
        }
      }
    }
  }


}
</script>

<style scoped>
.container {
  padding-top: 100px;
  padding-bottom: 100px;
}

.border1 {
  margin-top: 30px;
  background: #9c9ea326;
  padding: 10px 30px;
  border-radius: 20px;
}
.flex-head {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.border-radius {
  cursor: pointer;
  border-radius: 5px;
}
</style>
