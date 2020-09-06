<template>
  <section>
    <div class="open-type-style">
      <div>
        <h1 class="open-type-header">
          OpenType feature 
          and Variable fonts
        </h1>
        <button class="open-type-btn">Try For Free</button>
      </div>
      <div>
        <img class="open-type-img" src="../assets/card.png" alt="" />
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Contact",
};
</script>
<style>
.open-type-header {
  font-size: 30px;
  font-weight: normal;
  padding-left: 70px;
  padding-top: 7%;
}

.open-type-btn {
  display: block;
  background-color: #4452fe;
  color: #ffffff;
  border: none;
  padding: 15px 40px;
  margin-left: 17%;
}

.open-type-img {
  padding-left: 22.5%;
  padding-top: 2%;
}

.open-type-style {
  display: flex;
  background-color: #343434;
  border: none;
  border-radius: 33px;
  margin-top: 10%;
  margin-left: 15%;
  width: 55%;
  height: 200px;
  overflow-y: hidden;
}
</style>
