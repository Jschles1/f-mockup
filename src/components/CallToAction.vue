<template>
  <div class="call-container">
    <div class="call-content">
      <h1>Get Instant Access to the 3-Key Components to <br>Success</h1>
      
      <p>
        1.) Become Self-Aware: Learn from top practitioners how to master emotional intelligence, mindfulness, productivity, health and wellness, understanding your strengths and weaknesses, and more!
      </p>

      <p>
        2.) Become Skilled: Top experts teach you exactly how to do digital marketing, finance management, data analytics, growth hacks, and other important tactical ways to scale your business
      </p>

      <p>
        3.) Become Profitable: Hear from your favorite entrepreneurs on how to build your team, grow your income quickly, manage your operations, and other vital aspects of assuring you get paid and make an impact
      </p>

      <img src="https://fownders.s3.us-east-2.amazonaws.com/media.png" alt="Fownders Media">

      <div class="call-row">
        <div class="payment-header hidden">

        </div>
        <div class="payment-header">
          <p>Most Popular</p>
        </div>
      </div>

      <div class="call-row">
        <div class="payment-box">
          <p>Monthly</p>
          <p>$27/mo</p>
          <button class="access">GET INSTANT ACCESS</button>
          <p>Reoccuring Monthly Payment</p>
        </div>
        <div class="payment-box">
          <p>Annual</p>
          <p>$247</p>
          <button class="access">GET INSTANT ACCESS</button>
          <p>One Annual Payment</p>
        </div>
      </div>

      <p>For your security, all orders are processed on a secured server.</p>

      <div class="credit-cards">
        <img src="../assets/visa.png" alt="Visa">
        <img src="../assets/mastercard.png" alt="Master Card">
        <img src="../assets/amex.png" alt="American Express">
        <img src="../assets/discover.png" alt="Discover">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .call-container {
    background-image: url(https://fownders.s3.us-east-2.amazonaws.com/BG-11.jpg);
    background-size: cover;
    padding: 30px 0;

    .call-content {
      width: 80%;
      margin: 0 auto;
      color: white;
      text-align: center;
    }

    .call-row {
      vertical-align: top;

      .payment-header {
        overflow: hidden;
        display: inline-block;
        margin: 30px 11px -5px;
        height: 75px;
        width: 400px;
        border: 1px solid skyblue;
        color: white;
        background: linear-gradient(rgb(30, 186, 238), darken(rgb(30, 186, 238), 15%));

        p {
          padding-top: 12px;
        }
      }

      .payment-header.hidden {
        background: none;
        border: 0;
      }

      .payment-box {
        background-color: rgba(0,0,0,.1);
        overflow: hidden;
        display: inline-block;
        height: 250px;
        width: 400px;
        border: 1px solid skyblue;
        margin: 0 10px 20px;
        text-align: center;

        .access {
          margin: 30px 0;
          padding: 6px 45px;
          border-radius: 4px;
          font-size: 100%;
          color: white;
          border: 0.5px solid white;
          background: linear-gradient(rgb(30, 186, 238), darken(rgb(30, 186, 238), 15%));

          &:hover {
            cursor: pointer;
            box-shadow: 0 1px 1px rgb(59, 59, 59);
          }
        }
      }
    }

    .credit-cards {
      margin-bottom: 100px;
      -webkit-box-reflect: below 0px -webkit-gradient(linear, left top, left bottom, from(transparent), to(rgba(250, 250, 250, 0.1)));
    }
  }
</style>