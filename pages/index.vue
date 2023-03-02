<template>
<div class="bg-black text-white overflow-visible">

<div class="container mx-auto pt-6">
  <h2 class="text-center text-xl font-integral uppercase">Infline</h2>
  
  <div class="flex items-center justify-start"> 
      <div class="max-w-3xl flex flex-col justify-center px-16">
          <h3 class="text-5xl text-left font-integral stroke-infline-purple uppercase">La platforme<br>n°1 pour trouver<br>un <span id="influenceur" class="text-infline-black inline">influenceur</span></h3>
          
          <div class="flex mt-10" >
            <Button bgColor="bg-white" textColor="text-black" buttonText="Je suis influenceur" />
            <Button bgColor="bg-infline-purple" textColor="text-white" buttonText="Je suis une marque" />
          </div>
      </div>

      <img src="@/assets/img/photos/selfie.svg" alt="Your Image" class="w-96 h-auto absolute bottom-0 left-2/3" />

  </div>
</div>
</div>
</template>

<style scoped>
#influenceur{
    -webkit-text-stroke: 1px #B188EA;
}
</style>