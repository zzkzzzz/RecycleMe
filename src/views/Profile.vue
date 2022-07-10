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
        <div class="column is-12">
          <section class="hero is-info welcome is-small">
            <div class="hero-body">
              <div class="container">
                <h1 class="title">Hello, William.</h1>
                <h2 class="subtitle">Hope you are having a green day!</h2>
              </div>
            </div>
          </section>
          <section class="info-tiles">
            <div class="tile is-ancestor has-text-centered">
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <br>
                  <img style="height: 180px; width: 160px;"
                  src="https://d1nhio0ox7pgb.cloudfront.net/_img/g_collection_png/standard/512x512/tree.png"
                  alt="Tree"
                   />
                  <br>
                  <br>
                  <p class="title">6 Trees</p>
                  <p class="subtitle">planted physically in Singapore so far</p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <img
                  src="data:image/png;base64,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"
                  alt="waste"
                   />
                  <p class="title">18%</p>
                  <p class="subtitle">
                    more solid waste generated compared to last month
                  </p>
                </article>
              </div>
              
              <div class="tile is-parent">
                <article class="tile is-child box">
                  <img
                  src="https://img.freepik.com/premium-vector/recycle-icon-symbol-vector-illustration_77417-300.jpg?w=2000"
                  alt='recycle'
                   />
                  <p class="title">55%</p>
                  <p class="subtitle">
                    more solid waste is recycled compared to last month
                  </p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child box">
                   <img
                  src="https://www.mcicon.com/wp-content/uploads/2020/12/Industrial_Electricity_1-copy-10.jpg"
                  alt='electricity'
                   />
                  <p class="title">1902 Watts</p>
                  <p class="subtitle">
                    electrical energy is saved by recycling this month
                  </p>
                </article>
              </div>
            </div>
          </section>
         

          <div class="PieChart">
          <br>
          <br>
          <h1>Distribution of Waste Type this Month(%)</h1>
          </div>
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
          <br>
          <br>
         
         <div class="LineChart">
          <h1>Quantaty of waste recycled this month(kg)</h1>
          <line-chart :data="{ '2022-06-01':'0.640', 
          '2022-06-06':'0.35',
          '2022-06-08':'0.735',
          '2022-06-10':'0.506',
          '2022-06-11':'0.454',
          '2022-06-15':'0.450',
          '2022-06-20':'0.530',
          '2022-06-22':'0.570',
          '2022-06-25':'0.459',
          '2022-06-29':'0.530'}"
          :colors="[
          '#4dc567'
          ]">
          </line-chart>
          </div>
          <br>
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


