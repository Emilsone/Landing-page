<template>
  <section class="">
    <footer class="text-white">
      <div class="footer-style">
        <div>
          <ul class="footer-list-1">
            <li id="list-1">Fingertipe</li>
            <li>Home</li>
            <li>Examples</li>
            <li>Pricing</li>
            <li>Updates</li>
          </ul>
        </div>
        <div>
          <ul class="footer-list-2">
            <li id="list-1">Resources</li>
            <li>Home</li>
            <li>Examples</li>
            <li>Pricing</li>
            <li>Updates</li>
          </ul>
        </div>
        <div>
          <ul class="footer-list-3">
            <li id="list-1">About</li>
            <li>Home</li>
            <li>Examples</li>
            <li>Pricing</li>
            <li>Updates</li>
          </ul>
        </div>
        <div class="contact-style">
          <div class="contact-details-1">
            <div>
              <img src="../assets/bx_bx-map.png" alt="" />
            </div>
            <div>
              <p>7480 Mockingbird Hill undefined</p>
            </div>
          </div>
          <div class="contact-details-2">
            <div>
              <img src="../assets/ic_baseline-phone-android.png" alt="" />
            </div>
            <div>
              <p>(239) 555-0108</p>
            </div>
          </div>
          <div class="footer-logos">
            <img
              class="twitter-logo"
              src="../assets/twitter-vector.png"
              alt=""
            />
            <img class="facebook-logo" src="../assets/Fb vector.png" alt="" />
            <img
              class="linkedin-logo"
              src="../assets/linked-in vector.png"
              alt=""
            />
          </div>
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

.footer-style {
  display: flex;
  margin-top: 11%;
  margin-left: 18%;
}

.footer-style li {
  list-style-type: none;
  font-size: 16px;
  line-height: 3;
}

.footer-list-2 {
  margin-left: 100px;
}

.footer-list-3 {
  margin-left: 100px;
}

#list-1 {
  font-size: 20px;
}

.contact-style {
  padding-left: 300px;
  padding-bottom: 200px;
  padding-top: 20px;
}

.contact-details-1,
.contact-details-2 {
  display: flex;
}

.contact-details-2 {
  margin-top: 10px;
}

.facebook-logo {
  margin-left: 30px;
}

.footer-logos {
  margin-top: 30px;
}

.linkedin-logo {
  margin-left: 30px;
}
</style>
