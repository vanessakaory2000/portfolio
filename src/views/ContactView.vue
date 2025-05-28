<template>
    <section class="max-w-3xl mx-auto p-6 bg-white rounded-lg shadow-lg mt-12">
      <h2 class="text-4xl font-semibold text-center mb-8 text-gray-800">Contato</h2>
      
      <form class="space-y-6">
        <div>
          <label class="block text-lg font-semibold text-gray-700" for="nome">Nome</label>
          <input id="nome" type="text" class="w-full px-4 py-3 mt-2 border rounded focus:ring-2 focus:ring-blue-300 focus:outline-none" placeholder="Digite seu Nome" />
        </div>
  
        <div>
          <label class="block text-lg font-semibold text-gray-700" for="email">E-mail</label>
          <input id="email" type="text" class="w-full px-4 py-3 mt-2 border rounded focus:ring-2 focus:ring-blue-300 focus:outline-none" placeholder="Digite seu E-mail" />
        </div>
  
        <div>
          <label class="block text-lg font-semibold text-gray-700" for="mensagem">Mensagem</label>
          <textarea id="mensagem" class="w-full px-4 py-3 mt-2 border rounded focus:ring-2 focus:ring-blue-300 focus:outline-none" rows="4" placeholder="Digite sua Mensagem"></textarea>
        </div>
  
        <button type="submit" class="w-full bg-blue-600 text-white py-3 rounded hover:bg-blue-700">
          Enviar
        </button>
      </form>
      
      <div class="mt-12 text-center">
        <h3 class="text-2xl font-semibold text-gray-800 mb-6">Redes Sociais</h3>
        <ul class="flex justify-center space-x-8">
          <li><a href="https://github.com/vanessakaory2000" target="_blank" class="text-gray-700 hover:text-gray-900">GitHub</a></li>
          <li><a href="https://www.linkedin.com/in/vanessa-kurauchi-385466257/" target="_blank" class="text-gray-700 hover:text-gray-900">LinkedIn</a></li>
        </ul>
      </div>

      
    </section>
  </template>