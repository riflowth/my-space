<script>
  import CodernExperience from '@/components/experiences/CodernExperience.svelte';
  import TheExistingExperience from '@/components/experiences/TheExistingExperience.svelte';
  import PrefreshyCpeExperience from '@/components/experiences/PrefreshyCpeExperience.svelte';
  import ComcampExperience from '@/components/experiences/ComcampExperience.svelte';
</script>

<section id="experience" class="flex flex-col py-24">
  <span class="mb-10 text-2xl text-white font-semibold">Experience</span>

  <div class="space-y-4">
    <CodernExperience />
    <TheExistingExperience />
    <ComcampExperience />
    <PrefreshyCpeExperience />
  </div>
</section>