<script>
  import { onMount } from "svelte";
  import gsap from "gsap";
  onMount(() => {
    const tl = gsap.timeline({
      defaults: {
        ease: "power2.inout",
      },
    });

    tl.fromTo(
      ".hero__heading",
      { scale: 0.5 },
      { scale: 1, opacity: 1, duration: 1 },
    );
    tl.fromTo(
      ".hero__body",
      { y: 20 },
      { y: 0, opacity: 1, duration: 1 },
      "-=0.1",
    );
  });
</script>

<h1
  style="font-family:'Protest Guerrilla', system-ui;font-weight: 400;font-style: normal;"
  class="mix-blend-hard-light hero__heading opacity-0
      text-3xl md:text-4xl lg:text-5xl text-center
      py-10 bg-gradient-to-b from-yellow-100 to-yellow-500 bg-clip-text text-transparent tracking-wide"
>
  Who I am ?
</h1>

<p
  class="hero__body opacity-0 text-primary-200 text-xl md:text-3xl text-center"
>
  <span class="tracking-widest leading-loose">
    I am a <br /><b>full-stack developer</b><br />
    with expertise in <b>cybersecurity</b> <br />
    and a foundation in <b>software testing</b>.<br /><br />
    I am passionate about <br />
    <b>building secure, efficient</b> applications<br /> and ensuring
    <b>high-quality software solutions.</b></span
  >
</p>
