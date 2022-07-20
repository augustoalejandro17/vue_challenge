<script setup>
defineProps({
  textProp: {
    type: String,
    required: true
  }
})
</script>

<template>
    <label class="sr-only" for="inline-form-input">{{ textProp }}</label>
    <b-form-input
    id="inline-form-input-name"
    class="mb-2 mr-sm-2 mb-sm-0"
    placeholder="{{ textProp }}"
    ></b-form-input>
</template>