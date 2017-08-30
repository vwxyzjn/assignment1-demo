<template>
  <v-app light>
    <v-container>
      <v-layout>
        <v-flex xs12>
          <v-card>
            <v-card-media
              class="lighten-4 cyan"
            >
              <v-layout row wrap class="my-3">
                <v-flex xs12 align-end flexbox class="">
                  <div class="headline text-xs-right my-font-color mr-3" style="width:100%">Kevin's Journal</div>
                </v-flex>
                <v-flex xs12 align-end flexbox class="">
                  <div class="subheading text-xs-right my-font-color mr-3" style="width:100%">Confessions of a binge watcher</div>
                </v-flex>
              </v-layout>
            </v-card-media>
          </v-card>
        </v-flex>
      </v-layout>
      <v-layout row wrap>
        <v-flex xs12 md3>
          <v-card>
            <v-card-media
              class="lighten-4 cyan my-3"
            >
              <v-container fill-height fluid>
                <v-layout fill-height>
                  <v-flex xs12 align-end flexbox>
                    <span class="headline my-font-color">Top Binges</span>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-card-media>
            <v-card-text>
              <v-list dense>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon>star</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>Breaking Bad</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon>star</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>24</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
                <v-list-tile>
                  <v-list-tile-action>
                    <v-icon>star</v-icon>
                  </v-list-tile-action>
                  <v-list-tile-content>
                    <v-list-tile-title>WestWorld</v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
              </v-list>
            </v-card-text>
          </v-card>
        </v-flex>
        <v-flex xs12 md9>
          <v-flex xs12>
            <v-card>
              <v-card-media
                class="lighten-4 cyan my-3"
              >
                <v-container fill-height fluid>
                  <v-layout fill-height>
                    <v-flex xs12 align-end flexbox>
                      <span class="headline my-font-color">08/30/17: Where did it go?</span>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-card-media>
              <v-card-title>
                <v-layout row wrap>
                  <v-flex xs9>
                    I can't believe I lost my remote control again! What am I going to do now? Get up off the couch to change the channel?
                  </v-flex>
                  <v-flex xs3>
                    <v-card-media
                      :src="require('@/assets/remote.png')"
                      height="125px"
                      contain
                    ></v-card-media>
                  </v-flex>
                </v-layout>
              </v-card-title>
            </v-card>
          </v-flex>
          <v-flex xs12>
            <v-card>
              <v-card-media
                class="lighten-4 cyan my-3"
              >
                <v-container fill-height fluid>
                  <v-layout fill-height>
                    <v-flex xs12 align-end flexbox>
                      <span class="headline my-font-color">08/28/17: Watch Breaking Bad again?</span>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-card-media>
              <v-card-title>
                <v-layout row wrap>
                  <v-flex xs9>
                    <div>
                      Recently I've been wondering if it's time to re-binge Breaking Bad. But there are so many other shows to watch! Dilemmas, dilemmas.
                      <br><br>
                      Walter White once said, We're done when I say we're done. I wonder if that gives me any clues as to what I should do?
                    </div>
                  </v-flex>
                  <v-flex xs3>
                    <v-card-media
                      :src="require('@/assets/walterwhite.jpg')"
                      height="125px"
                      contain
                    ></v-card-media>
                  </v-flex>
                </v-layout>

              </v-card-title>
            </v-card>
          </v-flex>
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        clipped: false,
        drawer: true,
        fixed: false,
        items: [
          { icon: 'bubble_chart', title: 'Inspire' }
        ],
        miniVariant: false,
        right: true,
        rightDrawer: false,
        title: 'Vuetify.js'
      }
    }
  }
</script>

<style>
.my-font-color {
  color: #009097!important;
}
</style>

<style lang="stylus">
  @import './stylus/main'
</style>




