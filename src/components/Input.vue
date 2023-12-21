<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
   <div>
        <input class="border px-2 py-2" v-model="text" type="text" placeholder="Введите текст">
    </div>

 
</template>

