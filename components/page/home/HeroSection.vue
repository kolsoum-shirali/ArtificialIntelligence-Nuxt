<template>
  <section id="hero" class="d-flex align-items-center">
    <div class="container">
      <div class="row">
        <div
          class="col-lg-6 d-flex flex-column justify-content-center pt-4 pt-lg-0 order-2 order-lg-1"
          data-aos="fade-up"
          data-aos-delay="200"
        >
          <h1>Builidng AI-powered industries</h1>
          <h2>
            Leveraging the full potential of data to inform decision making,
            support evidence-based practice, and advance research and
            innovation.
          </h2>
          <div class="d-flex justify-content-center justify-content-lg-start">
            <a href="#about" class="btn-get-started scrollto">Get Started</a>
            <a
              href="https://youtu.be/vs03sYCtgec"
              class="glightbox btn-watch-video"
              ><i class="bi bi-play-circle"></i><span>Watch Video</span></a
            >
          </div>
        </div>
        <div
          class="col-lg-6 order-1 order-lg-2 hero-img"
          data-aos="zoom-in"
          data-aos-delay="200"
        >
          <img
            :src="require(`assets/images/hero-img.png`)"
            class="img-fluid animated"
            alt="hero"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>
