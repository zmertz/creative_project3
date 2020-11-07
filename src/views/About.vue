<template>
  <div class="about">
    <h1>About page</h1>

    <br>
    <h3> This application was created using the Vue CLI, a useful front end development tool
    that helps developers like myself keep up with the growing demands new technology and
    fast creation. </h3>

    <br>
    <h3>Special thanks to our cartographer, Google Images, who made all this possible! </h3>

    <img :src="'/images/States/USA.jpg'">
  </div>
</template>


<style scoped>

.h3 {
	display: flex;
	justify-content: left;
}

</style>