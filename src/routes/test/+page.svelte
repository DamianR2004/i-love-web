<script>
  import { onMount } from 'svelte';

  onMount(() => {
    const observer = new IntersectionObserver((entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        } else {
          entry.target.classList.remove('show');
        }
      });
    });

    const hiddenElements = document.querySelectorAll('.hidden');
    hiddenElements.forEach((el) => observer.observe(el));
  });
</script>

<main>
  <section class="hidden">
    <h1>Hallo wereld</h1>
    <p>Welkom op de pagina van de SvelteKit app</p>
    <img src="/840_2160.jpg" height="380" width="500" alt="osso">
  </section>

  <section class="hidden">
    <h1>Hallo wereld</h1>
    <p>Welkom op de pagina van de SvelteKit app</p>
    <img src="/840_2160.jpg" height="380" width="500" alt="osso">
  </section>

  <section class="hidden">
    <h1>Hallo wereld</h1>
    <p>Welkom op de pagina van de SvelteKit app</p>
    <img src="/840_2160.jpg" height="380" width="500" alt="osso">
  </section>

  <section class="hidden">
    <h1>Hallo wereld</h1>
    <p>Welkom op de pagina van de SvelteKit app</p>
    <img src="/840_2160.jpg" height="380" width="500" alt="osso">
  </section>
</main>

<style>
  .hidden{
    opacity: 0;
    transition: all 1.5s;
    filter: blur(5px);
    scale: 0.6;

    &.show{
      opacity: 1;
      filter: blur(0);
      scale: 1;
    }
  }
</style>