<template>
    <div class="Hero container">
 
  <h1 class="header">Hello Rusiru Nethmina </h1>
  <p class="snippet"> A snippet is defined as a small piece of something; it may in more specific contexts refer to: Sampling (music),
   the use of a short phrase of a recording as an element in a new piece of music. 
   </p>
   <button class="button btn"> Start Looking </button>
  <img src="~assets/avg/fire-extinguisher.svg" alt="fire-extinguisher.svg" class="image">



    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .Hero {
        height: 50vh;
        position: relative;
        display: flex;
        padding: 5rem 0;
        align-items: flex-start;
        justify-content: space-between;
    }
    .text-container {
        width: 50%;
        margin-top: 4rem;
    }
    .header {
        font-weight: 900;
        font-size: 4rem;
    }
    .snippet {
        color: grey;
        font-size: 1.25rem;
    }
    .image {
        width: 27.5rem;
        margin-top: 2rem;
    }
    .overlay {
        background: rgba(0, 0, 0, 0);
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
    }
    .button {
        padding: 1rem 4rem;
        border-radius: 100rem;
        background-color: rgb(231, 81, 43);
        color: white;
        width: 20rem;
        font-weight: 700;
        transition: 0.5s;
    }
    .button:hover {
        width: 21.5rem;
    }
    @media (max-width: 500px) {
        .Hero {
            height: 40vh;
        }
    }
</style>