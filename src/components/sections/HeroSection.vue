<template>
  <section id="inicio" class="relative h-screen pt-16 bg-gray-100">
    <div class="absolute inset-0">
      <img src="@/assets/img/fondo_hero.jpg" alt="Fondo" class="w-full h-full object-cover">
      <div class="absolute inset-0 bg-black opacity-50"></div>
    </div>
    <div class="relative container mx-auto px-4 h-full flex items-center">
      <div class="text-white max-w-2xl">
        <h1 class="text-4xl md:text-6xl font-bold mb-4">
          Oscar Guzman Abogados
        </h1>
        <p class="text-xl md:text-2xl mb-8">
          Expertos en derecho, comprometidos con tu justicia
        </p>
        <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition-colors">
          Contáctanos
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>