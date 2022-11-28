<template>
  <div class="d-flex p-5 my-5">
     <div class="d-flex flex-column  justify-content-around" style="width: 100px; height:auto">
         <img class="rounded" style="border:1px solid ;" src="../assets/img/side-1.png" alt="">
            <img class="rounded" style="border:1px solid;" src="../assets/img/side-2.png" alt="">
         <img class="rounded" style="border :1px solid" src="../assets/img/side-3.png" alt="">
         <img class="rounded" style="border:1px solid" src="../assets/img/side-1.png" alt="">
          <img class="rounded" style="border :1px solid" src="../assets/img/side-2.png" alt="">
     </div>


         <div >
            <img class=" p-4 rounded" id="kursiid" style="width:500px ;" src="../assets/img/chair.png" alt="kursi">
        </div>

        <div>
            <h1>Chair Thatty</h1>
            <p style="font-size: 15px ;">IDR 12.000.000</p>
            <a href="/form.html"  class="btn text-dark"  style="border-radius: 15px; background-color: pink;" type="submit"> <img  src="asset/cart-icon.png" alt=""> Add To Chart</a><hr>
        
        
            <h4>About The Product</h4>
            <p class="d-flex" style="font-size: 15px;">Tailored to a level of perfection synonymous with that of a savile
                Row suit and with understated quality in the detail,Jetty has been
            influenced by timeles 1950s style </p>
            <p class="d-flex" style="font-size: 15px ;">providing a subtle nod to the past,Jetty also provides a perfect solution for the way we
                 work today. A comprehensive product family,Jetty features a variety of elegant chairs
                 and sofas.
            </p>
        </div>
     </div>
</template>

<script>
export default {
  name: 'galleryComponent',
  props: {
    msg: String
  }
}
</script>

<style>

</style>