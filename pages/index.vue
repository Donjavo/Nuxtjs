<template>
  <h1>Welcome to my first nuxt app</h1>
</template>

<script>
export default {
  head(){
    return{
      title:'Application Nuxt Posts | Home',
      meta:[
        {
          hid:"dexcription",
          name:"description",
          content:"website about posts"

        }
      ],
      htmlAttrs:{
        lang:'en'
      }
    }
  }
}
</script>