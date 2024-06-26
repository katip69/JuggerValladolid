<template>
  <ion-app>
    <ion-page>
    <ion-header style="height: 5rem; max-height: 5rem; ">
      <ion-row class="ion-justify-content-center ion-align-items-center">
        <ion-img src="src/Imagenes/images.jpeg" style="height: 5rem;"></ion-img>
        <ion-row fixed="true" style="margin-left: 3rem;">
          <ion-label @click="$router.push({name:'Home'})">Inicio </ion-label> 
          <ion-label @click="$router.push({name:'QuienesSomos'})"> Quienes Somos</ion-label>
          <ion-label>Descargas</ion-label>
          <ion-label>Contacto</ion-label>
          <ion-label>Consultas socios</ion-label>
        </ion-row>
      </ion-row>
    </ion-header>
    <ion-content :fullscreen="true" class="ion-padding">
      <ion-router-outlet slot="fixed"/>
    </ion-content>
    </ion-page>
  </ion-app>
</template>

<script setup>
import { IonApp,IonImg,IonRow,IonLabel, IonHeader, IonRouterOutlet,IonContent,IonPage,IonFooter,IonItem} from '@ionic/vue';

</script>

<style scoped>
  ion-label{
    margin-right: 20px;
    cursor: pointer;
  }


</style>

