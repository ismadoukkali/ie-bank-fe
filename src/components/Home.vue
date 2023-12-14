<template>
    <div id="app">
      <section class="header">
        <h1>Welcome to Isma's Online Bank</h1>
        <h3>This is done to get a good grade.</h3>
      </section>
      <template>
        <div class="button-container">
          <router-link to="/skull" class="button">Skull babyyy</router-link>
          <router-link to="/accounts" class="button">My Accounts</router-link>
        </div>
      </template>
      <section class="section">
        <h2>How to use:</h2>
        <p>Click on Skull to test .env connections. <br> Click on My accunts to, well - manage your accounts.</p>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    name: 'WelcomePage'
  }
  </script>
  
  <style scoped>
body {
  font-family: Arial, sans-serif;
}


.header {
  padding: 40px;
  text-align: center;
  color: rgb(0, 0, 0);
}

.header h3 {
  text-align: center;
  color: rgb(170, 170, 170);
}

.section {
  padding: 50px;
}


.section h2 {
  text-align: center;
  color: rgb(0, 0, 0);
}

.section p {
  text-align: center;
  color: rgb(0, 0, 0);
}

.button-container {
  display: flex;
  justify-content: center;
  margin-top: 50px;
}


.button {
  margin: 0 10px;
  padding: 10px 20px;
  background-color: #81ea9f;
  color: #ffffff;
  text-decoration: none;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}
</style>
