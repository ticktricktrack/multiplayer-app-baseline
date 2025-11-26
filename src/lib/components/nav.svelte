<script lang="ts">
	import { Navbar, NavBrand, NavHamburger, NavLi, NavUl } from "flowbite-svelte";
  import logo from '$lib/assets/logo.svg';
</script>

<Navbar>
  <NavBrand href="/">
    <img src={logo} class="me-3 h-32 sm:h-32" alt="App Logo" />
    <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Baseline App</span>
  </NavBrand>
  <NavHamburger />
  <NavUl>
    <NavLi href="/">Home</NavLi>
    <NavLi href="/about">About</NavLi>
    <NavLi href="/contact">Contact</NavLi>
  </NavUl>
</Navbar>
