<template>
  <section id="nosotros" class="py-20 bg-gray-50">
    <div class="container mx-auto px-4">
      <div class="flex flex-col lg:flex-row items-center gap-12">
        <!-- Imagen -->
        <div class="w-full lg:w-1/2 relative">
          <div class="aspect-[4/3] rounded-lg overflow-hidden shadow-[0_0_25px_rgba(0,0,0,0.1)]">
            <img 
              src="@/assets/img/nosotros_img.jpg" 
              alt="Oscar Guzmán Abogado" 
              class="w-full h-full object-cover"
            >
          </div>
        </div>

        <!-- Contenido -->
        <div class="w-full lg:w-1/2">
          <h2 class="text-4xl md:text-5xl font-bold mb-6">
            Sobre Nosotros
          </h2>
          <p class="text-gray-700 mb-6 text-lg">
            Oscar Guzmán Abogados es un despacho jurídico especializado en derecho laboral con más de 15 años de experiencia defendiendo los derechos de trabajadores y empresas.
          </p>
          <p class="text-gray-600 mb-8">
            Nuestro compromiso es brindar asesoría legal de la más alta calidad, con un enfoque personalizado y resultados efectivos. Contamos con un equipo de abogados especializados que se mantienen actualizados en las últimas normativas laborales.
          </p>

          <!-- Estadísticas -->
          <div class="grid grid-cols-2 gap-8 mb-8">
            <div class="text-center">
              <div class="text-4xl font-bold text-amber-500 mb-2">500+</div>
              <div class="text-gray-600">Casos Exitosos</div>
            </div>
            <div class="text-center">
              <div class="text-4xl font-bold text-amber-500 mb-2">98%</div>
              <div class="text-gray-600">Satisfacción</div>
            </div>
          </div>

          <!-- Lista de características -->
          <ul class="space-y-4">
            <li class="flex items-center text-gray-700">
              <svg class="w-5 h-5 text-amber-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                <path d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"/>
              </svg>
              Experiencia comprobada en derecho laboral
            </li>
            <li class="flex items-center text-gray-700">
              <svg class="w-5 h-5 text-amber-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                <path d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"/>
              </svg>
              Atención personalizada y confidencial
            </li>
            <li class="flex items-center text-gray-700">
              <svg class="w-5 h-5 text-amber-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                <path d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"/>
              </svg>
              Resultados efectivos y oportunos
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>