<template>
  <base-layout>
    <v-container fluid>
      <v-row>
        <v-card
          class="pa-md-4 mx-lg-auto"
          cols="6"
          lg="12"
          md="12"
          color="amber lighten-5"
          width="100%"
          height="500px"
          elevation="0"
        >
          <v-col cols="12" md="4" lg="6">
            <Body2 class="pink--text">Lynn Ocharoenchai, 24</Body2><br />
            <Body2>Thiland</Body2>

            <h1>
              <br />(Formal role) and <br />
              (Informal role)
            </h1>
            <v-card-title>
              friend in figuring out how to take <br />
              care of mental heath in activisism</v-card-title
            >
          </v-col>

          <v-btn text>(photo/video of the mentor)</v-btn>
        </v-card>
      </v-row>
      <!-- end -->
      <v-container fluid>
        <v-row>
          <h2>I am lynn</h2>
        </v-row>

        <v-row>
          <v-col cols="12" lg="12">
            <v-row justify="center">
              <iframe
                width="100%"
                height="400px"
                src="https://www.youtube.com/embed/z7mIkruXgJQ"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </v-row> </v-col
        ></v-row>
      </v-container>
      <!-- end -->
      <v-container fluid>
        <v-divider></v-divider>
        <v-row>
          <v-col cols="12" md="12" lg="8">
            <p>
              <strong>Where I am coming from? </strong>Lorem ipsum dolor, sit
              amet consectetur adipisicing elit. Consequuntur incidunt obcaecati
              cum eveniet mollitia quo deleniti tempora accusantium error quis.
            </p>
            <h1>What you can learn from me?</h1>
            <p class="pink--text">
              <strong>
                1. How to stay optimistic? <br />
                2. How do I talk to my friends about climate change?</strong
              >
            </p>
            <p>
              (Notes: Tone should be positive encouraging)<br />(Insert personal
              information)
            </p>
          </v-col>

          <v-col cols="12" md="8" lg="4">
            <v-card
              height="400"
              width="80%"
              class="pa-2 aboutBox doubleBox1 rounded-xl d-flex align-end"
            >
              <v-card-text>
                <p class="ml-0">Check out my work:</p>
                <ul class="pink--text">
                  <li>Insert link here</li>
                  <li>Insert link here</li>
                  <li>Insert link here</li>
                </ul>
              </v-card-text>
            </v-card>
            <v-card height="300" width="80%" class="pa-2 aboutBox doubleBox2 rounded-xl">
              <v-card-title>I am a climate activist </v-card-title>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
      <!-- end -->

      <!-- Start Topic-1 -->

      <v-container>
        <h1>(topic-1)</h1>
        <v-row>
          <v-col lg="8" cols="6" md="8">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
              corrupti aliquid laboriosam dolores libero commodi ratione
              nesciunt nihil autem, cumque voluptatibus quibusdam ipsam
              repellendus inventore, reiciendis quia odio itaque quasi! Lorem
              ipsum dolor sit amet consectetur adipisicing elit. Exercitationem
              sed amet perspiciatis molestiae dolor, repellat nihil nesciunt
              nobis perferendis facilis doloremque unde eligendi quasi at
              repellendus sint ullam, debitis a!
            </p>
          </v-col>
        </v-row>

        <v-row lg="12" cols="12" md="12">
          <v-col lg="8" cols="6">
            <v-card>
              <iframe
                width="100%"
                height="300px"
                src="https://www.youtube.com/embed/z7mIkruXgJQ"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </v-card>
          </v-col>
          <v-col lg="4" cols="6">
            <v-card class="aboutBox" height="300px" width="100%"> </v-card>
          </v-col>
        </v-row>

        <v-row lg="12" cols="12" md="12">
          <v-col lg="2" cols="4">
            <v-row>
              <v-row
                class="pa-2"
                lg="4"
                cols="6"
                justify="space-around"
                align="center"
              >
                <v-avatar v-for="i in 3" :key="i" color="#0B0B2B">
                  {{ i }}
                </v-avatar>
              </v-row>
              <v-col lg="12" cols="12">
                <v-card class="pa-2 aboutBox" height="280px"></v-card>
              </v-col>
            </v-row>
          </v-col>

          <v-col lg="6" cols="4">
            <v-row>
              <v-row class="pa-2" lg="6" cols="6" justify="space-around">
                <h1>Lorem ipsum exinventore iure, soluta eum reprehenderit?</h1>
              </v-row>
              <v-col lg="12" cols="12">
                <v-card class="pa-2 aboutBox" height="200px"></v-card>
              </v-col>
            </v-row>
          </v-col>
          <v-col lg="4" cols="6">
            <v-card>
              <img src="@/assets/dog.png" height="320px" width="100%" />
            </v-card>
          </v-col>
        </v-row>
      </v-container>
      <!-- End Topic-1 -->
      <!-- Start Topic-2 -->
      <v-container>
        <v-divider></v-divider>

        <h1>(Topic 2)</h1>
        <v-col lg="8" cols="12"
          ><p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
            molestiae quae, tenetur libero mollitia unde debitis vitae neque
            consequatur nisi? Lorem, ipsum dolor sit amet consectetur
            adipisicing elit. Odit dolores nulla maxime commodi dolor quaerat
            praesentium perferendis nemo quisquam illo totam id fuga incidunt,
            tempore doloribus deleniti rem, fugiat quo.
          </p></v-col
        >

        <iframe
          width="100%"
          height="400px"
          src="https://www.youtube.com/embed/z7mIkruXgJQ"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </v-container>
      <!-- end Tpoic-2 -->

      <!-- Start Topic-3 -->
      <v-container>
        <v-divider></v-divider>
        <h1>(Topic 3)</h1>
        <v-col lg="8" cols="12"
          ><p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
            molestiae quae, tenetur libero mollitia unde debitis vitae neque
            consequatur nisi? Lorem, ipsum dolor sit amet consectetur
            adipisicing elit. Odit dolores nulla maxime commodi dolor quaerat
            praesentium perferendis nemo quisquam illo totam id fuga incidunt,
            tempore doloribus deleniti rem, fugiat quo.
          </p></v-col
        >
        <v-col cols="12" sm="6" md="3" lg="12">
          <v-text-field
            label="A Diagram"
            height="250px"
            outlined
          ></v-text-field>
        </v-col>
      </v-container>

      <!-- End Topic-3 -->

      <!-- Start Some fun stuff about me -->
      <v-container>
        <v-divider></v-divider>
        <h1>Some fun stuff about me</h1>
        <br />

        <v-row>
          <v-col cols="4" lg="4" md="2">
            <v-card class="aboutBox" height="300px" width="100%">
              <h1>Who inspire me?</h1>
            </v-card>
          </v-col>
          <v-col lg="2" cols="4">
            <v-row>
              <v-row
                class="d-flex flex-column mb-6"
                lg="2"
                cols="6"
                align="center"
              >
                <v-avatar v-for="i in 5" :key="i" color="#FFD236">
                  {{ i }}
                </v-avatar>
              </v-row>
            </v-row>
          </v-col>
          <v-col cols="4" lg="6" md="2">
            <v-card class="aboutBox" height="400px" width="100%">
              <h1>My hobbies</h1>
            </v-card>
          </v-col>
        </v-row>

        <v-row>
          <v-col lg="4">
            <v-card
              class="pa-2 aboutBox"
              height="300px"
              width="100%"
              style="top: -110px"
            >
              <h2 class="black--text font-weight-black text-sm-left">
                (insert text here)
              </h2>
            </v-card>
          </v-col>

          <v-col lg="8" col="4" md="8">
            <v-card class="pa-2 aboutBox" height="200px" width="100%">
              <h1 class="black--text font-weight-black text-sm-left">
                Favourite Place
              </h1>
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col lg="12">
            <v-card
              class="pa-2 aboutBox"
              height="250px"
              width="100%"
              style="top: -100px"
            >
              <h1>
                <a style="text-decoration: none" href="/" class="black--text"
                  >Where I get my ideas</a
                >
              </h1>
            </v-card>
          </v-col></v-row
        >
      </v-container>
      <!-- End Some fun stuff about me -->

      <!-- Start Social media -->
      <v-container>
        <v-row justify="center" cols="12" lg="6"> <h2>(Exit line)</h2></v-row
        ><br /><br />
        <v-row justify="center" cols="12" lg="6">
          <h2>If you need anything you can find me here:</h2>
        </v-row>
        <br />
        <br />
        <v-row justify="center">
          <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-4 black--text"
            icon
          >
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-row>
        <v-row justify="center">
          <v-btn class="pink white--text" outlined>Share this page</v-btn>
          <v-btn class="pink white--text" outlined>Copy link to the page</v-btn>
        </v-row>
      </v-container>

      <!-- End Social media -->
    </v-container>
    <!-- Start Whats Next -->

    <v-row class="pink white--text py-16 mx-0">
      <v-col lg="6" cols="12">
        <h1>
          <span class="yellow--text">What's Next? </span>The Butterfly hero
        </h1>
      </v-col>
      <v-col lg="6" cols="12">
        <h1>Go back to all guides</h1>
      </v-col>
    </v-row>

    <!-- End Whats Next -->
  </base-layout>
</template>

<script>
import BaseLayout from "../../App.vue";
export default {
  name: "ShiftUniversityInsidePage",
  components: {
    BaseLayout,
  },

  data: () => ({ icons: ["mdi-facebook", "mdi-instagram"] }),
};
</script>
