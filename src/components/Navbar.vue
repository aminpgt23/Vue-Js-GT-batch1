<template>
   <nav class="navbar navbar-light  justify-content-between p-2" >
        <div>
            <img src="../assets/img/logo.png" alt="">
        </div>
        <div class="mr-3">
            <a class="text-dark p-2" href="">Showchase</a>
            <a class="text-dark p-2" href="">Catalog</a>
            <a class="text-dark p-2" href="">Delivery</a>
            <a class="text-dark " href="">Reward</a>
            <img src="../assets/img/cart-icon.png" alt="">

        </div>
      </nav>
</template>

<script>
export default {
  name: 'NavbarComponent',
  props: {
    msg: String
  }
}
</script>

<style>

</style>