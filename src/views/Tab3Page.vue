<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Facts Page</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Facts Page</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-grid>
      <ion-row>
          <ion-col size="6">
            <p>First place!</p>
          </ion-col>
      </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonGrid, IonRow, IonCol } from '@ionic/vue';

export default defineComponent({
  name: 'Tab3Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonGrid, IonRow, IonCol }
});
</script>
