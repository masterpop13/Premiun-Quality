<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Concesionaria Autos Premium</title>
    <!-- Agregar Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
        <style>
        .navbar-nav .nav-link {
            padding-top: 0.75rem;
            padding-bottom: 0.75rem;
        }

        .nav-item {
            margin: 0;
            padding: 0;
        }

        .nav-link {
            font-size: 1rem;
        }
    </style>

</head>
<body>

   <!-- Barra de navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Autos Premium</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
            
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Inventario</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Financiación</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Carrusel de imágenes -->
    <div id="carouselExample" class="carousel slide mt-4" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="/imagenes/S10-2-removebg-preview.png" d-block w-100" alt="Auto 1">
            </div>
            <div class="carousel-item">
                <img src="/imagenes/Fiorino-9-removebg-preview.png" alt="Auto 2">
            </div>
            <div class="carousel-item">
                <img src="/imagenes/3-96-removebg-preview.png" class="d-block w-100" alt="Auto 3">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </button>
    </div>

    <!-- Sección de inventario -->
    <div class="container mt-5">
        <h2 class="text-center">Nuestro Inventario</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="auto1.jpg" class="card-img-top" alt="Auto 1">
                    <div class="card-body">
                        <h5 class="card-title">Modelo 2025</h5>
                        <p class="card-text">Un vehículo potente y elegante.</p>
                        <a href="#" class="btn btn-primary">Ver detalles</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="auto2.jpg" class="card-img-top" alt="Auto 2">
                    <div class="card-body">
                        <h5 class="card-title">SUV Premium</h5>
                        <p class="card-text">Comodidad y tecnología avanzada.</p>
                        <a href="#" class="btn btn-primary">Ver detalles</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="auto3.jpg" class="card-img-top" alt="Auto 3">
                    <div class="card-body">
                        <h5 class="card-title">Deportivo 2025</h5>
                        <p class="card-text">Velocidad y diseño innovador.</p>
                        <a href="#" class="btn btn-primary">Ver detalles</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Pie de página -->
    <footer class="bg-dark text-white text-center p-3 mt-5">
        <p>&copy; 2025 Autos Premium | Contacto: info@autospremium.com</p>
    </footer>

    <!-- Agregar Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>

</html>
