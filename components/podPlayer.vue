<template>
<div>
  <div class="body">
    <audio controls>
  <source src="https://ia800905.us.archive.org/19/items/FREE_background_music_dhalius/backsound.mp3"  type="audio/mp3">
  
</audio>  


  </div>
  </div>
</template>

<script>
export default {
 
}
</script>

<style scoped>
.body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  overflow: hidden;
  background: linear-gradient(to bottom right, #b968c5, skyblue);
}

.audio-player {
  height: 50px;
  width: 350px;
  background: #444;
  box-shadow: 0 0 20px 0 #000a;

  font-family: arial;
  color: white;
  font-size: 0.75em;
  overflow: hidden;

  display: grid;
  grid-template-rows: 6px auto;
 
  
  
}
</style>