<template>
  <ion-page
    ><ion-content><h1>this is login</h1> </ion-content></ion-page
  >
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { IonContent, IonPage } from "@ionic/vue";
export default defineComponent({
  name: "Login",
  components: {
    IonContent,
    IonPage,
  },
});
</script>
