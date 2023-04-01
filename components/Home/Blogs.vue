<script>
import BlogPost from "~/components/BlogPost";

export default {
  components: {
    BlogPost,
  },
};
</script>

<template>
  <div class="px-[5vw] py-[2vw] mb-[5vw]">
    <h3 class="text-left text-[3.5vw] text-infline-black font-integral uppercase ml-[3.4vw] mt-[2vw]">Les news</h3>
    <div class="flex items-center justify-center mt-[3vw] ">
      <BlogPost class="mx-[2vw]"
        date="2022-03-04"
        description="Trouver l’influenceur parfait pour votre marque"
        imageUrl="/assets/img/blog/blog1.svg"
      />
      <BlogPost class="mx-[2vw]"
        date="2022-03-07"
        description="50 nouvelles influenceuses rejoignent la plateforme"
        imageUrl="/assets/img/blog/blog1.svg"
      />
      <BlogPost class="mx-[2vw]"
        date="2022-06-01"
        description="Instagram investit 100 millions d’euros dans Infline"
        imageUrl="/assets/img/blog/blog1.svg"
      />
    </div>
  </div>
</template>
  
