<script setup>
import "../components/CardImageComponent.vue"
import "../components/DatePickerComponent.vue"
import "./TextFormComponent.vue"
</script>

<template>
    
  
<div>
    <b-card
      overlay
      img-src="https://picsum.photos/900/250/?image=3"
      img-alt="Card Image"
      text-variant="white"
    >
    <b-card-body>
        <div>
            <b-form inline>
                <label class="sr-only" for="inline-form-input-name">Name</label>
                <b-form-input
                id="inline-form-input-name"
                placeholder="Origen"
                ></b-form-input>

                <label class="sr-only" for="inline-form-input-username">Username</label>
                <b-form-input 
                id="inline-form-input-username" 
                placeholder="Destino"
                ></b-form-input>

                <label class="sr-only" for="example-datepicker">Fecha de partida</label>
                <b-form-datepicker 
                id="example-datepicker" 
                placeholder="Fecha de partida"
                ></b-form-datepicker>

                <label class="sr-only" for="example-datepicker">Fecha de regreso</label>
                <b-form-datepicker 
                id="example-datepicker" 
                placeholder="Fecha de regreso"
                ></b-form-datepicker>

                <b-button variant="primary" style="margin-top:20px">
                    <router-link to="/about" style="text-decoration: none; color: white;">Buscar</router-link>
                </b-button>
            </b-form>
        </div>
    </b-card-body>
    </b-card>
</div>
</template>