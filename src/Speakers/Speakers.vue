<template>
  <section class="Speakers">
    <div class="Container" id="Speakers">
      <h2 class="Title">Speaker<br><span class="Accent">opportunities</span></h2>
      <p class="IntroText">
          Sign up for call for speaker news in 2024
      </p>
      <!-- <h2 class="Title">Who are<br><span class="Accent">The Speakers?</span></h2>
      <div class="row no-gutters justify-content-center">
        <div
          class="col-md-3 SpeakerCol"
          v-for="speakerId in speakersList"
          :key="speakerId">
          <div class="Speaker">
            <div
              class="Img"
              :style="{
                backgroundImage: `url(${speakers[speakerId].img})`
              }">
            </div>
            <h3 class="Name">{{speakers[speakerId].name}}</h3>
            <h5 class="Position">{{speakers[speakerId].position}}</h5>
          </div>
        </div>
      </div> -->
      <div class="CallToActionContainer">
        <!-- <a href="https://bit.ly/speakJS2022" class="Button -call-to-action" target="_blank">
          Become a Speaker!
        </a> -->
        <a href="https://bit.ly/3Se0b9l" class="Button -call-to-action" target="_blank">
          Subscribe
        </a>
      </div>
    </div>
    <div class="SpeakersBg"></div>
  </section>
</template>

<script>
import speakers from '@/_services/speakers';

export default {
  data: () => ({
    speakers,
    speakersList: [
      'suren',
      'gleb',
      'lilit',
      'sandro',
      'natalia',
      'davit',
      'illya',
      'elmira',
      'hrach',
      'vitaly',
      'nairi',
      'armenv',
      'vasiliy',
      'david',
      'armen',
      'yonatan',
      'varuzhan',
      'arsen',
      'mike',
      'khachatur',
    ],
  }),
  methods: {
    getSpeaker: function getSpeaker(speakerId) {
      return this.speakers[speakerId];
    },
  },
};
</script>

<style scoped lang="scss">
.Speakers {
  padding:  100px 0 50px 0;
  position: relative;
}

.IntroText {
 font-size: 2em;
  font-weight: normal;
  line-height: 1.2em;
  margin-bottom: 1em;
}

.Title {
  font-size: 4em;
  font-weight: normal;
  line-height: 1.2em;
  margin-bottom: 1em;

  .Accent {
    font-size: 1.2em;
    color: #93d8f7;
    font-weight: 900;
  }
}

.SpeakerCol {
  display: flex;
  justify-content: center;
}

.Speaker {
  max-width: 200px;
  width: 100%;
  text-align: center;
  margin-bottom: 25px;
}

.Img {
  width: 100%;
  padding-bottom: 100%;
  margin-bottom: 10px;
  background-size: cover;
  border: 1px solid #ccc;
  background-color: #fff;
  border-radius: 50%;
  filter: grayscale(90%);
  transition: .3s ease all;
}

.Speaker:hover {
  .Img {
    filter: grayscale(0);
  }
}

.Name {
  margin-bottom: 0;
  font-size: 1em,
}

.Position {
  color: #999;
  font-size: 0.8em,
}

.CallToActionContainer {
  padding-top: 50px;
  text-align: center;
}

.SpeakersBg {
  position: absolute;
  z-index: -1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-repeat: no-repeat;
  background-image: url('./SpeakersBg.svg');
  background-size: 70%;
  background-position-y: 12%;
  background-position-x: right;
}

@media (max-width: 600px) {
  .Title {
    font-size: 3em;
  }

  .Speakers {
    padding: 50px 0 50px;
  }
}
</style>
