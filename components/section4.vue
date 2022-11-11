<script setup>
import section4ButtonVue from './section4-button.vue';
</script>

<template>
    <div>
        <section class="section4">
<div>
<h2>OUR PORTFOLIO</h2> <hr>
<p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet <br>
    consectetur, adipisci velit, sed quia non numquam</p>
   <section4ButtonVue/>
   


</div>
   </section>
    </div>
</template>
<style>
/* section 4 start */
.section4{
    background-color: #ffdd99;
}
.section4 h2{
    padding: 100px 100px 20px 100px;
    font-size: 40px;
    letter-spacing: 4px;
    line-height: 30px;
    color: #393939;
    font-weight: 700;
    font-family: "Titillium Web";
    text-align: center;
}
.section4 p{
    padding: 30px;
    font-size: 18px;
    letter-spacing: 0px;
    line-height: 26px;
    color: #393939;
    font-weight: 400;
    font-family: "Titillium Web";
    text-align: center;
}
.section4 ul li{
display: inline-block;
margin: 0;
text-decoration: none;
padding: 0;
}
.section4 ul{
    display: flex;
    justify-content: space-between;
}
    </style>