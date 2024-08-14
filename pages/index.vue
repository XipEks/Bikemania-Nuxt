<template>
  <div class="strona-gwna-container10">
    <div class="strona-gwna-header">
      <header
        data-thq="thq-navbar"
        class="strona-gwna-navbar-interactive navbarContainer"
      >
        <a href="#up" class="strona-gwna-logo1 logo">BIKEMANIA</a>
        <div data-thq="thq-navbar-nav" class="strona-gwna-desktop-menu">
          <nav class="strona-gwna-links1">
            <span class="strona-gwna-text10 bodySmall">
                                              Rowery
            </span>
            <span class="strona-gwna-text11 bodySmall">Akcesoria</span>
            <a href="#bottom" class="strona-gwna-link1 bodySmall">Społeczność</a>
            <a href="#bottom" class="strona-gwna-link2 bodySmall">Kontakt</a>
          </nav>
          <div class="strona-gwna-buttons1">
            <nuxt-link to="/login" class="strona-gwna-login1 buttonFlat">
              Zaloguj sie
            </nuxt-link>
            <nuxt-link
              to="/rejestracja"
              class="strona-gwna-register1 buttonFilled"
            >
              Utwórz Konto
            </nuxt-link>
          </div>
        </div>
        <div data-thq="thq-burger-menu" class="strona-gwna-burger-menu">
          <svg viewBox="0 0 1024 1024" class="strona-gwna-icon10 socialIcons">
            <path
              d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
            ></path>
          </svg>
        </div>
        <div
          data-thq="thq-mobile-menu"
          class="strona-gwna-mobile-menu1 mobileMenu"
        >
          <div class="strona-gwna-nav1">
            <div class="strona-gwna-top">
              <span class="logo">BIKEMANIA</span>
              <div data-thq="thq-close-menu" class="strona-gwna-close-menu">
                <svg
                  viewBox="0 0 1024 1024"
                  class="strona-gwna-icon12 socialIcons"
                >
                  <path
                    d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                  ></path>
                </svg>
              </div>
            </div>
            <nav class="strona-gwna-links2">
              <span class="strona-gwna-nav12 bodySmall">Home</span>
              <span class="strona-gwna-nav22 bodySmall">Bikes</span>
              <span class="strona-gwna-nav32 bodySmall">Accessories</span>
              <span class="strona-gwna-nav42 bodySmall">Community</span>
              <span class="strona-gwna-nav52 bodySmall">Contact</span>
            </nav>
            <div class="strona-gwna-buttons2">
              <button class="buttonFlat">Login</button>
              <button class="buttonFilled">Register</button>
            </div>
          </div>
          <div>
            <svg
              viewBox="0 0 950.8571428571428 1024"
              class="strona-gwna-icon14 socialIcons"
            >
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path></svg
            ><svg
              viewBox="0 0 877.7142857142857 1024"
              class="strona-gwna-icon16 socialIcons"
            >
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path></svg
            ><svg
              viewBox="0 0 602.2582857142856 1024"
              class="strona-gwna-icon18 socialIcons"
            >
              <path
                d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
              ></path>
            </svg>
          </div>
        </div>
      </header>
    </div>
    <div class="strona-gwna-hero1">
      <div id="up" class="strona-gwna-hero2 heroContainer">
        <div class="strona-gwna-container11">
          <h1 class="strona-gwna-hero-heading heading1">Witamy w BikeMania</h1>
          <span class="strona-gwna-hero-sub-heading">
            Odkryj naszą różnorodną gamę wysokiej jakości rowerów, w tym modele
            górskie i miejskich. Znajdź swój idealny rower na każdą przygodę lub
            dojazd. Kup teraz, korzystając z atrakcyjnych ofert!
          </span>
          <div class="strona-gwna-btn-group">
            <button class="buttonFilled">Zobacz naszą ofertę</button>
            <a href="#wiecej" class="strona-gwna-hero-button2 buttonFlat">
              Dowiedz sie wiecej o BikeMania→
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="strona-gwna-container12">
      <div
        data-thq="slider"
        data-autoplay="false"
        data-navigation="true"
        data-pagination="true"
        class="strona-gwna-slider swiper"
      >
        <div data-thq="slider-wrapper" class="swiper-wrapper">
          <div
            data-thq="slider-slide"
            class="strona-gwna-slider-slide1 swiper-slide"
          ></div>
          <div
            data-thq="slider-slide"
            class="strona-gwna-slider-slide2 swiper-slide"
          ></div>
          <div
            data-thq="slider-slide"
            class="strona-gwna-slider-slide3 swiper-slide"
          ></div>
          <div
            data-thq="slider-slide"
            class="strona-gwna-slider-slide4 swiper-slide"
          ></div>
        </div>
        <div
          data-thq="slider-pagination"
          class="strona-gwna-slider-pagination swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
        >
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
        </div>
        <div
          data-thq="slider-button-prev"
          class="strona-gwna-slider-button-prev swiper-button-prev"
        ></div>
        <div
          data-thq="slider-button-next"
          class="strona-gwna-slider-button-next swiper-button-next"
        ></div>
      </div>
    </div>
    <div class="strona-gwna-features1">
      <div class="strona-gwna-features-container featuresContainer">
        <div id="wiecej" class="strona-gwna-features2">
          <div class="strona-gwna-container13">
            <h2 class="strona-gwna-features-heading Heading">
              Dowiedz się więcej o naszym sklepie
            </h2>
            <span class="strona-gwna-features-sub-heading bodyLarge">
              <span>
                <span>
                  <span>
                    Explore the key features that set BikeMania Kalisz apart and
                    make us the ultimate destination for all your cycling needs
                  </span>
                  <span><span v-html="rawxwft"></span></span>
                </span>
                <span>
                  <span><span v-html="raw2w5n"></span></span>
                  <span><span v-html="rawdiee"></span></span>
                </span>
              </span>
              <span>
                <span>
                  <span><span v-html="rawjeyk"></span></span>
                  <span><span v-html="raw665z"></span></span>
                </span>
                <span>
                  <span><span v-html="rawyqhj"></span></span>
                  <span><span v-html="raweubk"></span></span>
                </span>
              </span>
            </span>
          </div>
          <div class="strona-gwna-container14">
            <feature-card
              heading="Wide Selection of Bikes"
              subHeading="Explore our diverse range of mountain and everyday bikes for every type of rider"
            ></feature-card>
            <feature-card1
              rootClassName="feature-card1-root-class-name"
            ></feature-card1>
            <feature-card11
              rootClassName="feature-card11-root-class-name"
            ></feature-card11>
            <feature-card111
              rootClassName="feature-card111-root-class-name"
            ></feature-card111>
          </div>
        </div>
      </div>
    </div>
    <div class="strona-gwna-banner1">
      <div class="strona-gwna-banner2 bannerContainer">
        <h1 class="strona-gwna-banner-heading">Zobacz nasza ofertę tutaj</h1>
        <span class="strona-gwna-banner-sub-heading bodySmall">
          <span>
            <span>
              <span>
                At BikeMania Kalisz, we are dedicated to providing cyclists with a
                diverse range of products, exceptional customer service, and
                competitive pricing. Whether you&apos;re a beginner or an
                experienced enthusiast, we have everything you need to fuel your
                passion for cycling. Join our community and embark on
                unforgettable cycling adventures with us.
              </span>
              <span><span v-html="rawoib6"></span></span>
            </span>
            <span>
              <span><span v-html="rawpmm9"></span></span>
              <span><span v-html="rawao0v"></span></span>
            </span>
          </span>
          <span>
            <span>
              <span><span v-html="rawukeb"></span></span>
              <span><span v-html="rawwld5"></span></span>
            </span>
            <span>
              <span><span v-html="raw2fnm"></span></span>
              <span><span v-html="rawm3fp"></span></span>
            </span>
          </span>
        </span>
        <button class="buttonFilled">Oferta Sklepu</button>
      </div>
    </div>
    <div class="strona-gwna-faq1">
      <div class="faqContainer">
        <div class="strona-gwna-faq2">
          <div class="strona-gwna-container15">
            <span class="overline">
              <span>FAQ</span>
              <br />
            </span>
            <h2 class="strona-gwna-text43 heading2">
              Najczęstsze Pytania Do Nas
            </h2>
            <span class="strona-gwna-text44 bodyLarge">
              <span>
                Oto odpowiedzi niektóre z najczęstszych pytań, jakie otrzymujemy.
              </span>
              <br class="bodyLarge" />
            </span>
          </div>
          <div class="strona-gwna-container16">
            <app-question1
              answer="We offer a diverse range of bikes, including mountain bikes, everyday bikes, and more, tailored to meet the needs and preferences of every rider."
              question="What types of bikes do you offer at BikeMania Kalisz?"
            ></app-question1>
            <app-question11
              rootClassName="question11-root-class-name"
            ></app-question11>
            <app-question111
              rootClassName="question111-root-class-name"
            ></app-question111>
            <app-question1111
              rootClassName="question1111-root-class-name"
            ></app-question1111>
            <app-question11111
              rootClassName="question11111-root-class-name"
            ></app-question11111>
          </div>
        </div>
      </div>
    </div>
    <div class="strona-gwna-footer1">
      <footer id="bottom" class="strona-gwna-footer2 footerContainer">
        <div class="strona-gwna-container17">
          <span class="strona-gwna-logo3 logo">BIKEMANIA</span>
          <nav class="strona-gwna-nav2">
            <span class="strona-gwna-text47 bodySmall">Rowery</span>
            <span class="strona-gwna-text48 bodySmall">Akcesoria</span>
            <span class="strona-gwna-text49 bodySmall">Społeczność</span>
            <span class="strona-gwna-text50 bodySmall">Kontakt</span>
          </nav>
        </div>
        <div class="strona-gwna-container18">
          <div class="strona-gwna-container19">
            <h1 class="strona-gwna-text51 bodyLarge">
              <span>• Kontakt</span>
              <br />
            </h1>
            <span class="strona-gwna-text54 bodySmall">• 48+ 928-324-343</span>
            <span class="strona-gwna-text55 bodySmall">
              • bikemania.kalisz@gmail.com
            </span>
            <span class="strona-gwna-text56 bodySmall">• @bikemania.kalisz</span>
          </div>
        </div>
        <div class="strona-gwna-separator"></div>
        <div class="strona-gwna-container20">
          <span class="strona-gwna-text57 bodySmall">
            © 2024 BikeMania, Wszystkie Prawa Zastrzeżone.
          </span>
          <div class="strona-gwna-icon-group2">
            <a
              href="https://twitter.com/"
              target="_blank"
              rel="noreferrer noopener"
              class="strona-gwna-link3"
            >
              <svg
                viewBox="0 0 950.8571428571428 1024"
                class="strona-gwna-icon20 socialIcons"
              >
                <path
                  d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                ></path>
              </svg>
            </a>
            <a
              href="https://instagram.com"
              target="_blank"
              rel="noreferrer noopener"
              class="strona-gwna-link4"
            >
              <svg
                viewBox="0 0 877.7142857142857 1024"
                class="strona-gwna-icon22 socialIcons"
              >
                <path
                  d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                ></path>
              </svg>
            </a>
            <a
              href="https://facebook.com"
              target="_blank"
              rel="noreferrer noopener"
              class="strona-gwna-link5"
            >
              <svg
                viewBox="0 0 602.2582857142856 1024"
                class="strona-gwna-icon24 socialIcons"
              >
                <path
                  d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
                ></path>
              </svg>
            </a>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import FeatureCard from '../components/feature-card'
import FeatureCard1 from '../components/feature-card1'
import FeatureCard11 from '../components/feature-card11'
import FeatureCard111 from '../components/feature-card111'
import AppQuestion1 from '../components/question1'
import AppQuestion11 from '../components/question11'
import AppQuestion111 from '../components/question111'
import AppQuestion1111 from '../components/question1111'
import AppQuestion11111 from '../components/question11111'

export default {
  name: 'StronaGwna',
  components: {
    FeatureCard,
    FeatureCard1,
    FeatureCard11,
    FeatureCard111,
    AppQuestion1,
    AppQuestion11,
    AppQuestion111,
    AppQuestion1111,
    AppQuestion11111,
  },
  data() {
    return {
      rawxwft: ' ',
      raw2w5n: ' ',
      rawdiee: ' ',
      rawjeyk: ' ',
      raw665z: ' ',
      rawyqhj: ' ',
      raweubk: ' ',
      rawoib6: ' ',
      rawpmm9: ' ',
      rawao0v: ' ',
      rawukeb: ' ',
      rawwld5: ' ',
      raw2fnm: ' ',
      rawm3fp: ' ',
    }
  },
  head: {
    title: 'BikeMania',
  },
}
</script>

<style scoped>
.strona-gwna-container10 {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.strona-gwna-header {
  width: 100%;
  display: flex;
  z-index: 100;
  position: fixed;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
  background-color: var(--dl-color-gray-white);
}
.strona-gwna-navbar-interactive {
  align-self: flex-start;
}
.strona-gwna-logo1 {
  color: #ffffff;
  text-decoration: none;
}
.strona-gwna-desktop-menu {
  flex: 1;
  display: flex;
  position: relative;
  justify-content: space-between;
}
.strona-gwna-links1 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.strona-gwna-text10 {
  color: #ffffff;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
}
.strona-gwna-text11 {
  color: rgb(255, 255, 255);
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
}
.strona-gwna-link1 {
  color: rgb(255, 255, 255);
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  text-decoration: none;
}
.strona-gwna-link2 {
  color: rgb(255, 255, 255);
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
  text-decoration: none;
}
.strona-gwna-buttons1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.strona-gwna-login1 {
  border-color: #bde420;
  border-style: outset;
  border-width: 2px;
  margin-right: 32px;
  text-decoration: none;
}
.strona-gwna-register1 {
  text-decoration: none;
}
.strona-gwna-burger-menu {
  display: none;
}
.strona-gwna-icon10 {
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
}
.strona-gwna-mobile-menu1 {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: absolute;
  flex-direction: column;
  justify-content: space-between;
}
.strona-gwna-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.strona-gwna-top {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.strona-gwna-close-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
.strona-gwna-icon12 {
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
}
.strona-gwna-links2 {
  flex: 0 0 auto;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
.strona-gwna-nav12 {
  margin-bottom: var(--dl-space-space-unit);
}
.strona-gwna-nav22 {
  margin-bottom: var(--dl-space-space-unit);
}
.strona-gwna-nav32 {
  margin-bottom: var(--dl-space-space-unit);
}
.strona-gwna-nav42 {
  margin-bottom: var(--dl-space-space-unit);
}
.strona-gwna-nav52 {
  margin-bottom: var(--dl-space-space-unit);
}
.strona-gwna-buttons2 {
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.strona-gwna-icon14 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.strona-gwna-icon16 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.strona-gwna-icon18 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.strona-gwna-hero1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  margin-top: 96px;
  align-items: flex-start;
  justify-content: center;
}
.strona-gwna-hero2 {
  background-color: #202020;
}
.strona-gwna-container11 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.strona-gwna-hero-heading {
  color: #ffffff;
  max-width: 800px;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.strona-gwna-hero-sub-heading {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-style: normal;
  text-align: center;
  font-family: "Hind";
  font-weight: 500;
  line-height: 150%;
}
.strona-gwna-btn-group {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.strona-gwna-hero-button2 {
  border-color: #bde420;
  border-width: 2px;
  text-decoration: none;
  background-color: #1e1e1e;
}
.strona-gwna-container12 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #292929;
}
.strona-gwna-slider {
  width: 386px;
  height: 365px;
  display: inline-block;
  background-color: #000000;
}
.strona-gwna-slider-slide1 {
  display: flex ;
  background-size: contain;
  background-image: url("https://play.teleporthq.io/static/svg/default-img.svg");
  background-repeat: repeat;
  background-position: center;
}
.strona-gwna-slider-slide2 {
  display: flex ;
  background-size: contain;
  background-image: url("https://play.teleporthq.io/static/svg/default-img.svg");
  background-repeat: no-repeat;
  background-position: center;
}
.strona-gwna-slider-slide3 {
  display: flex ;
  background-size: cover;
  background-image: url("https://play.teleporthq.io/static/svg/default-img.svg");
  background-position: center;
}
.strona-gwna-slider-slide4 {
  display: flex ;
  background-size: contain;
  background-image: url("https://play.teleporthq.io/static/svg/default-img.svg");
  background-repeat: repeat-x;
  background-position: center;
}
.strona-gwna-slider-pagination {
  fill: #bde420;
  color: #bde420;
  display: block;
}
.strona-gwna-slider-button-prev {
  fill: var(--dl-color-theme-neutral-dark);
  color: #bde420;
}
.strona-gwna-slider-button-next {
  fill: var(--dl-color-theme-neutral-dark);
  color: #bde420;
}
.strona-gwna-features1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.strona-gwna-features-container {
  background-color: #171717;
}
.strona-gwna-features2 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: flex-start;
}
.strona-gwna-container13 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.strona-gwna-features-heading {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.strona-gwna-features-sub-heading {
  font-size: 18px;
  text-align: center;
}
.strona-gwna-container14 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-oneandhalfunits);
  grid-template-columns: 1fr 1fr;
}
.strona-gwna-banner1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.strona-gwna-banner2 {
  background-size: auto;
  background-color: transparent;
  background-image: url("/unsplash-image-1500w.jpeg");
  background-position: top;
}
.strona-gwna-banner-heading {
  color: rgb(255, 255, 255);
  text-align: center;
}
.strona-gwna-banner-sub-heading {
  color: #ffffff;
  max-width: var(--dl-size-size-maxwidth);
  margin-top: var(--dl-space-space-twounits);
  text-align: center;
  margin-bottom: var(--dl-space-space-twounits);
}
.strona-gwna-faq1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.strona-gwna-faq2 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-fourunits);
}
.strona-gwna-container15 {
  display: flex;
  max-width: 35%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.strona-gwna-text43 {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.strona-gwna-text44 {
  text-align: left;
}
.strona-gwna-container16 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.strona-gwna-footer1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  justify-content: center;
}
.strona-gwna-footer2 {
  top: 0px;
  left: 0px;
  position: absolute;
}
.strona-gwna-container17 {
  gap: var(--dl-space-space-unit);
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.strona-gwna-logo3 {
  color: #ffffff;
}
.strona-gwna-nav2 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.strona-gwna-text47 {
  color: #ffffff;
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
}
.strona-gwna-text48 {
  color: rgb(255, 255, 255);
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
}
.strona-gwna-text49 {
  color: rgb(255, 255, 255);
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
}
.strona-gwna-text50 {
  color: rgb(255, 255, 255);
  margin-left: var(--dl-space-space-halfunit);
  margin-right: var(--dl-space-space-halfunit);
}
.strona-gwna-container18 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: flex-start;
}
.strona-gwna-container19 {
  flex: 1;
  width: 356px;
  height: 236px;
  display: flex;
  margin-top: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  margin-left: var(--dl-space-space-unit);
  border-color: #312f2f;
  border-width: 1.5px;
  flex-direction: column;
  background-color: #191919;
}
.strona-gwna-text51 {
  color: #828282;
  margin-top: var(--dl-space-space-halfunit);
  margin-left: var(--dl-space-space-halfunit);
  text-transform: none;
  text-decoration: none;
}
.strona-gwna-text54 {
  color: #737373;
  margin-top: var(--dl-space-space-halfunit);
  margin-left: var(--dl-space-space-halfunit);
}
.strona-gwna-text55 {
  color: #737373;
  margin-left: var(--dl-space-space-halfunit);
}
.strona-gwna-text56 {
  color: #737373;
  margin-left: var(--dl-space-space-halfunit);
}
.strona-gwna-separator {
  flex: 0 0 auto;
  width: 100%;
  height: 0px;
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  margin-left: 0px;
  border-color: var(--dl-color-gray-900);
  border-style: solid;
  border-width: 1px;
  margin-right: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.strona-gwna-container20 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.strona-gwna-text57 {
  color: #ffffff;
}
.strona-gwna-icon-group2 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.strona-gwna-link3 {
  display: contents;
}
.strona-gwna-icon20 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
  text-decoration: none;
}
.strona-gwna-link4 {
  display: contents;
}
.strona-gwna-icon22 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
  text-decoration: none;
}
.strona-gwna-link5 {
  display: contents;
}
.strona-gwna-icon24 {
  width: 24px;
  height: 24px;
  text-decoration: none;
}
@media(max-width: 991px) {
  .strona-gwna-hero2 {
    flex-direction: column;
  }
  .strona-gwna-container11 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .strona-gwna-hero-heading {
    text-align: center;
  }
  .strona-gwna-features-sub-heading {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .strona-gwna-banner-sub-heading {
    max-width: 100%;
  }
  .strona-gwna-text44 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 767px) {
  .strona-gwna-navbar-interactive {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .strona-gwna-desktop-menu {
    display: none;
  }
  .strona-gwna-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .strona-gwna-nav12 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .strona-gwna-nav22 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .strona-gwna-nav32 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .strona-gwna-nav42 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .strona-gwna-nav52 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .strona-gwna-hero2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .strona-gwna-features2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .strona-gwna-features-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .strona-gwna-container14 {
    grid-template-columns: 1fr;
  }
  .strona-gwna-banner2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .strona-gwna-banner-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .strona-gwna-faq2 {
    flex-direction: column;
  }
  .strona-gwna-container15 {
    max-width: 100%;
    align-self: center;
    align-items: center;
    justify-content: center;
  }
  .strona-gwna-text44 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .strona-gwna-footer2 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .strona-gwna-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .strona-gwna-container20 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .strona-gwna-text57 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .strona-gwna-navbar-interactive {
    padding: var(--dl-space-space-unit);
  }
  .strona-gwna-mobile-menu1 {
    padding: 16px;
  }
  .strona-gwna-hero2 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .strona-gwna-container11 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .strona-gwna-btn-group {
    flex-direction: column;
  }
  .strona-gwna-features2 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .strona-gwna-banner2 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .strona-gwna-footer2 {
    padding: var(--dl-space-space-unit);
  }
  .strona-gwna-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .strona-gwna-container20 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .strona-gwna-text57 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
