# gm-styler
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GM Styler</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white">

  <!-- Header -->
  <header class="bg-black shadow-lg">
    <div class="max-w-7xl mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold text-blue-500">GM Styler</h1>
      <nav class="space-x-4">
        <a href="#loja" class="hover:text-blue-400">Loja</a>
        <a href="#shopee" class="hover:text-blue-400">Shopee</a>
        <a href="#ofertas" class="hover:text-blue-400">Ofertas</a>
        <a href="#sobre" class="hover:text-blue-400">Sobre</a>
        <a href="#contato" class="hover:text-blue-400">Contato</a>
      </nav>
    </div>
  </header>

  <!-- Banner -->
  <section class="bg-gradient-to-r from-blue-700 to-gray-800 text-center py-16">
    <h2 class="text-4xl font-bold mb-4">Os melhores produtos de academia com os menores preços!</h2>
    <p class="text-lg">GM Styler — Seu treino começa com economia!</p>
  </section>

  <!-- Loja -->
  <section id="loja" class="max-w-7xl mx-auto p-6">
    <h3 class="text-3xl font-bold mb-6 text-blue-400">Loja GM Styler</h3>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <div class="bg-gray-800 p-4 rounded-2xl shadow">
        <h4 class="text-xl font-semibold">Halter Ajustável</h4>
        <p class="text-gray-400">Ideal para treino em casa</p>
        <button class="mt-3 bg-blue-500 px-4 py-2 rounded">Adicionar ao carrinho</button>
      </div>
      <div class="bg-gray-800 p-4 rounded-2xl shadow">
        <h4 class="text-xl font-semibold">Roupa Esportiva</h4>
        <p class="text-gray-400">Conforto e estilo</p>
        <button class="mt-3 bg-blue-500 px-4 py-2 rounded">Adicionar ao carrinho</button>
      </div>
      <div class="bg-gray-800 p-4 rounded-2xl shadow">
        <h4 class="text-xl font-semibold">Whey Protein</h4>
        <p class="text-gray-400">Alta performance</p>
        <button class="mt-3 bg-blue-500 px-4 py-2 rounded">Adicionar ao carrinho</button>
      </div>
    </div>
  </section>

  <!-- Shopee Afiliados -->
  <section id="shopee" class="bg-gray-800 p-6">
    <div class="max-w-7xl mx-auto">
      <h3 class="text-3xl font-bold mb-6 text-blue-400">Afiliados Shopee</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-gray-900 p-4 rounded-2xl">
          <h4 class="text-lg">Kit Academia Completo</h4>
          <p class="text-green-400">Desconto exclusivo</p>
          <a href="#" target="_blank" class="block mt-3 bg-green-500 text-center py-2 rounded">Compre Agora</a>
        </div>
        <div class="bg-gray-900 p-4 rounded-2xl">
          <h4 class="text-lg">Corda de Pular</h4>
          <p class="text-green-400">Preço baixo</p>
          <a href="#" target="_blank" class="block mt-3 bg-green-500 text-center py-2 rounded">Compre Agora</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Ofertas -->
  <section id="ofertas" class="max-w-7xl mx-auto p-6">
    <h3 class="text-3xl font-bold mb-6 text-blue-400">Ofertas do Dia</h3>
    <div class="bg-gray-800 p-4 rounded-2xl">
      <p>🔥 Promoção especial com até 50% OFF!</p>
    </div>
  </section>

  <!-- Sobre -->
  <section id="sobre" class="bg-gray-800 p-6">
    <div class="max-w-5xl mx-auto">
      <h3 class="text-3xl font-bold mb-4 text-blue-400">Sobre Nós</h3>
      <p class="text-gray-300">A GM Styler nasceu com o objetivo de oferecer os melhores produtos fitness com os menores preços do mercado. Trabalhamos com curadoria e integração com afiliados para garantir qualidade e economia.</p>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="max-w-5xl mx-auto p-6">
    <h3 class="text-3xl font-bold mb-4 text-blue-400">Contato</h3>
    <form class="space-y-4">
      <input type="text" placeholder="Seu nome" class="w-full p-2 rounded bg-gray-800" />
      <input type="email" placeholder="Seu email" class="w-full p-2 rounded bg-gray-800" />
      <textarea placeholder="Mensagem" class="w-full p-2 rounded bg-gray-800"></textarea>
      <button class="bg-blue-500 px-4 py-2 rounded">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-black text-center p-4">
    <p>© 2026 GM Styler - Todos os direitos reservados</p>
  </footer>

</body>
</html>
