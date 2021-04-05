<template>
  <div id="navbar">
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Bugtracker on VueJS</ion-title>
      </ion-toolbar>
    </ion-header>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { IonHeader, IonToolbar } from "@ionic/vue";
export default defineComponent({
  name: "navBar",
  components: {
    IonHeader,
    IonToolbar,
  },
});
</script>
<style>
#navbar {
  position: absolute;
  left: 0;
  right: 0;
  height: 100px;
  background: linear-gradient(99deg, #9ad7c7 0%, #b8c3b8 100%);
}
</style>
