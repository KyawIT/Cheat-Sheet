<script>
</script>

<header
      class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom bg-white"
    >
      <a
        href="/"
        class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none"
      >
        <svg class="bi me-2" width="40" height="32">
          <use xlink:href="#bootstrap"></use>
        </svg>
        <span class="fs-4">CheatSheet</span>
      </a>
      <ul class="nav nav-pills">
        <li class="nav-item">
          <a href="/" class="nav-link active" aria-current="page">Home</a>
        </li>
        <li class="nav-item"><a href="/RA1" class="nav-link">RA1</a></li>
        <li class="nav-item"><a href="/RA2" class="nav-link">RA2</a></li>
        <li class="nav-item"><a href="/RA3" class="nav-link">RA3</a></li>
      </ul>
    </header>

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