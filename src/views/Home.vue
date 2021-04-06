<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>
          <img src="assets/icon/logo-white.png" alt="logo" class="logo" />
        </ion-title>
        <ion-buttons end>
          <ion-menu-button></ion-menu-button>
        </ion-buttons>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-card>
        <ion-card-header>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
          <ion-card-title>Card Title</ion-card-title>
        </ion-card-header>

        <ion-card-content>
          Keep close to Nature's heart... and break clear away, once in awhile,
          and climb a mountain or spend a week in the woods. Wash your spirit
          clean.
        </ion-card-content>
      </ion-card>

      <ion-card>
        <ion-item>
          <ion-icon :icon="pin" slot="start"></ion-icon>
          <ion-label>ion-item in a card, icon left, button right</ion-label>
          <ion-button fill="outline" slot="end">View</ion-button>
        </ion-item>

        <ion-card-content>
          This is content, without any paragraph or header tags, within an
          ion-card-content element.
        </ion-card-content>
      </ion-card>
      <ion-card>
        <ion-item href="#" class="ion-activated">
          <ion-icon :icon="wifi" slot="start"></ion-icon>
          <ion-label>Card Link Item 1 activated</ion-label>
        </ion-item>

        <ion-item href="#">
          <ion-icon :icon="wine" slot="start"></ion-icon>
          <ion-label>Card Link Item 2</ion-label>
        </ion-item>
      </ion-card>
      <ion-card> This is card 4</ion-card>
      <ion-card> This is card 5</ion-card>
      <ion-card> This is card 6</ion-card>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonHeader,
  IonPage,
  IonToolbar,
  IonTitle,
  // IonMenu,
  IonMenuButton,
  IonButtons,
} from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
  components: {
    IonToolbar,
    IonPage,
    IonHeader,
    IonTitle,
    // IonMenu,
    IonMenuButton,
    IonButtons,
  },
});
</script>
