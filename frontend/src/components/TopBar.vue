<template>
  <div id="topnav">
    <img src="../assets/logo.png" alt="logo" />
    <a>
      POLITICA
    </a>
    <a>
      ECONOMIE
    </a>
    <a>
      EXTERNE
    </a>
    <a>
      SPORT
    </a>
    <a>
      ACTUALITATE
    </a>
    <a id="info" href="info.html">
      INFO
    </a>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#topnav {
  background: var(--blue);
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
}

a {
  font-family: 'Stoke', serif;
  margin: 1%;
  font-size: 1.25rem;
  color: white;
}

img {
  height: 50px;
}

@media screen and (max-width: 600px) {
  a {
    display: none;
  }
  #info {
    display: block;
  }
}
</style>
