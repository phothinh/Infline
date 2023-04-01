<template>
    <div>
      <div class="flex flex-col">
        <div class="mr-2">
          <p class="text-sm text-infline-black font-medium">{{ formatDate(date) }}</p>
          <div class="h-px w-[24vw] bg-infline-black my-2"></div>
          <p class="text-base font-medium w-[16vw] mb-[0.6vw]">{{ description }}</p>
        </div>

        <img src="@/assets/img/blog/blog1.svg" alt="blogpost image" class="w-[24vw]">

      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      date: {
        type: Date,
        required: true,
      },
      description: {
        type: String,
        required: true,
      },
      imageUrl: {
        type: String,
        required: true,
      },
    },
    methods: {
      formatDate(date) {
        const options = { year: "numeric", month: "long", day: "numeric" };
        return new Intl.DateTimeFormat("fr-FR", options).format(new Date(date));
      },
    },
  };
  </script>