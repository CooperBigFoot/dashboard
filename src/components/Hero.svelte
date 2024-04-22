<script lang="ts">
  import { Button } from "$lib/components/ui/button/index.js";
  import { Input } from "$lib/components/ui/input/index.js";
</script>

<div class="pt-10 pt-hero min-h-screen bg-gray-200">
  <h1
    class="text-center text-5xl font-semibold sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl 2xl:text-8xl"
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
  <div class="flex flex-wrap justify-center">
    <div class="relative max-w-4xl mx-2 my-4 bg-white p-4">
      <img src="assets/timeseries_monthly.png" alt="Image 1" />
      <a
        href="assets/timeseries_monthly.png"
        download
        class="absolute top-2 right-2 flex items-center space-x-1 text-lg"
      >
        <i class="fas fa-download fa-lg"></i>
        <span>Download .png</span>
      </a>
    </div>
    <div class="relative max-w-4xl mx-2 my-4 bg-white p-4">
      <img src="assets/water_balance.png" alt="Image 2" />
      <a
        href="assets/water_balance.png"
        download
        class="absolute top-2 right-2 flex items-center space-x-1 text-lg"
      >
        <i class="fas fa-download fa-lg"></i>
        <span>Download .png</span>
      </a>
    </div>
  </div>
</div>
