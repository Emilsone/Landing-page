<template>
  <section class="testimonial-section">
    <h2 class="testimonial">
      Testimonial
    </h2>
    <div class="slide-style">
      <div class="slide1">
        <div class="profile">
          <img
            class="profile-picture"
            src="../assets/profile picture 1.png"
            alt=""
          />
          <p class="profile-name">
            CLaire bell <br />
            Designer
          </p>
        </div>
        <p class="slide-p">
          Slate helps you see how many more days you need to work to reach your
          financial goal for the month and year. Slate helps you see how many
          more days you need to work to reach your financial goal for the month
          and year.your financial goal for the month and year.
        </p>
      </div>
      <div class="slide2">
        <div class="profile">
          <img
            class="profile-picture"
            src="../assets/Profile picture 2.png"
            alt=""
          />
          <p class="profile-name">
            Francisco Lane <br />
            Designer
          </p>
        </div>
        <p class="slide-p">
          Slate helps you see how many more days you need to work to reach your
          financial goal for the month and year. Slate helps you see how many
          more days you need to work to reach your financial goal for the month
          and year.your financial goal for the month and year.
        </p>
      </div>
    </div>
    <div class="slide-style-2">
      <div class="slide3">
        <div class="profile">
          <img
            class="profile-picture"
            src="../assets/Profile picture 3.png"
            alt=""
          />
          <p class="profile-name">
            Ralph Fisher <br />
            Designer
          </p>
        </div>
        <p class="slide-p">
          Slate helps you see how many more days you need to work to reach your
          financial goal for the month and year. Slate helps you see how many
          more days you need to work to reach your financial goal for the month
          and year.your financial goal for the month and year.
        </p>
      </div>

      <div class="slide4">
        <div class="profile">
          <img
            class="profile-picture"
            src="../assets/Profile picture 4.png"
            alt=""
          />
          <p class="profile-name">
            Jorge Murphy <br />
            Designer
          </p>
        </div>
        <p class="slide-p">
          Slate helps you see how many more days you need to work to reach your
          financial goal for the month and year. Slate helps you see how many
          more days you need to work to reach your financial goal for the month
          and year.your financial goal for the month and year.
        </p>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Partners",
};
</script>
<style scoped>
.testimonial {
    margin-top: 10%;
    text-align: center;
    font-weight: normal;
    font-size: 52px;
    letter-spacing: 0.2px;
}

.slide1, .slide2, .slide3, .slide4 {
    border: 1px solid #DEDEDE;
    border-radius: 10px;
    width: 430px;
    height: 328px;
}

.slide2, .slide4 {
    margin-left: 1%;
}

.profile {
    display: flex;
    margin-left: 15%;
    margin-top: 5%;
}

.profile-name {
    font-size: 16px;
    line-height: 24px;
    margin-left: 5%;
    margin-top: 8%;
}

.slide-style {
    display: flex;
    justify-content: center;
    margin-top: 4%;
}

.slide-style-2 {
    display: flex;
    justify-content: center;
    margin-top: 1%;
}

.slide-p {
    line-height: 24px;
    padding-left: 15%;
    padding-right: 15%;
    padding-top: 1%;
}

.profile-picture {
    height: 60px;
    margin-top: 8%;
}
</style>
