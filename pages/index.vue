<!-- <style>
@import url("https://fonts.googleapis.com/css2?family=Ysabeau+Office:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&display=swap");
* {
  font-family: "Ysabeau Office", sans-serif;
}
</style> -->
<script></script>

<template>
  <div>
    <!-- header -->
    <nav
      class="navbar navbar-expand-lg navbar-dark bg-dark shadow-sm"
      aria-label="Offcanvas navbar large"
    >
      <!-- <div class="container-md col-lg-9-md col-lg-9 px-4"> -->
      <div class="container-md col-lg-9">
        <a class="navbar-brand" href="#"> My Blog </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="offcanvas"
          data-bs-target="#offcanvasNavbar2"
          aria-controls="offcanvasNavbar2"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="offcanvas offcanvas-start text-bg-dark"
          tabindex="-1"
          id="offcanvasNavbar2"
          aria-labelledby="offcanvasNavbar2Label"
          style="width: 270px"
        >
          <div class="offcanvas-header">
            <h5 class="offcanvas-title" id="offcanvasNavbar2Label">
              <a class="navbar-brand" href="#"> My Blog </a>
            </h5>
            <button
              type="button"
              class="btn-close btn-close-white"
              data-bs-dismiss="offcanvas"
              aria-label="Close"
            ></button>
          </div>
          <div class="offcanvas-body">
            <ul class="navbar-nav justify-content-end flex-grow-1">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item"><a class="nav-link" href="#">About</a></li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Blog</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>

    <!-- Page header with logo and tagline-->
    <header class="py-5 bg-light mb-4 border-bottom">
      <div class="container-md col-lg-9 py-5">
        <div class="text-center my-5">
          <h1 class="fw-bolder">Welcome to My Simple Blog!</h1>
          <p class="lead mb-0">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, ad!
          </p>
        </div>
      </div>
    </header>
    <!-- Page content-->

    <div class="container-md col-lg-9 mt-5">
      <div class="row">
        <div class="col-lg-8">
          <div class="pe-0 pe-lg-4">
            <!-- Featured blog post-->
            <div class="card mb-4 shadow border-0">
              <a href="#"
                ><img
                  class="card-img-top"
                  src="https://dummyimage.com/850x350/dee2e6/6c757d.jpg"
                  alt="..."
              /></a>
              <div class="card-body">
                <div class="small text-muted">January 1, 2022</div>
                <h2 class="card-title">Featured Post Title</h2>
                <p class="card-text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                  Reiciendis aliquid atque, nulla? Quos cum ex quis soluta, a
                  laboriosam. Dicta expedita corporis animi vero voluptate
                  voluptatibus possimus, veniam magni quis!
                </p>
                <a class="btn btn-primary" href="#">Read more →</a>
              </div>
            </div>
            <!-- Nested row for non-featured blog posts-->
            <div class="row">
              <div class="col-lg-6">
                <!-- Blog post-->
                <div class="card border-0 shadow-sm mb-4">
                  <a href="#"
                    ><img
                      class="card-img-top"
                      src="https://dummyimage.com/700x375/dee2e6/6c757d.jpg"
                      alt="..."
                  /></a>
                  <div class="card-body">
                    <div class="small text-muted">January 1, 2023</div>
                    <h2 class="card-title h4">Post Title</h2>
                    <p class="card-text">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                      Reiciendis aliquid atque, nulla.
                    </p>
                    <a class="btn btn-primary" href="#">Read more →</a>
                  </div>
                </div>
                <!-- Blog post-->
                <div class="card border-0 shadow-sm mb-4">
                  <a href="#"
                    ><img
                      class="card-img-top"
                      src="https://dummyimage.com/700x375/dee2e6/6c757d.jpg"
                      alt="..."
                  /></a>
                  <div class="card-body">
                    <div class="small text-muted">January 1, 2023</div>
                    <h2 class="card-title h4">Post Title</h2>
                    <p class="card-text">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                      Reiciendis aliquid atque, nulla.
                    </p>
                    <a class="btn btn-primary" href="#">Read more →</a>
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <!-- Blog post-->
                <div class="card border-0 shadow-sm mb-4">
                  <a href="#"
                    ><img
                      class="card-img-top"
                      src="https://dummyimage.com/700x375/dee2e6/6c757d.jpg"
                      alt="..."
                  /></a>
                  <div class="card-body">
                    <div class="small text-muted">January 1, 2023</div>
                    <h2 class="card-title h4">Post Title</h2>
                    <p class="card-text">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                      Reiciendis aliquid atque, nulla.
                    </p>
                    <a class="btn btn-primary" href="#">Read more →</a>
                  </div>
                </div>
                <!-- Blog post-->
                <div class="card border-0 shadow-sm mb-4">
                  <a href="#"
                    ><img
                      class="card-img-top"
                      src="https://dummyimage.com/700x375/dee2e6/6c757d.jpg"
                      alt="..."
                  /></a>
                  <div class="card-body">
                    <div class="small text-muted">January 1, 2023</div>
                    <h2 class="card-title h4">Post Title</h2>
                    <p class="card-text">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                      Reiciendis aliquid atque, nulla? Quos cum ex quis soluta,
                      a laboriosam.
                    </p>
                    <a class="btn btn-primary" href="#">Read more →</a>
                  </div>
                </div>
              </div>
            </div>
            <!-- Pagination-->
            <nav aria-label="Pagination">
              <hr class="my-0" />
              <ul class="pagination justify-content-center my-4">
                <li class="page-item disabled">
                  <a
                    class="page-link"
                    href="#"
                    tabindex="-1"
                    aria-disabled="true"
                    >Newer</a
                  >
                </li>
                <li class="page-item active" aria-current="page">
                  <a class="page-link" href="#">1</a>
                </li>
                <li class="page-item"><a class="page-link" href="#">2</a></li>
                <li class="page-item"><a class="page-link" href="#">3</a></li>
                <li class="page-item disabled">
                  <a class="page-link" href="#">...</a>
                </li>
                <li class="page-item"><a class="page-link" href="#">15</a></li>
                <li class="page-item">
                  <a class="page-link" href="#">Older</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>

        <div class="col d-lg-none">
          <hr class="my-5" />
        </div>

        <!-- Side widgets-->
        <div class="col-lg-4">
          <div class="position-sticky ps-0 ps-lg-3" style="top: 1.5rem">
            <!-- Search widget-->
            <div class="pb-4">
              <h5 class="fw-bold mb-3">Search Post</h5>
              <div class="input-group">
                <input
                  class="form-control shadow-sm"
                  type="text"
                  placeholder="Enter keyword..."
                  aria-label="Enter search term..."
                  aria-describedby="button-search"
                />
                <button
                  class="btn btn-dark px-4 shadow-sm"
                  id="button-search"
                  type="button"
                >
                  Gas!
                </button>
              </div>
            </div>

            <!-- Related Post -->
            <div class="py-4 mt-2">
              <h5 class="fw-bold mb-4">Popular Posts</h5>
              <div class="d-flex mt-3 pb-2">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">Cara Berinteraksi Sosial Melalui Gmeeet</h6>
                  <div class="small text-muted fst-italic">Feb 3, 22</div>
                </div>
              </div>
              <div class="d-flex mt-3">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">
                    Tutorial Internet Gratis 0p0k No Root Work 100%
                  </h6>
                  <div class="small text-muted fst-italic">Jan 1, 22</div>
                </div>
              </div>
              <div class="d-flex mt-3 pb-2">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">
                    Tutorial Internet Gratis 0p0k No Root Work 100%
                  </h6>
                  <div class="small text-muted fst-italic">Feb 1, 22</div>
                </div>
              </div>
            </div>

            <!-- Popular Post -->
            <div class="py-4 mt-2">
              <h5 class="fw-bold mb-4">Popular Posts</h5>
              <div class="d-flex mt-3 pb-2">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">Cara Berinteraksi Sosial Melalui Gmeeet</h6>
                  <div class="small text-muted fst-italic">Feb 3, 22</div>
                </div>
              </div>
              <div class="d-flex mt-3 pb-2">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">
                    Tutorial Internet Gratis 0p0k No Root Work 100%
                  </h6>
                  <div class="small text-muted fst-italic">Feb 1, 22</div>
                </div>
              </div>
              <div class="d-flex mt-3">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">
                    Tutorial Internet Gratis 0p0k No Root Work 100%
                  </h6>
                  <div class="small text-muted fst-italic">Jan 1, 22</div>
                </div>
              </div>
              <div class="d-flex mt-3 pb-2">
                <div class="flex-shrink-0">
                  <img
                    class="rounded"
                    src="https://dummyimage.com/75x55/ced4da/6c757d.jpg"
                    alt="..."
                  />
                </div>
                <div class="ms-3">
                  <h6 class="mb-0">
                    Tutorial Internet Gratis 0p0k No Root Work 100%
                  </h6>
                  <div class="small text-muted fst-italic">Feb 1, 22</div>
                </div>
              </div>
            </div>

            <!-- Categories widget-->
            <div class="py-4 mt-2">
              <h5 class="fw-bold mb-3">Categories</h5>
              <ul class="list-unstyled m-0 p-0">
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">HTML</div>
                      <div class="col text-end">20</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">CSS</div>
                      <div class="col text-end">15</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">Javascript</div>
                      <div class="col text-end">5</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">Node JS</div>
                      <div class="col text-end">5</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">HTML</div>
                      <div class="col text-end">20</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">CSS</div>
                      <div class="col text-end">15</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">Javascript</div>
                      <div class="col text-end">5</div>
                    </div>
                  </a>
                </li>
                <li class="mb-2 border-bottom">
                  <a class="text-decoration-none text-reset" href="#">
                    <div class="row justify-content-between mb-2">
                      <div class="col text-start">Node JS</div>
                      <div class="col text-end">5</div>
                    </div>
                  </a>
                </li>
              </ul>
            </div>

            <div class="pt-4 pb-5 mt-2">
              <h5 class="fw-bold mb-3">Popular Tags</h5>
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#Olahraga</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#sepakbola</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#sepakbola</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#bulutangksi</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#bolavoli</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#bulutangksi</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#bolavoli</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#sepakbola</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#sepakbola</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#bulutangksi</a
              >
              <a href="#" class="badge border text-reset px-3 py-2 my-1"
                >#bolavoli</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Footer -->
    <footer class="py-5 bg-dark">
      <div class="container-md col-lg-9">
        <div class="text-center text-white mb-2">&copy; Umam Alfarizi 2023</div>
        <p class="small text-center text-light col-lg-6 mx-auto">
          Haloo! Nama saya Umam Alfarizi, saya sedang berkuliah di Universitas
          Mataram dengan program studi Teknik Informatika. Saya mengikuti
          Sekolah Beta Intensif dengan harapan bisa menambah skill dan sekalian
          mencari peluang kerja untuk sambilan kegiatan perkuliahan.
        </p>
      </div>
    </footer>
  </div>
</template>
