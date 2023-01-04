<template>
<div class=" card-mb-4">
    <div class ="card-body">
        <h5 class ="card-title">{{post.title}}</h5>
        <p class ="card-text">{{post.body}}</p>
    </div>
</div>
</template>

<script setup>

 const props = definedProps({
    post:{
        type: Object,
        required: true,
    }
 })
</script>

<style>


</style>