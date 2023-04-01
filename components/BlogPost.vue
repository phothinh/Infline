<template>
    <div class="p-4">
      <div class="flex items-center">
        <div class="mr-2">
          <p class="text-sm text-gray-600 font-medium">{{ formatDate(date) }}</p>
          <div class="h-px w-6 bg-gray-300 my-2"></div>
          <p class="text-base font-medium">{{ description }}</p>
        </div>
        <div class="flex-shrink-0">
          <img :src="'/'+imageUrl" alt="blogpost image">
        </div>
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