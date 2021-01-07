<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logo</h2>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/en/thumb/d/d3/Starbucks_Corporation_Logo_2011.svg/1200px-Starbucks_Corporation_Logo_2011.svg.png"
        alt=""
      />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Burger_King_logo.svg/1200px-Burger_King_logo.svg.png"
        alt=""
      />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/McDonald%27s_Golden_Arches.svg/1200px-McDonald%27s_Golden_Arches.svg.png"
        alt=""
      />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/en/thumb/d/d3/Starbucks_Corporation_Logo_2011.svg/1200px-Starbucks_Corporation_Logo_2011.svg.png"
        alt=""
      />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Burger_King_logo.svg/1200px-Burger_King_logo.svg.png"
        alt=""
      />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/McDonald%27s_Golden_Arches.svg/1200px-McDonald%27s_Golden_Arches.svg.png"
        alt=""
      />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Burger_King_logo.svg/1200px-Burger_King_logo.svg.png"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos",
};
</script>

<style scoped>
.title-header {
  margin-bottom: 80px;
  text-align: left;
}

.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}

.item-logos {
  float: left;
  margin-right: 70px;
  margin-bottom: 20px;
  width: 150px;
  height: 150px;
}

.item-logos .logo {
  width: 150px;
  height: 150px;
}
</style>