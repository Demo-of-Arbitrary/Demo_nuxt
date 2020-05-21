<template>
  <div class="main">
    <div class="header-dark">
      <div class="logo">
        <img src="https://miro.medium.com/max/1400/1*p0OGaNEm_F9uWaGmN517TA.jpeg" alt="image" @click="myMethod()">
      </div>
    </div>
    <div class="social-nav"></div>
  </div>
</template>

<script>
export default {
  methods: {
    myMethod(event) {
      scrollTo(0, 0);
    }
  }
}
</script>
