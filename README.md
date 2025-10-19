# about.html[about.html](https://github.com/user-attachments/files/22989241/about.html)
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About — Responsive personal Portfolio website</title>
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header class="bg-light shadow-sm">
    <nav class="container navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand fw-bold" href="index.html">My Responsive Personal Portfolio Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMain">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMain">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link active" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="projects.html">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <main class="container py-5">
    <section class="row align-items-center mb-5">
      <div class="col-md-4 text-center">
        <img src="c:\Users\NIRA\Desktop\cal.jpg" alt="Portrait of Kideganono Lawrence" class="img-fluid rounded-circle shadow-sm" width="222">
      </div>
      <div class="col-md-8">
        <h1 class="display-6">About Me</h1>
        <p class="lead">I am KIDEGANONO LAWRENCE, a front-end developer focused on building accessible, responsive web experiences using HTML5, CSS3, and Bootstrap 5.</p>
        <p>I design clean interfaces, implement responsive layouts, and enjoy learning new web technologies. This portfolio showcases my projects, skills, and contact information.</p>
        <a class="btn btn-primary me-2" href="projects.html">View Projects</a>
        <a class="btn btn-outline-secondary" href="contact.html">Get in touch</a>
      </div>
    </section>

    <section aria-labelledby="skills-heading" class="mb-5">
      <h2 id="skills-heading" class="h4 mb-3">Technical Skills</h2>
      <div class="row g-4">
        <div class="col-md-6">
          <div class="mb-3"><span class="badge bg-info text-dark">HTML5</span></div>
          <div class="progress mb-3" style="height:12px">
            <div class="progress-bar bg-success" role="progressbar" style="width:95%" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100">95%</div>
          </div>

          <div class="mb-3"><span class="badge bg-info text-dark">CSS3</span></div>
          <div class="progress mb-3" style="height:12px">
            <div class="progress-bar bg-success" role="progressbar" style="width:90%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100">90%</div>
          </div>

          <div class="mb-3"><span class="badge bg-info text-dark">Bootstrap 5</span></div>
          <div class="progress" style="height:12px">
            <div class="progress-bar bg-success" role="progressbar" style="width:92%" aria-valuenow="92" aria-valuemin="0" aria-valuemax="100">92%</div>
          </div>
        </div>

        <div class="col-md-6">
          <h3 class="h5">Tools & Workflow</h3>
          <ul class="list-unstyled">
            <li><span class="badge bg-secondary me-2">Git</span> Version control</li>
            <li><span class="badge bg-secondary me-2">VS Code</span> Editor</li>
            <li><span class="badge bg-secondary me-2">Chrome DevTools</span> Debugging</li>
            <li><span class="badge bg-secondary me-2">Figma</span> Design</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="mb-5" aria-labelledby="edu-heading">
      <h2 id="edu-heading" class="h4 mb-3">I studied IT for one and half semester and so I still have little experince but hope to cope up.</h2>
      <div class="row row-cols-1 row-cols-md-2 g-4">
        <article class="col">
          <div class="card h-100">
            <div class="card-body">
              <h3 class="card-title h6">Bachelor of Science in Information Technology</h3>
              <p class="card-text mb-0"><small class="text-muted">Uganda Christian University  — 2025</small></p>
              <p class="mt-2">Focusing on web development, UI/UX, and software design principles.</p>
            </div>
          </div>
        </article>

        <article class="col">
          <div class="card h-100">
            <div class="card-body">
              <h3 class="card-title h6">Frontend Developer</h3>
              <p class="card-text mb-0"><small class="text-muted">Media Lab UCU— 2025</small></p>
              <p class="mt-2">Working on responsive UI components and landing pages using Bootstrap and custom CSS.</p>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section aria-labelledby="image-heading">
      <h2 id="image-heading" class="h4 mb-3">c:\Users\NIRA\Desktop\1ba9e993-3c37-474c-b4ea-fffaeffd6bb2.jpg</h2>
      <div class="ratio ratio-16x9">
        <image controls>
          <source src="assets/image/intro.mp3" type="image/mp3">
        </image>
      </div>
      <p class="mt-2 small text-muted">Focusing on web development, UI/UX, and software design principles.</p>
    </section>
  </main>

  <footer class="bg-dark text-light py-4">
    <div class="container d-flex flex-column flex-md-row justify-content-between align-items-center">
      <p class="mb-2 mb-md-0">© <span id="year"></span>Kideganono Lawrence. God Cares.</p>
      <ul class="list-inline mb-0">
        <li class="list-inline-item"><a class="text-light" href="#" aria-label="LinkedIn">LinkedIn</a></li>
        <li class="list-inline-item"><a class="text-light" href="#" aria-label="GitHub">GitHub</a></li>
        <li class="list-inline-item"><a class="text-light" href="contact.html" aria-label="Contact">Contact</a></li>
      </ul>
    </div>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
 <script>
    document.getElementById('2025').textContent = new Date(17/10/2025).getFullYear(17/10/2025);
  </script>
</body>
</html>
