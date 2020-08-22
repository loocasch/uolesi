<template>
  <div class="container-fluid wrapper-small-box">
    <div id="menu" class="item-box">
      <h2 class="text-center font-lora font-weight-bold mb-5">Menu</h2>
      <div class="text-center">
        Oferujemy w barze zestawy obiadowe, dania fastfood, lody oraz napoje
        chłodzące.
      </div>

      <div class="row mt-5 justify-content-center card-box">
        <div class="col-md-3">
          <div class="card p-3 mb-md-0 mb-3">
            <img class="card-img-top" src="~assets/images/ham.jpg" alt="" />
          </div>
        </div>
        <div class="col-md-3">
          <div class="card p-3 mb-md-0 mb-3">
            <img class="card-img-top" src="~assets/images/obiad.jpg" alt="" />
          </div>
        </div>
        <div class="col-md-3">
          <div class="card p-3 mb-md-0 mb-3">
            <img
              class="card-img-top"
              src="~assets/images/ice-cream.jpg"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
    <div id="rental" class="item-box">
      <h2 class="text-center font-lora font-weight-bold mb-5">
        Wypożyczalnia
      </h2>
      <div class="text-center">
        <p>
          Oferujemy wypożyczanie sprzętu wodnego na godziny, a także na cały
          dzień w atrakcyjnych cenach. <br />
          Do dyspozycji mamy kajaki oraz rowery wodne. Posiadamy również rowery
          turystyczne.<br />
          Organizujemy spływy kajakowe. <br />Mamy do zaoferowania nocleg w
          Ostaszewskiej chacie - 300 zł/doba.<br />
          Telefon kontaktowy:
          <a href="tel:+48501398022" class="text-default">501398022</a>.
        </p>

        <div class="row mt-5 justify-content-center card-box">
          <div class="col-md-3">
            <div class="card p-3 mb-md-0 mb-3">
              <img
                class="card-img-top"
                src="~assets/images/image7.jpg"
                alt=""
              />
            </div>
          </div>
          <div class="col-md-3">
            <div class="card p-3 mb-md-0 mb-3">
              <img
                class="card-img-top"
                src="~assets/images/image3.jpg"
                alt=""
              />
            </div>
          </div>
          <div class="col-md-3">
            <div class="card p-3 mb-md-0 mb-3">
              <img
                class="card-img-top"
                src="~assets/images/image6.jpg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="gallery" class="item-box">
      <h2 class="text-center font-lora font-weight-bold mb-5">Galeria</h2>
      <Gallery />
    </div>
    <div id="partners" class="item-box">
      <h2 class="text-center font-lora font-weight-bold mb-5">Partnerzy</h2>
      <div class="row mt-5 justify-content-center card-box">
        <div class="col-md-3">
          <a
            href="http://pawieoczko.eu/"
            class="card p-3 mb-md-0 mb-3 text-default"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img
              class="card-img-top"
              src="~assets/images/logo-www-sm.svg"
              alt=""
            />
            <div class="text-center font-size-25 mt-4">
              Pawie Oczko
            </div>
          </a>
        </div>
      </div>
    </div>
    <div id="contact" class="item-box">
      <h2 class="text-center font-lora font-weight-bold mb-5">Kontakt</h2>
      <div class="row">
        <div class="col-md-6 mb-md-0 mb-4">
          <div class="font-size-20 py-md-5">
            <p>
              „U Olesi" w Ostaszewie nad Jeziorem Hartowiec.
            </p>
            <p>
              Ostaszewo 89A, 13-324 Grodziczno
            </p>
            <br />

            <p>Godziny otwarcia: 10:00 - 22:00</p>
            <br />
            <a
              href="https://www.facebook.com/ukolesi/"
              class="text-default"
              target="_blank"
              rel="noopener noreferrer"
            >
              facebook.com/uolesi</a
            >
          </div>
        </div>
        <div class="col-md-6">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d9515.781037724993!2d19.829352!3d53.3979191!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xe39bac19fd6c47dc!2sGastronomia%20Bar%20U%20Olesi!5e0!3m2!1spl!2spl!4v1597580900819!5m2!1spl!2spl"
            width="100%"
            height="450"
            frameborder="0"
            style="border: 0;"
            allowfullscreen=""
            aria-hidden="false"
            tabindex="0"
          ></iframe>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Gallery from '~/components/Gallery'
export default {
  components: {
    Gallery,
  },
}
</script>
