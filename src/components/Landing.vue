<template>
  <div class="home">
    <section class="header">
      <h1 class="firstName">SAM</h1>
      <h2 class="secondName">SLIKE</h2>
    </section>
    <div class="nav">
      <router-link  class="link" to="/">Home</router-link>
      <!-- <router-link  class="link" to="/" event="">Experience</router-link> -->
      <router-link  class="link" to="/projects">Projects</router-link>
      <a class='link' href="./Sam_Slike_Resume.pdf" target="_blank">Resume</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Landing",
};
</script>


<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Unica+One&display=swap');

.home {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 30%;
  max-height: 200px; 
  background: #FFFFFF 0% 0% no-repeat padding-box;
  opacity: 1;
  justify-content: space-between;
  align-items: center;
  .header {
    display: flex;
    flex-direction: column;
    .firstName {
      letter-spacing: 0;
      color: #456496;
      opacity: 1;
      font-size: 89px;
      font-family: 'Unica One';
      margin: 30% 0 0 17%;
    }
    .secondName {
      text-align: left;
      font-family: 'Unica One';
      font-size: 65px;
      letter-spacing: 0;
      color: #456496;
      opacity: 1;
      margin: 0 0 30% 17%;
    }
  }
  .nav {
    display: flex;
    flex-direction: column;
    margin: 2% 5% 0 0;
    .link {
      text-align: right;
      font-family: 'Unica One';
      font-size: 25px;
      letter-spacing: 0;
      color: #456496;
      opacity: 1;
      text-decoration: none;
      margin-bottom: 8%;
      &:hover {
        color: black;
      }
    }
  }
}

</style>
