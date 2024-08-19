<script>
    import "../app.css";
    import shihabdinlogo from "$lib/img/shihabdin.png";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';

      // Check screen size
    function checkScreenSize() {
      return window.innerWidth <= 768; // Adjust the value as needed
    }

  import { onMount } from "svelte";
  let lastScrollTop = 0;
  let navbarVisible = true;

  onMount(() => {
    const handleScroll = () => {
      const scrollTop = window.pageYOffset || document.documentElement.scrollTop;

      if (scrollTop > 70 && scrollTop > lastScrollTop) {
        navbarVisible = false; // Hide navbar when scrolled down more than 50px
      } else if (scrollTop < lastScrollTop || scrollTop <= 50) {
        navbarVisible = true;  // Show navbar when scrolling up or at the top
      }

      lastScrollTop = scrollTop <= 0 ? 0 : scrollTop; // Prevent negative scrolling
    };

    window.addEventListener("scroll", handleScroll);

    return () => {
      window.removeEventListener("scroll", handleScroll);
    };
  });

</script>



<div class:hidden={!navbarVisible}>


<Navbar let:toggle dir="ltr" class="fixed shadow-xl bg-black z-50">
    <NavBrand href="/">
      <img src={shihabdinlogo} class="rounded-full me-3 h-16" alt="Shihabdin Logo" />
      <span style="font-family:'Russo One', sans-serif;font-weight: 400;font-style: normal;" class="self-center whitespace-nowrap text-3xl text-white">Shihabdin</span>
    </NavBrand>
    <NavHamburger menuClass="text-white hover:text-black"  />
    <NavUl dir="rtl">
      <NavLi href="/" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-extrabold md:font-bold md:text-white md:text-base">Home</NavLi>
      <NavLi href="/services" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-bold md:text-white md:text-base">Services</NavLi>
      <NavLi href="/products" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-bold md:text-white md:text-base">Products</NavLi>
      <NavLi href="/contact" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-bold md:text-white md:text-base">Contact</NavLi>
    </NavUl>
  </Navbar>

</div>


<slot></slot>
<h1 style="font-family:cursive;" class="text-sm py-2 text-center font-medium">Start making money by following the steps.</h1>
<h1 style="font-family:'Russo One', sans-serif;font-weight: 400;font-style: normal;" class="text-center m-auto text-white">
  © 2024 Shihabdin
</h1>



<style>
</style>
