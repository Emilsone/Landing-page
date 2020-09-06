<template>
  <section>
    <div>
      <h2 class="content">
        Contents
      </h2>
      <p class="content-p">
        We focus on ergonomics and meeting you where you work. <br />
        It's only a keystroke away.
      </p>
    </div>
    <div class="card-style">
      <div class="card-1">
        <h3 class="card-header">Work</h3>
        <p class="cards-p">
          Ever wondered if you're too reliant <br />
          on a client for work? Slate helps <br />
          you identify.
        </p>
        <button class="content-btn-1">Sign Up</button>
        <div class="img-group">
          <img
            class="screen-mask-img"
            src="../assets/SCREEN MASK.png"
            alt=""
          />
          <img class="grip-img" src="../assets/grip.png" alt="" />
          <img class="base-img" src="../assets/Base.png" alt="" />
        </div>
      </div>
      <div class="card-2">
        <h3 class="card-header">Design with real data</h3>
        <p class="cards-p">
          Ever wondered if you're too reliant <br />
          on a client for work? Slate helps <br />
          you identify.
        </p>
        <button class="content-btn-2">Try For Free</button>
        <img
          class="board-img"
          src="../assets/Boards Notifications.png"
          alt=""
        />
      </div>
    </div>
  </section>
</template>
<script>
// import TabIndex from "@/components/TabIndex.vue";
// import Logo from "@/components/Logo.vue";
// import DigitalMarketing from "@/components/DigitalMarketing.vue";
export default {
  name: "Projects",

  data() {
    return {
      tabActiveIndex: 0,
    };
  },
  methods: {
    changeTab(val) {
      this.tabActiveIndex = val;
    },
  },
};
</script>
<style scoped>
.content {
  text-align: center;
  font-size: 52px;
  font-weight: normal;
  margin-top: 10%;
}

.content-p {
  text-align: center;
  font-size: 20px;
  line-height: 30px;
}

.card-style {
  display: flex;
  justify-content: center;
  margin-top: 3%;
}

.card-header {
  color: #000000;
}

.cards-p {
  font-size: 16px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.2px;
}

.card-1 {
  background-color: #ffffff;
  color: #5c5c5c;
  border: 1px solid #d3d3d3;
  border-radius: 7px;
  text-align: center;
  height: 470px;
  width: 350px;
}

.img-group {
  position: relative;
}

.screen-mask-img {
  border: 7px solid#000000;
  width: 250px;
  margin-top: 23%;
}

.grip-img {
  position: absolute;
  top: 246px;
  right: 150px;
}

.base-img {
  position: absolute;
  top: 250px;
  right: 27px;
  width: 300px;
}

.card-2 {
  background-color: #ffffff;
  color: #5c5c5c;
  border: 1px solid #d3d3d3;
  border-radius: 6px;
  text-align: center;
  margin-left: 2%;
  height: 470px;
  width: 350px;
}

.board-img {
  width: 330px;
  margin-top: 10%;
}

.content-btn-1 {
  margin-top: 1%;
  border: none;
  background-color: #4452fe;
  color: #ffffff;
  width: 90px;
  height: 40px;
}

.content-btn-2 {
  border: none;
  background-color: #4452fe;
  color: #ffffff;
  width: 90px;
  height: 40px;
}
</style>
