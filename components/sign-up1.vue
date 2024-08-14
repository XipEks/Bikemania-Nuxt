<template>
  <div class="sign-up1-container10">
    <div class="sign-up1-max-width thq-section-max-width">
      <div class="sign-up1-form-root thq-section-padding">
        <div class="sign-up1-form1">
          <div class="sign-up1-title-root">
            <h2 class="sign-up1-text10">{{ heading1 }}</h2>
            <div class="sign-up1-container11">
              <div class="sign-up1-container12">
                <p class="sign-up1-text11">Posiadasz już konto?</p>
                <nuxt-link to="/login" class="sign-up1-navlink1">
                  {{ button }}
                </nuxt-link>
              </div>
            </div>
          </div>
          <form class="sign-up1-form2">
            <div class="sign-up1-email">
              <label
                for="thq-sign-up-1-email"
                class="sign-up1-text12 thq-body-large"
              >
                Email
              </label>
              <input
                type="email"
                id="thq-sign-up-1-email"
                required="true"
                placeholder="Adres Email"
                class="sign-up1-textinput1 thq-body-large thq-input"
              />
            </div>
            <div class="sign-up1-username">
              <label
                for="thq-sign-up-1-username"
                class="sign-up1-text13 thq-body-large"
              >
                Pseudonim
              </label>
              <input
                type="text"
                id="thq-sign-up-1-username"
                required="true"
                placeholder="Pseudonim"
                class="sign-up1-textinput2 thq-body-large thq-input"
              />
            </div>
            <div class="sign-up1-password">
              <div class="sign-up1-textfield">
                <div class="sign-up1-container13">
                  <label
                    for="thq-sign-up-1-password"
                    class="sign-up1-text14 thq-body-large"
                  >
                    Hasło
                  </label>
                  <div class="sign-up1-hide-password">
                    <svg viewBox="0 0 1024 1024" class="sign-up1-icon1">
                      <path
                        d="M317.143 762.857l44.571-80.571c-66.286-48-105.714-125.143-105.714-206.857 0-45.143 12-89.714 34.857-128.571-89.143 45.714-163.429 117.714-217.714 201.714 59.429 92 143.429 169.143 244 214.286zM539.429 329.143c0-14.857-12.571-27.429-27.429-27.429-95.429 0-173.714 78.286-173.714 173.714 0 14.857 12.571 27.429 27.429 27.429s27.429-12.571 27.429-27.429c0-65.714 53.714-118.857 118.857-118.857 14.857 0 27.429-12.571 27.429-27.429zM746.857 220c0 1.143 0 4-0.571 5.143-120.571 215.429-240 432-360.571 647.429l-28 50.857c-3.429 5.714-9.714 9.143-16 9.143-10.286 0-64.571-33.143-76.571-40-5.714-3.429-9.143-9.143-9.143-16 0-9.143 19.429-40 25.143-49.714-110.857-50.286-204-136-269.714-238.857-7.429-11.429-11.429-25.143-11.429-39.429 0-13.714 4-28 11.429-39.429 113.143-173.714 289.714-289.714 500.571-289.714 34.286 0 69.143 3.429 102.857 9.714l30.857-55.429c3.429-5.714 9.143-9.143 16-9.143 10.286 0 64 33.143 76 40 5.714 3.429 9.143 9.143 9.143 15.429zM768 475.429c0 106.286-65.714 201.143-164.571 238.857l160-286.857c2.857 16 4.571 32 4.571 48zM1024 548.571c0 14.857-4 26.857-11.429 39.429-17.714 29.143-40 57.143-62.286 82.857-112 128.571-266.286 206.857-438.286 206.857l42.286-75.429c166.286-14.286 307.429-115.429 396.571-253.714-42.286-65.714-96.571-123.429-161.143-168l36-64c70.857 47.429 142.286 118.857 186.857 192.571 7.429 12.571 11.429 24.571 11.429 39.429z"
                      ></path>
                    </svg>
                    <span class="thq-body-small">Hide</span>
                  </div>
                </div>
                <input
                  type="password"
                  id="thq-sign-up-1-password"
                  required="true"
                  placeholder="Hasło"
                  class="sign-up1-textinput3 thq-body-large thq-input"
                />
              </div>
              <div class="sign-up1-pass-requirements">
                <div class="sign-up1-pass-conditions1">
                  <div class="sign-up1-bulletpoint1">
                    <div class="sign-up1-container14"></div>
                    <span class="sign-up1-text16">Użyj 8 lub więcej znaków</span>
                  </div>
                  <div class="sign-up1-bulletpoint2">
                    <div class="sign-up1-container15"></div>
                    <span class="sign-up1-text17">1 specjalny znak</span>
                  </div>
                </div>
                <div class="sign-up1-pass-conditions2">
                  <div class="sign-up1-bulletpoint3">
                    <div class="sign-up1-container16"></div>
                    <span class="sign-up1-text18">Jedna wielka litera</span>
                  </div>
                  <div class="sign-up1-bulletpoint4">
                    <div class="sign-up1-container17"></div>
                    <span class="sign-up1-text19">Jeden numer</span>
                  </div>
                </div>
                <div class="sign-up1-pass-conditions3">
                  <div class="sign-up1-bulletpoint5">
                    <div class="sign-up1-container18"></div>
                    <span class="sign-up1-text20">Jedna mała litera</span>
                  </div>
                </div>
              </div>
            </div>
          </form>
          <div class="sign-up1-container19">
            <input
              type="checkbox"
              id="thq-sign-up-1-newsletter"
              checked="true"
              class="thq-checkbox"
            />
            <label
              for="thq-sign-up-1-newsletter"
              class="sign-up1-text21 thq-body-large"
            >
              {{ content1 }}
            </label>
          </div>
          <div class="sign-up1-terms-agree">
            <p class="sign-up1-text22 thq-body-large">
              <span>
                Zakładając konto wyrażasz zgodę na Regulamin i Politykę
                Prywatności.
                <span v-html="rawdme0"></span>
              </span>
              <span><span v-html="raw6yli"></span></span>
            </p>
          </div>
          <nuxt-link to="/" class="sign-up1-button thq-button-filled">
            <span class="sign-up1-text25 thq-body-small">{{ action1 }}</span>
          </nuxt-link>
          <div class="sign-up1-container20">
            <p class="sign-up1-text26">Posiadasz już konto?</p>
            <nuxt-link to="/login" class="sign-up1-navlink2">
              {{ button }}
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SignUp1',
  props: {
    heading1: {
      type: String,
      default: 'Dołącz do społeczności BikeMania',
    },
    content1: {
      type: String,
      default:
        'Zarejestruj się, aby otrzymywać ekskluzywne oferty, aktualizacje o nowościach i porady rowerowe od naszych ekspertów.',
    },
    action1: {
      type: String,
      default: 'Zarejestruj się',
    },
    button: {
      type: String,
      default: 'Zaloguj się',
    },
  },
  data() {
    return {
      rawdme0: ' ',
      raw6yli: ' ',
    }
  },
}
</script>

<style scoped>
.sign-up1-container10 {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.sign-up1-max-width {
  height: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
  background-color: #202020;
}
.sign-up1-form-root {
  gap: var(--dl-space-space-unit);
  width: 60%;
  height: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  flex-shrink: 0;
  justify-content: center;
}
.sign-up1-form1 {
  gap: var(--dl-space-space-twounits);
  width: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
}
.sign-up1-title-root {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.sign-up1-text10 {
  color: #ffffff;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  line-height: 1.15;
  text-transform: none;
  text-decoration: none;
}
.sign-up1-container11 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  justify-content: flex-start;
}
.sign-up1-container12 {
  flex: 0 0 auto;
  width: 100%;
  height: 27px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.sign-up1-text11 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-navlink1 {
  fill: var(--dl-color-custom-primary1);
  color: var(--dl-color-custom-primary1);
  width: 120px;
  height: 25px;
  font-size: 18px;
  text-align: left;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
  padding-top: 2px;
  border-width: 0px;
  padding-right: var(--dl-space-space-unit);
  text-decoration: none;
  background-color: transparent;
}
.sign-up1-form2 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: column;
}
.sign-up1-email {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.sign-up1-text12 {
  color: #ffffff;
}
.sign-up1-textinput1 {
  color: #ffffff;
  width: 100%;
  border-color: var(--dl-color-custom-primary1);
  background-color: transparent;
}
.sign-up1-username {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.sign-up1-text13 {
  color: rgb(255, 255, 255);
}
.sign-up1-textinput2 {
  fill: var(--dl-color-gray-white);
  color: var(--dl-color-gray-white);
  width: 100%;
  border-color: var(--dl-color-custom-primary1);
  background-color: transparent;
}
.sign-up1-password {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.sign-up1-textfield {
  gap: 4px;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.sign-up1-container13 {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.sign-up1-text14 {
  color: rgb(255, 255, 255);
}
.sign-up1-hide-password {
  gap: var(--dl-space-space-halfunit);
  width: auto;
  height: auto;
  display: flex;
  align-items: center;
  flex-shrink: 1;
  justify-content: center;
}
.sign-up1-icon1 {
  fill: var(--dl-color-theme-neutral-dark);
  width: 24px;
  height: 24px;
}
.sign-up1-textinput3 {
  fill: var(--dl-color-gray-white);
  color: var(--dl-color-gray-white);
  width: 100%;
  border-color: var(--dl-color-custom-primary1);
  background-color: transparent;
}
.sign-up1-pass-requirements {
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}
.sign-up1-pass-conditions1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.sign-up1-bulletpoint1 {
  gap: 8px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: 8px 8px 8px 0;
  padding-right: 8px 8px 8px 0;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.sign-up1-container14 {
  flex: 0 0 auto;
  width: 6px;
  height: 6px;
  display: flex;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: #ffffff;
}
.sign-up1-text16 {
  color: rgb(255, 255, 255);
  font-size: 19px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-bulletpoint2 {
  gap: 8px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: 8px 8px 8px 0;
  padding-right: 8px 8px 8px 0;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.sign-up1-container15 {
  flex: 0 0 auto;
  width: 6px;
  height: 6px;
  display: flex;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: #ffffff;
}
.sign-up1-text17 {
  color: rgb(255, 255, 255);
  font-size: 19px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-pass-conditions2 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.sign-up1-bulletpoint3 {
  gap: 8px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: 8px 8px 8px 0;
  padding-right: 8px 8px 8px 0;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.sign-up1-container16 {
  flex: 0 0 auto;
  width: 6px;
  height: 6px;
  display: flex;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: #ffffff;
}
.sign-up1-text18 {
  color: rgb(255, 255, 255);
  font-size: 19px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-bulletpoint4 {
  gap: 8px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: 8px 8px 8px 0;
  padding-right: 8px 8px 8px 0;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.sign-up1-container17 {
  flex: 0 0 auto;
  width: 6px;
  height: 6px;
  display: flex;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: #ffffff;
}
.sign-up1-text19 {
  color: rgb(255, 255, 255);
  font-size: 19px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-pass-conditions3 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.sign-up1-bulletpoint5 {
  gap: 8px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: 8px 8px 8px 0;
  padding-right: 8px 8px 8px 0;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.sign-up1-container18 {
  flex: 0 0 auto;
  width: 6px;
  height: 6px;
  display: flex;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: #ffffff;
}
.sign-up1-text20 {
  color: rgb(255, 255, 255);
  font-size: 19px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-container19 {
  gap: var(--dl-space-space-halfunit);
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.sign-up1-text21 {
  color: #ffffff;
}
.sign-up1-terms-agree {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: center;
  justify-content: flex-start;
}
.sign-up1-text22 {
  color: rgb(255, 255, 255);
}
.sign-up1-button {
  fill: var(--dl-color-gray-500);
  color: var(--dl-color-gray-500);
  text-decoration: none;
  background-color: var(--dl-color-custom-primary1);
}
.sign-up1-text25 {
  fill: #202020;
  color: #202020;
  text-align: center;
}
.sign-up1-container20 {
  flex: 0 0 auto;
  width: 100%;
  height: 27px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.sign-up1-text26 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-up1-navlink2 {
  fill: var(--dl-color-custom-primary1);
  color: var(--dl-color-custom-primary1);
  width: 120px;
  height: 25px;
  font-size: 18px;
  text-align: left;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
  padding-top: 2px;
  border-width: 0px;
  padding-right: var(--dl-space-space-unit);
  text-decoration: none;
  background-color: transparent;
}
@media(max-width: 991px) {
  .sign-up1-form-root {
    width: 100%;
    padding: var(--dl-space-space-fourunits);
  }
}
@media(max-width: 479px) {
  .sign-up1-form-root {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .sign-up1-pass-requirements {
    flex-direction: column;
  }
  .sign-up1-button {
    width: 100%;
  }
}
</style>
