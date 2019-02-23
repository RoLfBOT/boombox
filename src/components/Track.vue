<template>
  <div class="col-12 mb-2 mt-2">
    <div class="card bg-dark shadow">
      <div class="row no-gutters">
        <div class="col-4">
          <img :src="track.art" class="card-img" />
        </div>
        <div class="col-8">
          <div class="card-body text-white">
            <h6 class="card-title mb-1">{{ track.title }}</h6>
            <p class="card-text mb-1">
              <small> {{ track.artist }} </small>
            </p>
            <p class="card-text">
              <small> {{ track.album }} </small>
            </p>
            <button class="btn btn-outline-primary">
              <i class="far fa-heart"></i>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    track: Object
  }
};
</script>

<style scoped>
.card {
  line-height: 1;
  border: none;
}

.card-img {
  object-fit: cover;
  height: 100%;
}
</style>
