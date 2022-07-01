<template>
  <div class="container">
         <Toggle :mode="mode" @toggle="$emit('toggle')" />
     <!-- <p>podcast title : </p>
    <input type="text"  placeholder="Enter your podcast title"> --> 
     
    <label
      for="website-admin"
      class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
      >Enter the  podcast title </label
    >
    <div class="flex">
      <span
        class="
          inline-flex
          items-center
          px-3
          text-sm text-gray-900
          bg-gray-200
          rounded-l-md
          border border-r-0 border-gray-300
          dark:bg-gray-600 dark:text-gray-400 dark:border-gray-600
        "
      >
        @
      </span>
      <input
        type="text"
        id="website-admin"
        class="
          rounded-none rounded-r-lg
          bg-gray-50
          border
          text-gray-900
          focus:ring-blue-500 focus:border-blue-500
          block
          flex-1
          min-w-0
          w-full
          text-sm
          border-gray-300
          p-2.5
          dark:bg-gray-700
          dark:border-gray-600
          dark:placeholder-gray-400
          dark:text-white
          dark:focus:ring-blue-500
          dark:focus:border-blue-500
        "
        placeholder="*******"
      />
     
    </div> 
    <button>start</button>
    
  </div>
</template>

<script>
import Toggle from './Toggle.vue';
export default {
  components:{
    Toggle
  }
};
</script>

<style>
.container {
  background-color:azure;
  border: 1px solid black;
  height: 300px;
  top: 40px;
  left: 40px;
  width: 78%;
  margin: 100px;
}
p input{
  margin: 60px;
 
}
</style>