<template>
<v-row
    
   
>
  <v-card
    class="mx-auto bottomCard"
    
  >
    <v-img
      :src="require('@/assets/DESKTOP/NoPath-1.png')" 
      height="141px"
    ></v-img>
    <v-card-title class="cardTitle">Crewmitarbeiter/IN</v-card-title>
    <p class="cardText">McDonald's<br/>8105 Regensdorf</p>
    <div align="center" justify="center"><a>anschauen & bewerben</a></div>
       
  </v-card>
  
  <v-card
    class="mx-auto bottomCard"
  >
    <v-img
      :src="require('@/assets/DESKTOP/NoPath - Kopie-1.png')" 
      height="141px"
    ></v-img>
    <v-card-title class="cardTitle">Senior Accountant</v-card-title>
    <p class="cardText">LIPO Einrichtungsmärkte AG<br/>4133 Pratteln</p>
    <div align="center" justify="center"><a>anschauen & bewerben</a></div>
    
  </v-card>

  <v-card
    class="mx-auto bottomCard"
   
  >
    <v-img
      :src="require('@/assets/DESKTOP/NoPath.png')" 
      height="141px" 
    ></v-img>
    <v-card-title class="cardTitle">Hauswart (m/w)</v-card-title>
    <p class="cardText">ISS Facility Services AG<br/>4126 Bettingen</p>
    <div align="center" justify="center"><a>anschauen & bewerben</a></div>
  </v-card>

  <v-col cols=12>
   <div class="text-center">
    MERH JOBS
  </div>
  </v-col>
 
  <v-card
    class="mx-auto bottomCard"
    width="1185px"
  >
        <v-row>
       <v-col
            cols="12"
            md="4"            
        >
          <v-card
            class="mx-auto bottomCard"
            max-width="392px"
          >
            <v-img
              :src="require('@/assets/DESKTOP/SVGZeichenfläche 10.png')" 
              height="188px" 
              width="236px"
            
            ></v-img>
            <v-card-title class="cardTitle">Schritt 1</v-card-title>
            <p class="cardText">Erstellen Sie Ihr Profil</p>
        
          </v-card>
       </v-col>  
       <v-col
            cols="12"
            md="4"            
        >
          <v-card
            class="mx-auto bottomCard"
            max-width="1185px"
          >
            <v-img
              :src="require('@/assets/DESKTOP/SVGZeichenfläche 19.png')" 
              height="188px" 
              width="236px"
            ></v-img>
            <v-card-title class="cardTitle">Schritt 2</v-card-title>
            <p class="cardText">Lassen Sie sich finden oder suche den passenden Jobn</p>
          </v-card>
       </v-col> 
       
       <v-col
            cols="12"
            md="4"            
        >
          <v-card
            class="mx-auto bottomCard"
            
          >
            <v-img
              :src="require('@/assets/DESKTOP/SVG02Zeichenfläche 18.png')" 
              height="188px" 
              width="236px"
            ></v-img>
            <v-card-title class="cardTitle">Schritt 3</v-card-title>
            <p class="cardText">Bewerben Sie sich mit einem Klick</p>
          </v-card>
       </v-col> 
    </v-row>

  </v-card>

  
</v-row>
  

</template>
<style >
.bottomCard {
  background: white !important;
  margin-top: 20px;
  font-size: 14px;
  max-width: 1185px;
}
.bottomCard1{
  background: white !important;
  margin-top: 20px;
  font-size: 14px;
  
}
.cardTitle{
  font-family: Roboto;
  color:#546E7A;
  font-size: 20px;
}
.cardText{
  color:#546E7A;
  margin-left: 17px;
}
a{
  align-items: center;
}
@media (max-width:1074px) {

}

@media (max-width:678px) {
.bottomCard {
  max-width: 360px;
}
}
</style>
