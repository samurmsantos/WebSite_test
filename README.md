<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Completo</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body { font-family: Arial, sans-serif; }
        .hero { background: #007bff; color: white; padding: 100px 0; text-align: center; }
        .section { padding: 50px 0; }
        footer { background: #333; color: white; text-align: center; padding: 10px; margin-top: 20px; }
    </style>
</head>
<body>
    
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Meu Site</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#sobre">Sobre</a></li>
                    <li class="nav-item"><a class="nav-link" href="#servicos">Serviços</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
                </ul>
            </div>
        </div>
    </nav>
    
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Bem-vindo ao Meu Site</h1>
            <p>Um site simples e responsivo feito com HTML, CSS e Bootstrap.</p>
        </div>
    </section>

    <!-- Sobre -->
    <section id="sobre" class="section container">
        <h2>Sobre Nós</h2>
        <p>Somos uma empresa especializada em desenvolvimento web, criando soluções modernas e eficientes.</p>
    </section>
    
    <!-- Serviços -->
    <section id="servicos" class="section bg-light container">
        <h2>Nossos Serviços</h2>
        <ul>
            <li>Desenvolvimento Web</li>
            <li>Marketing Digital</li>
            <li>Consultoria Tecnológica</li>
        </ul>
    </section>

    <!-- Contato -->
    <section id="contato" class="section container">
        <h2>Contato</h2>
        <form>
            <div class="mb-3">
                <label class="form-label">Nome:</label>
                <input type="text" class="form-control" required>
            </div>
            <div class="mb-3">
                <label class="form-label">E-mail:</label>
                <input type="email" class="form-control" required>
            </div>
            <div class="mb-3">
                <label class="form-label">Mensagem:</label>
                <textarea class="form-control" rows="4" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
    </section>
    
    <!-- Rodapé -->
    <footer>
        <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
    </footer>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
