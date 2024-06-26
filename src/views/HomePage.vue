<template>
  <ion-page>
    <ion-content color="primary" :fullscreen="true"  class="ion-padding">
      <ion-card>
        <ion-card-content class="ion-padding">
          <ion-row class="ion-align-items-center" >
        <ion-col style="display: flex; justify-content:center">
          <ion-img style="width: 50%;" src="src/Imagenes/Primera.jpg"></ion-img>
        </ion-col>
        <ion-col>
          <ion-item class="ion-text-start" lines="none" style="width: 100%;">
            <ion-label>El jugger es una disciplina de equipo originado en Alemania entre los años 1989 y 1995, inspirado en el film La sangre de los héroes de 1989. Se trata de una actividad deportiva de equipo que combina elementos de rugby y esgrima.
              El jugger se basa en la habilidad y la estrategia, no en la fuerza de los jugadores. El reglamento limita en todo momento los golpes fuertes y el contacto físico entre jugadores
              El jugger se basa en la mayor anotación de puntos en la base del equipo opuesto. La notación se consigue cuando el móvil, llamado jugg, se introduce en la base.
            </ion-label>
          </ion-item>
        </ion-col>
      </ion-row>
        </ion-card-content>
      </ion-card>
    </ion-content>
  </ion-page>
</template>

<script setup>
import { IonContent, IonPage, IonItem,IonRow,IonLabel,IonTitle,IonCol,IonImg,IonFooter,IonCard,IonCardContent} from '@ionic/vue';
</script>

<style scoped>

 

</style>
