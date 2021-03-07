<template>
  <div class="home flex justify-center flex-col items-center">
    <h1 class="text-5xl">Welcome!</h1>
    <img
        class="hidden md:block w-full h-64 object-cover"
        src="https://source.unsplash.com/random"
        alt=""
    />
    <div class="flex flex-col -m-24 items-center bg-gray-400 w-1/3 p-10 rounded-lg shadow-xl">
      <img
          class="h-64 w-64 rounded-full object-cover"
          src="https://source.unsplash.com/random"
          alt=""
      />
      <h5 class="text-2xl font-semibold">Some Image Information</h5>
      <p class="text-left mt-4">
        <span class="sm:text-purple-900 md:text-indigo-50 font-extrabold">Nunquam convertam</span> ratione. Fortune is a golden girl. Why
        does the cosmonaut warp? Fly wildly like a carnivorous
        planet. The c-beam warps mind like a virtual starship. Equisos observare in hamburgum! None of these loves will
        be lost in mysteries like sonic showers in alarms</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
