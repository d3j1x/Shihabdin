<script>
    import "../app.css";
    import shihabdinlogo from "$lib/img/shihabdin.png";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';

</script>


<Navbar dir="ltr" class="fixed shadow-lg bg-black">
    <NavBrand href="/">
      <img src={shihabdinlogo} class="me-3 h-14 md:h-16 invert-0" alt="Shihabdin Logo" />
      <span style="font-family: Arial, Helvetica, sans-serif;" class="self-center whitespace-nowrap text-3xl font-extrabold text-white">Shihabdin</span>
    </NavBrand>
    <NavHamburger menuClass="text-white hover:text-black"  />
    <NavUl dir="rtl">
      <NavLi href="/" class="text-black font-extrabold md:text-white">Home</NavLi>
      <NavLi href="/services" class="text-black font-bold md:text-white">Services</NavLi>
      <NavLi href="/products" class="text-black font-bold md:text-white">Products</NavLi>
      <NavLi href="/contact" class="text-black font-bold md:text-white">Contact</NavLi>
    </NavUl>
  </Navbar>


<slot></slot>
