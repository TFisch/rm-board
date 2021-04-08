<template>
  <ion-card>
    <ion-card-header>
      <ion-avatar>
        <img
          src="https://static01.nyt.com/images/2020/04/22/science/22VIRUS-PETCATS1/merlin_150476541_233fface-f503-41af-9eae-d90a95eb6051-superJumbo.jpg?quality=90&auto=webp"
        />
      </ion-avatar>
    </ion-card-header>
    <ion-grid>
      <ion-row>
        <ion-col class="col-center-content">
          <Byte name="No" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
        <ion-col class="col-center-content">
          <Byte name="first" />
        </ion-col>
      </ion-row>
    </ion-grid>
  </ion-card>
</template>

<script lang="ts">
import {
  IonAvatar,
  IonCard,
  IonGrid,
  IonCol,
  IonRow,
  IonCardHeader
} from '@ionic/vue';
import Byte from './Byte.vue';

export default {
  name: 'BytesContainer',
  components: {
    IonAvatar,
    IonCard,
    IonGrid,
    IonCol,
    IonRow,
    Byte,
    IonCardHeader
  },
  props: {
    name: String
  }
};
</script>

<style scoped></style>
