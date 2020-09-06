<template>
  <section class="partners">
    <div>
      <h2 class="partners-heading">
        Partners
      </h2>
      <p class="partners-p">
        We focus on ergonomics and meeting you where you work. <br />
        It's only a keystroke away.
      </p>
      <div class="logos">
        <img class="logo" src="../assets/logos_apple-app-store.png" alt="" />
        <img class="logo" src="../assets/logos_apiary.png" alt="" />
        <img class="logo" src="../assets/logos_android-icon.png" alt="" />
        <img class="logo" src="../assets/logos_basecamp.png" alt="" />
        <img class="logo" src="../assets/logos_airbnb.png" alt="" />
        <img class="logo" src="../assets/logos_ibm.png" alt="" />
      </div>
      <button class="partners-btn">All Partners</button>
    </div>
  </section>
</template>
<script>
export default {
  name: "Partners",
};
</script>
<style scoped>
.partners {
  text-align: center;
  margin-top: 12%;
}

.partners-heading {
  font-size: 52px;
  font-weight: lighter;
}

.partners-p {
  text-align: center;
  font-size: 20px;
  line-height: 30px;
}

.logos {
    display: flex;
  justify-content: center;
  margin: 40px 0px;
}

.logo {
  margin: 0px 30px;
}

.partners-btn {
  background-color: #181818;
  color: #ffffff;
  border: 1px solid #ffffff;
  width: 120px;
  height: 40px;
  margin: 10px auto;
  display: block;
}
</style>
