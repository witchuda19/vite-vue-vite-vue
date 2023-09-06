<template>
  <div id="app">
    <h1>เกมเป่ายิ้งฉุบ</h1>
    <GameComponent />
  </div>

</template>

<script>
import GameComponent from './components/game.vue';

export default {
  components: {
    GameComponent,
  },
};
</script>

<style>
#app {
  text-align: center;
  color: #000000;
  margin-top: 0px;
  background-color: #02ffff;
  width: 70%; /* ความกว้างเต็มหน้าจอ */
  height: 110vh; /* ความสูงเต็มหน้าจอ */
  display: flex;
  flex-direction: column;
}

h1 {
  font-size: 5em;
}

.player1-name {
  color: #111dff; 
}
.player2-name {
  color: #ff3730; 
}


.player-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}

.reset-button {
  margin-left: 70px; 
  background-color: #00a957; 
  color: #fff; 
  border-radius: 5px; 
}

.reset-button:hover {
  background-color: #008c47; 
}
.round-button:hover {
  background-color: #b10202ee; 
}

.round-button {
  
  background-color: #e70707; 
  color: #fff;
  border-radius: 5px; 
}

.score-container {
  background-color: #ffffff; 
  color: #000000; 
  padding: 3px; 
  margin-top: 15px; 
  text-align: center; 
  border-radius: 15px; 
  border: 2px solid #f6ff00; 
  max-width: 300px; 
  margin: 15px auto;
}

.score-text {
  margin: 0; 
}


</style>



