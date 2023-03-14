<template>
     
        <!-- Start -->
        <section class="relative bg-[url('../../assets/images/utility.jpg')] bg-no-repeat bg-center bg-cover">
            <div class="absolute inset-0 bg-black/25"></div>
            <div class="absolute inset-0 bg-gradient-to-b from-transparent via-black/40 to-black"></div>
            <div class="container-fluid relative">
                <div class="grid grid-cols-1">
                    <div class="flex flex-col min-h-screen justify-center md:px-10 py-10 px-4">
                        <div class="text-center">
                            <a href="/"><img src="@/assets/images/logo-icon-64.png" class="mx-auto" alt=""></a>
                        </div>
                        <div class="title-heading text-center my-auto">
                            <h1 class="text-white mt-3 mb-6 md:text-5xl text-3xl font-bold">We Are Coming Soon...</h1>
                            <p class="text-white/70 text-lg max-w-xl mx-auto">Start working with Techwind that can provide everything you need to generate awareness, drive traffic, connect.</p>
                        
                            <div id="countdown">
                                <ul class="count-down list-none inline-block text-white text-center mt-8 m-6">
                                    <li id="days" class="count-number inline-block m-2"></li>
                                    <li id="hours" class="count-number inline-block m-2"></li>
                                    <li id="mins" class="count-number inline-block m-2"></li>
                                    <li id="secs" class="count-number inline-block m-2"></li>
                                    <li id="end" class="h1"></li>
                                </ul>
                            </div>
                        </div>
                        <div class="text-center">
                            <p class="mb-0 text-slate-400">©  Techwind. Design with <i class="mdi mdi-heart text-red-600"></i> by <a href="https://shreethemes.in/" target="_blank" class="text-reset">Shreethemes</a>.</p>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->
        </section><!--end section-->

        <div class="fixed bottom-3 ltr:right-3 rtl:left-3">
            <a href="" class="back-button btn btn-icon bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-full"><i data-feather="arrow-left" class="h-4 w-4"></i></a>
        </div>

        <!-- Switcher -->
        <div class="fixed top-[30%] -right-2 z-50">
            <span class="relative inline-block rotate-90">
                <input type="checkbox" class="checkbox opacity-0 absolute" id="chk" />
                <label class="label bg-slate-900 dark:bg-white shadow dark:shadow-gray-800 cursor-pointer rounded-full flex justify-between items-center p-1 w-14 h-8" for="chk">
                    <i class="uil uil-moon text-[20px] text-yellow-500"></i>
                    <i class="uil uil-sun text-[20px] text-yellow-500"></i>
                    <span class="ball bg-white dark:bg-slate-900 rounded-full absolute top-[2px] left-[2px] w-7 h-7"></span>
                </label>
            </span>
        </div>
        <!-- Switcher -->

        <!-- LTR & RTL Mode Code -->
        <div class="fixed top-[40%] -right-3 z-50">
            <a href="" id="switchRtl">
                <span class="py-1 px-3 relative inline-block rounded-t-md -rotate-90 bg-white dark:bg-slate-900 shadow-md dark:shadow dark:shadow-gray-800 font-bold rtl:block ltr:hidden" >LTR</span>
                <span class="py-1 px-3 relative inline-block rounded-t-md -rotate-90 bg-white dark:bg-slate-900 shadow-md dark:shadow dark:shadow-gray-800 font-bold ltr:block rtl:hidden">RTL</span>
            </a>
        </div>
        <!-- LTR & RTL Mode Code -->
       
</template>