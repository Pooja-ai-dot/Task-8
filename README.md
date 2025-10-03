# Task-8
## Task 8: Create a Simple Blog Layout Using Bootstrap 5.
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pooja's Blog</title>
  <!-- Bootstrap 5 CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand" href="#">Pooja's Blog</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Blog Cards -->
  <div class="container my-5">
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="Blog Image">
          <div class="card-body">
            <h5 class="card-title">Building a To-Do App</h5>
            <p class="card-text">Learn how I built a responsive To-Do List using HTML, CSS, and JavaScript.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="Blog Image">
          <div class="card-body">
            <h5 class="card-title">REST API with Node.js</h5>
            <p class="card-text">A breakdown of how I created a book management API using Express and Postman.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="Blog Image">
          <div class="card-body">
            <h5 class="card-title">Understanding Flexbox</h5>
            <p class="card-text">A visual guide to mastering Flexbox layout for responsive design.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">© 2025 Pooja | Built with Bootstrap 5</p>
  </footer>

  <!-- Bootstrap JS Bundle -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
