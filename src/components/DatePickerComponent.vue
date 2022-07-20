<script setup>
defineProps({
  textProp: {
    type: String,
    required: true
  }
})
</script>

<template>
    <label class="sr-only" for="example-datepicker">{{ textProp }}</label>
    <b-form-datepicker 
        id="example-datepicker" 
        placeholder="{{ textProp }}"
        class="mb-2 mr-sm-2 mb-sm-0"
    ></b-form-datepicker>
</template>