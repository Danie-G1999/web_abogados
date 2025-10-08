<template>
  <section id="contacto" class="py-20 bg-gray-50">
    <div class="container mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-4xl md:text-5xl font-bold mb-4">Contáctanos</h2>
        <p class="text-gray-600 max-w-2xl mx-auto">
          ¿Necesitas asesoría legal? Estamos aquí para ayudarte. Solicita tu consulta gratuita y obtén la orientación que necesitas.
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 max-w-6xl mx-auto">
        <!-- Información de Contacto -->
        <div class="space-y-8">
          <h3 class="text-2xl font-bold mb-6">Información de Contacto</h3>
          
          <!-- Dirección -->
          <div class="flex items-start">
            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
              </svg>
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold mb-1">Dirección</h4>
              <p class="text-gray-600">Av. Principal 123, Torre Empresarial, Piso 15</p>
              <p class="text-gray-600">Ciudad, País 12345</p>
            </div>
          </div>

          <!-- Teléfono -->
          <div class="flex items-start">
            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
              </svg>
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold mb-1">Teléfono</h4>
              <p class="text-gray-600">+1 (555) 123-4567</p>
              <p class="text-gray-600">+1 (555) 123-4568</p>
            </div>
          </div>

          <!-- Email -->
          <div class="flex items-start">
            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
              </svg>
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold mb-1">Email</h4>
              <p class="text-gray-600">info@oscarguzmanlaboral.com</p>
              <p class="text-gray-600">consultas@oscarguzmanlaboral.com</p>
            </div>
          </div>

          <!-- Horarios -->
          <div class="flex items-start">
            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold mb-1">Horarios</h4>
              <p class="text-gray-600">Lunes - Viernes: 8:00 AM - 6:00 PM</p>
              <p class="text-gray-600">Sábados: 9:00 AM - 2:00 PM</p>
            </div>
          </div>

          <!-- Mapa -->
          <div class="w-full h-64 rounded-lg overflow-hidden shadow-md">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1000!2d-74.0060!3d40.7128!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zM40!5e0!3m2!1sen!2sus!4v1234567890!5m2!1sen!2sus"
              width="100%"
              height="100%"
              style="border:0;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Formulario de Contacto -->
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <h3 class="text-2xl font-bold mb-6">Solicita tu Consulta Gratuita</h3>
          <form @submit.prevent="enviarConsulta" class="space-y-6">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
              <div>
                <label class="block text-gray-700 mb-2" for="nombre">Nombre Completo *</label>
                <input
                  type="text"
                  id="nombre"
                  v-model="formulario.nombre"
                  class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent"
                  placeholder="Tu nombre completo"
                  required
                >
              </div>
              <div>
                <label class="block text-gray-700 mb-2" for="email">Email *</label>
                <input
                  type="email"
                  id="email"
                  v-model="formulario.email"
                  class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent"
                  placeholder="tu@email.com"
                  required
                >
              </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
              <div>
                <label class="block text-gray-700 mb-2" for="telefono">Teléfono</label>
                <input
                  type="tel"
                  id="telefono"
                  v-model="formulario.telefono"
                  class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent"
                  placeholder="+1 (555) 123-4567"
                >
              </div>
              <div>
                <label class="block text-gray-700 mb-2" for="tipo">Tipo de Consulta *</label>
                <select
                  id="tipo"
                  v-model="formulario.tipo"
                  class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent"
                  required
                >
                  <option value="">Selecciona un tipo</option>
                  <option value="laboral">Derecho Laboral</option>
                  <option value="seguridad">Seguridad Social</option>
                  <option value="contratos">Contratos</option>
                  <option value="otros">Otros</option>
                </select>
              </div>
            </div>

            <div>
              <label class="block text-gray-700 mb-2" for="mensaje">Describe tu situación *</label>
              <textarea
                id="mensaje"
                v-model="formulario.mensaje"
                rows="4"
                class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent resize-none"
                placeholder="Describe brevemente tu situación legal..."
                required
              ></textarea>
              <p class="text-sm text-gray-500 mt-1">0/500 caracteres</p>
            </div>

            <button
              type="submit"
              class="w-full bg-amber-500 hover:bg-amber-600 text-white font-bold py-3 px-6 rounded-lg transition-colors flex items-center justify-center"
            >
              <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/>
              </svg>
              Enviar Consulta
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection',
  data() {
    return {
      formulario: {
        nombre: '',
        email: '',
        telefono: '',
        tipo: '',
        mensaje: ''
      }
    }
  },
  methods: {
    enviarConsulta() {
      // Aquí irá la lógica para enviar el formulario
      console.log('Formulario enviado:', this.formulario)
    }
  }
}
</script>