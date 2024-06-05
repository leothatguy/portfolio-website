<script setup>
import NavBar from '../components/NavBar.vue';

</script>

<template>
    <div class="container">
        <NavBar />
        <div class="content">
            <div class="userInfo">
                <p>Hi, my name is</p>
                <p class="userName">DIVINE O. ANESI</p>
                <p class="userSummary">I LOVE CODING, JUST AS I LOVE EATING</p>
                <p class="userAbout">
                    I am a Web Developer👨‍💻  Passionate about creating solutions,<br /> Building Scalable Web Applications and exploring new technologies…
                </p>
                <a href="#"><button>Click to know more..</button></a>
            </div>
        </div>
    </div>
</template>

<style scoped>
*{
    margin: 0;
    padding: 0;
}

NavBar{
    opacity: 0.4;
}
.container{
    background: url("../assets/796169491973.jpg") center;
    background-size: cover;
    min-height: 100%;
    padding: 0 15px;
}

.content{
    margin-top: 10vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.userInfo{
    padding: 40px;
}

p{
    opacity: 0.9;
    margin-bottom: 10px;
}
.userName{
    font-size:2.5rem;
    font-weight: 600;
    opacity: 0.8;
    margin-bottom: 0;
}
.userSummary{
    margin-bottom:10px;
    font-size:2rem;
    font-weight: 600;
    opacity: 0.4;
}

.userInfo button{
    margin-top: 20px;
    padding: 15px;
    background: none;
    border: 1px solid;
    border-radius: 20px;
    opacity: 0.6;
}

</style>