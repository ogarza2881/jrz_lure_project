<template>
  <div>
    <div class="position-relative">
      <!-- shape Hero -->
      <section class="section-shaped my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="container shape-container d-flex">
          <div class="col px-0">
            <div class="row">
              <div class="col-lg-6">
                <h1 class="display-3 text-white">
                  Lurus
                  <span>Lorem Ipsum is simply dummy text</span>
                </h1>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section section-components pb-0" id="section-components">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-12">
              <h2 class="mb-5">
                <span>Lorem Ipsum</span>
              </h2>
              <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s, when an unknown printer took a galley
                of type and scrambled it to make a type specimen book. It has
                survived not only five centuries, but also the leap into
                electronic typesetting, remaining essentially unchanged. It was
                popularised in the 1960s with the release of Letraset sheets
                containing Lorem Ipsum passages, and more recently with desktop
                publishing software like Aldus PageMaker including versions of
                Lorem Ipsum.
              </p>
            </div>
          </div>
        </div>
      </section>
    </div>

    <br><br>

    <div class="container container-lg">
      <div class="row">
        <div class="col-md-6 mb-5 mb-md-0">
          <div class="card card-lift--hover shadow border-0">
            <router-link to="/landing" title="Landing Page">
              <img v-lazy="'img/app/lurus1.jpg'" class="card-img" />
            </router-link>
          </div>
        </div>
        <div class="col-md-6 mb-5 mb-lg-0">
          <div class="card card-lift--hover shadow border-0">
            <router-link to="/profile" title="Profile Page">
             <img v-lazy="'img/app/lurus1.jpg'" class="card-img" />
            </router-link>
          </div>
        </div>
      </div>
      <br><br>
            <div class="row">
        <div class="col-md-6 mb-5 mb-md-0">
          <div class="card card-lift--hover shadow border-0">
            <router-link to="/landing" title="Landing Page">
           <img v-lazy="'img/app/lurus2.jpg'" class="card-img" />
            </router-link>
          </div>
        </div>
        <div class="col-md-6 mb-5 mb-lg-0">
          <div class="card card-lift--hover shadow border-0">
            <router-link to="/profile" title="Profile Page">
                  <img v-lazy="'img/app/lurus2.jpg'" class="card-img" />
            </router-link>
          </div>
        </div>
      </div>
    </div>

    <section class="section section-lg">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-md-2">
            <img src="img/app/lurus3.jpg" class="img-fluid floating" />
          </div>
          <div class="col-md-6 order-md-1">
            <div class="pr-md-5">
              <icon
                name="ni ni-settings-gear-65"
                class="mb-5"
                size="lg"
                type="success"
                shadow
                rounded
              ></icon>
              <h3>Lorem Ipsum is simply dummy text</h3>
              <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s, when an unknown printer took a galley
                of type and scrambled it to make a type specimen book.
              </p>
              <ul class="list-unstyled mt-5">
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge
                      type="success"
                      circle
                      class="mr-3"
                      icon="ni ni-settings-gear-65"
                    ></badge>
                    <h6 class="mb-0">Lorem Ipsum is simply dummy text</h6>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge
                      type="success"
                      circle
                      class="mr-3"
                      icon="ni ni-html5"
                    ></badge>
                    <h6 class="mb-0">Lorem Ipsum is simply dummy text</h6>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge
                      type="success"
                      circle
                      class="mr-3"
                      icon="ni ni-satisfied"
                    ></badge>
                    <h6 class="mb-0">Lorem Ipsum is simply dummy text</h6>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>


  </div>
</template>

<script>
export default {
  name: "lurus",
  components: {},
};
</script>
