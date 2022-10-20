<script>
</script>


<nav class="navbar navbar-expand-lg bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="/">Cheat Sheet</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
              <a class="nav-link" href="/ra1">RA1</a>
        </li>
        <li class="nav-item">
              <a class="nav-link" href="/ra2">RA2</a>
        </li>
        <li class="nav-item">
              <a class="nav-link" href="/ra3">RA3</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/css">CSS</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<main>
	<slot />
</main>

<footer
      class="d-flex flex-wrap justify-content-between align-items-center py-3 mt-4 border-top bg-white"
    >
      <p class="col-md-4 mb-0 text-muted">© 2022 KHH, Inc</p>

      <a
        href="/"
        class="col-md-4 d-flex align-items-center justify-content-center mb-3 mb-md-0 me-md-auto link-dark text-decoration-none"
      >
        <svg class="bi me-2" width="40" height="32">
          <use xlink:href="#bootstrap"></use>
        </svg>
      </a>

      <ul class="nav col-md-4 justify-content-end">
        <li class="nav-item">
          <a href="/" class="nav-link px-2 text-muted">Home</a>
        </li>
      </ul>
</footer>