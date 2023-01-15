<script lang="ts">
  import FacebookLogo from '@/components/icons/FacebookLogo.svelte';
  import GitHubLogo from '@/components/icons/GitHubLogo.svelte';
  import LinkedinLogo from '@/components/icons/LinkedinLogo.svelte';
</script>

<section id="about" class="flex flex-col py-24">
  <span class="mb-10 text-2xl text-white font-semibold">About</span>

  <span class="mb-6 text-neutral-400">
    Currently based in Bangkok, TH as Computer Engineering student and Founder at <a href="https://vectier.com" class="font-medium underline">Vectier</a>.
    <br />
    <br class="sm:hidden" />
    I'm working around Full-stack web development and DevOps with cutting-edge technology.
  </span>

  <div class="flex flex-row space-x-6">
    <a
      href="https://www.linkedin.com/in/krid-heprakhone/"
      class="flex flex-row space-x-2 group hover:cursor-pointer"
    >
      <LinkedinLogo class="w-6 h-6 text-white" /> <span class="text-white group-hover:underline">Linkedin</span>
    </a>
    <a
      href="https://github.com/riflowth"
      class="flex flex-row space-x-2 group hover:cursor-pointer"
    >
      <GitHubLogo class="w-6 h-6 text-white" /> <span class="text-white group-hover:underline">GitHub</span>
    </a>
    <a
      href="https://www.facebook.com/OhmKrid/"
      class="flex flex-row space-x-2 group hover:cursor-pointer"
    >
      <FacebookLogo class="w-6 h-6 text-white" /> <span class="text-white group-hover:underline">Facebook</span>
    </a>
  </div>
</section>