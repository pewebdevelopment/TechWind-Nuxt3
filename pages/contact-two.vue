<template>
    
    <section class="md:h-screen w-full">
            <div class="container-fluid relative">
                <div class="grid grid-cols-1">
                    <div class="grayscale border-0 w-full">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d39206.002432144705!2d-95.4973981212445!3d29.709510002925988!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8640c16de81f3ca5%3A0xf43e0b60ae539ac9!2sGerald+D.+Hines+Waterwall+Park!5e0!3m2!1sen!2sin!4v1566305861440!5m2!1sen!2sin" style="border:0" class="h-screen w-full" allowfullscreen></iframe>
                    </div>

                    <div class="md:flex justify-center fixed top-2/4 -translate-y-2/4 ltr:md:-translate-x-2/4 rtl:md:translate-x-2/4 ltr:md:left-2/4 rtl:md:right-2/4 ltr:left-3 rtl:right-3 ltr:md:right-auto rtl:md:left-auto ltr:right-3 rtl:left-3 m-auto">
                        <div class="max-w-[400px] w-full bg-white dark:bg-slate-900 rounded-md shadow-xl dark:shadow-gray-800 px-6 py-8">
                            <a href="index.html"><img src="@/assets/images/logo-icon-64.png" class="mx-auto" alt=""></a>
                            <h3 class="my-6 text-2xl leading-normal font-medium text-center">Get in touch !</h3>

                            <form method="post" name="myForm" id="myForm" onsubmit="return validateForm()">
                                <p class="mb-0" id="error-msg"></p>
                                <div id="simple-msg"></div>
                                <div class="grid lg:grid-cols-12 lg:gap-6">
                                    <div class="lg:col-span-6 mb-5">
                                        <div class="ltr:text-left rtl:text-right">
                                            <label for="name" class="font-semibold">Your Name:</label>
                                            <div class="form-icon relative mt-2">
                                                <i data-feather="user" class="w-4 h-4 absolute top-3 ltr:left-4 rtl:right-4"></i>
                                                <input name="name" id="name" type="text" class="form-input ltr:pl-11 rtl:pr-11" placeholder="Name :">
                                            </div>
                                        </div>
                                    </div>
    
                                    <div class="lg:col-span-6 mb-5">
                                        <div class="ltr:text-left rtl:text-right">
                                            <label for="email" class="font-semibold">Your Email:</label>
                                            <div class="form-icon relative mt-2">
                                                <i data-feather="mail" class="w-4 h-4 absolute top-3 ltr:left-4 rtl:right-4"></i>
                                                <input name="email" id="email" type="email" class="form-input ltr:pl-11 rtl:pr-11" placeholder="Email :">
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <div class="grid grid-cols-1">
                                    <div class="mb-5">
                                        <div class="ltr:text-left rtl:text-right">
                                            <label for="subject" class="font-semibold">Your Question:</label>
                                            <div class="form-icon relative mt-2">
                                                <i data-feather="book" class="w-4 h-4 absolute top-3 ltr:left-4 rtl:right-4"></i>
                                                <input name="subject" id="subject" class="form-input ltr:pl-11 rtl:pr-11" placeholder="Subject :">
                                            </div>
                                        </div>
                                    </div>

                                    <div class="mb-5">
                                        <div class="ltr:text-left rtl:text-right">
                                            <label for="comments" class="font-semibold">Your Comment:</label>
                                            <div class="form-icon relative mt-2">
                                                <i data-feather="message-circle" class="w-4 h-4 absolute top-3 ltr:left-4 rtl:right-4"></i>
                                                <textarea name="comments" id="comments" class="form-input ltr:pl-11 rtl:pr-11 h-28" placeholder="Message :"></textarea>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <button type="submit" id="submit" name="send" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md w-full justify-center flex items-center">Send Message</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>

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