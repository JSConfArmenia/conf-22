<template>
  <div class="Faq" id="Faq">
    <h2 class="Title"> FREQUENTLY ASKED QUESTIONS</h2>

    <div class="row Answers">
      <div class="col-md-6">
        <h3 class="Question">What is JavaScript Conference Armenia?</h3>
        <p class="Answer">
          JS Conf Armenia is an international annual JavaScript conference and the biggest tech conf in the region hosting 1000+ people every year.
        </p>
        <h3 class="Question">When and where is it going to take place?</h3>
        <p class="Answer">
          JSConfAM23 date and location will be announced. Stay tuned and follow our social media pages.
        </p>
        <h3 class="Question">What is the conference language?</h3>
        <p class="Answer">
          The conference will be held in Armenian, English and Russian depending on the speaker.
        </p>
        <h3 class="Question">Who are the speakers?</h3>
        <p class="Answer">
          Anyone who has knowledge to share with developer peers who use JavaScript.
          <!-- To learn more about our speakers, please,
          <a href="#Speakers">click here</a>. -->
        </p>
        <!-- <h3 class="Question">What are the talk topics?</h3>
        <p class="Answer">
          To see the conf agenda, please,
          <a href="#Schedule">click here</a>.
        </p> -->
        <h3 class="Question">Who are the organizers? </h3>
        <p class="Answer">
          To see JS Conf Armenia team, please,
          <a href="#Team">click here</a>.
        </p>
        <!-- <h3 class="Question">Who supports JS Conf Armenia?</h3>
        <p class="Answer">
          Armenian and regional tech companies who value community events and experience exchange activities.
          To learn about our sponsors and partners, please,
          <a href="#Sponsors">click here</a>.
        </p> -->
      </div>

      <div class="col-md-6">
        <h3 class="Question">How to participate?</h3>
        <p class="Answer">
          The registration call will be announced accordingly. Follow our social media for the updates.
          <!-- The entry is invite-only. Send your invite request <a href="https://bit.ly/joinJSConfAM22">here</a>. -->
        </p>
        <h3 class="Question">How much is the entry-ticket?</h3>
        <p class="Answer">
          The invitation ticket is free of charge.
        </p>
        <!-- <h3 class="Question">When is the deadline for registration?</h3>
        <p class="Answer">
          The last batch of invitation tickets will be sent on October 14 at 22:00. Make sure to request your ticket before that.
        </p> -->
        <!-- <h3 class="Question">How can I help the team?</h3>
        <p class="Answer">
        This year we are not accepting volunteer applications but you can share the word about the conf that will be appreciated.
        </p> -->
        <h3 class="Question">How to become a speaker?</h3>
        <p class="Answer">
          Sign up <a href="https://bit.ly/3Se0b9l">here</a> for conference speaker opportunities in 2024.
          <!-- Submit your topics <a href="https://bit.ly/speakJS2022">here</a>. -->
        </p>
        <h3 class="Question">How to become a sponsor?</h3>
        <p class="Answer">
          Sign up <a href="https://bit.ly/3qRPuOm">here</a> for conference news and sponsorship opportunities in 2024.
          <!-- Request JSConfAM22 sponsorship info <a href="http://bit.ly/supportJSConfAM22">here</a>. -->
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped lang="scss">
.Faq {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  flex-direction: column;
  padding: 100px 0;
}

a {
  color: #4bb463;
  font-weight: bold;
}


.Title {
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 50px;
  color: #198dbf;
}

.Question {
  color: #333;
}

.Answer {
  margin-bottom: 1.5em;
}

.Answers {
  width: 65%;
}

@media (max-width: 768px) {
  .Faq {
    padding: 50px 0 20px;
  }

  .Answers {
    width: 100%;
  }

  .Title {
    font-size: 1.6em;
    margin-bottom: 20px;
  }

  .Question {
    font-size: 1em;
  }
}
</style>
