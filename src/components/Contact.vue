<template>
  <section>
    <div>
      <h2 class="gallery">
        Gallery
      </h2>
      <p class="gallery-p">
        We focus on ergonomics and meeting you where you work. <br />
        It's only a keystroke away.
      </p>
    </div>
    <div>
      <div class="first-gallery">
        <div>
          <img
            src="../assets/Rectangle 1.png"
            href=""
            alt=""
          />
        </div>
        <div>
          <img
            src="../assets/Rectangle 2.png"
            href=""
            alt=""
          />
        </div>
        <div>
          <img
            src="../assets/Rectangle 3.png"
            href=""
            alt=""
          />
        </div>
        <div>
          <img
            src="../assets/Rectangle 4.png"
            href=""
            alt=""
          />
        </div>
      </div>
      <div class="second-gallery">
        <div>
          <img
            src="../assets/Rectangle 5.png"
            href=""
            alt=""
          />
        </div>
        <div>
          <img
            src="../assets/Rectangle 6.png"
            href=""
            alt=""
          />
        </div>
        <div>
          <img
            src="../assets/Rectangle 7.png"
            href=""
            alt=""
          />
        </div>
      </div>
    </div>
    <button class="see-more">See more</button>
  </section>
</template>
<script>
export default {
  name: "Contact",
};
</script>
<style>
.gallery {
  margin-top: 10%;
  text-align: center;
  font-size: 52px;
  font-weight: normal;
}

.gallery-p {
  text-align: center;
  font-size: 20px;
  line-height: 30px;
}

.first-gallery {
  display: flex;
  justify-content: center;
}

.first-gallery div {
  margin: 20px;
}

.first-gallery img {
  border-radius: 10px;
}

.second-gallery {
  display: flex;
  justify-content: center;
}

.second-gallery img {
  border-radius: 10px;
}

.second-gallery div {
  margin: 5px;
}

.see-more {
  text-decoration: none;
  background-color: #181818;
  color: #ffffff;
  border: 1px solid #ffffff;
  width: 110px;
  height: 40px;
  margin: 2% auto;
  display: block;
}
</style>
