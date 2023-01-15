<script lang="ts">
  import Navbar from '@/components/navbars/Navbar.svelte';
  import Hero from '@/components/hero/Hero.svelte';
  import About from '@/components/abouts/About.svelte';
  import Experiences from '@/components/experiences/Experiences.svelte';
</script>

<Navbar />
<Hero />

<div class="container">
  <About />
  <Experiences />
</div>