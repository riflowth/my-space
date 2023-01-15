<script lang="ts">
  import { Router, Route } from 'svelte-navigator';
  import IndexPage from '@/components/pages/IndexPage.svelte';
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" />
</svelte:head>

<main class="min-h-screen bg-black">
  <Router>
    <Route path="/" component="{IndexPage}" />
  </Router>
</main>