<template>
    <div>
        <div class="text-center my-5">
            <img src="../assets/img/logo.png" alt="">
        </div>
        <div class="row justify-content-around">
            <div class="d-flex flex-column">
                <h4>Overview</h4>
                <a class="text-dark" href="">Shipping</a>
                <a class="text-dark" href="">Refund</a>
                <a class="text-dark" href="">Promotion</a>
            </div>

            <div class="d-flex flex-column">
                <h4>Company</h4>
                <a class="text-dark" href="">About</a>
                <a class="text-dark" href="">Career</a>
                <a class="text-dark" href="">Contact Us</a>
            </div>

            <div class="d-flex flex-column">
                <h4>Explore</h4>
                <a class="text-dark" href="">Terms & Conditions</a>
                <a class="text-dark" href="">Privacy police</a>
                <a class="text-dark" href="">for developer</a>
            </div>
       

            <div class=" p-2">
                <h4>Special letters</h4>
                <div class="d-flex">

                <input style="width:200px; " class="form-control mr-sm-2" type="search" placeholder="Your Email Addres" aria-label="Search" id="inputemail">
                <button  style="background-color: pink; border: 0px; height:40px; " class="rounded my-2 my-sm-0" type="submit" id="clik"><img src="../assets/img/tele-icon.png" alt=""></button>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
  name: 'fouterComponent',
  props: {
    msg: String
  }
}
</script>

<style>

</style>