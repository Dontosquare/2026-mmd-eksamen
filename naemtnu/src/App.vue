<script setup>
import Header from "@/components/Header.vue";
import SeoProcess from "@/components/SeoProcess.vue";
import Soegeord from "@/assets/soegeord.png";
import Anbefalinger from "@/assets/anbefalinger.png";
import Faq from "@/components/Faq.vue";
import kontakt from "@/assets/kontakt.png";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <Header />
  <SeoProcess />
  <Soegeord />
  <Anbefalinger />
  <Faq />
  <kontakt />
  <Footer />
  <RouterView />
</template>

<style scoped></style>
