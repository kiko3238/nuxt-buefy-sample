<template>
  <!-- Begin features Content -->
  <div class="section-color features" id="features">
    <div class="container is-horizonal-centered">
      <div class="columns is-multiline">
        <div
          class="column is-12">
          <h1 class="title has-text-centered section-title">features</h1>

          <h2 class="subtitle">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua
          </h2>
          <br />
        </div>
        <div class="columns is-12 is-marginless">
          <div class="column is-4 has-text-centered">
            <i class="fas fa-meteor fa-3x"></i>
            <hr />
            <h2>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
              do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
          </div>
          <div class="column is-4 has-text-centered">
            <i class="fas fa-paint-brush fa-3x"></i>
            <hr />
            <h2>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
              do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
          </div>
          <div class="column is-4 has-text-centered">
            <i class="fas fa-rocket fa-3x"></i>
            <hr />
            <h2>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
              do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
          </div>
        </div>
        <div class="columns is-12 is-marginless">
          <div class="column is-4 has-text-centered">
            <i class="fas fa-upload fa-3x"></i>
            <hr />
            <h2>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
              do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
          </div>
          <div class="column is-4 has-text-centered">
            <i class="fas fa-bus fa-3x"></i>
            <hr />
            <h2>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
              do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
          </div>
          <div class="column is-4 has-text-centered">
            <i class="fas fa-code fa-3x"></i>
            <hr />
            <h2>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
              do eiusmod tempor incididunt ut labore et dolore magna aliqua
            </h2>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End features Content -->
</template>

<script>

export default {}
</script>

<style lang="scss" scoped>

#features {
  margin-top: 100px;
}

.section-color.features {
  padding: 100px;
  background-color: #43485c;
  color: white;

  @media (max-width: 599px) {
    padding: 40px;
  }
}

.section-color.features .title,
.section-color.features .subtitle {
  color: white;
}

.section-color.features i {
  font-size: 3rem;
  padding: 20px;
}

.section-title {
  color: #43485c;
  text-transform: uppercase;
  font-size: 1.8rem;
  letter-spacing: 2px;
  padding-bottom: 30px;
}

.is-horizonal-centered {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.has-text-centered {
  padding: 20px;
}
</style>