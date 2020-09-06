<template>
  <section class="banner">
    <div>
      <h1 class="headline">
        Work at the speed <br />
        of thought
      </h1>
      <p class="banner-p">
        Most calendars are designed for teams. Slate is designed for <br />
        freelancers who want a simple way to plan their schedule.
      </p>
    </div>
    <div class="banner-btn">
      <button class="try-for-free-btn">Try For Free</button>
      <button class="learn-more-btn">Learn More</button>
    </div>
    <div class="banner-img-div">
      <img class="banner-img" src="../assets/screens.png" alt="" />
    </div>
  </section>
</template>
<script>
export default {
  name: "Banner",
};
</script>
<style scoped>
.banner {
  display: flex;
  flex-direction: column;
  background: linear-gradient(180deg, rgba(0, 0, 0, 0) 0%, #0e0e0e 66.15%);
}

.banner-p {
  font-size: 20px;
  text-align: center;
  line-height: 30px;
}

.banner-btn {
  margin-left: 40%;
  justify-content: center;
}

.try-for-free-btn {
  border: none;
  background-color: #4452fe;
  color: #ffffff;
  width: 178px;
  height: 60px;
}

.learn-more-btn {
  border: 1px solid #ffffff;
  background-color: #181818;
  color: #ffffff;
  width: 178px;
  height: 60px;
  margin-left: 3%;
}
.headline {
    font-weight: 500;
    font-size: 80px;
    line-height: 88px;
    text-align: center;
}

.banner-img-div {
  align-self: center;
  margin-top: 2.5%;
}

.banner-img {
  width: 1820px;
  height: auto;
}
</style>
