<template>
  <ion-content>
    <bytes-container></bytes-container>
    <audio ref="audioElm">
      <source src="assets/audio/ben_no.mp3" type="audio/mpeg" />
      Your browser does not support the audio element.
    </audio>
    <button v-on:click="play">X</button>
  </ion-content>
</template>

<script>
import BytesContainer from '@/components/BytesContainer.vue';
import { IonContent } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: {
    IonContent,
    BytesContainer
  },
  methods: {
    play: function(event) {
      console.log(this.$refs);
    }
  }
});
</script>

<style scoped>
.col-center-content {
  text-align: center;
}
</style>
