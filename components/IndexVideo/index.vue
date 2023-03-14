<template>
    
    <section class="relative h-screen flex items-center">
            <div class="absolute top-0 left-0 w-full h-full z-0 pointer-events-none overflow-hidden">
                <!-- <iframe src="https://player.vimeo.com/video/33955001?background=1&autoplay=1&loop=1&byline=0&title=0" class="absolute top-1/2 ltr:left-1/2 ltr:-translate-x-1/2 rtl:right-1/2 rtl:translate-x-1/2  -translate-y-1/2 w-screen h-[56.25vw] min-h-screen min-w-[177.77vw]"></iframe> -->
                <!--Note: Vimeo Embed Background Video-->

                <iframe src="https://www.youtube.com/embed/gJpXlRkW6Fw?controls=0&showinfo=0&rel=0&autoplay=1&loop=1&mute=1" class="absolute top-1/2 ltr:left-1/2 ltr:-translate-x-1/2 rtl:right-1/2 rtl:translate-x-1/2  -translate-y-1/2 w-screen h-[56.25vw] min-h-screen min-w-[177.77vw]"></iframe>
                <!--Note: Youtube Embed Background Video-->
            </div>
            <div class="absolute inset-0 bg-black/40"></div>
            
            <div class="container">
                <div class="grid grid-cols-1">
                    <img src="@/assets/images/video/bg.png" alt="">
                </div>
            </div>

            <div class="container-fluid">
                <div class="fixed bottom-0 left-0 right-0 pb-8">
                    <div class="container">
                        <div class="grid grid-cols-1">
                            <div class="block">
                                <div class="flex justify-between">
                                    <h5 class="text-white text-xl font-semibold">Videos for Ads</h5>
                                    <a href="video-portfolio.html" class="btn btn-link text-white hover:text-white after:bg-white duration-500 ease-in-out">See Videos <i class="uil uil-arrow-right"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

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
</template>