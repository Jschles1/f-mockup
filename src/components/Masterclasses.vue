<template>
  <div class="master-container">
    <div class="master-content">
      <h1>Your Successful Entrepreneurship Journey Starts Here</h1>
      <p>
        In addition to our mini lessons and workshops available within the app, you also get access to all of our Masterclasses. Masterclasses help you achieve one specific result and often contain a whole series of video lessons to teach you what you need to know from A-Z on a particular topic. New Masterclasses are being added every month - be sure to let us know in our Slack Channel which Masterclasses you would like to see shortly. Here are some of the Masterclasses you can start watching today:
      </p>

      <div class="master-row">
        <div class="master-box">

        </div>
        <div class="master-box">
          <p>
            30+ videos about unlocking your potential, developing your personal brand, growing your following on social media, and building real relationships. Use the power of Social Currency to become a prominent influencer and build a thriving personal brand all while living your purpose.
          </p>
        </div>
      </div>

      <div class="master-row">
        <div class="master-box">

        </div>
        <div class="master-box">
          <p>
            Overcome fear and become who you are capable of becoming. Learn how to break free of your limiting beliefs and get rid of all your fears with the new Mindset Masterclass.
          </p>
        </div>
      </div>

      <div class="master-row">
        <div class="master-box">

        </div>
        <div class="master-box">
          <p>
            Learn how to establish a mission, vision, recruit an early stage team, and bring your idea to reality in a big way with Adam Braun.
          </p>
        </div>
      </div>

      <div class="master-row">
        <div class="master-box">

        </div>
        <div class="master-box">
          <p>
            In this masterclass, learn how you can start your very OWN clothing brand that’ll make it in the industry.
          </p>
        </div>
      </div>

      <div class="master-row">
        <div class="master-box">

        </div>
        <div class="master-box">
          <p>
            In this Cryptocurrency Masterclass, you’ll learn how cryptocurrency works, how you can build a sustainable organization, and launch an ICO.
          </p>
        </div>
      </div>

      <div class="master-row">
        <div class="master-box">

        </div>
        <div class="master-box">
          <p>
            So you want to start making some money by selling things on Shopify, but you have no idea where to start, right? Emilio D’Angelo is a Shopify guru who took his business to a million dollars in six months and is going to teach you exactly how he did it.
          </p>
        </div>
      </div>

      <div class="master-row">
        <div class="payment-header hidden">

        </div>
        <div class="payment-header">
          <p>Most Popular</p>
        </div>
      </div>

      <div class="master-row">
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
  .master-container {
    background: linear-gradient(0deg,hsla(0,0%,100%,.1),hsla(0,0%,100%,0)),url(https://fownders.s3.us-east-2.amazonaws.com/BG-6.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    padding: 30px 0;

    .master-content {
      width: 80%;
      margin: 0 auto;
      color: white;
      text-align: center;

      .master-row {
        vertical-align: top;
        
        .master-box {
          overflow: hidden;
          display: inline-block;
          height: 250px;
          width: 400px;
          margin: 20px 10px;
          text-align: left;
        }

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
    }

    .credit-cards {
      margin-bottom: 100px;
      -webkit-box-reflect: below 0px -webkit-gradient(linear, left top, left bottom, from(transparent), to(rgba(250, 250, 250, 0.1)));
    }
  }

</style>