<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 334</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 999</ion-title>
        </ion-toolbar>
      </ion-header>

      <ExploreContainer name="Tab 332 page" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent
} from '@ionic/vue';
import ExploreContainer from '@/components/Byte.vue';

export default {
  name: 'Tab2',
  components: {
    ExploreContainer,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonPage
  }
};
</script>
