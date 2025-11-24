<template>
  <div class="min-h-screen bg-white">
    <Header />
    <main>
      <HeroSection />
      <WhoWeAre />
      <WhatWeDo />
      <OurApproach />
      <CaseExamples />
      <TeamSection />
      <ContactSection />
    </main>
    <Footer />
  </div>
</template>

<script setup lang="ts">
import Header from '~/components/Header.vue'
import HeroSection from '~/components/HeroSection.vue'
import WhoWeAre from '~/components/WhoWeAre.vue'
import WhatWeDo from '~/components/WhatWeDo.vue'
import OurApproach from '~/components/OurApproach.vue'
import CaseExamples from '~/components/CaseExamples.vue'
import TeamSection from '~/components/TeamSection.vue'
import ContactSection from '~/components/ContactSection.vue'
import Footer from '~/components/Footer.vue'

useHead({
  title: '3N Engineering & Digital Solutions',
  meta: [
    {
      name: 'description',
      content: 'เชื่อมโรงงาน–เครือข่าย–ซอฟต์แวร์ ให้กลายเป็นระบบอัจฉริยะ',
    },
  ],
})
</script>
