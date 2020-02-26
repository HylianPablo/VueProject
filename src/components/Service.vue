<template>
  <section class="page-section" id="services">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h2 class="section-heading text-uppercase">Sitios web</h2>
          <h3 class="section-subheading text-muted">Sitios web personales.</h3>
        </div>
      </div>
      <div class="row text-center">

        <div class="col-md-4" v-for="(obj,key) in serviceJSON" :key="key">
          
          <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
          </span>
          <h4 class="service-heading"> {{obj.title}}</h4>
           <a class="service-link" data-toggle="modal" :href="obj.url">
          <p
            class="text-muted"
          >{{obj.text}}</p>
          </a>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
    data: () => ({
        serviceJSON: [
            {
                title: "GitHub",
                text: "HylianPablo",
                url: "https://github.com/HylianPablo"
            },
            {
                title: "LinkedIn",
                text: "Pablo Martínez López",
                url: "https://www.linkedin.com/in/pablomartinezbss/"
            },
            {
                title: "Correo electrónico",
                text: "pablomartinezbss@gmail.com",
                url: "https://www.gmail.com"
            }
        ]
    })
};
</script>

<style lang="css"></style>