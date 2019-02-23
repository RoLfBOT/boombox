<template>
  <div class="container h-100 bg">
    <div class="row h-100 justify-content-center align-items-center">
      <div class="col-12 text-center">
        <h1 class="text-primary">BoomBox</h1>
        <p class="text-primary">The Brew Estate</p>
        <div class="row align-items-center justify-content-center">
          <div class="col-8 text-center">
            <router-link
              to="/vote"
              class="btn btn-block rounded-pill btn-outline-primary"
              >Start Voting</router-link
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.btn {
  border-width: 2px;
}

.bg {
  background: url("../assets/bg.svg");
  background-repeat: no-repeat;
  background-position: center center;
  background-attachment: fixed;
  background-size: contain;
  -webkit-background-size: contain;
  -moz-background-size: contain;
  -o-background-size: contain;
}
</style>
