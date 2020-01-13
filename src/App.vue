<template>
  <div class="main">
    <button @click="show = !show">きりかえ</button>
    <transition name = "fade">
      <p v-if="show">hello</p>
    </transition>
  </div>
</template>

<script>
export default {
  data(){
    return{
      show:true
    }
  }
}
</script>

<style scoped>
.fade-enter{}
.fade-enter-active{}
.fade-enter-to{}
.fade-enter-leave{}
.fade-enter{}
.fade-enter{}

.main{
  width: 70%;
  margin: auto;
  padding-top: 5rem;
  text-align: center;
}
</style>