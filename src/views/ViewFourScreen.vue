<template>
  <div class="ViewFourScreen">
    <div class="effect-glass">
      <div class="PricingView container p-3">
        <h1 class="PricingHero-module__PricingHero__heading___3PBKD mb-5 text-center text-white" data-testid="pricing-hero"><span>You’ve got the ideas,</span><span>we’ve got the plans</span></h1>
        <div style="height: 100%" class="row">
          <div class="col-lg-4">
            <div class="rounded-circle-card bg-white">
              <div class="p-3">
                <h3>Basic</h3>
                <div class="p-3 border-bottom">
                  <ul class="list p-0">
                    <li>
                      Free
                    </li>
                    <li>
                      Resources
                    </li>
                  </ul>
                </div>
                <div class="py-3">
                  <h2 class="d-inline">$ 0</h2>
                  <label>
                    /year
                  </label>
                </div>
                <button class="btn rounded-0 btn-outline-dark p-3 w-100">Sign Up Free</button>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="border-custom-color rounded-circle-card bg-background-color-custom">
              <div class="p-3">
                <h3>Full</h3>
                <div class="p-2 border-bottom">
                  <ul class="list p-0">
                    <li>
                      Teaching Tools
                    </li>
                    <li>
                      Sonidos
                    </li>
                    <li>
                      Sílabas
                    </li>
                    <li>
                      Juntando 2 Sílabas
                    </li>
                    <li>
                      Sílabas Inversas y Extensiones
                    </li>
                    <li>
                      Juntando 3 sílabas
                    </li>
                    <li>
                      Sílabas trabadas y especiales
                    </li>
                    <li>
                      Resources
                    </li>
                    <li>
                      Classrooms
                    </li>
                    <li>
                      Reports
                    </li>
                  </ul>
                </div>
                <div>
                  <div class="m-3">
                    <h2 class="d-inline py-3 ">
                      $ 63
                    </h2>
                    <label>
                      /year
                    </label>
                  </div>
                </div>
                <button class="btn btn-outline-dark w-100 btn-lg p-3 rounded-0">Upgrate to pro</button>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="border-custom-color bg-background-color-custom-dark p-3">
              <h3>Schools</h3>
              <div class="p-3 border-bottom">
                <ul class="list p-0">
                  <li>
                    Teaching Tools
                  </li>
                  <li>
                    Sonidos
                  </li>
                  <li>
                    Sílabas
                  </li>
                  <li>
                    Juntando 2 Sílabas
                  </li>
                  <li>
                    Sílabas Inversas y Extensiones
                  </li>
                  <li>
                    Juntando 3 sílabas
                  </li>
                  <li>
                    Sílabas trabadas y especiales
                  </li>
                  <li>
                    Resources
                  </li>
                  <li>
                    Student Edition
                  </li>
                  <li>
                    Classrooms
                  </li>
                  <li>
                    Reports
                  </li>
                </ul>
              </div>
              <div class="">
                <h2 class="py-2">
                  Quote for year
                </h2>
                <button class="btn-outline-light btn w-100 btn-lg p-3 rounded-0">Contact Us for a Quote</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ViewFourScreen"
}
</script>

<style scoped>

.effect-glass {
  height: 100%;
  backdrop-filter: blur(10px);
  background-color: rgba(37, 37, 38, 0.39);
}

.PricingView {
  height: 100%;
}
.bg-background-color {
  background-color: #3fb8d3;
}
.list {
  list-style: none;
}

.rounded-circle-button {
  border-radius: 50vh;
}
.rounded-circle-card {

}

.border-custom-color {
  border: 1px solid #9cfffe;
}
.text-color-custom {
  color: #006071;
}
.bg-background-color-custom {
  background-color: #d3fffe;
  color: #006071;
}
.bg-background-color-custom-dark {
  background-color: #006071;
  color: #d3fffe;
}
.PricingHero-module__PricingHero__heading___3PBKD {
  display: flex;
  flex-direction: column;
  font-size: 40px;
  font-weight: 400;
  letter-spacing: -.02em;
  line-height: 90%;
  padding-top: 24px;
}
.ViewFourScreen {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
  background-image: url("../assets/imagen5.9ff47db1.jpg");
}

</style>
