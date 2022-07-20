<script setup lang="ts">
import HomePage from '../components/HomePage.vue';
</script>


<template>
  <div class="about">
    <div>
        <b-card
            no-body 
            class="overflow-hidden text-center" 
            style="max-width: auto; max-height: auto; margin-top: 10px; padding-top: 20px; padding-bottom: 20px;"
        >
            <b-row no-gutters>
                <b-row md="12" >
                    <b-col md="4">
                        <b-card-text style="margin-left: 10px;" >
                            Airline logo
                        </b-card-text>
                    </b-col>
                    <b-col md="2" >
                        <b-card-text style="margin-left: 10px;">
                            Avianca
                        </b-card-text>
                    </b-col>
                    <b-col md="2" >
                        <b-card-text style="margin-left: 10px;">
                            3 escalas
                        </b-card-text>
                    </b-col>
                    <b-col md="2" >
                        <b-card-text style="margin-left: 10px;">
                            19h25m 
                        </b-card-text>
                    </b-col>
                    <b-col md="2" >
                        <b-card-text>
                        $25.00
                      </b-card-text>
                      <b-button variant="primary">Comprar</b-button>
                    </b-col>
                </b-row>
                
            </b-row>
        </b-card>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
