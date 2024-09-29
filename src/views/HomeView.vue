<script setup>
import NavbarComp from '@/components/NavbarComp.vue'
import FotoerComp from '@/components/FooterComp.vue'
import TopSection from '@/components/TopSection.vue'
import CategoryCard from '@/components/CategoryCard.vue'
import HighlightProducts from '@/components/HighlightProducts.vue'
import AboutSection from '@/components/AboutSection.vue'
</script>

<template>
  <header>
    <NavbarComp />
  </header>
  <main>
    <TopSection />
    <CategoryCard />
    <AboutSection />
    <HighlightProducts />
  </main>
  <footer>
    <FotoerComp />
  </footer>
</template>
