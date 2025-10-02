<template>
  <footer class="bg-gray-800 text-white py-12">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Logo y descripción -->
        <div>
          <img src="@/assets/img/logo_1.png" alt="Oscar Guzman Abogados" class="h-16 mb-4">
          <p class="text-gray-400">
            Comprometidos con la excelencia legal y el servicio al cliente.
          </p>
        </div>

        <!-- Enlaces rápidos -->
        <div>
          <h3 class="text-xl font-bold mb-4">Enlaces Rápidos</h3>
          <ul class="space-y-2">
            <li><a href="#inicio" class="text-gray-400 hover:text-white transition-colors">Inicio</a></li>
            <li><a href="#servicios" class="text-gray-400 hover:text-white transition-colors">Servicios</a></li>
            <li><a href="#contactanos" class="text-gray-400 hover:text-white transition-colors">Contáctanos</a></li>
          </ul>
        </div>

        <!-- Contacto -->
        <div>
          <h3 class="text-xl font-bold mb-4">Contacto</h3>
          <ul class="space-y-2 text-gray-400">
            <li>Teléfono: (123) 456-7890</li>
            <li>Email: contacto@oscarguzman.com</li>
            <li>Dirección: Calle Principal #123</li>
          </ul>
        </div>
      </div>

      <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
        <p>&copy; {{ new Date().getFullYear() }} Oscar Guzman Abogados. Todos los derechos reservados.</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
}
</script>