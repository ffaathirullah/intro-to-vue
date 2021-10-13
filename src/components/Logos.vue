<template>
    <div class="logos-wrapper">
        <h1>Heading 1</h1>
        <div class="item-logos">
            <img src="" alt="">
        </div>
        <div class="item-logos">
            <img src="" alt="">
        </div>
        <div class="item-logos">
            <img src="" alt="">
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
    background: red;
    float: left;
    margin-right: 20px;
}
</style>