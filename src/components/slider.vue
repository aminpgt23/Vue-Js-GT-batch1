<template>
  <div class="bg-light ">

         <div>
           <h4 class=" pt-5 ml-5 ">Complete Your Room <br>with what we Design</h4>
         </div>

        <div class="d-flex justify-content-around ">

         <card v-for="(item,index) in arrcardTitle" 
         :key="index" :cardTitle="item" 
         :cardPrice="arrcardPrice[index]"
         :cardImage="arrcardImage[index]"></card>
        </div>
      </div>
</template>
 
<script>
import card from './card.vue'
export default {
  name: 'sliderComponent',
  components : {
    card
  },
  data () {
    return{
        arrcardTitle :["Cangkir Mauttie","Samman Kaka", "Lino Dino", "Syail Ammeno"],
        arrcardPrice : ["10.000.000","12.0000.000","90.000.000","23.000.000"],
        arrcardImage :["chair-1","chair-2","chair-3","chair-4"]
    }
  }
}
</script>

<style>

</style>