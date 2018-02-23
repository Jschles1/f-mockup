<template>
  <div class="comm-container">
    <div class="comm-content">
      <h1>Advance Your Business & Your Lifestyle</h1>
      <p>
        Join a global community of like-minded entrepreneurs, creatives, and visionaries. Be inspired to think bigger, contribute back, and receive support while you express your purpose.
      </p>
      <div class="comm-row">
        <div class="comm-box-img">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/Slack%20%281%29.jpg" alt="Slack">
        </div>
        <div class="comm-box">
          <h3>SLACK COMMUNITY</h3>
          <p>
            Our Premium Private Slack Channel is the place for you to interact and build real relationships with other entrepreneurs around the world. Within this select group of entrepreneurs you will find mentors, leaders, and business owners from all over the globe.
          </p>
        </div>
      </div>

      <div class="comm-row">
        <div class="comm-box">
          <h3>FACEBOOK LIVESTREAMS</h3>
          <p>
            Our leadership team and mentors will answer your questions on personal and business development, tactical marketing strategies, and more within the exclusive Facebook community via a private Facebook live stream every month.
          </p>
        </div>
        <div class="comm-box-img">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/Livestream%20%281%29.jpg" alt="Facebook Livestream">
        </div>
      </div>

      <div class="comm-row">
        <div class="comm-box-img">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/Downloadable%20%281%29.jpg" alt="Downloadable">
        </div>
        <div class="comm-box">
          <h3>DOWNLOADABLE RESOURCES</h3>
          <p>
            Download secrets of the trade! Each Masterclass includes checklists that are significant assets to use to your advantage.
          </p>
        </div>
      </div>

      <div class="comm-row">
        <div class="comm-box">
          <h3>OFFLINE EXPERIENCES</h3>
          <p>
            What you get is priority access and discounts to our best events, experiences, and gatherings. Network at our startup grinds, workshops, masterminds, and summits. And most importantly: build real personal connections with amazing people that care about providing you value.
          </p>
        </div>
        <div class="comm-box-img">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/bg-offline.jpg" alt="Offline">
        </div>
      </div>

      <br>

      <button class="join community-join">JOIN FOWNDERS</button>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .comm-container {
    background-image: url(https://cdn2.hubspot.net/hubfs/3357911/sales-page-bg/H6.png);
    background-size: cover;
    background-color: skyblue;
    padding: 30px 0;

    .comm-content {
      width: 80%;
      margin: 0 auto;
      color: white;
      text-align: center;
      

      .comm-row {
        display: inline-block;
        vertical-align: top;
        
        .comm-box {
          overflow: hidden;
          display: inline-block;
          height: 210px;
          width: 350px;
          margin: 20px 10px;
          text-align: left;
        }

        .comm-box-img {
          display: inline-block;
          height: 210px;
          width: 350px;
          margin: 20px 10px;
          text-align: left;

          img {
            height: 100%;
            box-shadow: 0 16px 24px 2px rgba(0,0,0,.14), 0 6px 30px 5px rgba(0,0,0,.12), 0 8px 10px -5px rgba(0,0,0,.3);
          }
        }
      }

      .community-join {
        margin: 32px 0;
      }
    }
  }
</style>