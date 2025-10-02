<template>
  <section id="inicio" class="relative h-screen pt-16 bg-gray-100">
    <div class="absolute inset-0">
      <img src="@/assets/img/fondo_hero.jpg" alt="Fondo" class="w-full h-full object-cover">
      <div class="absolute inset-0 bg-black opacity-60"></div>
    </div>
    <div class="relative container mx-auto px-4 h-full flex items-center">
      <div class="text-white max-w-4xl">
        <h1 class="text-5xl md:text-7xl font-bold mb-4">
          Defendemos Tus<br>
          <span class="text-amber-400">Derechos Laborales</span>
        </h1>
        <p class="text-xl md:text-2xl mb-8 max-w-3xl">
          Más de 15 años de experiencia en derecho laboral. Asesoría especializada, representación legal y defensa de tus derechos como trabajador o empleador.
        </p>
        <div class="flex flex-wrap gap-4">
          <a href="#contacto" class="bg-amber-500 hover:bg-amber-600 text-white font-bold py-3 px-6 rounded transition-colors inline-flex items-center">
            <span class="mr-2">Consulta Gratuita</span>
          </a>
          <a href="#servicios" class="bg-transparent border-2 border-white hover:bg-white hover:text-gray-900 text-white font-bold py-3 px-6 rounded transition-all inline-flex items-center">
            <span class="mr-2">Conocer Servicios</span>
          </a>
        </div>

        <!-- Estadísticas -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-16">
          <div class="text-center">
            <div class="text-4xl font-bold text-amber-400">500+</div>
            <div class="text-sm mt-2">Casos Exitosos</div>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-amber-400">15+</div>
            <div class="text-sm mt-2">Años de Experiencia</div>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-amber-400">98%</div>
            <div class="text-sm mt-2">Satisfacción del Cliente</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>