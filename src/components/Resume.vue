<template>
    <div class="w-full min-h-screen bg-gradient-to-br from-blue-900 via-indigo-900 to-purple-900 relative overflow-hidden" id="resume">
        <!-- Background Elements -->
        <div class="absolute inset-0">
            <div class="absolute top-20 right-20 w-80 h-80 bg-blue-400/10 rounded-full blur-3xl animate-pulse"></div>
            <div class="absolute bottom-20 left-20 w-96 h-96 bg-indigo-400/10 rounded-full blur-3xl animate-pulse delay-1000"></div>
        </div>

        <!-- Main Content -->
        <div class="relative z-10 py-20 px-6">
            <!-- Section Title -->
            <div class="text-center mb-16">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-4 animate-fade-in">
                    Resume
                </h1>
                <div class="w-24 h-1 bg-gradient-to-r from-cyan-400 to-blue-500 mx-auto rounded-full"></div>
            </div>

            <!-- Resume Content -->
            <div class="max-w-6xl mx-auto">
                <!-- Download Button -->
                <div class="text-center mb-8">
                    <a href="/src/assets/QuocAnhNguyen_Backend.pdf" target="_blank" download class="inline-block bg-gradient-to-r from-blue-500 to-indigo-600 text-white px-8 py-3 rounded-full font-semibold hover:from-blue-600 hover:to-indigo-700 transform hover:scale-105 transition-all duration-300 shadow-lg hover:shadow-xl">
                        <svg class="w-5 h-5 inline mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                        </svg>
                        Download Resume (PDF)
                    </a>
                </div>

                <!-- Resume Display -->
                <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20">
                    <div class="bg-white rounded-lg shadow-2xl overflow-hidden">
                        <iframe 
                            src="/src/assets/QuocAnhNguyen_Backend.pdf" 
                            class="w-full h-[800px] md:h-[1000px]"
                            title="Resume PDF"
                        ></iframe>
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
</style>