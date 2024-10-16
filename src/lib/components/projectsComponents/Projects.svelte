<script>
  import smxtnlogo from "$lib/img/001.jpg";
  import earnmoneytnlogo from "$lib/img/002.png";
  import bitcoinstreetlogo from "$lib/img/003.png";

  let imageUrl = "/src/lib/img/001.jpg";
  let altText = "A sample image";
  let imageWidth = 300;
  let imageHeight = 200;
</script>

<section class="projects text-black py-10 lg:py-20" id="projects">
  <h2 class="title text-4xl md:text-5xl font-bold mb-10">Projects</h2>
  <div class="content bg-white pt-10">
    <div class="project-card mb-10 mx-4 md:mx-10">
      <div class="project-image max-w-7xl">
        <img src={smxtnlogo} alt={altText} />
      </div>
      <div class="project-info text-2xl md:text-3xl lg:text-4xl">
        <p class="project-category">Smart Tips Hints Resources..</p>
        <strong class="project-title">
          <span>SMRT MRKT X</span>
          <a href="https://smx.tn" target="_blank" class="more-details"
            >More detais</a
          >
        </strong>
      </div>
    </div>
    <div class="project-card my-10 md:my-10 mx-4 md:mx-10">
      <div class="project-image max-w-7xl">
        <img src={earnmoneytnlogo} alt={altText} />
      </div>
      <div class="project-info text-2xl md:text-3xl lg:text-4xl">
        <p class="project-category">
          Earn Passive Income, Best Crypto Faucets, Next Level..
        </p>
        <strong class="project-title">
          <span>EARNMONEY</span>
          <a href="https://earnmoney.tn" target="_blank" class="more-details"
            >More details</a
          >
        </strong>
      </div>
    </div>
    <div class="project-card my-10 md:my-10 mx-4 md:mx-10">
      <div class="project-image max-w-7xl">
        <img src={bitcoinstreetlogo} alt={altText} />
      </div>
      <div class="project-info text-2xl md:text-3xl lg:text-4xl">
        <p class="project-category">BTC CRYPTO-NEWS BEST WALLETS</p>
        <strong class="project-title">
          <span>BITCOIN STREET</span>
          <a
            href="https://bitcoin-street.vercel.app/"
            target="_blank"
            class="more-details">More details</a
          >
        </strong>
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
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap;
  }

  .projects {
    background-color: #000016;
  }

  .project-card {
    background-color: #3a6cf4;
    border: 1px solid #fff;

    overflow: hidden;
    border-radius: 10px;
  }

  .project-image img {
    width: 100%;
  }

  .project-info {
    padding: 1em;
  }

  .project-category {
    font-size: 0.8em;
    color: #000;
  }

  .project-title {
    display: flex;
    justify-content: space-between;
    text-transform: uppercase;
    font-weight: 800;
    margin-top: 10px;
  }

  .more-details {
    text-decoration: none;
    color: #fff;
  }

  .more-details:hover {
    color: yellowgreen;
  }
</style>
