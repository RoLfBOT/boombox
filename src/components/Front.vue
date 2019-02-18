<template>
  <div class="container h-100">
    <div class="row h-100 justify-content-center align-items-center">
      <div class="col-12 text-center">
        <h1>BoomBox</h1>
        <p>The Brew Estate</p>
        <div class="row align-items-center justify-content-center">
          <div class="col-8 text-center">
            <router-link
              to="/vote"
              class="btn btn-block rounded-pill btn-outline-success"
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
</style>
