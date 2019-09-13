<template>
  <v-card
    elevation="24"
    max-width="444"
    class="mx-auto card-right"
  >
      <v-form
        ref="form"
        lazy-validation
      >
        <p class="headline text-center text-white">lch mochte mich jetzt <br/>kostenlos registrienren</p>
        <p class="subtitle-1 text-center text-white">Registrieren Sie Such mit Ihrem Social <br/>Media Konto an. </p>
        <div class="text-center">
          <v-btn class="ma-2 btn-ma" style="background-color:#F5F5F5; color:black; width:100%"><v-icon>mdi-google</v-icon> &nbsp;&nbsp;G MIT GOOGLE REGISTRAEREN
          </v-btn>
           <v-btn class="ma-2 btn-ma" style="background-color:#F5F5F5; color:black; width:100%"><v-icon dark right>mdi-facebook</v-icon> &nbsp;&nbsp;f MIT FACEBOOK REGISTRAEREN</v-btn>
        </div>

       
        
        <p class="subtitle-1 text-center text-white">oder registrieren Sie sich mit Ihrer E-Mail-Adresse an.</p>
        <v-text-field

          label="Vorname"
          required
        ></v-text-field>
        <v-text-field

          label="Familienname"
          required
        ></v-text-field>
        <v-text-field


          label="Private E-mail-Adresse"
          required
        ></v-text-field>
        <p class="subtitle-1 text-center text-white">Sie erklären sich mit der Nutzervereinbarung, der Datenschutzrichtlinie und der Cookie-Richtlinie von TEMPI einverstanden. </p>
        <v-btn
          class="vtn-login"
          color="primary"
        >
          Kostenlos Registrieren
        </v-btn>
        
      </v-form>
      
    </v-card>
</template>
<style>

.card-right {
  background: white !important;
  opacity: 0.9 !important;
}

.v-label {
   color: black !important;
}

.v-input__slot:before {
  border-color: black !important;
}

.v-form {
  padding: 30px;
}
.vtn-login {
  width: 100%;
}

.text-white {
  color: black;
}
.btn-ma{
background-color:#F5F5F5; 
color:black
}
@media (max-width:678px) {

}
</style>



