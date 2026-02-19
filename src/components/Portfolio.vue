<template>
  <section class="py-24 px-6 reveal" id="portfolio">
        <div class="max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div>
                    <h2 class="text-4xl md:text-5xl font-bold mb-4">Selected Works</h2>
                    <p class="text-gray-400">Showcasing excellence in software engineering.</p>
                </div>
                <a class="mt-4 md:mt-0 text-purple-400 hover:text-white transition-colors flex items-center group font-semibold"
                    href="#">
                    Explore All Projects <svg class="w-5 h-5 ml-2 group-hover:translate-x-1 transition-transform"
                        fill="none" stroke="currentColor" viewbox="0 0 24 24">
                        <path d="M17 8l4 4m0 0l-4 4m4-4H3" stroke-linecap="round" stroke-linejoin="round"
                            stroke-width="2"></path>
                    </svg>
                </a>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <!-- Project 1 -->
                <div class="group relative">
                    <div class="relative overflow-hidden rounded-[2.5rem] glass aspect-video mb-6">
                        <img alt="Aether Wallet"
                            class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-700"
                            src="https://lh3.googleusercontent.com/aida-public/AB6AXuDm7o91ymzRPTaKRSwq9i3zPdmRGWqiT_NUiZvQaAqJmMXVE2X_OExupAdENHlE_sMXzIBaNlB4ao0Qc6AgxlE6O6QFxs6SIw1GZZy-mMAokHCyXIgXYbtKj-VpI1ZAY03Ao4qGQ-8jc0QxwkrE-xR60tCopvd-apeyJbDE_ZBqD2rO78v72-vUM_pWdmO-F_JEqkvMneNyIu-Awe56LUfv8IqSq-2G5rnxyoVx7cK03Jf_Yn3cTlpXRIDpK3kbJErtoZWvI_pz8g" />
                        <div
                            class="absolute inset-0 bg-gradient-to-t from-dark/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex items-end p-8">
                            <div class="flex gap-4">
                                <span class="px-3 py-1 glass rounded-lg text-xs font-mono">React</span>
                                <span class="px-3 py-1 glass rounded-lg text-xs font-mono">Web3.js</span>
                            </div>
                        </div>
                    </div>
                    <h3 class="text-2xl font-bold group-hover:text-purple-400 transition-colors">Aether Wallet</h3>
                    <p class="text-gray-400 mt-2">Next-gen multi-chain crypto wallet with biometric security and gasless
                        transactions.</p>
                </div>
                <!-- Project 2 -->
                <div class="group relative">
                    <div class="relative overflow-hidden rounded-[2.5rem] glass aspect-video mb-6">
                        <img alt="Nebula Core"
                            class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-700"
                            src="https://lh3.googleusercontent.com/aida-public/AB6AXuAVRoqJwH1SZ0SChswyttZ96EMKHm1EuS2dwdRc6gLE3GPEkQxu6Z7F0J3zw6J56OB5TTEv25wUPcqZ-c44fmbswfhBYaW2HPvYlFFgbz3wDDMF0u50hIksp8oYZV9C4C3SXRo85zLSLaLS6Tjgkihrt0zhvG_QtJoo-bbY6muqIyr31qJjy9bPIxIU3rkNLTAlwiSv0yZTCXM1LGyyx94nUfsuQ5qth1BJVDoSskodhMj71hXOTPvafNiwr7Ms3kNKq0c4EhtWlQ" />
                        <div
                            class="absolute inset-0 bg-gradient-to-t from-dark/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex items-end p-8">
                            <div class="flex gap-4">
                                <span class="px-3 py-1 glass rounded-lg text-xs font-mono">Go</span>
                                <span class="px-3 py-1 glass rounded-lg text-xs font-mono">Kubernetes</span>
                            </div>
                        </div>
                    </div>
                    <h3 class="text-2xl font-bold group-hover:text-cyan-400 transition-colors">Nebula Core</h3>
                    <p class="text-gray-400 mt-2">Distributed microservices orchestration platform designed for
                        real-time edge computing.</p>
                </div>
            </div>
        </div>
    </section>
</template>
