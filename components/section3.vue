
<script setup>
import section3WebVue from './section3-web.vue';
</script>
<template>
    <div>
        <section class="section3">
    <h2>WE GOT SKILLS!</h2> <hr>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod <br>
    tempor incididunt ut labore et dolore magna aliqua.</p>
    <section3WebVue/>

   </section>
    </div>
</template>
<style>
/* section 3 */
.section3 h2{
    padding: 100px 100px 30px 100px;
    font-size: 40px;
letter-spacing: 4px;
line-height: 30px;
color: #3c4761;
font-weight: 700;
font-family: "Titillium Web";
text-align: center;
}
.section3 p{
    padding: 30px 100px 100px 100px;
    font-size: 18px;
letter-spacing: 0px;
line-height: 26px;
color: #3c4761;
font-weight: 400;
font-family: "Titillium Web";
text-align: center;
}
.base{
    display: flex;
    justify-content: space-between;
}
</style>