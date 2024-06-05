<script setup>
import { contactData } from '../assets/data.js';
</script>

<template>
    <div class="link" v-for="link in contactData.links">
        <a :href="link.address" target="_blank">
            <button>{{ link.linkName }}</button>
        </a>
        
    </div>
</template>

<style>
.link{
    max-width: 100%;
    margin-bottom: 10px;
}
.link:last-child{
    margin-bottom: 0;
}
button{
    color: white;
}
button:hover{
    border: 1px rgb(0, 209, 0) solid;
}
button:active{
    background: rgb(0, 209, 0);
}
</style>