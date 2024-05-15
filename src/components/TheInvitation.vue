<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'

</script>

<template>

<div class="item">
    <div class="back-img">
       <img alt="balloons" class="logo" src="../assets/balloonGroup.png" width="200" />
    </div>
    <div class="front-img">
        <img alt="balloon rose" class="logo" src="../assets/balloon01.png" width="140" />
    </div>
    <div class="text-container">
        <h3>It's a Girl!</h3>
        <p>Join us</p>
        <p>for a baby shower honoring</p>
        <h3>Michela Huaira</h3>
        <p>Saturday, May 18</p>
        <p>at 6:00 pm</p>
        <a href="https://maps.apple.com/?address=650%20Stadium%20Ave,%20Provo,%20UT%20%2084604,%20United%20States&ll=40.261002,-111.646801&q=650%20Stadium%20Ave&t=m">650 stadium Ave, Provo, UT</a>   
    </div>
    <div class="link-container">
        <div class="button-amazon">
            <a href="https://www.amazon.com/baby-reg/keylaynim-rosales-julio-2024-provo/KO7Z4TY7SKOI">Registry at Amazon</a>
        </div>
        
    </div>
</div>
    

</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Josefin+Slab:ital,wght@0,100..700;1,100..700&family=Nanum+Myeongjo&display=swap');


.item {
  display: grid;
  grid-template-columns: 50% 50%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

.back-img{
    grid-column: 1/2;
    grid-row: 1/4;
    place-self: center;
}
.front-img{
    grid-column: 1/2;
    grid-row: 2/5;
    justify-self: center;
    align-self: start;
}
.text-container{
    grid-column: 2/3;
    grid-row: 1/5;
    place-self: center;
    text-align: right;
}
.link-container{
    grid-column: 1/3;
    grid-row: 5/6;
    place-self: center;
}

.button-amazon{
    background-color: #FCF7F3;
    color: #fff;
    border-radius: 8px;
    padding: 8px;
    border: 1px solid #EDC09E;
}


h3{
    font-family: "Josefin Slab", serif;
    font-optical-sizing: auto;
    font-weight: 600;
    font-style: normal;
    font-size: 2em;
    margin: 20px 0;
}
p{
    font-family: "Nanum Myeongjo", serif;
    font-weight: 400;
    font-style: normal;
}


</style>