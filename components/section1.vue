<script setup>
import section1PVue from './section1-p.vue';
</script>

<template>
    <div>
    
        <section id="services">
          <section1PVue/>
            <div class="icons">
            <div>
                <img src="../src/assets/Flag icon.png"/>
                <h2>Branding</h2>
                <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit, sed diam nonummy nibh.</p>
            </div>
            <div>
                <img src="../src/assets/Crayon icon.png"/>
                <h2>Design</h2>
                <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit, sed diam nonummy nibh.</p>
            </div>
            <div>
                <img src="../src/assets/Gears icon.png"/>
                <h2>Development</h2>
                <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit, sed diam nonummy nibh.</p>
            </div>
            <div>
                <img src="../src/assets/Rocket icon.png"/>
                <h2>ROCKET SCIENCE</h2>
                <p>Lorem ipsum dolor sit amet, 
                    consectetuer adipiscing elit, sed diam nonummy nibh.</p>
            </div>
         
         </div>
    </section>
    </div>
</template>

<style>
/* section css start */
#services {
    background-color: #17c2a4;


}

hr {
    margin: auto !important;
    width: 87px;
    height: 4px;
    background-color: #000000;
    color: #14a58c;
}



.header h2 {
    padding: 150px 100px 40px 150px;
    font-size: 40px;
    letter-spacing: 4px;
    line-height: 30px;
    color: #ffffff;
    font-weight: 700;
    font-family: "Titillium Web";
    text-align: center;
}

.header p {
    margin: 25px;
    font-size: 18px;
    letter-spacing: 0px;
    line-height: 26px;
    color: #ffffff;
    font-weight: 400;
    font-family: "Titillium Web";
    text-align: center;
}

.icons {
    padding-top: 100px;
}

.icons div {
    margin: 35px;
justify-content: space-between;
    display: inline-block;
    align-items: center;
    text-align: center;
}

.icons h2 {
    padding: 10px;
    font-size: 24px;
    letter-spacing: 0px;
    line-height: 18px;
    color: #ffffff;
    font-weight: 700;
    font-family: "Titillium Web";
}

.icons p {
    padding: 20px;
    width: 204px;
    height: 192px;
    font-size: 16px;
    letter-spacing: 0px;
    line-height: 24px;
    color: #ffffff;
    font-weight: 300;
    font-family: "Titillium Web";
    text-align: center;
}
</style>