<template>
    <div class="nameDiv1">
        <h1 class="name1" >JOVANNI RODRIGUEZ &nbsp; &nbsp; &nbsp; &nbsp;JOVANNI RODRIGUEZ &nbsp; &nbsp; &nbsp; &nbsp; JOVANNI RODRIGUEZ &nbsp; &nbsp; &nbsp; &nbsp;JOVANNI RODRIGUEZ</h1>
        
    </div>
    
      
    <h1 class="" id="name2">JOVANNI RODRIGUEZ</h1>

    <div class="circles">
        <svg width="5000" height="705">
            <circle cx="900" cy="230" r="200" stroke="black" fill="none" stroke-width="3" id="circle1"></circle>
            <circle cx="900" cy="500" r="200" stroke="black" fill="none" stroke-width="3"></circle>
            <circle cx="780" cy="350" r="200" stroke="black" fill="none" stroke-width="3"></circle>
            <circle cx="1020" cy="350" r="200" stroke="black" fill="none" stroke-width="3"></circle>
        </svg>
    </div>

    <div class="row">
        <div class="col">
            <ul class="text-end" style="list-style-type: none; font-family: 'Karantina';"> 
                <li>
                    <h1 class="projects">Projects</h1>
                </li>

                <li>
                    <h1>
                        <a href="https://github.com/JovanniRodriguez/photography-portfolio-site" class="project-link">Photography Portfolio Site</a>
                    </h1>
                </li>

                
            </ul>
        </div>
        
    </div>
     
</template>

<script>
    export default {
        name: 'Home'
    }
</script>

<style>
.name1{
    /* position: absolute;
    left: -1000px; */
    font-family: 'Karantina';
    font-size: 80px;
    color: #000;
    letter-spacing: 7.65px;
    margin-left: 0px;
    margin-top: -10px;
    animation-name: name1Scroll;
    animation-duration: 10s;
    animation-timing-function: linear;
    /* animation-fill-mode: both; */
    animation-iteration-count: infinite;
    width: 2600px;
    white-space: nowrap;
}

#name2{
    position: absolute;
    top: 550px;
    left: -490px;
    font-family: 'Karantina';
    font-size: 180px;
    color: #000;
    letter-spacing: 18.53px;
    rotate: -90deg;
}

.nameDiv1{
    width: 100%;
    overflow-x: hidden;
}

.projects{
    color: #000;
    font-size: 100px;
    margin-right: 100px;
}

.project-link{
    text-decoration-line: none;
    color: #373737;
    margin-right: 100px;
}


@keyframes name1Scroll{
   from { transform: translateX(0);}
   to   { transform: translateX(-80%);}
}


</style>