<template>
  <div>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        <nuxt-link class="navbar-brand js-scroll-trigger" to="/"><img src="~/static/wordmark.svg" alt="Cursor" /></nuxt-link>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-heading">Code an App with Cursor</div>
        </div>
      </div>
    </header>

    <!-- Resources -->
    <section id="about" class="bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">Resources</h2>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-3 mx-auto">
            <a href="https://docs.google.com/presentation/d/1EG2o4_A-VhmDY9TQCvIMX4tTABXEiSM9AyFg3F0cfug/edit?usp=sharing" target="_blank">
              <font-awesome-layers class="fa-8x">
                <font-awesome-icon icon="circle"></font-awesome-icon>
                <font-awesome-icon icon="desktop" transform="shrink-7 left-1" class="fa-inverse"></font-awesome-icon>
              </font-awesome-layers>
              <h4>Slides</h4>
            </a>
          </div>
          <div class="col-md-3 mx-auto">
            <a href="https://github.com/cursorclub/react-native-todo" target="_blank">
              <font-awesome-layers class="fa-8x">
                <font-awesome-icon icon="circle"></font-awesome-icon>
                <font-awesome-icon :icon="['fab', 'github']" transform="shrink-3" class="fa-inverse"></font-awesome-icon>
              </font-awesome-layers>
              <h4>Finished Todo List Example</h4>
            </a>
          </div>
          <div class="col-md-3 mx-auto">
            <a href="http://www.rhpl.richmondhill.on.ca/Programs/ProgramDetail.cfm?programID=2210" target="_blank">
              <font-awesome-layers class="fa-8x">
                <font-awesome-icon icon="circle"></font-awesome-icon>
                <font-awesome-icon icon="calendar" transform="shrink-7" class="fa-inverse"></font-awesome-icon>
              </font-awesome-layers>
              <h4>Library Event Page</h4>
            </a>
          </div>
          <div class="col-md-3 mx-auto">
            <a href="https://www.eventbrite.ca/e/code-an-app-with-cursor-tickets-44928685909?aff=es2" target="_blank">
              <font-awesome-layers class="fa-8x">
                <font-awesome-icon icon="circle"></font-awesome-icon>
                <font-awesome-icon icon="ticket-alt" transform="shrink-7 left-1" class="fa-inverse"></font-awesome-icon>
              </font-awesome-layers>
              <h4>Eventbrite</h4>
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Downloads -->
    <section id="about">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">Downloads</h2>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-3">
            <div class="row">
              <div class="col-lg-12 text-center">
                <h3 class="section-heading">Languages</h3>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12 text-center">
                <ul>
                  <a href="https://nodejs.org/en/download/" target="_blank"><li>Node.js</li></a>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="row">
              <div class="col-lg-12 text-center">
                <h3 class="section-heading">Expo Packagers</h3>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12 text-center">
                <ul>
                  <a href="https://github.com/expo/xde/releases" target="_blank"><li>Expo XDE</li></a>
                  <a href="https://snack.expo.io" target="_blank"><li>Expo Snack</li></a>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="row">
              <div class="col-lg-12 text-center">
                <h3 class="section-heading">Text Editors</h3>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12 text-center">
                <ul>
                  <a href="https://code.visualstudio.com/Download" target="_blank"><li>Visual Studio Code</li></a>
                  <a href="https://atom.io/" target="_blank"><li>Atom</li></a>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="row">
              <div class="col-lg-12 text-center">
                <h3 class="section-heading">Expo Clients</h3>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12 text-center">
                <ul>
                  <a href="https://itunes.apple.com/app/apple-store/id982107779" target="_blank"><li>Expo Client for iOS</li></a>
                  <a href="https://play.google.com/store/apps/details?id=host.exp.exponent" target="_blank"><li>Expo Client for Android</li></a>
                  <a href="https://dabbott.github.io/react-native-web-player" target="_blank"><li>React Native Web Player</li></a>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Further Reading -->
    <section id="about" class="bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">Further Learning</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12 text-center">
            <p><a href="https://facebook.github.io/react-native/docs/getting-started">React Native getting started guide</a></p>
            <p><a href="https://docs.expo.io/versions/v28.0.0/guides/">Expo guides</a></p>
            <p><a href="https://react-native-training.github.io/react-native-elements/docs/overview.html">React Native Elements documentation</a></p>
            <p>If you need help working through the workshop, we're here to help. You can always send us an email at <a href="mailto:hello@cursor.club">hello@cursor.club</a> or message us about anything on <a href="https://m.me/cursor.club">Facebook</a>.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <cursor-footer></cursor-footer>
  </div>
</template>

<script>
// Import Font Awesome
import fontawesome from '@fortawesome/fontawesome'
import { FontAwesomeIcon, FontAwesomeLayers } from '@fortawesome/vue-fontawesome'
import { faDesktop, faTicketAlt, faCalendar } from '@fortawesome/fontawesome-free-solid'
import { faGithub } from '@fortawesome/fontawesome-free-brands'
import CursorFooter from '~/components/CursorFooter'

// Add them all to the library
fontawesome.library.add(faGithub, faDesktop, faTicketAlt, faCalendar)

export default {
  components: {
    FontAwesomeIcon,
    FontAwesomeLayers,
    CursorFooter
  }
}
</script>
