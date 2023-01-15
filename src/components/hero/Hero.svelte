<script lang="ts">
  import ChevronDown from '@/components/icons/ChevronDown.svelte';
</script>

<div class="h-screen flex justify-center items-center py-12">
  <div class="flex flex-row items-center space-x-16">
    <div class="flex flex-col">
      <div class="flex flex-col mb-8">
        <span class="mb-3 text-lg text-white">
          A Software Engineering
        </span>
        <span class="mb-5 text-6xl md:text-7xl text-white font-semibold">
          Krid<br />Heprahone
        </span>
        <span class="text-sm text-neutral-400">
          who passionate about the technology world
        </span>
      </div>
      
      <a
        href="#about"
        class="w-fit flex flex-row items-center space-x-1 px-4 py-2 text-black hover:text-white bg-white hover:bg-black font-semibold border border-white rounded-md transition ease-in-out duration-200"
      >
        <span>My Journey</span>
        <ChevronDown class="w-4 h-4" />
      </a>
    </div>
    <img src="/avatar.png" alt="" class="hidden md:block w-72 drop-shadow-2xl shadow-white" />
  </div>
</div>
