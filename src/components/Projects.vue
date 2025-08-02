<template>
    <div class="w-full h-full bg-gradient-to-br from-indigo-900 via-purple-900 to-pink-900 relative overflow-hidden"
        id="projects">
        <!-- Background Elements -->
        <div class="absolute inset-0">
            <div class="absolute top-20 right-20 w-80 h-80 bg-pink-400/10 rounded-full blur-3xl animate-pulse"></div>
            <div
                class="absolute bottom-20 left-20 w-96 h-96 bg-purple-400/10 rounded-full blur-3xl animate-pulse delay-1000">
            </div>
        </div>

        <!-- Main Content -->
        <div class="relative z-10 py-20 px-6">
            <!-- Section Title -->
            <div class="text-center mb-16">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-4 animate-fade-in">
                    Featured Projects
                </h1>
                <div class="w-24 h-1 bg-gradient-to-r from-cyan-400 to-blue-500 mx-auto rounded-full"></div>
            </div>

            <!-- Projects Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 md:gap-8 max-w-7xl mx-auto">
                <!-- Mad Village Game -->
                <div
                    class="group bg-white/10 backdrop-blur-sm rounded-2xl p-6 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <!-- Project Image -->
                    <div class="relative mb-6 overflow-hidden rounded-xl">
                        <img src="/src/assets/images/mad-village-game.gif" alt="Mad Village Game Demo" class="w-full aspect-video object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent"></div>
                        <div class="absolute top-2 right-2">
                            <a href="https://github.com/toi-la-qanh/mad-village-game" target="_blank"
                                class="bg-black/50 backdrop-blur-sm text-white p-2 rounded-lg hover:bg-black/70 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Mad Village Game</h3>
                    <p class="text-cyan-300 text-sm mb-4">Online Board Game</p>
                    <p class="text-blue-200 text-sm leading-relaxed mb-4">
                        Developed and deployed a scalable online board game supporting up to <span
                            class="text-cyan-300 font-medium">1,000 concurrent players</span> using Node.js for backend
                        development and Vue.js for building a responsive, dynamic frontend.
                    </p>
                    <div class="space-y-2 mb-4">
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-green-400 rounded-full mr-2"></div>
                            <span>MongoDB for player data & game states</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-green-400 rounded-full mr-2"></div>
                            <span>Socket.io for real-time updates</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-green-400 rounded-full mr-2"></div>
                            <span>Synchronized gameplay across all players</span>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-green-400/20 text-green-300 px-2 py-1 rounded-full text-xs">Node.js</span>
                        <span class="bg-green-400/20 text-green-300 px-2 py-1 rounded-full text-xs">Vue.js</span>
                        <span class="bg-green-400/20 text-green-300 px-2 py-1 rounded-full text-xs">MongoDB</span>
                        <span class="bg-green-400/20 text-green-300 px-2 py-1 rounded-full text-xs">Socket.io</span>
                    </div>
                </div>

                <!-- Social Media Website -->
                <div
                    class="group bg-white/10 backdrop-blur-sm rounded-2xl p-6 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <!-- Project Image -->
                    <div class="relative mb-6 overflow-hidden rounded-xl">
                        <img src="/src/assets/images/social-media-pages.gif" alt="Social Media Pages" class="w-full aspect-video object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent"></div>
                        <div class="absolute top-2 right-2">
                            <a href="https://github.com/toi-la-qanh/Thread-Pages" target="_blank"
                                class="bg-black/50 backdrop-blur-sm text-white p-2 rounded-lg hover:bg-black/70 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Thread Pages</h3>
                    <p class="text-cyan-300 text-sm mb-4">Social Media Pages</p>
                    <p class="text-blue-200 text-sm leading-relaxed mb-4">
                        Built a dynamic social media platform centered around user interactions with short posts,
                        delivering a fast, responsive, and interactive interface using ReactJS library.
                    </p>
                    <div class="space-y-2 mb-4">
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-blue-400 rounded-full mr-2"></div>
                            <span>Laravel backend with RESTful APIs</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-blue-400 rounded-full mr-2"></div>
                            <span>PostgreSQL with Eloquent ORM</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-blue-400 rounded-full mr-2"></div>
                            <span>Real-time user feed updates</span>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-blue-400/20 text-blue-300 px-2 py-1 rounded-full text-xs">PHP</span>
                        <span class="bg-blue-400/20 text-blue-300 px-2 py-1 rounded-full text-xs">JavaScript</span>
                        <span class="bg-blue-400/20 text-blue-300 px-2 py-1 rounded-full text-xs">Laravel</span>
                        <span class="bg-blue-400/20 text-blue-300 px-2 py-1 rounded-full text-xs">ReactJS</span>
                        <span class="bg-blue-400/20 text-blue-300 px-2 py-1 rounded-full text-xs">PostgreSQL</span>
                    </div>
                </div>

                <!-- Online Courses Website -->
                <div
                    class="group bg-white/10 backdrop-blur-sm rounded-2xl p-6 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <!-- Project Image -->
                    <div class="relative mb-6 overflow-hidden rounded-xl">
                        <img src="/src/assets/images/online-courses.jpg" alt="Online Courses Platform" class="w-full aspect-video object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent"></div>
                        <div class="absolute top-2 right-2">
                            <a href="https://github.com/toi-la-qanh/Online-Courses" target="_blank"
                                class="bg-black/50 backdrop-blur-sm text-white p-2 rounded-lg hover:bg-black/70 transition-colors duration-300">
                                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Online Courses Platform</h3>
                    <p class="text-cyan-300 text-sm mb-4">Programming Learning Platform</p>
                    <p class="text-blue-200 text-sm leading-relaxed mb-4">
                        Developed a comprehensive online learning platform for programming courses with support for
                        manual transfers and future payment gateway integrations.
                    </p>
                    <div class="space-y-2 mb-4">
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-purple-400 rounded-full mr-2"></div>
                            <span>Comprehensive learning management</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-purple-400 rounded-full mr-2"></div>
                            <span>Real-time notification system</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm">
                            <div class="w-2 h-2 bg-purple-400 rounded-full mr-2"></div>
                            <span>jQuery fetch for user updates</span>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-purple-400/20 text-purple-300 px-2 py-1 rounded-full text-xs">PHP</span>
                        <span class="bg-purple-400/20 text-purple-300 px-2 py-1 rounded-full text-xs">JavaScript</span>
                        <span class="bg-purple-400/20 text-purple-300 px-2 py-1 rounded-full text-xs">MySQL</span>
                        <span class="bg-purple-400/20 text-purple-300 px-2 py-1 rounded-full text-xs">jQuery</span>
                    </div>
                </div>
            </div>

            <!-- Project Stats -->
            <div
                class="mt-12 bg-gradient-to-r from-cyan-400/10 to-blue-500/10 backdrop-blur-sm rounded-2xl p-6 border border-cyan-400/20">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
                    <div>
                        <div class="text-2xl md:text-3xl font-bold text-cyan-300 mb-2">3+</div>
                        <div class="text-blue-200 text-sm md:text-base">Projects Completed</div>
                    </div>
                    <div>
                        <div class="text-2xl md:text-3xl font-bold text-cyan-300 mb-2">1,000+</div>
                        <div class="text-blue-200 text-sm md:text-base">Concurrent Users</div>
                    </div>
                    <div>
                        <div class="text-2xl md:text-3xl font-bold text-cyan-300 mb-2">100%</div>
                        <div class="text-blue-200 text-sm md:text-base">GitHub Open Source</div>
                    </div>
                </div>
            </div>

            <!-- GitHub Link -->
            <div class="mt-8 text-center">
                <p class="text-blue-200 text-lg mb-4">Other projects go to my GitHub page</p>
                <a href="https://github.com/toi-la-qanh" target="_blank" class="inline-flex items-center bg-gradient-to-r from-blue-500 to-indigo-600 text-white px-6 py-3 rounded-full font-semibold hover:from-blue-600 hover:to-indigo-700 transform hover:scale-105 transition-all duration-300 shadow-lg hover:shadow-xl">
                    <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
                    </svg>
                    View All Projects on GitHub
                </a>
            </div>
        </div>
    </div>

</template>

<style scoped>
.animate-fade-in {
    animation: fadeIn 1s ease-in;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}
</style>