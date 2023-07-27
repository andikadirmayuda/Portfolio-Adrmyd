# Portfolio-AndikaDirmaYuda
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio | Adrmyd</title>
    <!-- boostrap css -->
    <link rel="stylesheet" href="vendors/boostrap/css/bootstrap.min.css" />
    <!-- boxicons -->
    <link rel="stylesheet" href="vendors/boxicons/css/boxicons.min.css" />
    <!-- swiperjs -->
    <link rel="stylesheet"href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css"/>
    <!-- Feather  -->
    <script src="https://unpkg.com/feather-icons"></script>
    <!-- css -->
    <link rel="stylesheet" href="styles/style.css" />
  </head>
  <body>
    <!-- NAVBAR -->
    <nav class="navbar navbar-expand-md">
      <div class="container">
        <a class="navbar-brand fw-bold ms-5 text-white" href="#">@adrmyd</a>
        
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link text-white" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#portfolio">Portofolio</a>
            </li>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#skills">Skills</a>
            </li>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#Timeline">Timeline</a>
            </li>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#News">News</a>
            </li>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white " href="#Contact">Contact</a>
            </li>
          </ul>
          
        </div>
      </div>
    </nav>
  <!-- HEADER -->
  <section class="header-section " id="header">
    <div class="div container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <p class="text-orange fw-semibold">Hai,</p>
          <h1 class="header-title  fw-semibold text-white"> I'am <br>Andika Dirma Yuda</h1>
          <br>
          <a href="#" class="header-skill d-inline-flex align-items-center gap-2">Web Development<i class=" fs-4"></i></a> <br>
          <a href="#" class="header-skill d-inline-flex align-items-center gap-2">Graphic Designer<i class="fs-4"></i></a> <br>
          <a href="#" class="header-skill d-inline-flex align-items-center gap-2">Adventurer<i class="fs-4"></i></a>

          <div class="d-flex align-items-center gap-5 mt-4">
            <div class="d-flex align-items-center gap-2">
              <h2 class="header-skill fw-bold"></h2>
              <p class="text-secondary fs-7 mb-0" ></p>
            </div>
          </div>
          <div class="d-flex align-items-center gap-5 mt-4">
            <div class="d-flex align-items-center gap-2">
              <h2 class="header-skill fw-bold"></h2>
              <p class="text-secondary fs-7 mb-0" >DON'T FOLLOW ME,</BR>BECAUSE I'M ALSO LOST</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <img src="images/me.jpg" class="header-img justify-content-between" alt="">
        </div>
      </div>
    </div>
  </section>

  <!-- PORTFOLIO -->
      <section class="portfolio-section" id="portfolio">
        <div class="container">
          <div class="row align-items-center justify-content-between">
    
          <p class="text-orange fw-semibold">Portfolio</p>
          <h2 class="section-title text-white mb-5">My Works</h2>

      <!-- swiper -->
      <div class="swiper portofolio-swiper">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/portofolio-1.jpg " alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Study</h6>
                <a href="#" class="text-dark"></a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/portofolio-2.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Make Your Schedule</h6>
                <a href="#" class="text-dark"></a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/portofolio-6.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Drawing</h6>
                <a href="#" class="text-dark"></a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/adventure.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Adventurer</h6>
                <a href="#" class="text-dark"></a>
              </div>
             </div>
            </div>

          
          <br>
        </div>
      </div>
      
      <div class="d-flex align-items-center justify-content-end gap-3 mt-3">
        <button class="btn btn-light d-flex align-items-center justify-content-center btn-next">
          <i class="bx bx-left-arrow-alt fs-5"></i>
        </button>
        <button class="btn btn-light d-flex align-items-center justify-content-center btn-prev">
          <i class="bx bx-right-arrow-alt fs-5"></i>
        </button>
      </div>
  </section>

  <!-- SKILLS -->
  <section class="skills-section" id="skills">
    <div class="container">
      <div class="row align-items-center justify-content-between">
        <div class="col-md-6">
          <p class="fw-semibold">Skills</p>
          <h2 class="section-title text-white mb-5">My Skills</h2>

          <div class="mb-3">
            <div class="d-flex align-items-center justify-content-between mb-2">
              <p class="text-white text-uppercase fw-semiblod mb-0">Nothing</p>
              <p class="text-white text-uppercase mb-0">0%</p>
            </div>
            <div class="progrees-bar">
                <span class="progrees" style="width: 1%"></span>
            </div>
          <div class="mb-3">
            <div class="d-flex align-items-center justify-content-between mb-2">
              <p class="text-white text-uppercase fw-semiblod mb-0">Nothing</p>
              <p class="text-white text-uppercase mb-0">0%</p>
            </div>
            <div class="progrees-bar">
                <span class="progrees" style="width: 1%"></span>
            </div>
          <div class="mb-3">
            <div class="d-flex align-items-center justify-content-between mb-2">
              <p class="text-white text-uppercase fw-semiblod mb-0">Nothing</p>
              <p class="text-white text-uppercase mb-0">0%</p>
            </div>
            <div class="progrees-bar">
                <span class="progrees" style="width: 1%"></span>
            </div>
          </div>
        </div>
      </div>
      </div>
      <div class="foto col-md-5 justify-content-between">
          <img src="images/not.jpg" alt="">
    </div>
      </div>
    </div>
  </section>


  <!-- TIMELINE -->
  <section class="Timeline-section " id="Timeline">
    <div class="container">
      <p class="text-orange fw-semibold">Timeline</p>
      <h2 class="section-title text-white mb-5">Roadmap</h2>
      <div class="row py-3 border-bottom text-white">
        <div class="col-md-4">Sunday</div>
        <div class="col-md-4">Makan</div>
        <div class="col-md-4">Home</div>
      </div>
      <div class="row py-3 border-bottom text-white">
        <div class="col-md-4">Monday</div>
        <div class="col-md-4">Tidur</div>
        <div class="col-md-4">Home</div>
      </div>
      <div class="row py-3 border-bottom text-white">
        <div class="col-md-4">Thusday</div>
        <div class="col-md-4">Makan</div>
        <div class="col-md-4">Home</div>
      </div>
      <div class="row py-3 border-bottom text-white">
        <div class="col-md-4">Everyday</div>
        <div class="col-md-4">Tidur</div>
        <div class="col-md-4">Home</div>
      </div>
    </div>
  </section>

  <!-- NEWS -->
  <section class="News-section" id="News">
    <div class="container">
      <p class="text-orange fw-semibold">News</p>
      <h2 class="section-title text-white mb-5">Latest News</h2>

      <!-- swiper -->
      <div class="swiper portofolio-swiper">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/eat.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Makan</h6>
                <p class="text-black">Everyday</p>
                <a href="#" class="text-dark">Detail News</a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/sleep.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Tidur</h6>
                <p class="text-black">Everyday</p>
                <a href="#" class="text-dark">Detail News</a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/eat.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Makan</h6>
                <p class="text-black">Everyday</p>
                <a href="#" class="text-dark">Detail News</a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/sleep.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Tidur</h6>
                <p class="text-black">Everyday</p>
                <a href="#" class="text-dark">Detail News</a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/eat.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Makan</h6>
                <p class="text-black">Everyday</p>
                <a href="#" class="text-dark">Detail News</a>
              </div>
             </div>
            </div>
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body">
                <img src="images/sleep.jpg" alt="" class="card-img-top rounded mb-3" width="100px">
                <h6 class="fw-semibold">Tidur</h6>
                <p class="text-black">Everyday</p>
                <a href="#" class="text-dark">Detail News</a>
              </div>
             </div>
            </div>
        </div>
      </div>
      
      <div class="d-flex align-items-center justify-content-end gap-3 mt-3">
        <button class="btn btn-light d-flex align-items-center justify-content-center btn-next">
          <i class="bx bx-left-arrow-alt fs-5"></i>
        </button>
        <button class="btn btn-light d-flex align-items-center justify-content-center btn-prev">
          <i class="bx bx-right-arrow-alt fs-5"></i>
        </button>
      </div>
  </section>

  <!-- CONTACT -->
  <section class="Contact-section" id="Contact">
    <div class="container">
      <div class="row align-items-center justify-content-between">

      <p class="text-orange fw-semibold">Contact</p>
      <h2 class="section-title text-white mb-5">Get in touch</h2>
      <p class="text-white mb-3">
        
      </p>

      <div class="d-flex align-items-center gap-2 mb-3">
        <i class="bx bx-map-pin text-white fs-5"></i>
      <div class="mb-0 text-white">Indonesia</div>
      </div>
      <div class="d-flex align-items-center gap-2 mb-3">
        <i class="bx bx-phone-call text-white fs-5"></i>
        <div class="mb-0 text-white">+62 XXX-XXXX-XXXX</div>
      </div>
      <div class="d-flex align-items-center gap-2 mb-3">
        <i class="bx bx-envelope text-white fs-5"></i>
        <div class="mb-0 text-white">aaaaaa21@gmail.com</div>
      </div>
    
        <div class="col-md-5">
          <form action="#">
            <input 
            type="text" 
            name="name" 
            id="name"
            placeholder="name"
            class="form-control rounded-0 mb-2">
            <input 
            type="text" 
            name="email" 
            id="email"
            placeholder="email"
            class="form-control rounded-0 mb-2">
            <textarea 
            name="body" 
            id="body" 
            placeholder="Message" 
            cols="30" 
            rows="3" 
            class="form-control rounded-0 mb-3"></textarea>
  
            <button class="btn btn-orange w-100"><p class="text-center">Submit</p></button>
      </div>
      

      
        </form>
      </div>
      </div>
    </div>

  </section>

  <!-- Footer Start-->
  <footer class="footer bg-black">
    <div class="socials">
      <a href="https://youtube.com/@adrmyd"><i data-feather="youtube"></i></a>
      <a href="https://www.instagram.com/adrmyd"><i data-feather="instagram"></i></a>
      <a href="https://twitter.com/Ngaatau_"><i data-feather="twitter"></i></a>
      <a href="Nothing"><i data-feather="facebook"></i></a>
    </div>

    <div class="links text-white">
      <a href="#">Home</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#skills">Skills</a>
      <a href="#Timeline">Timeline</a>
      <a href="#News">News</a>
      <a href="#Contact">Contact</a>
    </div>

    <div class="credit">
      <p>Create by <a href="">Adrmyd</a> | &copy; 2023</p>
    </div>
  </footer>
  <!-- Footer End-->

  <!-- script swiper -->
  <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
    <!-- Initialize Swiper -->
    <script>
      var swiper = new Swiper(".portofolio-swiper", {
        slidesPerView: 3,
        spaceBetween: 30,
        navigation:{
          nextEl:".btn-prev",
          prevEl:".btn-next",
        },
        breakpoints: {
            320:{
              slidesPerView:2,
              spaceBetween:20,
            },
            480:{
              slidesPerView: 3,
              spaceBetween: 30,
            },
        }
      });
    </script>
    <!-- Feather -->
    <script>
      feather.replace();
    </script>
    <!-- script boostrap -->
    <script src="vendors/boostrap/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
