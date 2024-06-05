<script setup>
import { pageData } from "../assets/data"
</script>

<template>
    <nav class="navBar">
        <div class="logo"><a href="#">{{ pageData.pageName }}</a></div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Projects</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</template>

<style scoped>
*{
    text-decoration: none;
}
.navBar{
    display: flex;
    justify-content: space-between;
    background: rgba(0, 0, 47, 0);
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 5px;
}
.logo a{
    font-size: 35px;
    font-weight: 600;
    color: rgb(182, 182, 182);
}

.logo a:active{
    color: rgb(165, 45, 30);
}
.navBar ul li{
    list-style-type: none;
    display: inline-block;
}

.navBar ul li a{
    color: rgb(182, 182, 182);
    font-size: 18px;
    font-weight: bold;
    padding: 20px;
}

a:hover{
    opacity: 0.5;
}
.navBar ul li a:active{
    background-color: rgb(165, 45, 30);
    opacity: 0.5;
}
</style>