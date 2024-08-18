<script>
    import "../app.css";
    import shihabdinlogo from "$lib/img/shihabdin.png";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';

      // Check screen size
    function checkScreenSize() {
      return window.innerWidth <= 768; // Adjust the value as needed
    }

</script>


<Navbar let:toggle dir="ltr" class="fixed shadow-lg bg-black z-50">
    <NavBrand href="/">
      <img src={shihabdinlogo} class="me-3 h-14 md:h-16 invert-0" alt="Shihabdin Logo" />
      <span style="font-family:'Russo One', sans-serif;font-weight: 400;font-style: normal;" class="self-center whitespace-nowrap text-3xl text-white">Shihabdin</span>
    </NavBrand>
    <NavHamburger menuClass="text-white hover:text-black"  />
    <NavUl dir="rtl">
      <NavLi href="/" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-extrabold md:text-white">Home</NavLi>
      <NavLi href="/services" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-bold md:text-white">Services</NavLi>
      <NavLi href="/products" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-bold md:text-white">Products</NavLi>
      <NavLi href="/contact" on:click={() => { if (checkScreenSize()) toggle(); }} class="text-black font-bold md:text-white">Contact</NavLi>
    </NavUl>
  </Navbar>


<slot></slot>

<h1 style="font-family:'Russo One', sans-serif;font-weight: 400;font-style: normal;" class="text-center m-auto text-white">
  © 2024 Shihabdin
</h1>
