<template>
  <div class="home">
    <section class="hero is-dark vw-100">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">GOOSEBUMPS</h1>
          <h2 class="subtitle">COME STANDARD</h2>
          <p class="paragraph">
            Discover the benefits of DRIVECLUB Trade-in and get a free vehicle
            evaluation
          </p>
          <div>
            <b-button class="button">
              Contact us
              <img src="../assets/chevron.svg" />
            </b-button>
          </div>
        </div>
      </div>
    </section>
    <section class="content">
      <b-container class="bv-example-row" fluid="sm">
        <b-row>
          <b-col>
            <b-card class="mb-2">
              <h3 class="subtitles">NEW RANGE</h3>
              <h1 class="title">LA FERRARI</h1>
              <a class="link">
                <router-link to="/learn"> LEARN MORE </router-link>
              </a>
            </b-card>
          </b-col>

          <b-col>
            <b-card class="mb-2">
              <img class="car" src="../assets/car-large.jpg" />
            </b-card>
          </b-col>
        </b-row>
      </b-container>

      <div class="card-row"></div>
    </section>
  </div>
</template>

<script>

export default {
  name: "home",
  components: {}
};
</script>

<style lang="scss" scoped>
.hero {
  text-align: left;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100%;
  padding-left: 15%;
}
.content {
  background-position: left;
}
.hero-body .title {
  font-size: 80px;
  color: white;
}
.subtitle {
  text-shadow: 4px 4px 4px rgba(91, 89, 89, 0.7);
  font-size: 40px;
}
.hero-body .paragraph {
  color: white;
}
.bv-example-row {
  border: 2px solid white;
  padding-right: 2px;
  width: 50%;
  .mb-2 {
    margin-top: 5px;
    .link {
      color: rgb(236, 16, 16);
      font-weight: 3px;
    }
    .subtitles {
      color: whitesmoke;
    }
  }
  .mb-2 {
    .car {
      width: 40%;
      height: 30%;
    }
  }
}
.button {
  border: 3px solid rgb(202, 50, 50);
  background-color: rgb(113, 61, 61);
  margin-right: 50px;
  padding-right: 50px;
  color: white;
}
.is-xl {
  font-size: 1.7rem;
}
</style>
