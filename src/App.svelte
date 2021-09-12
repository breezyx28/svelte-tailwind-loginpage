<script>
  import TailwindCSS from './TailwindCSS.svelte';
  import Fa from 'svelte-fa';
  import {
    faStackOverflow,
    faMailchimp,
    faKeybase,
  } from '@fortawesome/free-brands-svg-icons';
  import LeftScreen from './components/leftScreen/image.svelte';
  import RightScreen from './components/rightScreen/formContainer.svelte';
</script>

<TailwindCSS />

<div class="w-screen h-screen">
  <div class="grid grid-cols-2">
    <LeftScreen {faStackOverflow} {Fa} />
    <div class="relative">
      <img
        src="img/bg.jpg"
        alt=""
        class="absolute w-full h-full object-cover"
      />
      <div class="absolute">
        <div class="container mx-10 pt-12">
          <div class="inline-flex space-x-4">
            <div class="flex-1">
              <Fa icon={faStackOverflow} size="2x" color={'blue'} />
            </div>
            <p class="flex-1 text-3xl font-bold">Lorem</p>
          </div>
        </div>
      </div>
    </div>

    <!-- right screen -->
    <RightScreen />
  </div>
</div>
