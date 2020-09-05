<template>
  <section class="">
    <footer class="text-white p-8">
      <div class="container flex flex-wrap justify-around">
        <div class="icons">
          <h1 class="text-sm py-2">Company, Alright Reserved</h1>
        </div>
        <div class="logo-image">
          <img src="../assets/logo.png" class="" alt="" />
        </div>
        <div class="py-2">
          <span
            ><i class="fa fa-facebook  px-4 text-xl" aria-hidden="true"></i
          ></span>
          <span
            ><i class="fa fa-instagram  px-4 text-xl" aria-hidden="true"></i
          ></span>
          <span
            ><i class="fa fa-twitter  px-4 text-xl" aria-hidden="true"></i
          ></span>
          <span
            ><i class="fa fa-behance  px-4 text-xl" aria-hidden="true"></i
          ></span>
        </div>
      </div>
    </footer>
  </section>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style scoped>
.container {
  color: black;
}

@media (max-width: 755px) {
  .container {
    flex-direction: column;
    text-align: center;
    
  }
  .icons {
    text-align: center;
    padding: 35px 0px;
  }
  .fa-facebook,
  .fa-twitter,
  .fa-instagram,
  .behance {
    font-size: 13px;
  }
  img{
    display: block;
    margin: 0px auto;
  }
}
</style>
