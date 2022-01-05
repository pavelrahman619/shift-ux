<template>
  <div class="white">
    <v-container fluid class="yellow lighten-5 plan-main-text">
      <v-row>
        <h1 class="pink--text">
          Let's make a plan for <br />
          your idea.
        </h1>
      </v-row>
      <v-row>
        <h2>
          Before we begin, let me give you a brief <br />
          explanation why we need this plan:
        </h2>
      </v-row>
    </v-container>

    <v-container fluid>
      <v-row justify="center">
        <v-card>
          <v-col>
            <iframe
              width="560"
              height="315"
              src="https://www.youtube.com/embed/nhBVL41-_Cw"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </v-col>
        </v-card>
      </v-row>
    </v-container>

    <v-container fluid>
      <v-form>
        <v-container>
          <v-row>
            <v-col cols="6" align="center">
              <v-icon size="5em"> mdi-upload </v-icon>
            </v-col>

            <v-col cols="6">
              <v-row>
                <v-text-field
                  :counter="50"
                  label="Title of your plan"
                  required
                ></v-text-field>
              </v-row>

              <v-row>
                <v-text-field
                  :counter="50"
                  label="Group name"
                  required
                ></v-text-field>
              </v-row>

              <v-row>
                <v-text-field
                  :counter="50"
                  label="Topic"
                  required
                ></v-text-field>
              </v-row>
            </v-col>
          </v-row>
        </v-container>
      </v-form>
    </v-container>

    <v-container fluid>
      <v-card>
        <v-row justify="center" class="pink white--text">
          <h1>Take our guided planning</h1>
        </v-row>
      </v-card>
    </v-container>

    <v-container fluid>
      <v-row>
        <v-col cols="8">
          <h2>...or pick a card and fill up at your own pace</h2>
        </v-col>
        <v-col cols="4">
          <a href="#" class="pink--text">I want to see a sample</a>
        </v-col>
      </v-row>

      <v-row><h2>Your Plan</h2> </v-row>

      <v-row>
        <v-col cols="6">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col cols="6">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>

      <v-row>
        <v-col cols="6">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col cols="6">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>

      <v-row><h2>Your Creative Plan</h2> </v-row>
      <v-row>
        <v-col cols="12">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-card class="yellow lighten-5">
            <v-card-title>
              <h1>The Problem</h1>
            </v-card-title>
            <v-card-text>
              <v-text-field
                label="What is the issue that can be solved"
                required
              >
                <template v-slot:append>
                  <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
                </template>
              </v-text-field>
            </v-card-text>
            <v-card-actions>
              <v-col cols="6">
                <a href="#" class="pink--text">Save this entry</a>
              </v-col>
              <v-col cols="6" class="d-flex justify-end">
                <a href="#" class="pink--text">I need help</a>
              </v-col>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>

      <v-row justify="center"><h2>Are you done writing your plan?</h2></v-row>
      <v-row justify="center" class="pa-3">
        <v-btn class="pink white--text">Download my plan as PDF</v-btn>
        <v-btn class="pink white--text">Download my plan as JPG</v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn class="pink white--text">Make me a presentation deck</v-btn>
      </v-row>

      <br />
      <br />
      <br />
      <br />

      <v-row justify="center">
        <v-col cols="6" class="d-flex justify-end">
          <p class="text-justify">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur.
          </p>
        </v-col>
      </v-row>

      <br />
      <br />
      <br />
      <br />

      <v-row justify="center"><h2>Are you ready to Shift?</h2></v-row>
      <v-row justify="center" class="pa-3">
        <v-btn class="pink white--text">Yes, I want to apply now</v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn class="pink white--text">Nope, send me more details</v-btn>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>