<script setup>
import headerDivVue from './header-div.vue';
</script>

<template>
    <div>

        <header>
            <headerDivVue/>
       
            <div class="header-body">
                <h2>Hi there! We are the new kids on the block 
                    and we build awesome websites and mobile apps.</h2>
                   <button>WORK WITH US!</button>
            </div>
       
    </header>
    </div>
</template>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --font: Titillium Web
}

.container {
    max-width: 1100px;
    margin: auto;
}

/* header css start */
header {
    background-color: #87509c;
}

header nav {
    padding-top: 60px;
}

header nav ul {
    float: right;
    padding-top: 10px;
}

header nav ul li {
    display: inline;
    margin-left: 25px;
}

header ul li a {
    font-size: 16px;
    line-height: 18px;
    color: #ffffff;
    font-weight: 400;
    font-family: "Titillium Web";
    text-decoration: none;
    text-transform: uppercase;
    padding: 10px 15px;
}

.active,
header nav li a:hover {
    background-color: #643a79;
    border-radius: 4px;

}

/* header-body start */
.header-body {
    padding-bottom: 140px !important;
    margin-top: 140px !important;
    font-size: 42px !important;
    line-height: 49px !important;
    color: #f7f3ea;
    font-weight: 700;
    font-family: "Titillium Web" !important;
    text-align: center !important;
}
.header-body h2{
    font-family: "Titillium Web" !important;
    font-size: 45px !important;
    text-align: center !important;
    margin-left: 25px;
}

div button {

    background-color: #eb7d4b;
    border: 0;
    border-radius: 6px;
    border-bottom: 4px solid #c86a40;
    margin: 55px;
    padding: 20px 50px;
    font-size: 18px;
    letter-spacing: 0px;
    line-height: 26px;
    color: #ffffff;
    font-weight: 600;
    font-family: "Titillium Web";

}
</style>