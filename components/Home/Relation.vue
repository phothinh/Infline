<template>
    <div class="bg-infline-white text-white overflow-visible">
        
        

        <div class="flex justify-center items-center">
            
            <img src="@/assets/img/photos/shooting.svg" alt="Your Image" class="w-[28vw] h-auto mx-[2vw] -mt-20 mb-32"/>
            

            <div class="flex flex-col mx-[5vw]">
                <h2 class="text-[1.8vw]  text-infline-black font-poppins font-bold w-[29vw] mx-auto mt-8">Une relation <span class="circle">transparente.</span></h2>
                <p class="text-[1.3vw] text-infline-black font-poppins w-[29vw] mx-auto mt-4">Pas de bullshit, pas de chichis. Chez Infline, la relation entre influenceurs et marques est transparente. Prix affichées, conditions définies, tout est clair dès le départ et des deux côtés.</p>
            </div>
            
        </div>
    </div>
</template>

<style scoped>
.circle {
  position: relative;
}

.circle::before {
  content: '';
  position: absolute;
  left: 1.5vw;
  height: 3vw;
  width: 8vw;
  border: 1px solid #B188EA;
  rotate: 8deg;
  border-radius: 50%;
}

</style>