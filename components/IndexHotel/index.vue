<template>
    
        <!-- Start Hero -->
        <section class="relative table w-full py-36 lg:py-64">
            <div class="absolute inset-0" id="overlay"></div>
            <div class="absolute inset-0 ltr:md:bg-gradient-to-l rtl:md:bg-gradient-to-r md:from-transparent md:via-indigo-600/80 md:to-indigo-800"></div>
            <div class="container">
                <div class="grid grid-cols-1">
                    <div class="ltr:md:text-left rtl:md:text-right text-center mt-10">
                        <h1 class="font-bold text-white lg:leading-normal leading-normal text-4xl lg:text-5xl mb-6">Make your holidays <br> memorables</h1>
                        <p class="text-white/70 text-xl max-w-xl">Start working with Tailwind CSS that can provide everything you need to generate awareness, drive traffic, connect.</p>

                        <a href="">
                            <i class="mdi mdi-arrow-down text-center inline-flex items-center justify-center rounded-full bg-white dark:bg-slate-900 h-12 w-12 mx-auto shadow-md dark:shadow-gray-800 mt-6"></i>
                        </a>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->
        </section><!--end section-->
        <!-- End Hero -->

        <!-- Start -->
        <section class="relative">
            <div class="container">
                <div class="grid grid-cols-1 justify-center">
                    <div class="relative -mt-28">
                        <div class="p-6 bg-white dark:bg-slate-900 rounded-md shadow dark:shadow-gray-800">
                            <div class="section-title">
                                <h4 class="text-2xl font-semibold mb-3">Search your trip</h4>
                                <p class="text-slate-400 mx-auto para-desc">We make it a priority to offer flexible services to accomodate your needs</p>
                            </div>

                            <form class="mt-4" action="#">
                                <div class="grid lg:grid-cols-5 md:grid-cols-2 grid-cols-1 gap-4">
                                    <div>
                                        <label class="font-semibold">Check in :</label>
                                        <input name="date" type="text" class="form-input mt-2 start" placeholder="Select date :">
                                    </div>

                                    <div>
                                        <label class="font-semibold">Check out :</label>
                                        <input name="date1" type="text" class="form-input mt-2 end" placeholder="Select date :">
                                    </div>

                                    <div>
                                        <label class="font-semibold">Adults :</label>
                                        <input type="number" min="0" autocomplete="off" id="adult" class="form-input mt-2" required="false" placeholder="Adults :">
                                    </div>

                                    <div>
                                        <label class="font-semibold">Childrens :</label>
                                        <input type="number" min="0" autocomplete="off" id="childrens" class="form-input mt-2" required="false" placeholder="Childrens :">
                                    </div>

                                    <div class="lg:mt-7">
                                        <input type="submit" id="submit" name="send" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md w-full" value="Search Now">
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->
        </section>

        <section class="relative md:py-24 py-16 overflow-hidden">
            <div class="container">
                <div class="grid md:grid-cols-12 grid-cols-1 items-center gap-[30px]">
                    <div class="lg:col-span-5 md:col-span-6">
                        <div class="relative">
                            <img src="@/assets/images/hotel/ab1.jpg" class="rounded-full lg:w-[400px] w-[280px]" alt="">
                            <div class="absolute ltr:-right-5 rtl:-left-5 -bottom-16">
                                <img src="@/assets/images/hotel/ab2.jpg" class="rounded-full lg:w-[280px] w-[200px] border-8 border-white dark:border-slate-900" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7 md:col-span-6 mt-8 md:mt-0">
                        <div class="ltr:lg:ml-5 rtl:lg:mr-5">
                            <h3 class="mb-6 md:text-3xl text-2xl md:leading-normal leading-normal font-semibold">Get inspiration for future trips weekly</h3>

                            <p class="text-slate-400 max-w-xl">Start working with Tailwind CSS that can provide everything you need to generate awareness, drive traffic, connect. Dummy text is text that is used in the publishing industry or by web designers to occupy the space which will later be filled with 'real' content.</p>

                            <ul class="list-none text-slate-400 mt-4">
                                <li class="mb-1 flex"><i class="uil uil-check-circle text-indigo-600 text-xl ltr:mr-2 rtl:ml-2"></i> Digital Marketing Solutions for Tomorrow</li>
                                <li class="mb-1 flex"><i class="uil uil-check-circle text-indigo-600 text-xl ltr:mr-2 rtl:ml-2"></i> Our Talented & Experienced Marketing Agency</li>
                                <li class="mb-1 flex"><i class="uil uil-check-circle text-indigo-600 text-xl ltr:mr-2 rtl:ml-2"></i> Create your own skin to match your brand</li>
                            </ul>
                        
                            <div class="mt-6">
                                <a href="contact-one.html" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md ltr:mr-2 rtl:ml-2 mt-2"><i class="uil uil-envelope"></i> Contact us</a>
                            </div>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid md:grid-cols-6 grid-cols-2 justify-center gap-[30px]">
                    <div class="mx-auto py-4">
                        <img src="@/assets/images/client/amazon.svg" class="h-6" alt="">
                    </div>

                    <div class="mx-auto py-4">
                        <img src="@/assets/images/client/google.svg" class="h-6" alt="">
                    </div>
                    
                    <div class="mx-auto py-4">
                        <img src="@/assets/images/client/lenovo.svg" class="h-6" alt="">
                    </div>
                    
                    <div class="mx-auto py-4">
                        <img src="@/assets/images/client/paypal.svg" class="h-6" alt="">
                    </div>
                    
                    <div class="mx-auto py-4">
                        <img src="@/assets/images/client/shopify.svg" class="h-6" alt="">
                    </div>
                    
                    <div class="mx-auto py-4">
                        <img src="@/assets/images/client/spotify.svg" class="h-6" alt="">
                    </div>
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid grid-cols-1 pb-8 text-center">
                    <h3 class="mb-6 md:text-3xl text-2xl md:leading-normal leading-normal font-semibold">Popular Tours</h3>

                    <p class="text-slate-400 max-w-xl mx-auto">Start working with Tailwind CSS that can provide everything you need to generate awareness, drive traffic, connect.</p>
                </div><!--end grid-->

                <div class="grid lg:grid-cols-4 md:grid-cols-3 grid-cols-1 gap-[30px] mt-8">
                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/1.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/2.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/3.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/4.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/5.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/6.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/7.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->

                    <div class="group relative overflow-hidden rounded-md shadow dark:shadow-gray-800">
                        <img src="@/assets/images/hotel/8.jpg" alt="">
                        <span class="absolute inset-0 bg-slate-900/20 duration-500"></span>
                        <div class="absolute top-0 left-0 p-4 pb-0">
                            <span class="bg-orange-600 text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Recommend</span>
                        </div>

                        <div class="absolute bottom-0 left-0 right-0 p-4 pt-0">
                            <a href="" class="text-white/80 hover:text-white text-xl font-semibold">Paradise Beach, Island</a>

                            <div class="flex justify-between mt-1">
                                <span class="text-gray-100"><i class="uil uil-dollar-sign text-[18px]"></i> 549</span>
                                <span class="text-gray-100"><i class="uil uil-plane-fly text-[18px]"></i> 10 Days</span>
                            </div>
                        </div>
                    </div><!--end content-->
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid md:grid-cols-12 grid-cols-1 items-center gap-[30px]">
                    <div class="lg:col-span-5 md:col-span-6 order-1 md:order-2">
                        <img src="@/assets/images/hotel/ab3.jpg" class="rounded-full" alt="">
                    </div>

                    <div class="lg:col-span-7 md:col-span-6 order-2 md:order-1">
                        <div class="ltr:lg:mr-5 rtl:lg:ml-5">
                            <h3 class="mb-6 md:text-3xl text-2xl md:leading-normal leading-normal font-semibold">Resort Surprises</h3>

                            <p class="text-slate-400 max-w-xl">Start working with Tailwind CSS that can provide everything you need to generate awareness, drive traffic, connect. Dummy text is text that is used in the publishing industry or by web designers to occupy the space which will later be filled with 'real' content.</p>

                            <ul class="list-none text-slate-400 mt-4">
                                <li class="mb-1 flex"><i class="uil uil-check-circle text-indigo-600 text-xl ltr:mr-2 rtl:ml-2"></i> Digital Marketing Solutions for Tomorrow</li>
                                <li class="mb-1 flex"><i class="uil uil-check-circle text-indigo-600 text-xl ltr:mr-2 rtl:ml-2"></i> Our Talented & Experienced Marketing Agency</li>
                                <li class="mb-1 flex"><i class="uil uil-check-circle text-indigo-600 text-xl ltr:mr-2 rtl:ml-2"></i> Create your own skin to match your brand</li>
                            </ul>
                        
                            <div class="mt-6">
                                <a href="#!" data-type="youtube" data-id="yba7hPeTSjk" class="btn btn-icon rounded-full bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white lightbox"><i data-feather="video" class="h-4 w-4"></i></a><span class="font-semibold ltr:ml-2 rtl:mr-2 align-middle">Watch Now</span>
                            </div>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid grid-cols-1 pb-8 text-center">
                    <h3 class="mb-6 md:text-3xl md:leading-normal text-2xl leading-normal font-semibold">What our customer <br> say about us</h3>

                    <p class="text-slate-400 max-w-xl mx-auto">Start working with Techwind that can provide everything you need to generate awareness, drive traffic, connect.</p>
                </div><!--end grid-->

                <div class="grid grid-cols-1 mt-8">
                    <div class="tiny-three-item">
                        <div class="tiny-slide text-center">
                            <div class="customer-testi">
                                <div class="content relative rounded shadow dark:shadow-gray-800 m-2 p-6 bg-white dark:bg-slate-900">
                                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                                    <p class="text-slate-400">" It seems that only fragments of the original text remain in the Lorem Ipsum texts used today. "</p>
                                    <ul class="list-none mb-0 text-amber-400 mt-3">
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                    </ul>
                                </div>
                                
                                <div class="text-center mt-5">
                                    <img src="@/assets/images/client/01.jpg" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                                    <h6 class="mt-2 font-semibold">Calvin Carlo</h6>
                                    <span class="text-slate-400 text-sm">Manager</span>
                                </div>
                            </div>
                        </div>

                        <div class="tiny-slide text-center">
                            <div class="customer-testi">
                                <div class="content relative rounded shadow dark:shadow-gray-800 m-2 p-6 bg-white dark:bg-slate-900">
                                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                                    <p class="text-slate-400">" The most well-known dummy text is the 'Lorem Ipsum', which is said to have originated in the 16th century. "</p>
                                    <ul class="list-none mb-0 text-amber-400 mt-3">
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                    </ul>
                                </div>
                                
                                <div class="text-center mt-5">
                                    <img src="@/assets/images/client/02.jpg" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                                    <h6 class="mt-2 font-semibold">Christa Smith</h6>
                                    <span class="text-slate-400 text-sm">Manager</span>
                                </div>
                            </div>
                        </div>

                        <div class="tiny-slide text-center">
                            <div class="customer-testi">
                                <div class="content relative rounded shadow dark:shadow-gray-800 m-2 p-6 bg-white dark:bg-slate-900">
                                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                                    <p class="text-slate-400">" One disadvantage of Lorum Ipsum is that in Latin certain letters appear more frequently than others. "</p>
                                    <ul class="list-none mb-0 text-amber-400 mt-3">
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                    </ul>
                                </div>
                                
                                <div class="text-center mt-5">
                                    <img src="@/assets/images/client/03.jpg" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                                    <h6 class="mt-2 font-semibold">Jemina CLone</h6>
                                    <span class="text-slate-400 text-sm">Manager</span>
                                </div>
                            </div>
                        </div>

                        <div class="tiny-slide text-center">
                            <div class="customer-testi">
                                <div class="content relative rounded shadow dark:shadow-gray-800 m-2 p-6 bg-white dark:bg-slate-900">
                                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                                    <p class="text-slate-400">" Thus, Lorem Ipsum has only limited suitability as a visual filler for German texts. "</p>
                                    <ul class="list-none mb-0 text-amber-400 mt-3">
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                    </ul>
                                </div>
                                
                                <div class="text-center mt-5">
                                    <img src="@/assets/images/client/04.jpg" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                                    <h6 class="mt-2 font-semibold">Smith Vodka</h6>
                                    <span class="text-slate-400 text-sm">Manager</span>
                                </div>
                            </div>
                        </div>

                        <div class="tiny-slide text-center">
                            <div class="customer-testi">
                                <div class="content relative rounded shadow dark:shadow-gray-800 m-2 p-6 bg-white dark:bg-slate-900">
                                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                                    <p class="text-slate-400">" There is now an abundance of readable dummy texts. These are usually used when a text is required. "</p>
                                    <ul class="list-none mb-0 text-amber-400 mt-3">
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                    </ul>
                                </div>
                                
                                <div class="text-center mt-5">
                                    <img src="@/assets/images/client/05.jpg" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                                    <h6 class="mt-2 font-semibold">Cristino Murfi</h6>
                                    <span class="text-slate-400 text-sm">Manager</span>
                                </div>
                            </div>
                        </div>

                        <div class="tiny-slide text-center">
                            <div class="customer-testi">
                                <div class="content relative rounded shadow dark:shadow-gray-800 m-2 p-6 bg-white dark:bg-slate-900">
                                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                                    <p class="text-slate-400">" According to most sources, Lorum Ipsum can be traced back to a text composed by Cicero. "</p>
                                    <ul class="list-none mb-0 text-amber-400 mt-3">
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                        <li class="inline"><i class="mdi mdi-star"></i></li>
                                    </ul>
                                </div>
                                
                                <div class="text-center mt-5">
                                    <img src="@/assets/images/client/06.jpg" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                                    <h6 class="mt-2 font-semibold">Cristino Murfi</h6>
                                    <span class="text-slate-400 text-sm">Manager</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid grid-cols-1 pb-8 text-center">
                    <h3 class="mb-6 md:text-3xl text-2xl md:leading-normal leading-normal font-semibold">Blog Or News</h3>

                    <p class="text-slate-400 max-w-xl mx-auto">Start working with Tailwind CSS that can provide everything you need to generate awareness, drive traffic, connect.</p>
                </div><!--end grid-->

                <div class="grid grid-cols-1 lg:grid-cols-3 md:grid-cols-2 mt-8 gap-[30px]">
                    <div class="blog relative rounded-md shadow dark:shadow-gray-800 overflow-hidden">
                        <img src="@/assets/images/hotel/b1.jpg" alt="">

                        <div class="content p-6">
                            <a href="blog-detail.html" class="title h5 text-lg font-medium hover:text-indigo-600 duration-500 ease-in-out">Design your apps in your own way</a>
                            <p class="text-slate-400 mt-3">The phrasal sequence of the is now so that many campaign and benefit</p>
                            
                            <div class="mt-4">
                                <a href="blog-detail.html" class="btn btn-link font-normal hover:text-indigo-600 after:bg-indigo-600 duration-500 ease-in-out">Read More <i class="uil uil-arrow-right"></i></a>
                            </div>
                        </div>
                    </div>

                    <div class="blog relative rounded-md shadow dark:shadow-gray-800 overflow-hidden">
                        <img src="@/assets/images/hotel/b2.jpg" alt="">

                        <div class="content p-6">
                            <a href="blog-detail.html" class="title h5 text-lg font-medium hover:text-indigo-600 duration-500 ease-in-out">How apps is changing the IT world</a>
                            <p class="text-slate-400 mt-3">The phrasal sequence of the is now so that many campaign and benefit</p>
                            
                            <div class="mt-4">
                                <a href="blog-detail.html" class="btn btn-link font-normal hover:text-indigo-600 after:bg-indigo-600 duration-500 ease-in-out">Read More <i class="uil uil-arrow-right"></i></a>
                            </div>
                        </div>
                    </div>

                    <div class="blog relative rounded-md shadow dark:shadow-gray-800 overflow-hidden">
                        <img src="@/assets/images/hotel/b3.jpg" alt="">

                        <div class="content p-6">
                            <a href="blog-detail.html" class="title h5 text-lg font-medium hover:text-indigo-600 duration-500 ease-in-out">Smartest Applications for Business</a>
                            <p class="text-slate-400 mt-3">The phrasal sequence of the is now so that many campaign and benefit</p>
                            
                            <div class="mt-4">
                                <a href="blog-detail.html" class="btn btn-link font-normal hover:text-indigo-600 after:bg-indigo-600 duration-500 ease-in-out">Read More <i class="uil uil-arrow-right"></i></a>
                            </div>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->
        </section><!--end section-->
        <!-- end section -->

</template>