<template>
    <div class="w-full h-screen bg-gradient-to-br from-blue-900 via-blue-800 to-indigo-900 relative overflow-hidden" id="home">
        <!-- Animated Background Elements -->
        <div class="absolute inset-0">
            <div class="absolute top-20 left-20 w-72 h-72 bg-blue-400/10 rounded-full blur-3xl animate-pulse"></div>
            <div class="absolute bottom-20 right-20 w-96 h-96 bg-indigo-400/10 rounded-full blur-3xl animate-pulse delay-1000"></div>
            <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-80 h-80 bg-cyan-400/5 rounded-full blur-3xl animate-pulse delay-500"></div>
        </div>

        <!-- Navigation Menu -->
        <div :class="openMenu ? 'fixed inset-0 bg-black/50 backdrop-blur-sm z-40' : 'hidden'" @click="openMenu = false">
            <div class="fixed top-0 left-0 h-full w-80 bg-gradient-to-b from-blue-900/95 to-indigo-900/95 backdrop-blur-md shadow-2xl transform transition-transform duration-300 z-50" @click.stop>
                <div class="p-8">
                    <div class="flex items-center justify-between mb-8">
                        <h2 class="text-2xl font-bold text-white">Menu</h2>
                        <button @click="openMenu = false" class="text-white hover:text-cyan-300 transition-colors duration-300">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                            </svg>
                        </button>
                    </div>
                    <nav class="space-y-4">
                        <a href="#home" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-cyan-400/20 rounded-lg flex items-center justify-center group-hover:bg-cyan-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Home</span>
                        </a>
                        <a href="#education" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-blue-400/20 rounded-lg flex items-center justify-center group-hover:bg-blue-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5z"></path>
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Education</span>
                        </a>
                        <a href="#skills" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-indigo-400/20 rounded-lg flex items-center justify-center group-hover:bg-indigo-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Skills</span>
                        </a>
                        <a href="#experience" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-purple-400/20 rounded-lg flex items-center justify-center group-hover:bg-purple-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2-2v2m8 0V6a2 2 0 012 2v6a2 2 0 01-2 2H8a2 2 0 01-2-2V8a2 2 0 012-2V6"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Experience</span>
                        </a>
                        <a href="#projects" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-pink-400/20 rounded-lg flex items-center justify-center group-hover:bg-pink-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Projects</span>
                        </a>
                        <a href="#resume" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-yellow-400/20 rounded-lg flex items-center justify-center group-hover:bg-yellow-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Resume</span>
                        </a>
                        <a href="#contact" @click="openMenu = false" class="flex items-center space-x-3 text-white hover:text-cyan-300 hover:bg-white/10 rounded-lg p-3 transition-all duration-300 group">
                            <div class="w-8 h-8 bg-green-400/20 rounded-lg flex items-center justify-center group-hover:bg-green-400/30 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                                </svg>
                            </div>
                            <span class="font-medium">Contact</span>
                        </a>
                    </nav>
                </div>
            </div>
        </div>

        <!-- Menu Button -->
        <button :class="!openMenu ? 'fixed top-6 left-6 w-10 h-10 bg-white/10 backdrop-blur-sm rounded-lg flex items-center justify-center z-50 hover:bg-white/20 transition-all duration-300' : 'hidden'" @click="openMenu = !openMenu">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6 text-white" viewBox="0 0 640 640">
                <path fill="currentColor" d="M96 160C96 142.3 110.3 128 128 128L512 128C529.7 128 544 142.3 544 160C544 177.7 529.7 192 512 192L128 192C110.3 192 96 177.7 96 160zM96 320C96 302.3 110.3 288 128 288L512 288C529.7 288 544 302.3 544 320C544 337.7 529.7 352 512 352L128 352C110.3 352 96 337.7 96 320zM544 480C544 497.7 529.7 512 512 512L128 512C110.3 512 96 497.7 96 480C96 462.3 110.3 448 128 448L512 448C529.7 448 544 462.3 544 480z" />
            </svg>
        </button>

        <!-- Main Content -->
        <div class="relative z-10 flex flex-col items-center justify-center h-full text-center px-6">
            <!-- Greeting Text -->
            <div class="mb-8">
                <h2 class="text-2xl md:text-3xl text-cyan-300 font-light mb-4 animate-fade-in">
                    Hello, I'm
                </h2>
                <h1 class="text-5xl md:text-7xl font-bold text-white mb-6 animate-slide-up">
                    Quoc Anh Nguyen
                </h1>
                <div class="text-xl md:text-2xl text-blue-200 font-light animate-fade-in-delay">
                    <span class="inline-block animate-bounce">👋</span>
                    Backend Developer
                </div>
            </div>

            <!-- Animated Typewriter Effect -->
            <div class="mb-12">
                <div class="text-lg md:text-xl text-blue-100 font-mono">
                    <span class="typing-text">I create amazing digital experiences</span>
                    <span class="typing-cursor">|</span>
                </div>
            </div>

            <!-- Call to Action Buttons -->
            <div class="flex flex-col sm:flex-row gap-4 animate-fade-in-delay-2">
                <a href="#projects" class="px-8 py-3 bg-gradient-to-r from-cyan-500 to-blue-600 text-white font-semibold rounded-full hover:from-cyan-600 hover:to-blue-700 transform hover:scale-105 transition-all duration-300 shadow-lg hover:shadow-xl">
                    View My Work
                </a>
                <a href="#resume" class="px-8 py-3 border-2 border-cyan-400 text-cyan-400 font-semibold rounded-full hover:bg-cyan-400 hover:text-blue-900 transform hover:scale-105 transition-all duration-300">
                    Download CV
                </a>
            </div>

            <!-- Scroll Indicator -->
            <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce">
                <div class="w-6 h-10 border-2 border-cyan-400 rounded-full flex justify-center">
                    <div class="w-1 h-3 bg-cyan-400 rounded-full mt-2 animate-pulse"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
export default {
    name: 'Home',
    data() {
        return {
            openMenu: false,
        }
    }
}
</script>

<style scoped>
.animate-fade-in {
    animation: fadeIn 1s ease-in;
}

.animate-slide-up {
    animation: slideUp 1s ease-out;
}

.animate-fade-in-delay {
    animation: fadeIn 1s ease-in 0.5s both;
}

.animate-fade-in-delay-2 {
    animation: fadeIn 1s ease-in 1s both;
}

.typing-text {
    border-right: 2px solid #67e8f9;
    animation: typing 3s steps(30, end), blink-caret 0.75s step-end infinite;
    white-space: nowrap;
    overflow: hidden;
}

.typing-cursor {
    animation: blink 1s infinite;
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

@keyframes slideUp {
    from { 
        opacity: 0; 
        transform: translateY(30px); 
    }
    to { 
        opacity: 1; 
        transform: translateY(0); 
    }
}

@keyframes typing {
    from { width: 0; }
    to { width: 100%; }
}

@keyframes blink {
    0%, 50% { opacity: 1; }
    51%, 100% { opacity: 0; }
}

@keyframes blink-caret {
    from, to { border-color: transparent; }
    50% { border-color: #67e8f9; }
}
</style>