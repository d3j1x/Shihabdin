<script>

import { Card } from 'flowbite-svelte';
import { GiftBoxSolid } from 'flowbite-svelte-icons';



</script>

<svelte:head>
  <title>𝐒𝐡𝐢𝐡𝐚𝐛𝐝𝐢𝐧 ✪</title>
  <meta name="description" content="Shihabdin Official Portfolio.
  Cybersecurity specialist 🔐 | Full-Stack Developer 🛠 | Opensource 🔥.
  "/>
</svelte:head>

<div class="pt-14 rounded-sm">
    <h1 class="pt-1 text-center font-bold text-xs text-primary-400 z-50">𝕺𝖕𝖊𝖓𝖘𝖔𝖚𝖗𝖈𝖊 <span class="animate-pulse">🔥</span></h1>
</div>

<main class="mx-4">

<div class="py-8 md:py-10"></div>

<div class="glass-container  py-4 mx-auto w-fit max-w-7xl">
  


  <h1 style="font-family:'Protest Guerrilla', system-ui;font-weight: 400;font-style: normal;" 
    class="mb-8 md:mt-4 text-4xl md:text-5xl xl:text-6xl text-center font-bold 
    bg-gradient-to-b from-yellow-100 to-yellow-500 bg-clip-text not-italic text-transparent">
    Best Projects
  </h1>








  <div class="grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-20 xl:gap-40 m-5 xl:mx-20">
    <div class="myCustombg1 col-span-1 mx-auto md:my-20 flex-wrap 
    hover:bg-black transition-transform duration-300 hover:scale-105">
        <Card class="bg-transparent shadow-sm  shadow-yellow-300 border-none backdrop-blur-none">
            <a href="https://smx.tn" target="_blank" rel="noreferrer">
              <h5 class="my-4 text-center text-2xl md:text-2xl lg:text-3xl tracking-tight
               text-gray-300 font-extrabold goldHover">
                SMRT MRKT X
              </h5>
            </a>
            <p class="mb-3 font-bold text-gray-400  lg:text-lg">
              Join our community to stay ahead in the dynamic world.</p>
            <a href="https://smx.tn" target="_blank" rel="noreferrer" 
            class="inline-flex items-center text-gray-200 hover:underline font-semibold">
              Explore now
              <GiftBoxSolid class="w-4 h-4 ms-2.5" />
            </a>
        </Card>
    </div>
    <div class="hover:bg-black myCustombg2 col-span-1 m-auto transition-transform duration-300 hover:scale-105">
        <Card class="bg-transparent shadow-sm shadow-yellow-300 border-none backdrop-blur-none">
            <a href="https://earnmoney.tn" target="_blank" rel="noreferrer">
              <h5 class="my-4 text-2xl md:text-2xl lg:text-3xl  tracking-tight 
              text-center text-gray-300 font-extrabold goldHover">
                EARNMONEY</h5>
            </a>
            <p class="mb-3 font-bold text-gray-400 dark:text-gray-400 lg:text-lg">Discover the secrets to earning passive income.
            </p>
            <a href="https://earnmoney.tn" target="_blank" rel="noreferrer" 
            class="inline-flex items-center text-gray-200 hover:underline font-semibold">
              Explore now
              <GiftBoxSolid class="w-4 h-4 ms-2.5" />
            </a>
        </Card>
    </div>
    

  </div>


</div>


</main>




<style>
  .myCustombg1 {
    background-image: url("../lib/img/smx.jpg");
    background-size: 60px;
    background-repeat: no-repeat;
    background-position:98% 95%;
  }

  .myCustombg2 {
    background-image: url("../lib/img/earnmoney.png");
    background-size: 60px;
    background-repeat: no-repeat;
    background-position:98% 95%;
    
  }


 .goldHover:hover {
  
  background: linear-gradient(to bottom, #fefcbf, #f59e0b); /* Gradient from yellow-100 (#fefcbf) to yellow-500 (#f59e0b) */
  -webkit-background-clip: text; /* Clipping the background to the text */
  background-clip: text; /* For other browsers */
  color: transparent; /* Makes the text itself transparent */
  font-style: normal; /* Ensures the text is not italic */
 }





</style>