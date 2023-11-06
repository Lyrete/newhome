<script>
  import { NavLi, NavUl, Navbar } from "flowbite-svelte";
  import "../app.css";
</script>

<div class="h-full w-full">
  <Navbar >
    <NavUl>
      <NavLi href="/">Home</NavLi>
      <NavLi href="/projects">Projects</NavLi>
      <NavLi href="/contact">Contact</NavLi>
    </NavUl>
  </Navbar>
  
  <slot />
</div>
