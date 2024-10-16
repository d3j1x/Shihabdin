<section class="cards py-10 lg:py-20" id="services">
  <h2 class="title text-4xl md:text-5xl font-bold mb-10">Services</h2>
  <div class="content md:my-10 lg:my-20 xl:my-28">
    <div class="card">
      <div class="icon">
        <i class="fa-solid fa-code"></i>
      </div>
      <div class="info">
        <h3>Full Stack Developement</h3>
        <p class="hover:font-semibold">
          Building dynamic, responsive websites and applications using front-end
          and back-end technologies ...
        </p>
      </div>
    </div>
    <div class="card">
      <div class="icon">
        <i class="fa-solid fa-microscope"></i>
      </div>
      <div class="info">
        <h3>Software Testing</h3>
        <p class="hover:font-semibold">
          Ensuring the highest quality and reliability of software through
          comprehensive testing and validation ...
        </p>
      </div>
    </div>
    <div class="card">
      <div class="icon">
        <i class="fa-solid fa-rectangle-ad"></i>
      </div>
      <div class="info">
        <h3>Digital Marketing</h3>
        <p class="hover:font-semibold">
          Helping businesses grow their online presence through targeted
          campaigns and digital strategies ...
        </p>
      </div>
    </div>
  </div>
</section>

<style>
  .title {
    display: flex;
    justify-content: center;
    color: #3a6cf4;
  }

  .content {
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    flex-wrap: wrap;
  }

  .card {
    background-color: #fff;
    color: #000;
    width: 21.25em;
    box-shadow: 0 5px 10px whitesmoke;
    border-radius: 10px;
    padding: 25px;
    margin: 15px;
    transition: 0.7s ease;
  }

  .card:hover {
    transform: scale(1.1);
  }

  .icon {
    color: #3a6cf4;
    font-size: 7em;
    text-align: center;
  }

  .info {
    text-align: center;
  }

  .info h3 {
    color: #3a6cf4;
    font-size: 1.2em;
    font-weight: 700;
    margin: 10px;
  }

  .contact .info h3 {
    color: #000;
  }

  .contact .info p {
    font-size: 1.5em;
  }
</style>
