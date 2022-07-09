<template>
  <body>
    <section class="hero is-info is-fullheight">
      <div class="hero-head">
        <!-- <nav class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <a class="navbar-item" href="../">
                <img
                  src="http://bulma.io/images/bulma-type-white.png"
                  alt="Logo"
                />
              </a>
              <span class="navbar-burger burger" data-target="navbarMenu">
                <span></span>
                <span></span>
                <span></span>
              </span>
            </div>
            <div id="navbarMenu" class="navbar-menu">
              <div class="navbar-end">
                <span class="navbar-item">
                  <a class="button is-white is-outlined" href="#">
                    <span class="icon">
                      <i class="fa fa-home"></i>
                    </span>
                    <span>Home</span>
                  </a>
                </span>
                <span class="navbar-item">
                  <a class="button is-white is-outlined" href="#">
                    <span class="icon">
                      <i class="fa fa-superpowers"></i>
                    </span>
                    <span>Examples</span>
                  </a>
                </span>
                <span class="navbar-item">
                  <a class="button is-white is-outlined" href="#">
                    <span class="icon">
                      <i class="fa fa-book"></i>
                    </span>
                    <span>Documentation</span>
                  </a>
                </span>
                <span class="navbar-item">
                  <a
                    class="button is-white is-outlined"
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/landing.html"
                  >
                    <span class="icon">
                      <i class="fa fa-github"></i>
                    </span>
                    <span>View Source</span>
                  </a>
                </span>
              </div>
            </div>
          </div>
        </nav> -->
      </div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <div class="column is-6 is-offset-3">
            <h1 class="title">Recycle for the greater good</h1>
            <h2 class="subtitle">
              Input values below to visualize the benefit of recycling
            </h2>
            <div class="box">
              <div class="field is-horizontal">
                <div class="field-body">
                  <!-- <div class="field">
                    <p class="control is-expanded">
                      <input
                        class="input is-primary"
                        type="text"
                        placeholder="Waste Category"
                      />
                    </p>
                  </div> -->
                  <div class="field">
                    <div class="control">
                      <div class="select">
                        <select>
                          <option>Paper</option>
                          <option>Glass</option>
                          <option>Organic</option>
                          <option>Plastic</option>
                        </select>
                      </div>
                    </div>
                  </div>
                  <div class="field">
                    <p class="control">
                      <input
                        class="input is-primary"
                        type="text"
                        placeholder="Weight(g)"
                      />
                    </p>
                  </div>
                  <div class="field">
                    <p class="control">
                      <a class="button is-info"> Recycle it! </a>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </body>
</template>

<style scoped>
@import "../../assets/css/tree.css";
</style>
