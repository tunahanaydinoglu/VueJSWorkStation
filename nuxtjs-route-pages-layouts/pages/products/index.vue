<template>
  <div class="container">
    <h3 class="title">Product List</h3>
    <!-- <div class="input-container">
      <input type="text" v-model="productID">
      <button class="button--green" @click="showProduct"> Show Product</button>
    </div> -->
    <p class="subtitle">Type the ID of the product you want to view.</p>
  </div>
</template>
 <script>
//   export default {
//     data(){
//       return {
//         productID : null
//       }
//     },
//     methods : {
//       showProduct(){
//         this.$router.push("/products/" + this.productID)
//       }
//     }
//   }
 </script>
<style scoped>

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    margin-top: 10px;
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }
  .container {
    min-height: 100vh;
    text-align: center;
    margin-top: 50px;
  }

</style>
