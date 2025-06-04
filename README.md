<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jonas Houst Brazilian Barber</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    .whatsapp-fixed {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 100;
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">
  <!-- Header -->
  <header class="bg-black text-white p-6">
    <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
      <h1 class="text-3xl font-bold">Jonas Houst Brazilian Barber</h1>
      <div class="text-sm md:text-base mt-2 md:mt-0">
        <p>📍 Rua Jorge Furtado, 166 - Parque Pavão III - Santo Antônio da Platina</p>
        <p>🕘 Seg a Sáb: 9h às 19h | 📱 (43) 99629-5628</p>
        <p>📸 Instagram: @jonashoustbrazilianbarber</p>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-cover bg-center h-64 md:h-96" style="background-image: url('img/IMG_7001.jpeg');">
    <div class="bg-black bg-opacity-60 w-full h-full flex items-center justify-center">
      <h2 class="text-white text-4xl md:text-6xl font-bold">Estilo e excelência é nosso ponto forte</h2>
    </div>
  </section>

  <!-- Sobre nós -->
  <section class="py-12 px-6 md:px-20">
    <h2 class="text-3xl font-bold mb-4">Sobre a Barbearia</h2>
    <p class="text-lg">A Jonas Houst Brazilian Barber é muito mais que uma barbearia. É um espaço pensado para oferecer conforto, estilo e uma experiência única, com uma decoração inspirada em Londres e atendimento de excelência.</p>
  </section>

  <!-- Serviços -->
  <section class="bg-gray-200 py-12 px-6 md:px-20">
    <h2 class="text-3xl font-bold mb-8 text-center">Nossos Serviços</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
      <div class="bg-white p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-bold mb-2">✂️ Corte Degradê (Fade)</h3>
        <p>Precisão, estilo e tendência para todos os gostos.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-bold mb-2">🧑‍💼 Corte Social</h3>
        <p>Elegância e cuidado para o dia a dia ou ocasiões especiais.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-bold mb-2">🧔 Barbaterapia</h3>
        <p>Barba aparada, hidratada e tratada com produtos de qualidade.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-bold mb-2">🔥 Cera Quente</h3>
        <p>Remoção precisa e duradoura dos pelos indesejados.</p>
      </div>
    </div>
  </section>

  <!-- Galeria -->
  <section class="py-12 px-6 md:px-20">
    <h2 class="text-3xl font-bold mb-8 text-center">Nosso Espaço</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
      <img src="img/IMG_7004.jpeg" alt="Interior da barbearia" class="rounded-xl shadow-lg">
      <img src="img/IMG_7001.jpeg" alt="Fachada da barbearia de dia" class="rounded-xl shadow-lg">
      <img src="img/IMG_7030.jpeg" alt="Fachada da barbearia à noite" class="rounded-xl shadow-lg">
    </div>
  </section>

  <!-- Contato -->
  <section class="bg-black text-white py-12 px-6 md:px-20">
    <h2 class="text-3xl font-bold mb-4">Contato</h2>
    <p class="mb-2">📞 Telefone/WhatsApp: (43) 99629-5628</p>
    <p class="mb-2">📸 Instagram: <a href="https://instagram.com/jonashoustbrazilianbarber" target="_blank" class="underline">@jonashoustbrazilianbarber</a></p>
    <p>📍 Rua Jorge Furtado, 166 - Parque Pavão III - Santo Antônio da Platina</p>
  </section>

  <!-- Botão flutuante do WhatsApp -->
  <a href="https://wa.me/5543996295628" target="_blank" class="whatsapp-fixed">
    <img src="https://img.icons8.com/color/48/000000/whatsapp--v1.png" alt="WhatsApp">
  </a>

  <footer class="bg-gray-800 text-white text-center py-4">
    <p>&copy; 2025 Jonas Houst Brazilian Barber. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
