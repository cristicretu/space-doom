<script lang="ts">
 import Counter from "./lib/Counter.svelte";
</script>

<main
 class="bg-gray-50 dark:bg-gray-900 p-8 motion-reduce:transform-none motion-reduce:transition-none h-full min-h-screen relative w-full"
>
 <div class="flex flex-col justify-center items-center">
  <h1 class="font-bold text-4xl">
   Svelte + Typescript + Tailwind + Vite = &lt;3
  </h1>

  <div class="hover:cursor-pointer">
   <Counter />
  </div>
 </div>
</main>
