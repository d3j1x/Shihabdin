<script>
  import { Card } from "flowbite-svelte";
</script>

<main>
  <div
    class="relative bg-gray-950/10
        py-10 mx-auto"
  >
    <h1
      style="font-family:'Protest Guerrilla', system-ui;font-weight: 400;font-style: normal;"
      class="mix-blend-hard-light my-20 md:my-20 lg:my-20
      text-3xl md:text-4xl lg:text-5xl text-center bg-gradient-to-b from-yellow-100 to-yellow-500 bg-clip-text text-transparent tracking-wide"
    >
      My Best
      <span class="my-2">
        <a
          class="hover:bg-gradient-to-t hover:from-yellow-100 hover:to-yellow-500
        hover:bg-clip-text hover:text-transparent"
          href="/projects">Projects</a
        > !
      </span>
    </h1>

    <div
      class=" grid grid-cols-1 md:grid-cols-2
        gap-10 xl:gap-20 m-5 xl:mx-40"
    >
      <div
        class="myCustombg1 rounded-md col-span-1 mx-auto md:my-16
        bg-black transition-transform duration-300 hover:scale-105 hover:bg-transparent"
      >
        <Card
          class="bg-transparent shadow-sm   shadow-yellow-300 border-none 
            backdrop-blur-none"
        >
          <a href="https://smx.tn" target="_blank" rel="noreferrer">
            <h5
              class="my-4 text-center text-2xl md:text-3xl lg:text-4xl
                   text-gray-200 font-extrabold goldHover"
            >
              SMRT MRKT X
            </h5>
          </a>
          <p
            class="mb-2 px-4 font-bold text-gray-400 text-lg lg:text-xl lg:my-4 text-center goldHover"
          >
            Join our community to stay ahead in the dynamic world.
          </p>
          <a
            href="https://smx.tn"
            target="_blank"
            rel="noreferrer"
            class="inline-flex items-center text-gray-200 font-semibold goldHover"
          >
            Explore now
          </a>
        </Card>
      </div>

      <div
        class="bg-primary-950 myCustombg2 rounded-md col-span-1 mx-auto md:my-16
        transition-transform duration-300 hover:scale-105 hover:bg-black/50"
      >
        <Card
          class="bg-transparent shadow-sm shadow-yellow-300 border-none backdrop-blur-none"
        >
          <a href="https://earnmoney.tn" target="_blank" rel="noreferrer">
            <h5
              class="my-4 text-2xl md:text-3xl lg:text-4xl
                 text-center text-gray-200 font-extrabold goldHover"
            >
              EARNMONEY
            </h5>
          </a>
          <p
            class="mb-2 px-4 font-bold text-gray-400 text-lg lg:text-xl lg:my-4 text-center goldHover"
          >
            Discover the secrets of earning online passive income.
          </p>
          <a
            href="https://earnmoney.tn"
            target="_blank"
            rel="noreferrer"
            class="inline-flex items-center text-gray-200 font-semibold goldHover"
          >
            Explore now
          </a>
        </Card>
      </div>
    </div>
  </div>
</main>

<style>
  .myCustombg1,
  .myCustombg2 {
    background-size: 60px;
    background-repeat: no-repeat;
    background-position: 98% 95%;
  }

  .myCustombg1 {
    background-image: url("/src/lib/img/smx.jpg");
  }

  .myCustombg2 {
    background-image: url("/src/lib/img/earnmoney.png");
  }

  .goldHover:hover {
    background: linear-gradient(
      to bottom,
      #fefcbf,
      #f59e0b
    ); /* Gradient from yellow-100 (#fefcbf) to yellow-500 (#f59e0b) */
    -webkit-background-clip: text; /* Clipping the background to the text */
    background-clip: text; /* For other browsers */
    color: transparent; /* Makes the text itself transparent */
    font-style: normal; /* Ensures the text is not italic */
  }
</style>
