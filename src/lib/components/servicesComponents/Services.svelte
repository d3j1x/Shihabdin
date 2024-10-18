<section class="py-10" id="services">
  <h2 class=" title text-4xl md:text-5xl font-bold mb-10">Services</h2>

  <div class="bg-slate-950/10 content md:my-10 xl:my-44">
    <div class="card max-w-sm bg-slate-950">
      <div class="icon text-7xl">
        <i class="fa-solid fa-code"></i>
      </div>
      <div class="info">
        <h3 class="text-2xl">Full Stack Developement</h3>
        <p class="text-lg tracking-widest leading-10 text-balance">
          Building dynamic, responsive websites and applications using front-end
          and back-end technologies.
        </p>
      </div>
    </div>
    <div class="card max-w-sm bg-slate-950">
      <div class="icon text-7xl">
        <i class="fa-solid fa-microscope"></i>
      </div>
      <div class="info">
        <h3 class="text-2xl">Software Testing</h3>
        <p class="text-lg tracking-widest leading-10 text-balance">
          Ensuring the highest quality and reliability of software through
          comprehensive testing and validation.
        </p>
      </div>
    </div>
    <div class="card max-w-sm bg-slate-950">
      <div class="icon text-7xl">
        <i class="fa-solid fa-rectangle-ad"></i>
      </div>
      <div class="info">
        <h3 class="text-2xl">Digital Marketing</h3>
        <p class="text-lg tracking-widest leading-10 text-balance">
          Helping businesses grow their online presence through targeted
          campaigns and digital strategies.
        </p>
      </div>
    </div>
  </div>
</section>

<style>
  .title {
    display: flex;
    justify-content: center;
    color: lightgray;
  }

  .content {
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    flex-wrap: wrap;
  }

  .card {
    color: white;
    border-radius: 10px;

    border: black solid 5px;
    padding: 10px;
    margin: 15px;
    transition: 0.7s ease;
  }

  .card:hover {
    transform: scale(1.1);
  }

  .icon {
    color: greenyellow;
    text-align: center;
    margin: 20px;
  }

  .info {
    text-align: center;
  }

  .info p {
    font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
      sans-serif;
  }

  .info h3 {
    color: #3a6cf4;
    font-weight: 700;
    margin: 10px;
  }
</style>
