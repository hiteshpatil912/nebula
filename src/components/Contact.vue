<template>
  <section class="py-24 px-6 reveal" id="contact">
        <div class="max-w-4xl mx-auto glass p-8 md:p-16 rounded-[3rem] border-white/10">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold mb-4">Start a Conversation</h2>
                <p class="text-gray-400">Have a project in mind? Let's build something extraordinary together.</p>
            </div>
            <form class="space-y-6">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="space-y-2">
                        <label class="text-sm font-semibold text-gray-400 ml-1">Your Name</label>
                        <input
                            class="w-full bg-white/5 border-white/10 rounded-2xl py-4 px-6 focus:ring-2 focus:ring-purple-500 focus:border-transparent transition-all outline-none"
                            placeholder="John Doe" type="text" />
                    </div>
                    <div class="space-y-2">
                        <label class="text-sm font-semibold text-gray-400 ml-1">Email Address</label>
                        <input
                            class="w-full bg-white/5 border-white/10 rounded-2xl py-4 px-6 focus:ring-2 focus:ring-purple-500 focus:border-transparent transition-all outline-none"
                            placeholder="john@example.com" type="email" />
                    </div>
                </div>
                <div class="space-y-2">
                    <label class="text-sm font-semibold text-gray-400 ml-1">Your Message</label>
                    <textarea
                        class="w-full bg-white/5 border-white/10 rounded-2xl py-4 px-6 focus:ring-2 focus:ring-purple-500 focus:border-transparent transition-all outline-none"
                        placeholder="Tell me about your project..." rows="4"></textarea>
                </div>
                <button
                    class="w-full py-5 bg-gradient-to-r from-purple-600 to-cyan-500 text-white font-bold rounded-2xl hover:scale-[1.02] transition-transform active:scale-95 neon-glow-purple"
                    type="submit">
                    Send Inquiry
                </button>
            </form>
            <div
                class="mt-12 pt-12 border-t border-white/5 flex flex-col md:flex-row items-center justify-between gap-6">
                <div class="flex gap-6">
                    <a class="text-gray-400 hover:text-white transition-colors" href="#">GitHub</a>
                    <a class="text-gray-400 hover:text-white transition-colors" href="#">LinkedIn</a>
                    <a class="text-gray-400 hover:text-white transition-colors" href="#">X / Twitter</a>
                </div>
                <div class="text-gray-400 text-sm">
                    contact@nebula.io
                </div>
            </div>
        </div>
    </section>
</template>
