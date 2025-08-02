<template>
    <div class="w-full h-full bg-gradient-to-br from-indigo-900 via-blue-900 to-cyan-900 relative overflow-hidden" id="skills">
        <!-- Background Elements -->
        <div class="absolute inset-0">
            <div class="absolute top-20 right-20 w-80 h-80 bg-cyan-400/10 rounded-full blur-3xl animate-pulse"></div>
            <div class="absolute bottom-20 left-20 w-96 h-96 bg-blue-400/10 rounded-full blur-3xl animate-pulse delay-1000"></div>
        </div>

        <!-- Main Content -->
        <div class="relative z-10 py-20 px-6">
            <!-- Section Title -->
            <div class="text-center mb-16">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-4 animate-fade-in">
                    Skills & Expertise
                </h1>
                <div class="w-24 h-1 bg-gradient-to-r from-cyan-400 to-blue-500 mx-auto rounded-full"></div>
            </div>

            <!-- Skills Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 md:gap-8 max-w-6xl mx-auto">
                <!-- Backend Development -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 bg-gradient-to-br from-cyan-400 to-blue-600 rounded-xl flex items-center justify-center mr-4">
                            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-white">Backend Development</h3>
                            <p class="text-cyan-300">Server & API Development</p>
                        </div>
                    </div>
                    <div class="space-y-3">
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">Node.js</span>
                        </div>
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">Express.js</span>
                        </div>
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">Socket.IO</span>
                        </div>
                    </div>
                </div>

                <!-- Database & Tools -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 bg-gradient-to-br from-blue-500 to-indigo-600 rounded-xl flex items-center justify-center mr-4">
                            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4"></path>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-white">Database & Tools</h3>
                            <p class="text-cyan-300">Data Management</p>
                        </div>
                    </div>
                    <div class="space-y-3">
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">MongoDB</span>
                        </div>
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">RESTful APIs</span>
                        </div>
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">PostgreSQL</span>
                        </div>
                    </div>
                </div>

                <!-- Additional Skills -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 bg-gradient-to-br from-indigo-500 to-purple-600 rounded-xl flex items-center justify-center mr-4">
                            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-white">Additional Skills</h3>
                            <p class="text-cyan-300">Backend Technologies</p>
                        </div>
                    </div>
                    <div class="space-y-3">
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">PHP</span>
                        </div>
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">Git Control</span>
                        </div>
                        <div class="skill-item bg-white/5 rounded-lg p-3 hover:bg-white/10 transition-all duration-300">
                            <span class="text-blue-200 font-medium">Unit Test</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.animate-fade-in {
    animation: fadeIn 1s ease-in;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

.skill-item {
    transition: all 0.3s ease;
}

.skill-item:hover {
    transform: translateX(5px);
}
</style>