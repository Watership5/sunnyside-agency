<script setup>
  import egg from "../assets/image-transform.jpg"
  import "../styles/index.css"
  import lotta from "../assets/image-stand-out.jpg"
</script>

<template>
  <section class="main-content-section">
    <div class="style-container">
      <div class="content-container">
        <h1>
          Transform your brand
        </h1>
        <p>
          We are a full service creative agency specializing in helping brands grow fast. Engage your client through compelling visuals that do most of the marketing for you.
        </p>
        <button>
          Learn more
        </button>
      </div>
      <img :src="egg" alt="" width="943"/>
    </div>
    <div class="style-container-two">
      <img :src="lotta" alt="" width="960"/>
      <div class="content-container-two">
        <h1>
          Stand out to the right audience
        </h1>
        <p>
          Using a collaborative formula of designers, researchers, photographers, videographers, and copyrighters, we'll build and extend your brand in digital places
        </p>
        <button>
          Learn more
        </button>
      </div>
    </div>
    <div class="specialties-container">
      <div class="cherries">
        <!-- <img :src="cherries" alt="img" width="960"/> -->
        <div>
          <h1>
            Graphic Design
          </h1>
          <p>
            Great design makes you memorable. We deliver artwork that underscores your brand message and captures potential clients' attention.
          </p>
        </div>
      </div>
      <div class="orange">
        <!-- <img :src="orange" alt="img" width="960"/> -->
        <div>
          <h1>
            Photography
          </h1>
          <p>
            Increase your credibility by getting the most stunning, high-quality photos that improve your business image.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>