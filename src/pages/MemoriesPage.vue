<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
      <ion-title>The Memories Page</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item>Max</ion-item>
        <ion-item>George</ion-item>
        <ion-item>Julie</ion-item>
        <ion-item>Filippo</ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>


<script>
import { IonPage, IonHeader, IonTitle, IonContent, IonToolbar, IonList, IonItem } from "@ionic/vue";
export default {
  components: {
    IonPage,
    IonHeader,
    IonTitle,
    IonContent,
    IonToolbar,
    IonList,
    IonItem
  },
};
</script>
