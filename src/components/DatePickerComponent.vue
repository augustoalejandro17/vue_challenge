<script setup>
defineProps({
  textProp: {
    type: String,
    required: true
  }
})
</script>

<template>
    <div>
        <label class="sr-only" for="example-datepicker">ss</label>
        <b-form-datepicker 
            id="example-datepicker" 
            placeholder="ss"
            class="mb-2 mr-sm-2 mb-sm-0"
        ></b-form-datepicker>
    </div>
</template>