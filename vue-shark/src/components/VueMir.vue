<script setup>
    defineProps({
    title: String,
    price: Number,
    isAdded: Boolean

})




</script>


<template>
    <div class="montar">
        <h2>Услуга: {{title}}</h2>
        <h3>Цена: {{price}}</h3>
        <h3>Добавлено: {{ isAdded }}</h3>
    </div>
</template>

    <style>
    .montar{
        border: 1px solid red;
        padding: 25px;
        margin-bottom: 10px;

    }
    
    </style>



