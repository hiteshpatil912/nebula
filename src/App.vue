<template>
  <div class="bg-dark text-white font-sans selection:bg-purple-500 selection:text-white overflow-x-hidden">
    <NavBar />
    <main>
      <Hero />
      <About />
      <Services />
      <TechStack />
      <Portfolio @open="openModal" />
      <Testimonials />
      <Contact />
    </main>
    <Footer />

    <transition name="fade">
      <div v-if="modal" class="fixed inset-0 z-50 flex items-center justify-center bg-black/60">
        <div class="bg-dark max-w-3xl w-full p-6 rounded-2xl glass">
          <div class="flex justify-between items-start gap-4">
            <div>
              <h3 class="text-2xl font-bold">{{ modal.title }}</h3>
              <p class="text-gray-300 mt-3">{{ modal.desc }}</p>
            </div>
            <button @click="modal = null" class="text-gray-400 hover:text-white">Close</button>
          </div>
        </div>
      </div>
    </transition>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import NavBar from './components/NavBar.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Services from './components/Services.vue'
import TechStack from './components/TechStack.vue'
import Portfolio from './components/Portfolio.vue'
import Testimonials from './components/Testimonials.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

const modal = ref(null)
function openModal(item) { modal.value = item }

onMounted(() => {
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('active') })
  }, { threshold: 0.12 })
  document.querySelectorAll('.reveal').forEach(el => io.observe(el))
})
</script>
