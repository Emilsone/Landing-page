<template>
  <section>
    <div>
      <h2 class="features">
        FEATURES
      </h2>
      <p class="features-p">
        Most calendars are designed for teams. Slate is designed for <br />
        freelancers who want a simple way to plan their schedule.
      </p>
    </div>
    <div class="features-style">
      <div class="features-img1">
        <img src="../assets/Chat Bot.png" alt="" />
      </div>
      <div class="features-img2">
        <img src="../assets/Line Chart 1.png" alt="" />
      </div>
      <div class="features-txt">
        <div>
          <h3 class="truth">A single source of truth</h3>
          <p>
            When you add work to your <br />
            Slate calendar we automatically <br />
            calculate useful insights
          </p>
        </div>
        <div>
          <h3 class="interface">Intuitive interface</h3>
          <p>
            When you add work to your <br />
            Slate calendar we automatically <br />
            calculate useful insights
          </p>
        </div>
        <div>
          <h3 class="rules">Or with rules</h3>
          <p>
            When you add work to your <br />
            Slate calendar we automatically <br />
            calculate useful insights
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Welcome",
};
</script>
<style scoped>
.features {
  font-size: 52px;
  font-weight: lighter;
  line-height: 88px;
  text-align: center;
  margin-top: 10%;
}

.features-p {
  text-align: center;
  font-size: 20px;
  line-height: 30px;
}

.features-style {
  display: flex;
  justify-content: center;
  position: relative;
}

.features-txt {
  flex-direction: column;
  margin-left: 10%;
}

.features-txt p {
  font-size: 16px;
  /* line-height: 24px; */
  font-weight: normal;
}

.features-txt h3 {
  font-size: 20px;
  line-height: 30px;
  font-weight: 500;
}

.truth::before {
  /* content: url(../assets/Vector-one.png); */
  padding-right: 30px;
}

.interface::before {
  /* content: url(../assets/Vector-tw); */
  padding-right: 30px;
}

.rules::before {
  /* content: url(../assets/Vector-three); */
  padding-right: 30px;
}

.features-img2 {
  position: absolute;
  top: 60%;
}
</style>
