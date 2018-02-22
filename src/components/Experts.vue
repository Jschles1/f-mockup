<template>
  <div class="experts-container">
    <div class="experts-content">
      <h1 class="experts-main-header">Learn from THE Experts...</h1>
      <h1>the ones you wish you knew when you started!</h1>

      <p>
        Fownders partners with legendary experts across a variety of fields. They share their knowledge and experience with you in their lessons, Masterclasses, and workshops. Here are just a few lessons you can start watching today:
      </p>

      <div class="expert-row">
        <div class="expert-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/lewishowes.jpg" alt="Lewis Howes">
        </div>
        <div class="expert-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/TomBilyeu.jpg" alt="Tom Bilyeu">
        </div>
      </div>

      <div class="expert-row">
        <div class="expert-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/EricThomas.jpg" alt="Eric Thomas">
        </div>
        <div class="expert-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/MonicaAdams.jpg" alt="Monica Adams">
        </div>
      </div>

      <div class="expert-row">
        <div class="expert-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/mona.jpg" alt="Mona">
        </div>
        <div class="expert-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/toby.jpg" alt="Toby">
        </div>
      </div>
      <button class="join">JOIN FOWNDERS</button>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .experts-container {
    background-image: url(https://cdn2.hubspot.net/hubfs/3357911/sales-page-bg/H5.png);
    background-size: cover;
    background-color: #003e53;
    padding: 30px 0;

    .experts-content {
      width: 80%;
      margin: 0 auto;
      text-align: center;
      color: white;

      .experts-main-header {
        color: skyblue;
      }

      .expert-row {
        
        .expert-box {
          display: inline-block;
          height: 250px;
          width: 400px;
          margin: 20px 20px;

          img {
            height: 100%;
            box-shadow: 0 16px 24px 2px rgba(0,0,0,.14), 0 6px 30px 5px rgba(0,0,0,.12), 0 8px 10px -5px rgba(0,0,0,.3);
          }
        }
      }
    }
  }
</style>