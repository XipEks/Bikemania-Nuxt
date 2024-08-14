<template>
  <div class="sign-in1-container1 thq-section-padding">
    <div class="sign-in1-max-width thq-section-max-width">
      <div class="sign-in1-form-root">
        <div class="sign-in1-form1">
          <div class="sign-in1-title-root">
            <h2 class="sign-in1-text10">{{ heading1 }}</h2>
          </div>
          <form class="sign-in1-form2">
            <div class="sign-in1-email">
              <label
                for="thq-sign-in-1-email"
                class="sign-in1-text11 thq-body-large bodySmall"
              >
                Email
              </label>
              <input
                type="email"
                id="thq-sign-in-1-email"
                required="true"
                placeholder="Email address"
                class="sign-in1-textinput1 thq-body-large thq-input"
              />
            </div>
            <div class="sign-in1-password">
              <div class="sign-in1-container2">
                <label
                  for="thq-sign-in-1-password"
                  class="sign-in1-text12 bodySmall thq-body-large"
                >
                  Password
                </label>
                <div class="sign-in1-hide-password">
                  <svg viewBox="0 0 1024 1024" class="sign-in1-icon1">
                    <path
                      d="M317.143 762.857l44.571-80.571c-66.286-48-105.714-125.143-105.714-206.857 0-45.143 12-89.714 34.857-128.571-89.143 45.714-163.429 117.714-217.714 201.714 59.429 92 143.429 169.143 244 214.286zM539.429 329.143c0-14.857-12.571-27.429-27.429-27.429-95.429 0-173.714 78.286-173.714 173.714 0 14.857 12.571 27.429 27.429 27.429s27.429-12.571 27.429-27.429c0-65.714 53.714-118.857 118.857-118.857 14.857 0 27.429-12.571 27.429-27.429zM746.857 220c0 1.143 0 4-0.571 5.143-120.571 215.429-240 432-360.571 647.429l-28 50.857c-3.429 5.714-9.714 9.143-16 9.143-10.286 0-64.571-33.143-76.571-40-5.714-3.429-9.143-9.143-9.143-16 0-9.143 19.429-40 25.143-49.714-110.857-50.286-204-136-269.714-238.857-7.429-11.429-11.429-25.143-11.429-39.429 0-13.714 4-28 11.429-39.429 113.143-173.714 289.714-289.714 500.571-289.714 34.286 0 69.143 3.429 102.857 9.714l30.857-55.429c3.429-5.714 9.143-9.143 16-9.143 10.286 0 64 33.143 76 40 5.714 3.429 9.143 9.143 9.143 15.429zM768 475.429c0 106.286-65.714 201.143-164.571 238.857l160-286.857c2.857 16 4.571 32 4.571 48zM1024 548.571c0 14.857-4 26.857-11.429 39.429-17.714 29.143-40 57.143-62.286 82.857-112 128.571-266.286 206.857-438.286 206.857l42.286-75.429c166.286-14.286 307.429-115.429 396.571-253.714-42.286-65.714-96.571-123.429-161.143-168l36-64c70.857 47.429 142.286 118.857 186.857 192.571 7.429 12.571 11.429 24.571 11.429 39.429z"
                    ></path>
                  </svg>
                  <span class="sign-in1-text13 thq-body-small">Hide</span>
                </div>
              </div>
              <input
                type="password"
                id="thq-sign-in-1-password"
                required="true"
                placeholder="Password"
                class="sign-in1-textinput2 thq-body-large thq-input"
              />
            </div>
          </form>
          <div class="sign-in1-container3">
            <div class="sign-in1-container4">
              <nuxt-link to="/" class="sign-in1-button1 thq-button-filled">
                <span class="sign-in1-text14">{{ action1 }}</span>
              </nuxt-link>
              <div class="sign-in1-terms-agree">
                <p class="sign-in1-text15 thq-body-large">
                  <span>
                    Kontynuując, wyrażasz zgodę na Warunki użytkowania i Politykę
                    prywatności.
                    <span v-html="rawlt6n"></span>
                  </span>
                  <span><span v-html="rawjk7c"></span></span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="sign-in1-container5">
        <div class="sign-in1-divider1">
          <div class="sign-in1-divider2"></div>
          <span class="sign-in1-text18 thq-body-large">{{ content1 }}</span>
          <div class="sign-in1-divider3"></div>
        </div>
        <button type="button" class="sign-in1-button2 thq-button-outline">
          <span class="sign-in1-text19 thq-body-small">{{ action2 }}</span>
        </button>
      </div>
    </div>
    <div class="sign-in1-container6">
      <span class="sign-in1-text20">{{ text }}</span>
      <nuxt-link to="/rejestracja" class="sign-in1-navlink">
        {{ button1 }}
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SignIn1',
  props: {
    text: {
      type: String,
      default: 'Nie masz konta?',
    },
    content1: {
      type: String,
      default:
        'Zaloguj się na swoje konto, aby mieć dostęp do wszystkich funkcji sklepu BikeMania.',
    },
    button1: {
      type: String,
      default: 'Zarejestruj się teraz',
    },
    action1: {
      type: String,
      default: 'Zaloguj się',
    },
    action2: {
      type: String,
      default: 'Zapomniałeś hasła?',
    },
    heading1: {
      type: String,
      default: 'Zaloguj się do BikeMania',
    },
    button: {
      type: String,
      default: 'Zaloguj się',
    },
  },
  data() {
    return {
      rawlt6n: ' ',
      rawjk7c: ' ',
    }
  },
}
</script>

<style scoped>
.sign-in1-container1 {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #202020;
}
.sign-in1-max-width {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.sign-in1-form-root {
  gap: var(--dl-space-space-unit);
  width: 600px;
  height: auto;
  display: flex;
  overflow: hidden;
  max-width: 600px;
  align-items: center;
  flex-shrink: 0;
  border-radius: var(--dl-radius-radius-radius4);
  justify-content: center;
}
.sign-in1-form1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
}
.sign-in1-title-root {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-direction: column;
}
.sign-in1-text10 {
  color: #ffffff;
  font-size: 32px;
  font-family: Inter;
  font-weight: 700;
  line-height: 1.15;
  text-transform: none;
  text-decoration: none;
}
.sign-in1-form2 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: column;
}
.sign-in1-email {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.sign-in1-text11 {
  color: #ffffff;
}
.sign-in1-textinput1 {
  color: #ffffff;
  width: 100%;
  border-color: #ffffff;
  background-color: transparent;
}
.sign-in1-password {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.sign-in1-container2 {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.sign-in1-text12 {
  color: #ffffff;
}
.sign-in1-hide-password {
  gap: var(--dl-space-space-halfunit);
  width: auto;
  height: auto;
  display: flex;
  align-items: center;
  flex-shrink: 1;
  justify-content: center;
}
.sign-in1-icon1 {
  fill: #ffffff;
  width: 24px;
  height: 24px;
}
.sign-in1-text13 {
  color: #ffffff;
}
.sign-in1-textinput2 {
  color: #ffffff;
  width: 100%;
  border-color: var(--dl-color-custom-primary1);
  background-color: transparent;
}
.sign-in1-container3 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
}
.sign-in1-container4 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
}
.sign-in1-button1 {
  width: 100%;
  align-self: center;
  text-decoration: none;
  background-color: var(--dl-color-custom-primary1);
}
.sign-in1-text14 {
  color: #000000;
  font-size: 20px;
  text-align: center;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-in1-terms-agree {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: flex-start;
}
.sign-in1-text15 {
  color: rgb(255, 255, 255);
  margin-top: var(--dl-space-space-unit);
}
.sign-in1-container5 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.sign-in1-divider1 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  justify-content: center;
}
.sign-in1-divider2 {
  flex: 1;
  width: var(--dl-size-size-medium);
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-theme-primary1);
}
.sign-in1-text18 {
  color: #ffffff;
  align-self: center;
  text-align: left;
}
.sign-in1-divider3 {
  flex: 1;
  width: var(--dl-size-size-medium);
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-theme-primary1);
}
.sign-in1-button2 {
  fill: var(--dl-color-custom-primary1);
  color: var(--dl-color-custom-primary1);
  width: 100%;
  align-self: center;
  border-color: var(--dl-color-custom-primary1);
}
.sign-in1-text19 {
  text-align: center;
}
.sign-in1-container6 {
  width: 441px;
  height: 38px;
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: flex-start;
  justify-content: center;
}
.sign-in1-text20 {
  color: #ffffff;
  font-size: 23px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
}
.sign-in1-navlink {
  fill: var(--dl-color-custom-primary2);
  color: var(--dl-color-custom-primary2);
  font-size: 23px;
  font-family: Hind;
  font-weight: 400;
  line-height: 150%;
  margin-left: var(--dl-space-space-halfunit);
  border-width: 0px;
  text-decoration: none;
  background-color: transparent;
}
@media(max-width: 991px) {
  .sign-in1-form-root {
    width: 100%;
    padding: var(--dl-space-space-fourunits);
  }
}
@media(max-width: 479px) {
  .sign-in1-form-root {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .sign-in1-button1 {
    width: 100%;
  }
  .sign-in1-button2 {
    width: 100%;
  }
}
</style>
