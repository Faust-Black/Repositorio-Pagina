<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>GYM-BRO | Login</title>
  <link rel="stylesheet" href="style.css"> <!-- mismo estilo del header -->
    
</head>
<body>

  <header>
    <div class="logo">
      <a href="index.html">
        <img src="Imagenes/LogoGymBro.png" height="100" width="100" alt="Logo GYM-BRO">
      </a>
    </div>
    <div class="nav-links">
      <a href="index.html">Inicio</a>
      <a href="membresias.html">Membresías</a>
      <a href="login.html">Inicia sesión<br>Regístrate</a>
    </div>
  </header>

  <main class="auth-container">
  <div class="login-card">
    <h1>Iniciar Sesión</h1>
    <form action="login.php" method="POST">
      <input type="email" name="email" placeholder="Correo electrónico" required>
      <input type="password" name="password" placeholder="Contraseña" required>
      <button type="submit" class="btn btn--block">Ingresar</button>
    </form>
    <p>¿No tienes cuenta? <a href="signin.html">Regístrate aquí</a></p>
  </div>
</main>

</body>
</html>
