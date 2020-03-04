<template>
  <div id="contact-form-container">
    <h1 class="title has-text-centered">Contact Us</h1>
    <div class="columns is-mobile is-centered">
      <div class="column is-two-thirds">
          <div class="field">
            <label class="label">Name</label>
            <div class="control">
                <input class="input is-medium" type="text">
            </div>
          </div>
          <div class="field">
            <label class="label">Email</label>
            <div class="control">
                <input class="input is-medium" type="text">
            </div>
          </div>
          <div class="field">
            <label class="label">Message</label>
            <div class="control">
                <textarea class="textarea is-medium"></textarea>
            </div>
          </div>
          <div class="control">
            <button type="submit" class="button is-link is-fullwidth has-text-weight-medium is-medium">Send Message</button>
          </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {}
</script>

<style lang="scss" scoped>

#contact-form-container {
  margin-top: 150px;
}

</style>