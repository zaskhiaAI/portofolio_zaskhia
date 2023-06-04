<template>
    <!-- NAVBAR START  -->
    <nav
      id="home"
      class="navbar navbar-expand-lg navbar-dark bg-transparent mt-4"
    >
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-10 offset-1">
            <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav">
                <li class="nav-item mx-3">
                  <a class="nav-link active" aria-current="page" href="#home"
                    >Home</a
                  >
                </li>
                <li class="nav-item mx-3">
                  <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item mx-3">
                  <a class="nav-link" href="#project">Projects</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <!-- NAVBAR END -->

    <!-- HERO START -->
    <section id="hero">
      <div class="container">
        <div class="row position-relative">
          <div class="col-6 offset-1 my-auto">
            <h2>Hai Guys</h2>
            <h1 class="fw-bold">I am Zaskhia Artina Isnalifah</h1>
            <p>
              Grapic Designer || UI / UI Designer || Web Designer <br />
              Seorang mahasiswa yang tertarik di bidang web developer.
              <span class="color-acsent">Web programming susah yah ? Iya.</span>
            </p>

            <a href="#about" target="_blank"
              ><button class="button-custom" type="button">About Me</button></a
            >

            <div class="button_social">
              <a
                href="https://wa.me/085736469156"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-whatsapp-fill fs-4 mx-1"></i>
              </a>
              <a
                href="https://www.instagram.com/zskhrtina__/?hl=id"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-instagram-fill fs-4 mx-1"></i>
              </a>
              <a
                href="https://www.linkedin.com/in/zaskhia-artina-isnalifah-7026b2249/"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-linkedin-box-fill fs-4 mx-1"></i>
              </a>
              <a
                href="https://github.com/zaskhiaAI"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-github-fill fs-4 mx-1"></i>
              </a>
            </div>

            <a href="pdf/Zaskhia_cv.pdf" class="button text-decoration-none cv">
              Download
              <span class="color-acsent">Curiculum Vitae</span>
            </a>
          </div>
          <div class="col-5 justify-content-center">
            <div class="hero-profile">
              <div class="hero-border">
                <a href=""><img src="frontend/img/meprofile.png" width="100%" class="img-hero" alt=""></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- HERO END -->

    <!-- ABOUT START -->
    <section id="about">
      <div class="container-fluid">
        <div class="container">
          <div class="row justify-content-center mb-4">
            <div class="col-10">
              <h1 class="text-center fw-semibold">About</h1>
              <hr />
            </div>
            <div class="col-10 mt-3">
              <p class="text-center color-acsent">
                "Teknologi adalah media, positif atau tidak tergantung
                pemakainya"
              </p>
              <p class="text-center text-white">
                Saya mahasiswa semester 6 jurusan teknik informatika, saait ini
                sedang kuliah di kampus Universitas Negeri Surabaya. Mampu
                bekerja secara individu maupun kelompok. memiliki keterkaitan di
                bidang teknologi informasi.
              </p>
            </div>
            <a href="#about" target="_blank"><center><button class="center button-custom" type="button">About Me</button></center></a
            >
          </div>
        </div>
      </div>
    </section>
    <!-- ABOUT END -->

    <!-- PROJECT START -->
    <section id="project">
      <div class="container-fluid">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-10">
              <h1 class="text-center fw-semibold">Project</h1>
              <hr />
            </div>
          </div>
          <div class="row justify-content-center mt-3">
            <div class="col-3">
              <div class="card p-4">
                <div class="row">
                  <a href=""><img src="frontend/img/project1.jpg" width="50%" alt="" /></a>
                  <div class="col">
                    <h3>Web Programming</h3>
                    <p>Tugas Analisis 1</p>
                    <a href="frontend/pdf/Zaskhia Artina Isnalifah_Tugas Analisis 1.pdf"
                      ><button class="button-custom">Read More</button></a
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="col-3">
              <div class="card p-4">
                <div class="row">
                  <a href=""><img src="frontend/img/project1.jpg" width="50%" alt="" /></a>
                  <div class="col">
                    <h3>Web Programming</h3>
                    <p>Tugas Analisis 2</p>
                    <a href="frontend/pdf/Zaskhia Artina Isnalifah_Tugas Analisis 2.pdf"
                      ><button class="button-custom">Read More</button></a
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="col-3">
              <div class="card p-4">
                <div class="row">
                  <a href=""><img src="frontend/img/project1.jpg" width="50%" alt="" /></a>
                  <div class="col">
                    <h3>Web Programming</h3>
                    <p>Tugas Analisis 3</p>
                    <a href="frontend/pdf/Zaskhia Artina Isnalifah_Tugas Analisis 2.pdf"
                      ><button class="button-custom">Read More</button></a
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- PROJECT END -->

    <!-- FOOTER START -->
    <footer class="footer py-2">
      <div class="container">
        <div class="row">
          <div class="co-12 text-center">
            <p class="text-center text-white mt-3">
              Thank For Scrolling, That's All Folks
            </p>
            <div class="button-social-footer">
              <a
                href="https://wa.me/085736469156"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-whatsapp-fill fs-4 mx-1"></i>
              </a>
              <a
                href="https://www.instagram.com/zskhrtina__/?hl=id"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-instagram-fill fs-4 mx-1"></i>
              </a>
              <a
                href="https://www.linkedin.com/in/zaskhia-artina-isnalifah-7026b2249/"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-linkedin-box-fill fs-4 mx-1"></i>
              </a>
              <a
                href="https://github.com/zaskhiaAI"
                target="_blank"
                class="button button_social button_grey"
              >
                <i class="ri-github-fill fs-4 mx-1"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </footer>
    <!-- FOOTER END -->
</template>

<script>
export default {
  name: 'MasterView'
}
</script>

<style>
</style>
