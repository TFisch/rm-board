<template>
  <ion-card class="byte-card">
    <ion-card-content>
      {{ name }}
      <audio ref="byte">
        <source src="assets/audio/ben_no.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </ion-card-content>
  </ion-card>
</template>

<script lang="ts">
import { IonCard, IonCardContent } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Byte',
  components: { IonCard, IonCardContent },
  props: {
    name: String
  },
  $refs: {
    byte: Object
  }
});
</script>

<style scoped></style>
