<script>
  import Form from '../form.svelte';
  import Footer from '../Footer.svelte';
</script>

<div class="relative h-screen">
  <div class="mx-auto px-16 pt-8">
    <div class="grid grid-rows-2 gap-5">
      <div class="hero grid grid-rows-3">
        <div class="flex gap-3 text-3xl my-auto">
          <p>Welcom to</p>
          <div class="text-blue-500 font-extrabold">Lorem</div>
        </div>
        <p class="text-gray-400 my-auto">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium
          laborum mollitia sequi!
        </p>
        <div class="flex flex-row gap-1 my-auto">
          <div class="h-1 w-24 bg-blue-500 rounded-sm" />
          <div class="h-1 w-24 bg-gray-300 rounded-sm" />
        </div>
      </div>

      <Form />

      <Footer />
    </div>
  </div>
</div>
