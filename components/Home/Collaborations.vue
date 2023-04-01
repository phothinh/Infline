<template>
    <div class="bg-infline-black">
    
        <div class="black-div flex justify-center items-center">
            
            <img class="portrait" src="@/assets/img/collab/portrait1.svg">
            <img class="portrait" src="@/assets/img/collab/portrait2.svg">
            <img class="portrait" src="@/assets/img/collab/portrait3.svg">
            <img class="portrait" src="@/assets/img/collab/portrait4.svg">
            <img class="portrait" src="@/assets/img/collab/portrait5.svg">
            <img class="portrait" src="@/assets/img/collab/portrait6.svg">

            <h3 class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 z-10 text-center text-[3.2vw] text-white font-integral uppercase leading-[3vw]">déjà plus de <br><span class="text-infline-purple">250 collaborations</span></h3>
        </div>
    </div>
  </template>

<style scoped>
    .black-div {

    height: 30vw; 
    position: relative;
    overflow: hidden;
  }

  .portrait {
    position: absolute;
    top: 0;
    left: 0;
    animation-name: descendre;
    animation-duration: 5s; /* ajuster la durée de l'animation selon vos besoins */
    animation-iteration-count: infinite;
    animation-timing-function: linear;
  }

  .portrait:nth-child(1) {
    animation-duration: 14s;
  }

  .portrait:nth-child(2) {
    left: 40%;
    top : 20%;
    animation-duration: 20s;
  }

  .portrait:nth-child(3) {
    left: 85%;
    animation-duration: 10s;
  }

  .portrait:nth-child(4) {
    left: 10%;
    top: 80%;
    animation-duration: 14s;
  }

  .portrait:nth-child(5) {
    left: 45%;
    top: 70%;
    animation-duration: 16s;
  }

  .portrait:nth-child(6) {
    left: 80%;
    top: 80%;
    animation-duration: 22s;
  }

  @keyframes descendre {
    0% {
      transform: translate(0, -400%);
    }
    100% {
      transform: translate(0, 400%);
    }
  }

</style>