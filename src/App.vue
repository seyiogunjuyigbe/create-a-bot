<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" alt="Bot logo" src="./assets/build-a-bot-logo.png" />
            Build a bot
          </li>
        </ul>
      </nav>
    </header>

    <main>
      <RobotBuilder />
    </main>
  </div>
</template>

<script>
import RobotBuilder from "./build/RobotBuilder.vue";

export default {
  name: "App",
  components: {
    RobotBuilder,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
body {
  background: linear-gradient(to bottom #555, #999);
  background-attachment: fixed;
}
main {
  margin: 0 auto;
  padding: 30px;
  background-color: #fff;
  min-height: 300px;
  width: 100%;
}
header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
