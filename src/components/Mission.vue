<template>
  <div class="mission-container">
    <div class="mission-content">
      <h1>Unlock Your Greatest Potential With The Right Resources</h1>
      <p>
        Fownders was built out of a necessity for aspiring entrepreneurs to have a place to develop the hard, tactical skills needed to succeed. The skills that are not taught in school.
      </p>
      <div class="mission-list">
        <ul>
          <li>
            <div>
              <i class="material-icons">check</i>
            </div>
            <div>
              <p>Our focus is to bring you knowledge from the best in the game to teach you personal development, business development, and influencer development skills all vital to succeeding as an entrepreneur in today’s world.</p>
            </div>
          </li>
          <li>
            <div>
              <i class="material-icons">check</i>
            </div>
            <div>
              <p>Join our powerful circle of influence, network, form connections, and build a community of support in our exclusive Slack Channel.</p>
            </div>
          </li>
          <li>
            <div>
              <i class="material-icons">check</i>
            </div>
            <div>
              <p>Instantly gain access to hundreds of hours of exclusive video content that was designed to help you level up and grow your business quickly and efficiently.</p>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .mission-container {
    background-color: white;
    padding: 30px 0;
  }

  .mission-content {
    width: 80%;
    margin: 0 auto;
    color: skyblue;
    text-align: center;

    p {
      color: black;
    }

    .mission-list {
      width: 80%;
      margin: 0 auto;

      li {
        list-style: none;
        display: flex;

        p {
          color: skyblue;
        }

        i {
          color: orangered;
          line-height: 55px;
          font-weight: bolder;
        }
      }
    }
  }
</style>