<template>
    <div id="app">
      <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
        <div class="container">
          <a class="navbar-brand js-scroll-trigger" href="#page-top">Pablo Martínez López</a>
          <button
            class="navbar-toggler navbar-toggler-right"
            type="button"
            data-toggle="collapse"
            data-target="#navbarResponsive"
            aria-controls="navbarResponsive"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            Menu
            <i class="fas fa-bars"></i>
          </button>
          <div class="collapse navbar-collapse" id="navbarResponsive">
            <ul class="navbar-nav text-uppercase ml-auto">
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#services">Sitios web</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#portfolio">Aptitudes</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#about">Cursos</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#team">Delete</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#contact">Contacto</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>

      <!-- Header -->
      <header class="masthead">
        <div class="container">
          <div class="intro-text">
            <div class="intro-lead-in">Pablo Martínez López</div>
            <div class="intro-heading text-uppercase">Estudiante de Ingeniería Informática</div>
            <a
              class="btn btn-primary btn-xl text-uppercase js-scroll-trigger"
              href="#services"
            >Tell Me More</a>
          </div>
        </div>
      </header>

      <!-- Services -->
      <Service> </Service>

      <!--PortFolio Grid -->
      <Portfolio> </Portfolio>

      <!-- About -->
      
      <!-- Team -->
      <Asociaciones></Asociaciones> 

      <!-- Clients 
      
      <section class="py-5">
        <div class="container">
          <div class="row">
            <div class="col-md-3 col-sm-6">
              <a href="#">
                <img class="img-fluid d-block mx-auto" src="img/logos/envato.jpg" alt />
              </a>
            </div>
            <div class="col-md-3 col-sm-6">
              <a href="#">
                <img class="img-fluid d-block mx-auto" src="img/logos/designmodo.jpg" alt />
              </a>
            </div>
            <div class="col-md-3 col-sm-6">
              <a href="#">
                <img class="img-fluid d-block mx-auto" src="img/logos/themeforest.jpg" alt />
              </a>
            </div>
            <div class="col-md-3 col-sm-6">
              <a href="#">
                <img class="img-fluid d-block mx-auto" src="img/logos/creative-market.jpg" alt />
              </a>
            </div>
          </div>
        </div>
      </section> 
      -->

      <!-- Contact -->
      <section class="page-section" id="contact">
        <div class="container">
          <div class="row">
            <div class="col-lg-12 text-center">
              <h2 class="section-heading text-uppercase">Contacto</h2>
              <h3 class="section-subheading text-muted">Escríbeme si tienes alguna duda</h3>
            </div>
          </div>
          <div class="row">
            <div class="col-lg-12">
              <form id="contactForm" name="sentMessage" novalidate="novalidate">
                <div class="row">
                  <div class="col-md-6">
                    <div class="form-group">
                      <input
                        class="form-control"
                        id="name"
                        type="text"
                        placeholder="Nombre completo *"
                        required="required"
                        data-validation-required-message="Please enter your name."
                      />
                      <p class="help-block text-danger"></p>
                    </div>
                    <div class="form-group">
                      <input
                        class="form-control"
                        id="email"
                        type="email"
                        placeholder="Email *"
                        required="required"
                        data-validation-required-message="Please enter your email address."
                      />
                      <p class="help-block text-danger"></p>
                    </div>
                    <div class="form-group">
                      <input
                        class="form-control"
                        id="phone"
                        type="tel"
                        placeholder="Número de teléfono *"
                        required="required"
                        data-validation-required-message="Please enter your phone number."
                      />
                      <p class="help-block text-danger"></p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="form-group">
                      <textarea
                        class="form-control"
                        id="message"
                        placeholder="Escribe tu mensaje *"
                        required="required"
                        data-validation-required-message="Please enter a message."
                      ></textarea>
                      <p class="help-block text-danger"></p>
                    </div>
                  </div>
                  <div class="clearfix"></div>
                  <div class="col-lg-12 text-center">
                    <div id="success"></div>
                    <button
                      id="sendMessageButton"
                      class="btn btn-primary btn-xl text-uppercase"
                      type="submit"
                    >Enviar</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </section>

      <!-- Footer -->
      <footer class="footer">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-md-4">
              <span class="copyright">Copyright &copy; Your Website 2019</span>
            </div>
            <div class="col-md-4">
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
            <div class="col-md-4">
              <ul class="list-inline quicklinks">
                <li class="list-inline-item">
                  <a href="#">Privacy Policy</a>
                </li>
                <li class="list-inline-item">
                  <a href="#">Terms of Use</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </footer>

      <!-- Portfolio Modals -->

      <!-- Modal 1 -->
      <div
        class="portfolio-modal modal fade"
        id="portfolioModal1"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
              <div class="lr">
                <div class="rl"></div>
              </div>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-8 mx-auto">
                  <div class="modal-body">
                    <!-- Project Details Go Here -->
                    <h2 class="text-uppercase">Project Name</h2>
                    <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                    <img class="img-fluid d-block mx-auto" src="img/portfolio/01-full.jpg" alt />
                    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                    <ul class="list-inline">
                      <li>Date: January 2017</li>
                      <li>Client: Threads</li>
                      <li>Category: Illustration</li>
                    </ul>
                    <button class="btn btn-primary" data-dismiss="modal" type="button">
                      <i class="fas fa-times"></i>
                      Close Project
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Modal 2 -->
      <div
        class="portfolio-modal modal fade"
        id="portfolioModal2"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
              <div class="lr">
                <div class="rl"></div>
              </div>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-8 mx-auto">
                  <div class="modal-body">
                    <!-- Project Details Go Here -->
                    <h2 class="text-uppercase">Project Name</h2>
                    <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                    <img class="img-fluid d-block mx-auto" src="img/portfolio/02-full.jpg" alt />
                    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                    <ul class="list-inline">
                      <li>Date: January 2017</li>
                      <li>Client: Explore</li>
                      <li>Category: Graphic Design</li>
                    </ul>
                    <button class="btn btn-primary" data-dismiss="modal" type="button">
                      <i class="fas fa-times"></i>
                      Close Project
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Modal 3 -->
      <div
        class="portfolio-modal modal fade"
        id="portfolioModal3"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
              <div class="lr">
                <div class="rl"></div>
              </div>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-8 mx-auto">
                  <div class="modal-body">
                    <!-- Project Details Go Here -->
                    <h2 class="text-uppercase">Project Name</h2>
                    <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                    <img class="img-fluid d-block mx-auto" src="img/portfolio/03-full.jpg" alt />
                    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                    <ul class="list-inline">
                      <li>Date: January 2017</li>
                      <li>Client: Finish</li>
                      <li>Category: Identity</li>
                    </ul>
                    <button class="btn btn-primary" data-dismiss="modal" type="button">
                      <i class="fas fa-times"></i>
                      Close Project
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Modal 4 -->
      <div
        class="portfolio-modal modal fade"
        id="portfolioModal4"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
              <div class="lr">
                <div class="rl"></div>
              </div>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-8 mx-auto">
                  <div class="modal-body">
                    <!-- Project Details Go Here -->
                    <h2 class="text-uppercase">Project Name</h2>
                    <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                    <img class="img-fluid d-block mx-auto" src="img/portfolio/04-full.jpg" alt />
                    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                    <ul class="list-inline">
                      <li>Date: January 2017</li>
                      <li>Client: Lines</li>
                      <li>Category: Branding</li>
                    </ul>
                    <button class="btn btn-primary" data-dismiss="modal" type="button">
                      <i class="fas fa-times"></i>
                      Close Project
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Modal 5 -->
      <div
        class="portfolio-modal modal fade"
        id="portfolioModal5"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
              <div class="lr">
                <div class="rl"></div>
              </div>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-8 mx-auto">
                  <div class="modal-body">
                    <!-- Project Details Go Here -->
                    <h2 class="text-uppercase">Project Name</h2>
                    <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                    <img class="img-fluid d-block mx-auto" src="img/portfolio/05-full.jpg" alt />
                    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                    <ul class="list-inline">
                      <li>Date: January 2017</li>
                      <li>Client: Southwest</li>
                      <li>Category: Website Design</li>
                    </ul>
                    <button class="btn btn-primary" data-dismiss="modal" type="button">
                      <i class="fas fa-times"></i>
                      Close Project
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Modal 6 -->
      <div
        class="portfolio-modal modal fade"
        id="portfolioModal6"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
              <div class="lr">
                <div class="rl"></div>
              </div>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-8 mx-auto">
                  <div class="modal-body">
                    <!-- Project Details Go Here -->
                    <h2 class="text-uppercase">Project Name</h2>
                    <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                    <img class="img-fluid d-block mx-auto" src="img/portfolio/06-full.jpg" alt />
                    <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                    <ul class="list-inline">
                      <li>Date: January 2017</li>
                      <li>Client: Window</li>
                      <li>Category: Photography</li>
                    </ul>
                    <button class="btn btn-primary" data-dismiss="modal" type="button">
                      <i class="fas fa-times"></i>
                      Close Project
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>

import Portfolio from './components/Portfolio'
import Service from './components/Service'
import Asociaciones from './components/Asociaciones'

export default {
  name: "app",
  components: {
    Portfolio, Service, Asociaciones
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
