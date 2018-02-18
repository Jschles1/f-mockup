<template>
  <div class="feedback-container">
    <div class="feedback-content">
      <h1>Feedback from Fownders Members</h1>

      <div class="feedback-row">
        <div class="feedback-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/Faan-Rossouw.jpg" alt="Faan Rossouw">
          <p>
            "I LOVE that you guys are also posting real-world instructional videos that with practical advice and steps on how to get started! Appreciate all the other content too, but this is a great way to balance it out and give us some channels through which we can channel all that inspiration. I would also love if you guys could add a MasterClass on Personal Investing, Inbound Marketing, and Copywriting. Thanks G!"
          </p>
          <p class="quote-author">- Faan Rossouw</p>
        </div>

        <div class="feedback-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/cameronrn.jpg" alt="Cameronrn">
          <p>
            "Your motivational posts are the greatest, always stoked to see these, I legit sometimes even come here and scroll to look for past ones you posted. Rock on, looking forwards to more and more."
          </p>
          <p class="quote-author">- Cameronrn</p>
        </div>
      </div>

      <div class="feedback-row">
        <div class="feedback-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/Danny-Lizalde.jpg" alt="Danny Lizalde">
          <p>"This is exactly the training I needed. Love this community."</p>
          <p class="quote-author">- Danny Lizdale</p>
        </div>

        <div class="feedback-box">
          <img src="https://fownders.s3.us-east-2.amazonaws.com/Screen%20Shot%202018-01-03%20at%209.55.21%20PM.png" alt="deechapp032">
          <p>
            "Feels good to finally be around like minded people, I felt I’ve been missing something and I believe I’m one step closer to fulfilling my purpose and self mastery!"
          </p>
          <p class="quote-author">- deechapp032</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .feedback-container {
    background-color: white;
    padding: 30px 0;

    .feedback-content {
      width: 80%;
      margin: 0 auto;
      text-align: center;

      h1 {
        color: skyblue;
        margin-bottom: 40px;
      }

      .feedback-row {
        height: 100%;
        
        .feedback-box {
          display: inline-block;
          overflow: auto;
          border-top: 1px solid lightgray;
          height: 100%;
          width: 45%;
          margin: 0 5px;
          vertical-align: top;

          img {
            margin-top: 25px;
            width: 100px;
            height: 100px;
            border-radius: 100%;
          }

          .quote-author {
            color: skyblue;
          }
        }
      }
    }
  }
</style>

