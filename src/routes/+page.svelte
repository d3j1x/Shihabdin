<script>
  import Welcome from "$lib/components/homeComponents/Welcome.svelte";
  import Hero from "$lib/components/homeComponents/Hero.svelte";
  import Iam from "$lib/components/homeComponents/Iam.svelte";
</script>

<svelte:head>
  <title>𝐒𝐡𝐢𝐡𝐚𝐛𝐝𝐢𝐧 ✪</title>
  <meta
    name="description"
    content="Shihabdin Official Portfolio.
  Cybersecurity specialist 🔐 | Full-Stack Developer 🛠 | Opensource 🔥.
  "
  />
</svelte:head>

<div class="myCustombg0 bg-cover">
  <div class="pt-16 pb-2 backdrop-brightness-75">
    <div class="px-10 max-w-5xl m-auto">
      <Welcome />
    </div>
  </div>
</div>

<div class="py-10 md:py-20">
  <Iam />
</div>

<main>
  <div class="pb-20">
    <Hero />
  </div>
</main>

<style>
  .myCustombg0 {
    background-image: url("../lib/img/cover.jpg");
    background-repeat: no-repeat;
  }
</style>
