<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Hola mundo</h1>
    <buttom @click="goToDayBook" class="btn btn-primary">Primary</buttom>
    <buttom @click="goToDayBook" class="btn btn-secondary">Secundary</buttom>
    <buttom @click="goToDayBook" class="btn btn-success">Succes</buttom>
  </div>
</template>

<script>


export default {
  name: 'Home',
  components: {
   
  },
  methods:{
    goToDayBook(){
      this.$router.push({ name: 'no-entry' })
    }
  }
}
</script>
