<template>
  <div id="header">
    <img src="./assets/Logo_Club_bw.png" alt="CLUB Logo" />
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/help">Help</router-link>
      <router-link to="/about">About</router-link>
    </div>
  </div>
  <router-view />
</template>



<style>
@import url("https://fonts.googleapis.com/css?family=Orbitron");
@import url('https://fonts.googleapis.com/css2?family=Jost');
/* @font-face {
  font-family: 'Orbitron';
  font-weight: normal;
  src: url("https://fonts.googleapis.com/css2?family=Orbitron&display=swap");
}

@font-face {
  font-family: 'Orbitron';
  font-weight: bold;
  src: url("https://fonts.googleapis.com/css2?family=Orbitron:wght@400;900&display=swap");
} */
</style>

<style>
:root {
  --bg-black: #2c2c2c;
}

#app {
  font-family: "Orbitron", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  display: flex;
  flex-direction: column;
  background: url("./assets/background.jpg") no-repeat;
  background-attachment: fixed;
  background-size: cover;
  width: 100vw;
}

#header {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  padding: 5%;
  /* background-color: var(--bg-black); */
  background-position-x: 100%;
  background-size: 60%;
  height: 12vh;
  overflow: visible;
}

#nav {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 50%;
  margin: 5%;
}

#nav a {
  font-weight: bold;
  text-decoration: none;
  color: #ffffff;
  font-size: 24px;
}

#nav a:focus {
  color: rgba(64, 221, 194, 0.5);
}

h1 {
  display: flex;
  justify-content: center;
  text-align: center;
  font-size: 2.5em;
  letter-spacing: 0.3em;
  text-transform: uppercase;
}

h2 {
  font-size: 1.5em;
  margin: 0;
  letter-spacing: 0.1em;
}

p{
  font-family: "Jost";
  font-size: 1.3em;
}
</style>
