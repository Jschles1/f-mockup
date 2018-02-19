<template>
  <div class="footer-container">
    <div class="footer-sub-container">
      <div class="footer-content">
        <h2>F<span>OWN</span>DERS</h2>
      
        <ul>
          <li><a href="#">ABOUT</a></li>
          <li><a href="#">BLOG</a></li>
          <li><a href="#">CAREERS</a></li>
          <li><a href="#">TEAM</a></li>
          <li><a href="#">MENTORSHIP</a></li>
        </ul>
      </div>
    </div>
    <hr>
    <div class="footer-sub-container">
      <div class="footer-content">
        <p class="copy">&copy; Copyright 2017 Fownders. All Rights Reserved.</p>
        <ul class="tos">
          <li>PRIVACY POLICY</li>
          <li>TERMS OF SERVICE</li>
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
  .footer-container {
    background-color: black;
    padding: 30px 0;

    .footer-sub-container {
      margin-bottom: 20px;

      .footer-content {
        width: 80%;
        margin: 0 auto;
        color: white;
        text-align: center;
        position: relative;

        span {
          color: skyblue;
        }

        ul {
          padding: 0;

          li {
            display: inline;
            padding: 0 20px;
            border-right: 1px solid white;

            &:last-child {
              border: 0;
            }

            a {
              text-decoration: none;

              &:link, 
              &:visited {
                color: white;
              }

              &:hover,
              &:active {
                color: skyblue;
              }
            }
          }
        }

        .copy {
          font-size: 14px;
          float: left;
        }

        .tos {
          padding: 0;
          font-size: 14px;
          float: right;

          li {
            display: inline;
            padding: 0 10px;
            border-right: 1px solid white;

            &:last-child {
              border: 0;
            }

            a {
              text-decoration: none;

              &:link, 
              &:visited {
                color: white;
              }

              &:hover,
              &:active {
                color: skyblue;
              }
            }
          }
        }
      }
    }
  }  
</style>