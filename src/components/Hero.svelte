<script lang="ts">
  import { Button } from "$lib/components/ui/button/index.js";
  import { Input } from "$lib/components/ui/input/index.js";
</script>

<div class="pt-10 pt-hero min-h-screen bg-base-200">
  <h1
    class="flex flex-col text-center text-5xl font-semibold sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl 2xl:text-8xl"
  >
    Visualize your <span class="text-blue-500">bucket model</span> run with a simple
    click
  </h1>
  <div class="pt-10 flex justify-center items-center">
    <form class="flex w-full max-w-sm items-center space-x-2">
      <Input type="email" placeholder="upload .csv" />
      <Button type="submit">Visualise</Button>
    </form>
  </div>
</div>
