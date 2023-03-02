<template>
    <div class="bg-black text-white">

      <div class="container mx-auto pt-6">
        <h2 class="text-center text-xl font-integral uppercase">Infline</h2>
        
        <div class="flex items-center justify-center"> 
            <div class="max-w-3xl flex flex-col justify-center px-16">
                <h3 class="text-5xl text-left font-integral stroke-infline-purple uppercase">La platforme<br>n°1 pour trouver<br>un <span id="influenceur" class="text-infline-black inline">influenceur</span></h3>
                
                <div class="flex mt-10" >
                    <button class="bg-white text-black text-xs font-integral py-3 px-6 m-2 rounded-lg uppercase">
                    Je suis influenceur
                    </button>

                    <button class="bg-infline-purple text-white text-xs font-integral py-3 px-4 m-2 rounded-lg uppercase">
                    Je suis une marque
                    </button>
                </div>
            </div>

            <img src="@/assets/img/photos/selfie.svg" alt="Your Image" class="w-96" />


        </div>

        

      </div>

    </div>
  </template>

<style scoped>
#influenceur{
    -webkit-text-stroke: 1px #B188EA;
}
</style>