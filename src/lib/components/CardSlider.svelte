<script lang="ts">
  import { onDestroy, onMount} from 'svelte';
  import Swiper from 'swiper';

  export let breakpoints: { [key: number]: { slidesPerView: number } } = {};
  export let spaceBetween: number = 30;

  let swiper: Swiper;

  onMount(() => {
    swiper = new Swiper('.js-card-slide', {
      grabCursor: true,
      spaceBetween,
      pagination: {
        el: '.js-card-pagination',
        clickable: true
      },
      breakpoints
    });
  });
  onDestroy(() => {
    swiper.destroy(true, true);
  });
</script>

<div class="js-card-slide">
  <!-- Your slides here -->
</div>

<div class="js-card-pagination"></div>

<style>
  /* Your styles here */
</style>
