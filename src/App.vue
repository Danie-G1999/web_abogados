<template>
  <div class="min-h-screen flex flex-col">
    <SiteHeader />
    <main class="flex-grow">
      <HeroSection />
      <!-- Aquí irán las demás secciones -->
    </main>
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from '@/components/layout/Header.vue'
import SiteFooter from '@/components/layout/Footer.vue'
import HeroSection from '@/components/sections/HeroSection.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
    HeroSection
  }
}
</script>
