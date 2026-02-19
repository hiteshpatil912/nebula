<template>
  <nav class="fixed top-0 w-full z-50 px-6 py-4">
        <div class="max-w-7xl mx-auto flex items-center justify-between glass rounded-2xl px-6 py-3">
            <div class="flex items-center space-x-2">
                <div
                    class="w-8 h-8 bg-gradient-to-br from-purple-500 to-cyan-400 rounded-lg flex items-center justify-center font-bold text-dark">
                    N</div>
                <span
                    class="font-bold text-xl tracking-tight bg-clip-text text-transparent bg-gradient-to-r from-white to-gray-400">NEBULA.IO</span>
            </div>
            <div class="hidden md:flex items-center space-x-8 text-sm font-medium text-gray-300">
                <a class="hover:text-purple-400 transition-colors" href="#about">Experience</a>
                <a class="hover:text-purple-400 transition-colors" href="#services">Services</a>
                <a class="hover:text-purple-400 transition-colors" href="#portfolio">Work</a>
                <a class="px-5 py-2 bg-white text-dark rounded-full font-semibold hover:bg-purple-500 hover:text-white transition-all duration-300"
                    href="#contact">Hire Me</a>
            </div>
            <!-- Mobile Menu Toggle -->
            <button class="md:hidden text-white">
                <svg class="h-6 w-6" fill="none" stroke="currentColor" viewbox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg">
                    <path d="M4 6h16M4 12h16m-7 6h7" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
                    </path>
                </svg>
            </button>
        </div>
    </nav>
</template>
