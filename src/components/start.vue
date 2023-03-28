<template>
  <v-container class="fill-height">
    <v-responsive class="d-flex align-center text-center fill-height">
      <div id="container">
        <div class="text-body-2 font-weight-light mb-n1">Willkommen zu</div>

        <h1 class="text-h2 font-weight-bold">Spengerdates</h1>
        <br>
        <div>
          Spengerdates ist eine Dating-Plattform exklusiv für SchülerInnen der <a href="https://www.spengergasse.at">HTL Spengergasse</a>
        </div>
        <br>
        <div>
          <v-img
            contain
            height="300"
            src="@/assets/banner.png"
          />
        </div>
      </div>
    </v-responsive>
  </v-container>
</template>

<script lang="ts" setup>
  //
</script>

<style scoped>
.center,#container {
  width: 50%;
  margin: auto;
}
.v-container {
  background: linear-gradient(90deg, rgba(98,0,20,1) 0%, rgba(160,0,89,1) 100%);
  color: white;
  border-radius: 10px;
}

#container {
  background: white;
  color: black;
  border-radius: 10px;
}

::placeholder {
  text-align: center;
}
</style>
