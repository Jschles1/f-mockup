<template>
  <div class="intro-container">
    <div class="intro-content">
      <h1>Join Fownders</h1>
      <h1>For Entrepreneurs By Entrepreneurs</h1>
      <p>
        Fownders is a learning platform composed of videos and courses you need as an entrepreneur to succeed in mindset, marketing, business growth, and community. Learn specific skills you need to thrive from the most successful entrepreneurs in the game. Network, collaborate and find accountability with aspiring entrepreneurs just like you, determined to succeed.
      </p>
      <button class="join">JOIN FOWNDERS</button>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .intro-container {
    background-color: skyblue;
    padding: 30px 0;

    .intro-content {
      width: 80%;
      margin: 0 auto;
      color: white;
      text-align: center;
    }
  }

  .join {
    padding: 18px 55px;
    border-radius: 4px;
    font-size: 100%;
    color: white;
    border: 0.5px solid white;
    background: linear-gradient(orange, orangered);

    &:hover {
      cursor: pointer;
      box-shadow: 0 1px 1px rgb(59, 59, 59);
    }
  }

  h1 {
    margin: 0;
  }
</style>