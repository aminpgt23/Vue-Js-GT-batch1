<template>
<div class="d-flex justify-content-around">
    <div class="card p-4" style="width:300px;" >
        <a href="" class="chairs">
            <img class="card border-radius-24 " 
            :src="require('@/assets/img/' + cardImage + '.png')" alt="">
        </a>
        <p class="font-weight-bold mt-3 my-0">{{cardTitle}}</p>
        <p>IDR {{cardPrice}}</p>
    </div>
</div>
  
</template>


<script>
export default {
  name: 'cardComponent',
  props: 
    ["cardTitle","cardPrice","cardImage"]
}
</script>

<style>

</style>