<template>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Admin - Free Bulma template</title>
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <link
      href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,700"
      rel="stylesheet"
    />
    <!-- Bulma Version 0.9.0-->
    <link
      rel="stylesheet"
      href="https://unpkg.com/bulma@0.9.0/css/bulma.min.css"
    />
    <link rel="stylesheet" type="text/css" href="../css/admin.css" />
  </head>

  <body>
    <div class="container">
      <div class="columns">
        <div class="column is-9">
          <section class="hero is-info welcome is-small">
            <div class="hero-body">
              <div class="container">
                <h1 class="title">Hello, User.</h1>
                <h2 class="subtitle">Hope you are having a green day!</h2>
              </div>
            </div>
          </section>
          <section class="info-tiles">
            <div class="tile is-ancestor has-text-centered">
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <p class="title">18%</p>
                  <p class="subtitle">
                    more solid waste generated compared to last month
                  </p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <p class="title">6%</p>
                  <p class="subtitle">recycling rate of plastic</p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <p class="title">55%</p>
                  <p class="subtitle">
                    more solid waste is recycled compared to last month
                  </p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <p class="title">1902 Watts</p>
                  <p class="subtitle">
                    electrical energy is saved by recycling this month
                  </p>
                </article>
              </div>
            </div>
          </section>
          <h1>Distribution of Waste Type this Month (PieChart)</h1>

          <pie-chart
            :data="[['Paper & cardboard', '25%'],
          ['Glass', '25%'],
          ['Organic', '10%'],
          ['Plastic', '15%'],
          ['Metal', '10%'],
          ['Hazardous Wastes', '14%'],
          ['Other Wastes', '1%']]"
            :colors="[
              '#96c67f',
              '#90EE90',
              '#008000',
              '#006400',
              '#556B2F',
              '#228B22',
              '#32CD32',
            ]"
          ></pie-chart>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
</script>

<style>
@import "../../assets/css/admin.css";
</style>


