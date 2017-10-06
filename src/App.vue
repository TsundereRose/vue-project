<template>
  <div>
      Hello Vue
      <hr>
      {{name}}

      <router-view></router-view>
  </div>
</template>



<script>
export default {
  data(){
      return {
          name: "zs"
      }
  }
}
</script>

<style>

</style>

