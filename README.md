<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css"
    />
    <link rel="stylesheet" href="projekbootstrap.css" />
    <style></style>
    <title>Mari travel</title>
  </head>
  <body>
    <script
      src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js"
      integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.min.js"
      integrity="sha384-Rx+T1VzGupg4BHQYs2gCW9It+akI2MM/mndMCy36UVfodzcJcF0GGLxZIzObiEfa"
      crossorigin="anonymous"
    ></script>

    <nav
      class="navbar bg-dark border-bottom border-body fixed-top"
      data-bs-theme="dark"
    >
      <div class="container-fluid">
        <a class="navbar-brand" href="#"
          ><span class="text-primary">Gabriel</span>Travel</a
        >
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About us</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <section
      class="header bg-light tetex-center text-sm-start pt-5 pb-5 pb-lg-0 mt-5 text-dark"
    >
      <div class="container">
        <img src="images/homepage.svg" class="img-fluid h-100" z />
        <div>
          <h1>
            <span class="text-primary">Ayo</span> jalan jalan,<span
              class="text-primary"
              >Ayo</span
            >
            refreshing
          </h1>
          <p>jiwa sehat kepada orang yang sering healing</p>
          <div class="d-grid gap-2 d-md-block">
            <button class="btn btn-primary" type="button">Yuk Berangkat</button>
          </div>
        </div>
      </div>
    </section>

    <!-- ISI KONTEN TRAVELING -->

    <section class="p-5" id="Services">
      <div class="container">
        <div class="row text-center g-4">
          <div class="col-md">
            <div class="card">
              <img
                src="images/pesawat.svg"
                class="p-2 card-img-top"
                alt="..."
              />
              <div class="card-body bg-info text-light">
                <h5 class="card-title">Transport</h5>
                <p class="card-text">
                  perjalanan jauh terasa nyaman,Ayo boking transportasi mu...
                </p>
                <a href="#" class="btn btn-primary">Pesan tiket</a>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="images/hotel.svg" class="p-2 card-img-top" alt="..." />
              <div class="card-body bg-info text-light">
                <h5 class="card-title">Hotel</h5>
                <p class="card-text">
                  mau nginep gausah ribet lagi,tersedia banyak hotel dan motel
                  di dekatmu
                </p>
                <a href="#" class="btn btn-primary">Booking hotel</a>
              </div>
            </div>
          </div>
          <div class="col-md">
            <div class="card">
              <img src="images/wisata.svg" class="p-2card-img-top" alt="..." />
              <div class="card-body bg-info text-light">
                <h5 class="card-title">Tour</h5>
                <p class="card-text">
                  berbagai pilihan tempat wisata yang bisa kau pilih bersama
                  keluarga,teman dan pacar
                </p>
                <a href="#" class="btn btn-primary">jalan jalan </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Promoo Content -->

    <section class="bg-primary text-light p-5" id="promo">
      <div class="container">
        <div class="d-md-flex justify-content-between align-items-center">
          <h3>Dapatkan promo menarik</h3>

          <div class="input-group">
            <input
              type="text"
              class="form-control"
              placeholder="masukan email anda"
            />
            <button class="btn btn-light-btn-lg bg-info" type="button">
              submit
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact us -->

    <section class="p-5" id="contact">
      <div class="container">
        <div class="row g-4 align-items-center">
          <div class="col-md">
            <h2 class="text-center mb-4">Contact Us</h2>
            <ul class="list-group list-group-flush lead">
              <li class="list-group-item">
                <span class="fw-bold"
                  ><span><i class="bi bi-geo-alt-fill"></i></span
                  >Location:</span
                >
                <br />
                Jl.Dirgantara,IV Yogyakarta
              </li>
              <li class="list-group-item">
                <span class="fw-bold"
                  ><span><i class="bi bi-telephone"></i></span>Mobile
                  Phone:</span
                >
                <br />
                (+)62 812 7186 5371
              </li>
              <li class="list-group-item">
                <span class="fw-bold"
                  ><span><i class="bi bi-instagram"></i></span>Instagram</span
                >
                <br />
                @bakso.bulat.dikukus
              </li>
              <li class="list-group-item">
                <span class="fw-bold"
                  ><span><i class="bi bi-envelope-at"></i></span>Email</span
                >
                <br />
                gabrielhandrajati@gmail.com
              </li>
            </ul>
          </div>
          <div class="col-md">
            <img src="images/contactus.svg" class="img-fluid h-100" z />
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->

    <footer class="p-5 bg-dark text-white text-center position-relative">
      <div class="container">
        <p class="lead">Copyright &copy; 2023 gabrielindustries.com</p>
        <a href="#" class="position-absolute bottom-0 end-0 p-5">
          <i class="bi bi-arrow-up-circle-fill"></i>
        </a>
      </div>
    </footer>
  </body>
</html>
