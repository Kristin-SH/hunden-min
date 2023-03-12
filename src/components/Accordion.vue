<template>
   <div id="app">
     <div class="demo-container">
      <div class="demo-img">
        <img src="src\assets\images\agility.jpeg" alt="">
        <button @click="isShowing ^= true">Click Me</button>
      </div>
      <div v-show="isShowing" class="demo-text">
        <h1>Lorem ipsum dolor sit amet.</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Assumenda, maiores perspiciatis voluptates earum blanditiis quis officiis illo corrupti. Repellat corporis sed expedita possimus pariatur deserunt quis illum, excepturi ipsa eos labore neque repudiandae a deleniti iste nam cumque, debitis laboriosam?</p>
      </div>
     </div>

 </div>
</template>

<script>
export default {
  data() {
        return {
            isShowing:false
        }
    }
};
</script>

<style scoped>
.demo-container {
  display: flex;
}
</style>