<template>
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bulma Version 0.9.0-->
    <link
      rel="stylesheet"
      href="https://unpkg.com/bulma@0.9.0/css/bulma.min.css"
    />
    <link
      href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"
      rel="stylesheet"
      integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <!-- END NAV -->
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div class="columns is-8 is-variable">
            <div class="column is-two-thirds has-text-left">
              <h1 class="title is-1">Contact Us</h1>
              <p class="is-size-4">
                Feel free to reach out to us if you have any question :D
              </p>
              <div class="social-media">
                <a
                  href="https://facebook.com"
                  target="_blank"
                  class="button is-light is-large"
                  ><i class="fa fa-facebook-square" aria-hidden="true"></i
                ></a>
                <a
                  href="https://instagram.com"
                  target="_blank"
                  class="button is-light is-large"
                  ><i class="fa fa-instagram" aria-hidden="true"></i
                ></a>
                <a
                  href="https://twitter.com"
                  target="_blank"
                  class="button is-light is-large"
                  ><i class="fa fa-twitter" aria-hidden="true"></i
                ></a>
              </div>
            </div>
            <div class="column is-one-third has-text-left">
              <div class="field">
                <label class="label">Name</label>
                <div class="control">
                  <input class="input is-medium" type="text" />
                </div>
              </div>
              <div class="field">
                <label class="label">Email</label>
                <div class="control">
                  <input class="input is-medium" type="text" />
                </div>
              </div>
              <div class="field">
                <label class="label">Message</label>
                <div class="control">
                  <textarea class="textarea is-medium"></textarea>
                </div>
              </div>
              <div class="control">
                <button
                  type="submit"
                  class="button is-success is-fullwidth has-text-weight-medium is-medium"
                >
                  Send Message
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </body>
</template>

<style scoped>
@import "../../assets/css/contact.css";
</style>
