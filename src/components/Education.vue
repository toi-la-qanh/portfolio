<template>
    <div class="w-full min-h-screen bg-gradient-to-br from-blue-800 via-indigo-800 to-purple-900 relative overflow-hidden" id="education">
        <!-- Background Elements -->
        <div class="absolute inset-0">
            <div class="absolute top-10 right-10 w-64 h-64 bg-blue-400/10 rounded-full blur-3xl animate-pulse"></div>
            <div class="absolute bottom-10 left-10 w-80 h-80 bg-indigo-400/10 rounded-full blur-3xl animate-pulse delay-700"></div>
        </div>

        <!-- Main Content -->
        <div class="relative z-10 py-12 sm:py-16 md:py-20 px-4 sm:px-6">
            <!-- Section Title -->
            <div class="text-center mb-8 sm:mb-12 md:mb-16">
                <h1 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-3 sm:mb-4 animate-fade-in">
                    {{$t('education.title')}}
                </h1>
                <div class="w-16 sm:w-20 md:w-24 h-1 bg-gradient-to-r from-cyan-400 to-blue-500 mx-auto rounded-full"></div>
            </div>

            <!-- Education Cards -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8 max-w-6xl mx-auto">
                <!-- University Card -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-4 sm:p-6 md:p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105 hover:shadow-2xl">
                    <div class="flex items-center mb-4 sm:mb-6">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 md:w-16 md:h-16 bg-gradient-to-br from-cyan-400 to-blue-600 rounded-xl flex items-center justify-center mr-3 sm:mr-4">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7 md:w-8 md:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"></path>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-lg sm:text-xl font-bold text-white">{{$t('education.university.major')}}</h3>
                        </div>
                    </div>
                    <div class="space-y-2 sm:space-y-3">
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                            </svg>
                            <span class="break-words">{{$t('education.university.name')}}</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                            </svg>
                            <span>2021 - 2025</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                            <span>{{$t('education.university.diploma')}}</span>
                        </div>
                    </div>
                </div>

                <!-- High School Card -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-4 sm:p-6 md:p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105 hover:shadow-2xl">
                    <div class="flex items-center mb-4 sm:mb-6">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 md:w-16 md:h-16 bg-gradient-to-br from-blue-500 to-indigo-600 rounded-xl flex items-center justify-center mr-3 sm:mr-4">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7 md:w-8 md:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.746 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-lg sm:text-xl font-bold text-white">{{$t('education.highSchool.major')}}</h3>
                        </div>
                    </div>
                    <div class="space-y-2 sm:space-y-3">
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                            </svg>
                            <span class="break-words">{{$t('education.highSchool.name')}}</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                            </svg>
                            <span>2018 - 2021</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                            <span>{{$t('education.highSchool.diploma')}}</span>
                        </div>
                    </div>
                </div>

                <!-- Certifications Card -->
                <div class="group bg-white/10 backdrop-blur-sm rounded-2xl p-4 sm:p-6 md:p-8 border border-white/20 hover:bg-white/20 transition-all duration-500 transform hover:scale-105 hover:shadow-2xl">
                    <div class="flex items-center mb-4 sm:mb-6">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 md:w-16 md:h-16 bg-gradient-to-br from-indigo-500 to-purple-600 rounded-xl flex items-center justify-center mr-3 sm:mr-4">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7 md:w-8 md:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-lg sm:text-xl font-bold text-white">{{$t('education.certifications.title')}}</h3>
                        </div>
                    </div>
                    <div class="space-y-2 sm:space-y-3">
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                            <span class="break-words">{{$t('education.certifications.toeic')}}</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                            <span class="break-words">{{$t('education.certifications.english')}}</span>
                        </div>
                        <div class="flex items-center text-blue-200 text-sm sm:text-base">
                            <svg class="w-4 h-4 sm:w-5 sm:h-5 mr-2 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                            <span class="break-words">{{$t('education.certifications.professionalCommunication')}}</span>
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