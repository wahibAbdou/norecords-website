<template>
  <div class="container-nsr">
    <header class="header">
      <div class="navbar">
        <img src="~assets/logo-png.png" />
      </div>
      <h1>DEMO SUBMISSIONS</h1>
      <div class="demo-form">
        <div
          class="cui-embed"
          style="height: 400px; width: 100%"
          data-cui-uid="M84KnFrm"
          data-cui-avatar="https://images.typeform.com/images/kzvEuEYYKemm"
          data-cui-mode="widget"
        ></div>
        <script
          src="https://public-assets.typeform.com/confab/embed.js"
          async
        ></script>
      </div>
      <div class="footer">
        <p>Copyright © 2021 NØSIGNAL RECORDS. All rights reserved.</p>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  head: {
    title: 'DEMO SUBMISSIONS ~ NØSIGNAL RECORDS',
  },
}
</script>

<style>
.container-nsr {
  margin: 0 auto;
  min-height: 100vh;
}

.header {
  background: #000;
  width: 100%;
  height: 500px;
  padding: 0 100px;
}

.header .navbar {
  margin-bottom: 150px;
}

.header img {
  width: 190px;
}
.header h1 {
  text-align: center;
  font-size: 50px;
  color: #fff;
  font-family: 'Rajdhani', sans-serif;
  margin-bottom: 35px;
}

.header .demo-form {
  width: 75%;
  border: 1px solid #000;
  border-radius: 20px;
  overflow: hidden;
  margin: auto;
  margin-bottom: 30px;
}

.footer {
  text-align: center;
  color: #3a3a3a;
  margin-bottom: 160px;
}

/*
  ##Device = Desktops
  ##Screen = 1281px to higher resolution desktops
*/

@media (min-width: 1281px) {
  /* CSS */
}

/*
  ##Device = Laptops, Desktops
  ##Screen = B/w 1025px to 1280px
*/

@media (min-width: 1025px) and (max-width: 1280px) {
  /* CSS */
}

/*
  ##Device = Tablets, Ipads (portrait)
  ##Screen = B/w 768px to 1024px
*/

@media (min-width: 768px) and (max-width: 1024px) {
  /* CSS */
  .header {
    padding: 0 10px;
  }
  .header .demo-form {
    width: 90% !important;
  }
  .footer {
    margin-bottom: 260px;
  }
}

/*
  ##Device = Tablets, Ipads (landscape)
  ##Screen = B/w 768px to 1024px
*/

@media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
  /* CSS */
  .header {
    padding: 0 10px;
  }
  .header .demo-form {
    width: 90% !important;
  }
  .footer {
    margin-bottom: 260px;
  }
}

/*
  ##Device = Low Resolution Tablets, Mobiles (Landscape)
  ##Screen = B/w 481px to 767px
*/

@media (min-width: 481px) and (max-width: 767px) {
  /* CSS */
  .header {
    padding: 0 10px;
  }
  .header .demo-form {
    width: 80% !important;
  }
  .footer {
    margin-bottom: 260px;
  }
}

/*
  ##Device = Most of the Smartphones Mobiles (Portrait)
  ##Screen = B/w 320px to 479px
*/

@media (min-width: 320px) and (max-width: 480px) {
  /* CSS */
  .header {
    padding: 0 10px;
  }
  .header .demo-form {
    width: 90% !important;
  }
  .footer {
    margin-bottom: 260px;
  }
}
</style>
