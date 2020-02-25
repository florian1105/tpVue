<template>
<div id="app">
  <img width="25%" src="./assets/photo.jpg" id="imgAcc">
  <Header msg="Welcome to my PortFolio"></Header>
  <body>
    <FirstBody/>
    <SecBody/>
  </body>
  <Footer msg="Footer"/>
</div>
</template>

<script>
import Header from "./components/base/Header";
import Footer from "./components/base/Footer";
import FirstBody from "./components/base/body/firstBody";
import SecBody from "./components/base/body/secBody";

export default {
  name: "App",
  components: {
    Header,
    Footer,
    FirstBody,
    SecBody
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#imgAcc {
  border-radius: 50%;
}
</style>
