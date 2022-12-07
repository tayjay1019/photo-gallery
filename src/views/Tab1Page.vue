<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>About Page</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">About Page</ion-title>
        </ion-toolbar>
      </ion-header>
      <p>This will be a test of how well I as a new mobile developer can use this new system after a couple weeks.
          I am not currently finished but will continue to work on this for the rest of my time in the semeseter</p>
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
