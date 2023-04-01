<template>
    <div>
      <button :class="buttonClass(bgColor, textColor)" class="py-[1vw] px-[1.5vw] m-2 rounded-lg uppercase">
        {{ buttonText }}
      </button>
    </div>
</template>
  
<script>
    export default {
        name: 'MyButton',
        props: {
        bgColor: {
            type: String,
            default: 'bg-white'
        },
        textColor: {
            type: String,
            default: 'text-black'
        },
        buttonText: {
            type: String,
            default: 'Button Text'
        }
        },
        methods: {
        buttonClass(bgColor, textColor) {
            return `${bgColor} ${textColor} text-[0.8vw] font-integral`
        }
        }
    }
</script>
  
<style scoped>

</style>