<template>
 <section class="bg-light page-section" id="team">
        <div class="container">
          <div class="row">
            <div class="col-lg-12 text-center">
              <h2 class="section-heading text-uppercase">Cargos en asociaciones</h2>
              <h3 class="section-subheading text-muted">texto de ejemplo</h3>
            </div>
          </div>

          <div class="row">

            <div class="col-sm-6" v-for="(obj,key) in asosJSON" :key="key">

              <div class="team-member">
                <img class="Rounded mx-auto" :src="obj.photo"/>
                <h4>{{obj.name}}</h4>
                <p class="text-muted">{{obj.purpose}}</p>
                <ul class="list-inline social-buttons">
                  <li class="list-inline-item">
                    <a href="#">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </li>
                  <li class="list-inline-item">
                    <a href="#">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                  </li>
                  <li class="list-inline-item">
                    <a href="#">
                      <i class="fab fa-linkedin-in"></i>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
            
          </div>
          <div class="row">
            <div class="col-lg-8 mx-auto text-center">
              <p
                class="large text-muted"
              >Texto de ejemplo</p>
            </div>
          </div>
        </div>
      </section>
      </template>

      <script>
      export default {
    data: () => ({
        asosJSON: [
            {
                name: "Representante de centro",
                photo: '/eii.jpeg',
                purpose: "Representar al alumnado...etc"
            },
            {
                name: "Presidente",
                photo: '/gui.png',
                purpose: "Grupo destinado a la divulgación..."
            }
        ]
    })
};
      </script>

      <style lang="css"> </style>
