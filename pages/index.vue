<template>
  <div>
    <header>
      <img src="/logo-color.png" class="logo"/>
      <!-- <b-link href="#" class="apply"><span><i class="fa fa-pen"></i></span> Apply</b-link> -->
    </header>

    <div class="hero">
      <b-container>
        <b-row class="d-flex align-items-center">
          <b-col md="7">
            <h2>Lextax, for hassle-free tax compliance</h2>
            <p>Forget about missing the deadlines, tax penalties/fines, or any confusing forms, easy step as ABC, and your tax* problem, solved better.</p>
            <b-link class="get-started" href="#" v-scroll-to="'#feature'">Get Started <i class="fa fa-long-arrow-alt-down"></i></b-link>
          </b-col>
          <b-col md="5">
            <div class="v-wrap">
              <video autoplay="autoplay" loop="loop" muted="muted"><source src="/vid2.mp4" type="video/mp4"></video>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <div class="feature" id="feature">
      <b-container>
        <b-row>
          <b-col md="12">
            <!-- <h3 class="title">Our Feature</h3> -->
            <h3 class="title">Tailored for SMEs & Startup businesses needs</h3>
          </b-col>
          <b-col md="6">
            <div class="feature-item">
              <span class="number">01.</span>
              <p class="pt-2">Affordable monthly subscriptions</p>
            </div>
            <div class="feature-item">
              <span class="number">02.</span>
              <p><span class="bold">A STARTUP EXPERT</span><br/>was built from the ground up around the needs of founders & modern, agile businesses. </p>
            </div>
            <div class="feature-item">
              <span class="number">03.</span>
              <p>Our co-founder has committed to help navigate the tax compliance needs of young entrepreneurs. They also have the experienced as in support the widely known 1000 Startups movement and more impactful events supporting startup and SMEs ecosystem likewise.</p>
            </div>
          </b-col>
          <b-col md="6">
            <div class="feature-item">
              <span class="number">04.</span>
              <p class="pt-2">Operate with latest SAAS product by our partner Fintax.id</p>
            </div>
            <div class="feature-item">
              <span class="number">05.</span>
              <p>Our founders have involved in various tax litigation projects (including tax audit assistance, tax objection, tax appeal and tax reconsideration request), tax advisory works (in relation to the tax regulatory framework), tax due diligence, tax structuring, assurance support (assistance in financial audit process), tax compliance (both monthly and annual tax compliance projects) and assistance with tax amnesty program.</p>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <div class="how-we-help">
      <b-container>
        <b-row>
          <b-col lg="8" offset-lg="2">
            <div class="wrap-help">
              <h3>How we help clients</h3>
              <h4>Lextax will help you do the tax filing that includes PPh Pasal 21,23,26,4(2)</h4>

              <p>SPT Bulanan PPh – Perusahaan dengan penghasilan kurang dari Rp 100 juta per bulan</p>

              <div class="list"><span>-</span> Penyusunan SPT, pembuatan Kode Billing setoran, dan Submit SPT PPh Bulanan Pasal 21 atau 26</div>

              <div class="list"><span>-</span> Penyusunan SPT, pembuatan Kode Billing setoran, dan Submit SPT PPh Bulanan Pasal 23 atau 26</div>

              <div class="list"><span>-</span> Kode Billing PPh Bulanan PPh Pasal 25 atau Pasal 4 ayat 2 / PP 46</div>

              <p>
                SPT Bulanan PPh<br/>
                Laporan ini berupa pemenuhan kewajiban pemotongan dan pembayaran PPh Pasal 21,23,26,4(2) atas pengeluaran/pembayaran dari perusahaan kepada pihak lain (misalnya pembayaran gaji, jasa, sewa) dalam periode bulanan
              </p>

            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <div class="price">
      <b-container>
        <b-row>
          <b-col md="12">
            <h3 class="title text-center">Lextax does package to ease you</h3>
          </b-col>
          <b-col md="12" class="text-center">
            <div class="price-wrap">
              <img src="/briefcase.png" alt="">
              <h3>Package A</h3>
              <p>Rp. 1.200.000 -> Rp. 1.000.000</p>
              <p>Transaction + Employee up to 100 (combine)</p>
              <p>Additional: 10rb/transaction (or bundling by request)</p>
            </div>
            <div class="price-wrap">
              <img src="/box.png" alt="">
              <h3>Package B</h3>

              <p>Rp. 600.000 -> Rp. 500.000</p>
              <p>Transaction + Employee up to 50 (combine)</p>
              <p>Additional: 10rb/transaction (normal price)</p>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <footer>
      <b-container>
        <b-row>
          <b-col md="6">
            <img src="/logo-white.png" class="logo" />
            <p>Jalan Wahid Hasyim No. 10D, Kel. Kebon Sirih, Kec. Menteng, Jakarta Pusat, 10340</p>
          </b-col>
          <b-col md="6">
            <h4>Get in touch</h4>
            <b-link href="#" class="socmed"><i class="fab fa-facebook-f"></i></b-link>
            <b-link href="#" class="socmed"><i class="fab fa-twitter"></i></b-link>
            <b-link href="#" class="socmed"><i class="fab fa-instagram"></i></b-link>
            <b-link href="#" class="socmed"><i class="fab fa-linkedin-in"></i></b-link>
          </b-col>
          <b-col md="6">
            <p class="mb-0">© 2019 DOMISILI.ID, ALL RIGHTS RESERVED.</p>
          </b-col>
        </b-row>
      </b-container>
    </footer>
  </div>
</template>

<script>
export default {}
</script>