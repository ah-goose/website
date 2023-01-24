<template>
  <div class="home">
    <img class="logo" src="https://ahgoose.s3.us-east-2.amazonaws.com/ah-goose-dev.jpeg" alt="Ah Goose logo - pixel art of a cool looking goose with sunglasses" />
    <ul class="desc">
      <li class="first-li">Indie Games</li>
      <li>by Agustin Diaz-Barriga</li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style >
  .home {
    text-align: center;
  }
.logo {
  
}
.desc {
  font-size: 30px;
  display: inline-block;
  max-width: 500px;
  list-style: none;
  paddin: 0;
  margin: 10px;
  text-align: justify;
}
.first-li {
  font-size: 35;
  font-weight: 800;
  color: #3f3f74;
}
</style>