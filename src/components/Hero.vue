<template>
  <section class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden hero-mesh" id="hero">
        <!-- Animated background element -->
        <div class="absolute inset-0 z-0">
            <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-purple-600/20 rounded-full blur-[120px] animate-pulse">
            </div>
            <div class="absolute bottom-1/4 right-1/4 w-96 h-96 bg-cyan-600/20 rounded-full blur-[120px] animate-pulse"
                style="animation-delay: 2s"></div>
        </div>
        <div class="relative z-10 text-center px-6 max-w-4xl mx-auto">
            <span
                class="inline-block px-4 py-1.5 mb-6 text-xs font-semibold tracking-widest uppercase bg-purple-500/10 border border-purple-500/20 text-purple-400 rounded-full">Available
                for New Projects</span>
            <h1 class="text-5xl md:text-8xl font-extrabold mb-8 tracking-tighter leading-tight">
                Building the <span
                    class="bg-clip-text text-transparent bg-gradient-to-r from-purple-400 via-pink-500 to-cyan-400 animate-gradient">Digital
                    Future</span>
            </h1>
            <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed">
                I create immersive, high-performance web experiences using cutting-edge technologies and user-centric
                design principles.
            </p>
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                <a class="group relative px-8 py-4 bg-white text-dark font-bold rounded-xl overflow-hidden transition-all duration-300 hover:scale-105"
                    href="#portfolio">
                    <span class="relative z-10">View Projects</span>
                    <div
                        class="absolute inset-0 bg-gradient-to-r from-cyan-400 to-purple-500 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                    </div>
                </a>
                <a class="px-8 py-4 glass border-white/10 text-white font-bold rounded-xl hover:bg-white/10 transition-all duration-300"
                    href="#contact">
                    Get in Touch
                </a>
            </div>
        </div>
    </section>
</template>
