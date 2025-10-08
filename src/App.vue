<template>
  <div class="min-h-screen flex flex-col">
    <SiteHeader />
    <main class="flex-grow">
      <HeroSection />
      <ServicesSection />
      <AboutSection />
      <TeamSection />
      <ContactSection />
    </main>
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from '@/components/layout/Header.vue'
import SiteFooter from '@/components/layout/Footer.vue'
import HeroSection from '@/components/sections/HeroSection.vue'
import ServicesSection from '@/components/sections/ServicesSection.vue'
import AboutSection from '@/components/sections/AboutSection.vue'
import TeamSection from '@/components/sections/TeamSection.vue'
import ContactSection from '@/components/sections/ContactSection.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
    HeroSection,
    ServicesSection,
    AboutSection,
    TeamSection,
    ContactSection
  }
}
</script>
