<template>
  <ion-app>
    <ion-page>
    <ion-header>
      <ion-row>
        <ion-col>
          <ion-item @click="$router.push({name:'Home'})"> Inicio </ion-item>
        </ion-col>
        <ion-col>
          <ion-item @click="$router.push({name:'QuienesSomos'})"> Quienes Somos</ion-item>
        </ion-col>
      </ion-row>
    </ion-header>
    <ion-content><ion-router-outlet slot="fixed" /></ion-content>
    </ion-page>
  </ion-app>
</template>

<script setup>
import { IonApp,IonItem,IonRow,IonCol, IonHeader, IonRouterOutlet,IonContent,IonPage } from '@ionic/vue';
</script>
