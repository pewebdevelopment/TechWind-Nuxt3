<template>
    <!-- Start Hero -->
    <section class="relative h-screen flex justify-center items-center bg-slate-50 dark:bg-slate-800">
        <div class="container">
            <div class="md:flex justify-center">
                <div class="lg:w-2/5">
                    <div class="relative overflow-hidden rounded-md bg-white dark:bg-slate-900 shadow dark:shadow-gray-800">
                        <div class="px-6 py-12 bg-emerald-600 text-center">
                            <i class="uil uil-check-circle text-white text-8xl"></i>
                            <h5 class="text-white text-xl tracking-wide uppercase font-semibold mt-2">Success</h5>
                        </div>

                        <div class="px-6 py-12 text-center">
                            <p class="text-black font-semibold text-xl dark:text-white">Congratulations! 🎉</p>
                            <p class="text-slate-400 mt-4">Your account has been successfully created. <br> Enjoy your
                                journey. Thank you</p>

                            <div class="mt-6">
                                <a href="/"
                                    class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigobg-indigo-700 text-white rounded-md">Continue</a>
                            </div>
                        </div>

                        <div class="text-center p-6 border-t border-gray-100 dark:border-gray-700">
                            <p class="mb-0 text-slate-400">© Techwind. Design with <i
                                    class="mdi mdi-heart text-red-600"></i> by <a href="https://shreethemes.in/"
                                    target="_blank" class="text-reset">Shreethemes</a>.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div><!--end container-->
    </section><!--end section-->
    <!-- End Hero -->

    <!-- Back to top -->
    <a href="#" onclick="topFunction()" id="back-to-top"
        class="back-to-top fixed hidden text-lg rounded-full z-10 bottom-5 ltr:right-5 rtl:left-5 h-9 w-9 text-center bg-indigo-600 text-white leading-9"><i
            class="uil uil-arrow-up"></i></a>
    <!-- Back to top -->

    <!-- Switcher -->
    <div class="fixed top-[30%] -right-2 z-50">
        <span class="relative inline-block rotate-90">
            <input type="checkbox" class="checkbox opacity-0 absolute" id="chk" />
            <label
                class="label bg-slate-900 dark:bg-white shadow dark:shadow-gray-800 cursor-pointer rounded-full flex justify-between items-center p-1 w-14 h-8"
                for="chk">
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
        <span
            class="py-1 px-3 relative inline-block rounded-t-md -rotate-90 bg-white dark:bg-slate-900 shadow-md dark:shadow dark:shadow-gray-800 font-bold rtl:block ltr:hidden">LTR</span>
        <span
            class="py-1 px-3 relative inline-block rounded-t-md -rotate-90 bg-white dark:bg-slate-900 shadow-md dark:shadow dark:shadow-gray-800 font-bold ltr:block rtl:hidden">RTL</span>
    </a>
</div>
<!-- LTR & RTL Mode Code --></template>