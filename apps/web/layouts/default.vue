<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand" href="/">Start Bootstrap</a>
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
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/post">Sample Post</a>
            </li>
            <!-- <li class="nav-item">
              <a class="nav-link" href="/test">Nest.jsのtestページ</a>
            </li> -->
          </ul>
        </div>
      </div>
    </nav>
	<!-- このnuxtにpages/〇〇.vueの中身が展開される -->
    <nuxt />
	<!-- このnuxtに〇〇.vueの中身が展開される -->
    <hr />
    <!-- Footer -->
	<footer>
      <div class="container">
        <div class="row">
          <div class="col-lg-8 col-md-10 mx-auto">
            <p class="copyright text-muted">Copyright &copy; Your Website 3019</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
a {
  color: #212529;
  transition: all 0.2s;
}

#mainNav {
  position: absolute;
  border-bottom: 1px solid #e9ecef;
  background-color: white;
  font-family: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
}

footer {
  padding: 50px 0 65px;
  text-align: center;
}
</style>
