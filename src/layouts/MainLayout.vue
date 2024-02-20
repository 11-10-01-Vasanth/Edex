<template>

    <q-layout view="hHh Lpr lff" container style="height: 100vh" class="shadow-2 rounded-borders">
      <q-header elevated :class="$q.dark.isActive ? 'bg-secondary' : 'bg-light-blue-2'">
        <q-toolbar class="text-purple-10">
          <q-btn flat @click="drawer = !drawer" round dense icon="menu" />
          <q-toolbar-title>
            <div class="col-md-8 flex items-center">
            <!-- <b class="row"><div style="color:rgb(237, 26, 26);">Edex</div><div style="color:rgb(15, 94, 242)"> Tech</div></b> -->
            <img src="https://edextech.io/img/edextech.02baca65.png" height="25">
            </div>
          </q-toolbar-title>
        </q-toolbar>
      </q-header>
      <q-page-container>
      <router-view />
    </q-page-container>

      <q-drawer
        v-model="drawer"

        :mini="miniState"
        @mouseover="miniState = false"
        @mouseout="miniState = true"
        mini-to-overlay

        :width="200"
        :breakpoint="500"
        bordered
        :class="$q.dark.isActive ? 'bg-grey-9' : 'bg-light-blue-2'"
      >
        <q-scroll-area class="fit" :horizontal-thumb-style="{ opacity: 0 }">
          <q-list padding>
            <q-item clickable v-ripple>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                <q-btn label="Training" style="color: rgb(15, 12, 12);">
              <q-menu
                transition-show="flip-right"
                transition-hide="flip-left"
              >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>5 days a week</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Limitless learning</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Mentoring & Guidance</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>
              </q-item-section>
            </q-item>

            <q-separator />

            <q-item clickable v-ripple>
              <q-item-section avatar>
                <i class="bi bi-person-workspace text-h5"></i>
              </q-item-section>

              <q-item-section>
                <q-btn label="Courses" style="color: rgb(15, 12, 12);">
              <q-menu
                transition-show="flip-right"
                transition-hide="flip-left"
              >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>HTML</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>CSS</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Bootstrap</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Javascript</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>React</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>
              </q-item-section>
            </q-item>

            <q-separator />

            <q-item clickable v-ripple>
              <q-item-section avatar>
                <i class="bi bi-calendar-event text-h5"></i>
              </q-item-section>

              <q-item-section>
                <q-btn label="Events" style="color: rgb(15, 12, 12);">
              <q-menu
                transition-show="flip-right"
                transition-hide="flip-left"
              >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Coding Hackathon</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>UI Marathon</q-item-section>
            </q-item>
            <q-separator />
          </q-list>
        </q-menu>
      </q-btn>
              </q-item-section>
            </q-item>

            <q-separator />

            <q-item clickable v-ripple>
              <q-item-section avatar>
                <i class="bi bi-substack text-h5"></i>
              </q-item-section>

              <q-item-section>
                <q-btn label="Blogs" style="color: rgb(15, 12, 12);">
              <q-menu
                transition-show="flip-right"
                transition-hide="flip-left"
              >
          <q-list style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Elite Coaching Center</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>CEO & Founder</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Partners</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>
              </q-item-section>
            </q-item>

            <q-separator />


          </q-list>
        </q-scroll-area>
      </q-drawer>
      <q-footer bordered class="bg-light-blue-1">
        <q-tabs no-caps active-color="primary" indicator-color="transparent" class="text-grey-8" v-model="tab">
          <q-tab><i class="bi bi-facebook text-blue"></i></q-tab>
          <q-tab><i class="bi bi-instagram text-deep-orange"></i></q-tab>
          <q-tab><i class="bi bi-youtube text-red"></i></q-tab>
          <q-tab><i class="bi bi-twitch text-purple"></i></q-tab>
          <q-tab><i class="bi bi-twitter text-blue-8"></i></q-tab>
        </q-tabs>
      </q-footer>

    </q-layout>

</template>

<script>
import { ref } from 'vue'

export default{
  name: 'MainLayout',


  setup () {
    // const leftDrawerOpen = ref(false)

    return {
      model: ref('one'),
      secondModel: ref('one'),
      current: ref(1),
      drawer: ref(false),
      miniState: ref(true)
    }
  }
}
</script>
<style  scoped>
.my-custom-toggle
{
  border: 1px solid white;
}

</style>
