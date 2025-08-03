<template>
    <div class="w-full min-h-screen bg-gradient-to-br from-blue-800 via-indigo-800 to-purple-900 relative overflow-hidden" id="experience">
        <!-- Background Elements -->
        <div class="absolute inset-0">
            <div class="absolute top-10 right-10 w-64 h-64 bg-blue-400/10 rounded-full blur-3xl animate-pulse"></div>
            <div class="absolute bottom-10 left-10 w-80 h-80 bg-indigo-400/10 rounded-full blur-3xl animate-pulse delay-700"></div>
        </div>

        <!-- Main Content -->
        <div class="relative z-10 py-20 px-6">
            <!-- Section Title -->
            <div class="text-center mb-16">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-4 animate-fade-in">
                    {{$t('experience.title')}}
                </h1>
                <div class="w-24 h-1 bg-gradient-to-r from-cyan-400 to-blue-500 mx-auto rounded-full"></div>
            </div>

            <!-- Work Experience Counter -->
            <div class="max-w-4xl mx-auto mb-12">
                <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20">
                    <div class="text-center mb-6">
                        <h2 class="text-2xl md:text-3xl font-bold text-white mb-2">{{$t('experience.totalWorkExperience')}}</h2>
                        <p class="text-blue-200">{{$t('experience.professionalJourney')}}</p>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="text-center">
                            <div class="w-16 h-16 bg-gradient-to-br from-cyan-400 to-blue-600 rounded-xl flex items-center justify-center mx-auto mb-3">
                                <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                                </svg>
                            </div>
                            <div class="text-2xl md:text-3xl font-bold text-cyan-300 mb-1">3+</div>
                            <div class="text-blue-200 text-sm">{{$t('experience.monthsExperience')}}</div>
                        </div>
                        <div class="text-center">
                            <div class="w-16 h-16 bg-gradient-to-br from-blue-500 to-indigo-600 rounded-xl flex items-center justify-center mx-auto mb-3">
                                <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                                </svg>
                            </div>
                            <div class="text-2xl md:text-3xl font-bold text-blue-300 mb-1">2</div>
                            <div class="text-blue-200 text-sm">{{$t('experience.companies')}}</div>
                        </div>
                        <div class="text-center">
                            <div class="w-16 h-16 bg-gradient-to-br from-indigo-500 to-purple-600 rounded-xl flex items-center justify-center mx-auto mb-3">
                                <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"></path>
                                </svg>
                            </div>
                            <div class="text-2xl md:text-3xl font-bold text-indigo-300 mb-1">{{$t('experience.current')}}</div>
                            <div class="text-blue-200 text-sm">{{$t('experience.activePosition')}}</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Experience Timeline -->
            <div class="max-w-4xl mx-auto space-y-8">
                <!-- Outlier Freelance -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-6 md:p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-6">
                        <div class="flex items-center mb-4 md:mb-0">
                            <div class="w-12 h-12 md:w-16 md:h-16 bg-gradient-to-br from-cyan-400 to-blue-600 rounded-xl flex items-center justify-center mr-4">
                                <svg class="w-6 h-6 md:w-8 md:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"></path>
                                </svg>
                            </div>
                            <div>
                                <h3 class="text-xl md:text-2xl font-bold text-white">{{$t('experience.outlier.title')}}</h3>
                                <p class="text-cyan-300 text-base md:text-lg">{{$t('experience.outlier.work.title')}}</p>
                                <div class="flex items-center mt-2 space-x-3">
                                    <span class="inline-block bg-cyan-400/20 text-cyan-300 px-2 py-1 rounded-full text-xs font-medium">
                                        Freelance
                                    </span>
                                </div>
                            </div>
                        </div>
                        <div class="text-left md:text-right">
                            <span class="inline-block bg-cyan-400/20 text-cyan-300 px-3 md:px-4 py-2 rounded-full text-sm font-medium">
                                {{$t('experience.outlier.date')}}
                            </span>
                        </div>
                    </div>
                    <div class="space-y-4">
                        <div class="flex items-start space-x-3">
                            <div class="w-2 h-2 bg-cyan-400 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-blue-200 leading-relaxed text-sm md:text-base">
                                {{$t('experience.outlier.work.description_1')}}
                            </p>
                        </div>
                        <div class="flex items-start space-x-3">
                            <div class="w-2 h-2 bg-cyan-400 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-blue-200 leading-relaxed text-sm md:text-base">
                                {{$t('experience.outlier.work.description_2')}}
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Alta Software -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-6 md:p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-6">
                        <div class="flex items-center mb-4 md:mb-0">
                            <div class="w-12 h-12 md:w-16 md:h-16 bg-gradient-to-br from-blue-500 to-indigo-600 rounded-xl flex items-center justify-center mr-4">
                                <svg class="w-6 h-6 md:w-8 md:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                                </svg>
                            </div>
                            <div>
                                <h3 class="text-xl md:text-2xl font-bold text-white">{{$t('experience.altaSoftware.title')}}</h3>
                                <p class="text-cyan-300 text-base md:text-lg">{{$t('experience.altaSoftware.work.title')}}</p>
                                <div class="flex items-center mt-2 space-x-3">
                                    <span class="inline-block bg-green-400/20 text-green-300 px-2 py-1 rounded-full text-xs font-medium">
                                        Remote
                                    </span>
                                    <span class="inline-block bg-blue-400/20 text-blue-300 px-2 py-1 rounded-full text-xs font-medium">
                                        Internship
                                    </span>
                                </div>
                            </div>
                        </div>
                        <div class="text-left md:text-right">
                            <span class="inline-block bg-blue-400/20 text-blue-300 px-3 md:px-4 py-2 rounded-full text-sm font-medium">
                                {{$t('experience.altaSoftware.date')}}
                            </span>
                        </div>
                    </div>
                    <div class="space-y-4">
                        <div class="flex items-start space-x-3">
                            <div class="w-2 h-2 bg-blue-400 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-blue-200 leading-relaxed text-sm md:text-base">
                                {{$t('experience.altaSoftware.work.description_1')}}
                            </p>
                        </div>
                        <div class="flex items-start space-x-3">
                            <div class="w-2 h-2 bg-blue-400 rounded-full mt-2 flex-shrink-0"></div>
                            <p class="text-blue-200 leading-relaxed text-sm md:text-base">
                                {{$t('experience.altaSoftware.work.description_2')}}
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Skills Highlight -->
                <div class="bg-gradient-to-r from-cyan-400/10 to-blue-500/10 backdrop-blur-sm rounded-2xl p-6 border border-cyan-400/20">
                    <div class="text-center">
                        <h3 class="text-lg md:text-xl font-bold text-white mb-3">{{$t('experience.keyTechnologies.title')}}</h3>
                        <div class="flex flex-wrap justify-center gap-2 md:gap-3">
                            <span class="bg-cyan-400/20 text-cyan-300 px-2 md:px-3 py-1 rounded-full text-xs md:text-sm">{{$t('experience.keyTechnologies.aiMlTraining')}}</span>
                            <span class="bg-blue-400/20 text-blue-300 px-2 md:px-3 py-1 rounded-full text-xs md:text-sm">Javascript</span>
                            <span class="bg-indigo-400/20 text-indigo-300 px-2 md:px-3 py-1 rounded-full text-xs md:text-sm">PHP/Laravel</span>
                            <span class="bg-purple-400/20 text-purple-300 px-2 md:px-3 py-1 rounded-full text-xs md:text-sm">{{$t('experience.keyTechnologies.debugging')}}</span>
                            <span class="bg-pink-400/20 text-pink-300 px-2 md:px-3 py-1 rounded-full text-xs md:text-sm">{{$t('experience.keyTechnologies.codeReview')}}</span>
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
</style>