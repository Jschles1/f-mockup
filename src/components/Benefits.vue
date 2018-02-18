<template>
  <div class="benefits-container">
    <div class="benefits-content">
      <h1>Join Fownders Today & <br>Get Instant Access To</h1>

      <div class="benefits-row">
        <div class="benefits-box">
          <h2>1. Fownders Learning:</h2>

          <h3>Mindset Masterclass:</h3>
          <p>Learn how to break free of your limiting beliefs and get rid of all your fears with the new MindsetMasterclass</p>

          <h3>Building A For Purpose Business Masterclass:</h3>
          <p>Learn how to establish a mission, vision, recruit an early stage team, and bring your idea toreality in a big way with Adam Braun.</p>

          <h3>The Fashion Blueprint Masterclass:</h3>
          <p>In this masterclass, learn how you can start your very OWN clothing brand that’ll make it in the industry.</p>

          <h3>Cryptocurrency Masterclass:</h3>
          <p>In this Cryptocurrency Masterclass you’ll learn how cryptocurrency works, how you can build a sustainable organization, and launch an ICO.</p>

          <h3>Social Currency Masterclass:</h3>
          <p>30+ videos on unlocking your potential, developing your personal brand, growing your following on social media, and building real relationships</p>

          <h3>Shopify Masterclass:</h3>
          <p>Learn how to build, launch and grow your new Shopify store step-by-step in 3 hours or less.</p>

          <h3>New Masterclasses Every Month:</h3>
          <p>Masterclasses help you achieve one specific result, and look to improve your overall quality of life. We release one or more a month.</p>

          <h3>50+ Exclusive Video Lessons:</h3>
          <p>Over 50+ videos produced with our experts and you get instant access to all of them.</p>

          <h3>Downloadable Workbooks:</h3>
          <p>Download secrets of the trade, we have checklists accompanying every masterclass and are great assets to use to your advantage!</p>
        </div>

        <div class="benefits-box">
          <p>Image</p>
        </div>
      </div>

      <div class="benefits-row">
        <div class="benefits-box">
          <p>Image</p>
        </div>

        <div class="benefits-box">
          <h2>2. Fownders Community</h2>

          <h3>Private Slack Channel:</h3>
          <p>Within this select group of entrepreneurs you will find mentors, leaders, and business owners from all over the globe.</p>

          <h3>Private Facebook Livestreams:</h3>
          <p>Our leadership team will answer your questions within the exclusive Facebook community via a private Facebook livestream every month.</p>
        </div>
      </div>

      <div class="benefits-row">
        <div class="benefits-box">
          <h2>3. Fownders Experiences</h2>

          <h3>An exclusive invitation to our Masterminds:</h3>
          <p>An exclusive event with our mentors, leaders and experts for our members.</p>

          <h3>An exclusive invitation to our Workshops:</h3>
          <p>Around branding, business, and better living, come become the best version of yourself with us.</p>

          <h3>An exclusive invitation to our Meetups:</h3>
          <p>Fireside chats, startup nights, and all around the country meet-ups. Come connect in-person!</p>
        </div>

        <div class="benefits-box">
          <p>Image</p>
        </div>
      </div>

      <h1 style="margin-top: 25px;">Join the learning ecosystem for entrepreneurs by <br>entrepreneurs.<br> Select your preferred membership package:</h1>

      <div class="payment-row">
        <div class="payment-header hidden">

        </div>
        <div class="payment-header">
          <p>Most Popular</p>
        </div>
      </div>

      <div class="payment-row">
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
  .benefits-container {
    background-color: #003e53;
    padding: 30px 0;

    .benefits-content {
      width: 80%;
      margin: 0 auto;
      color: white;
      text-align: center;

      h1 {
        color: goldenrod;
      }

      .benefits-row {
        margin-top: 80px;
        height: 100%;

        .benefits-box {
          display: inline-block;
          text-align: left;
          height: 100%;
          width: 45%;
          margin: 0 10px;
          vertical-align: top;
          
          h2 {
            margin-top: -50px;
            color: goldenrod;
          }

          h3 {
            color: skyblue;
          }
        }
      }

      .payment-row {
        .payment-header {
          overflow: hidden;
          display: inline-block;
          margin: 30px 11px -5px;
          height: 75px;
          width: 400px;
          border: 1px solid goldenrod;
          color: white;
          background: goldenrod;

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
          border: 1px solid goldenrod;
          margin: 0 10px 20px;
          text-align: center;

          .access {
            margin: 30px 0;
            padding: 6px 45px;
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
        }
      }
        
      .credit-cards {
        margin-bottom: 100px;
        -webkit-box-reflect: below 0px -webkit-gradient(linear, left top, left bottom, from(transparent), to(rgba(250, 250, 250, 0.1)));
      }
    }
  }
</style>