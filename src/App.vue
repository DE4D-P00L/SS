<script setup>
import NavBar from './components/NavBar.vue'
import HeroSection from './components/HeroSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import ProjectsSection from './components/ProjectsSection.vue';
import UserReviewSection from './components/UserReviewSection.vue';
import FAQSection from './components/FAQSection.vue';
import CardSection from './components/CardSection.vue';
import FooterSection from './components/FooterSection.vue';
</script>

<template>
  <NavBar/>
  <main class="px-[30px] max-w-[1440px] mx-auto">
    <HeroSection/>
    <ServicesSection/>
    <ProjectsSection />
    <UserReviewSection/>
    <FAQSection/>
    <CardSection/>
    <FooterSection/>
  </main>
</template>