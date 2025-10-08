<template>
  <section id="equipo" class="py-20 bg-white">
    <div class="container mx-auto px-4 flex flex-col items-center">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl font-bold mb-4">Nuestro Equipo</h2>
        <p class="text-gray-600 max-w-3xl mx-auto">
          Profesionales altamente calificados con amplia experiencia en derecho laboral
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6 max-w-7xl mx-auto justify-items-center">
        <!-- Oscar Guzmán -->
        <div class="group">
          <div class="bg-white rounded-lg overflow-hidden shadow-[0_0_15px_rgba(0,0,0,0.1)] transition-all duration-300 group-hover:shadow-[0_0_25px_rgba(0,0,0,0.2)] group-hover:-translate-y-2">
            <div class="aspect-[4/5] relative overflow-hidden">
              <img 
                src="@/assets/img/jefe.jpg" 
                alt="Oscar Guzmán" 
                class="w-full h-full object-cover transition-transform duration-300 group-hover:scale-105"
              >
            </div>
            <div class="p-4">
              <h3 class="text-lg font-bold text-gray-900 mb-1">Oscar Guzmán</h3>
              <p class="text-amber-500 font-semibold text-sm mb-2">Socio Fundador</p>
              <p class="text-gray-600 text-sm mb-3">Derecho Laboral y Seguridad Social</p>
              <div class="flex items-center text-gray-500 text-sm">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"/>
                </svg>
                15+ años de experiencia
              </div>
            </div>
          </div>
        </div>

        <!-- María Elena Rodríguez -->
        <div class="group">
          <div class="bg-white rounded-lg overflow-hidden shadow-[0_0_15px_rgba(0,0,0,0.1)] transition-all duration-300 group-hover:shadow-[0_0_25px_rgba(0,0,0,0.2)] group-hover:-translate-y-2">
            <div class="aspect-[4/5] relative overflow-hidden">
              <img 
                src="@/assets/img/socio_1.jpg" 
                alt="María Elena Rodríguez" 
                class="w-full h-full object-cover transition-transform duration-300 group-hover:scale-105"
              >
            </div>
            <div class="p-4">
              <h3 class="text-lg font-bold text-gray-900 mb-1">María Elena Rodríguez</h3>
              <p class="text-amber-500 font-semibold text-sm mb-2">Socia</p>
              <p class="text-gray-600 text-sm mb-3">Litigios Laborales y Mediación</p>
              <div class="flex items-center text-gray-500 text-sm">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"/>
                </svg>
                12+ años de experiencia
              </div>
            </div>
          </div>
        </div>

        <!-- Carlos Mendoza -->
        <div class="group">
          <div class="bg-white rounded-lg overflow-hidden shadow-[0_0_15px_rgba(0,0,0,0.1)] transition-all duration-300 group-hover:shadow-[0_0_25px_rgba(0,0,0,0.2)] group-hover:-translate-y-2">
            <div class="aspect-[4/5] relative overflow-hidden">
              <img 
                src="@/assets/img/socio_2.jpg" 
                alt="Carlos Mendoza" 
                class="w-full h-full object-cover transition-transform duration-300 group-hover:scale-105"
              >
            </div>
            <div class="p-4">
              <h3 class="text-lg font-bold text-gray-900 mb-1">Carlos Mendoza</h3>
              <p class="text-amber-500 font-semibold text-sm mb-2">Abogado Senior</p>
              <p class="text-gray-600 text-sm mb-3">Contratos y Relaciones Laborales</p>
              <div class="flex items-center text-gray-500 text-sm">
                <svg class="w-4 h-4 mr-1" fill="currentColor" viewBox="0 0 20 20">
                  <path d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"/>
                </svg>
                10+ años de experiencia
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'TeamSection'
}
</script>