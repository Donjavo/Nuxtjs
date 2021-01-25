
<template>
  <div>
    <h1>About us</h1>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Officia
      doloremque tempore eos perspiciatis beatae laboriosam vero tempora,
      sapiente corporis ullam repellat numquam aspernatur at quaerat, debitis
      corrupti aperiam, voluptas eius!
    </p>
  </div>
</template> 

 <script>
export default {
  head() {
    return {
      title: "Posts | Home",
      meta: [
        {
          hid: "dexcription",
          name: "description",
          content: "website about posts",
        },
      ],
      htmlAttrs: {
        lang: "en",
      },
    };
  },
};
</script>