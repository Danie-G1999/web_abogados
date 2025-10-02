<template>
  <header class="fixed top-0 left-0 right-0 bg-white shadow-md z-50">
    <nav class="container mx-auto px-4 py-4">
      <div class="flex items-center justify-between">
        <!-- Logo -->
        <div class="flex items-center">
          <img src="@/assets/img/logo_5.png" alt="Oscar Guzman Abogados" class="h-12 md:h-16">
        </div>

        <!-- Mobile menu button -->
        <button @click="isMenuOpen = !isMenuOpen" class="md:hidden">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path v-if="!isMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
            <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
          </svg>
        </button>

        <!-- Desktop navigation -->
        <div class="hidden md:flex items-center space-x-8">
          <a href="#inicio" class="text-gray-700 hover:text-blue-600 transition-colors">Inicio</a>
          <a href="#servicios" class="text-gray-700 hover:text-blue-600 transition-colors">Servicios</a>
          <a href="#contactanos" class="text-gray-700 hover:text-blue-600 transition-colors">Contáctanos</a>
        </div>
      </div>

      <!-- Mobile navigation -->
      <div v-show="isMenuOpen" class="md:hidden">
        <div class="pt-2 pb-4 space-y-2">
          <a href="#inicio" class="block px-4 py-2 text-gray-700 hover:bg-blue-50 rounded transition-colors">Inicio</a>
          <a href="#servicios" class="block px-4 py-2 text-gray-700 hover:bg-blue-50 rounded transition-colors">Servicios</a>
          <a href="#contactanos" class="block px-4 py-2 text-gray-700 hover:bg-blue-50 rounded transition-colors">Contáctanos</a>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'SiteHeader',
  data() {
    return {
      isMenuOpen: false
    }
  }
}
</script>