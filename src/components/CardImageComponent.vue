<script setup>
    // import "./DatePickerComponent.vue"
    // import "./TextFormComponent.vue"
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
                    <TextFormComponent textProp="Origen"/>
                    <TextFormComponent textProp="Destino"/>
                    <DatePickerComponent textProp="Fecha de partida"/>
                    <DatePickerComponent textProp="Fecha de partida"/>  
                    <b-button variant="primary">Buscar</b-button>
                </b-form>
            </div>
        </b-card-body>
        </b-card>
    </div>
</template>