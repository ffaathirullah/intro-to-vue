<template>
    <div class="logos-wrapper">
        <h1>Heading 1</h1>
        <div class="item-logos">
           <img  class="logo" alt="Vue logo" src="./../assets/microsoft.jpg">
        </div>
        <div class="item-logos">
       <img class="logo"  alt="Vue logo" src="./../assets/google.png">
        </div>
        <div class="item-logos">
         <img  class="logo" alt="Vue logo" src="./../assets/microsoft.jpg">
        </div>
    </div>
</template>

<script>
export default {
  name: 'Logos',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.logos-wrapper{
    width: 70%;
    overflow: hidden;
    margin: auto;
}
.item-logos{
    width: 150px;
    height: 150px;
    float: left;
    margin-right: 20px;
    background: red;
}
.item-logos .logo{
    width: 150px;
    height: 150px;
}
</style>