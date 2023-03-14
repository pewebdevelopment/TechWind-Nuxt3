<template>
     <section class="relative table w-full py-36 md:py-56 bg-gray-50 dark:bg-slate-800">
            <div class="container">
                <div class="grid grid-cols-1 mt-10 text-center">
                    <h3 class="font-bold uppercase leading-normal text-4xl mb-5">Welcome to the Techwind Forum</h3>

                    <p class="text-slate-400 text-lg mx-auto">We're here to help. Get in touch and we'll get back to you as soon as we can</p>
                
                    <div class="subcribe-form mt-6">
                        <form class="relative max-w-xl mx-auto">
                            <input type="text" id="SearchForumKeyword" name="text" class="pt-4 ltr:pr-14 rtl:pl-14 pb-4 ltr:pl-6 rtl:pr-6 w-full h-[50px] outline-none text-black dark:text-white rounded-full bg-white dark:bg-slate-900 shadow dark:shadow-gray-800" placeholder="Enter your keywords :">
                            <button type="submit" class="btn btn-icon absolute top-[2px] ltr:right-[3px] rtl:left-[3px] w-[46px] h-[46px] bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-full"><i class="uil uil-search"></i></button>
                        </form><!--end form-->
                    </div>
                </div><!--end grid-->
            </div><!--end container-->
        </section><!--end section-->
        <!-- End -->

        <!-- Start -->
        <section class="relative md:pb-24 pb-16">
            <div class="container">
                <div class="grid grid-cols-1">
                    <div class="relative -mt-12 rounded-md shadow dark:shadow-gray-800 overflow-hidden bg-white dark:bg-slate-900">
                        <div class="grid md:grid-cols-12 grid-cols-1 items-center">
                            <div class="md:col-span-6">
                                <div class="w-full py-52 bg-slate-400 bg-[url('../../@/assets/images/saas/cta.jpg')] bg-no-repeat bg-top bg-cover jarallax" data-jarallax data-speed="0.5"></div>
                            </div><!--end col-->
                            <div class="md:col-span-6">
                                <div class="p-6">
                                    <h3 class="mb-6 md:text-3xl text-2xl md:leading-normal leading-normal font-semibold">Join Our Forum</h3>
    
                                    <p class="text-slate-400 max-w-xl">Talk about anything that's on your mind and see what others think. As a guest to our forum you are only able to view posts. When you register with the Forumix forum you can join in with topics, start new topics and generally be a part of the first level of our community.</p>
    
                                    <div class="mt-6">
                                        <a href="" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded ltr:mr-2 rtl:ml-2 mt-2">Register Now!</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div><!--end grid-->
            </div><!--end container-->

            <div class="container md:mt-24 mt-16">
                <div class="grid lg:grid-cols-12 grid-cols-1 gap-[30px]">
                    <div class="lg:col-span-8">
                        <div class="relative overflow-x-auto block w-full bg-white dark:bg-slate-900 rounded-md border border-gray-100 dark:border-slate-800">
                            <table class="w-full ltr:text-left rtl:text-right">
                                <thead class="text-lg border-b border-gray-100 dark:border-slate-800">
                                    <tr>
                                        <th class="py-6 px-4 font-semibold min-w-[300px]">Forum</th>
                                        <th class="text-center py-6 px-4 font-semibold min-w-[40px]">Topics</th>
                                        <th class="text-center py-6 px-4 font-semibold min-w-[40px]">Comments</th>
                                        <th class="py-6 px-4 font-semibold min-w-[220px]">Posted</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Techwind Announcements</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/01.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Calvin Carlo</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Web Designing and Developing</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/03.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Alia Reddy</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Hosting and providers</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/02.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Cristino Murphy</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">SEO starter guide</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/05.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Jennifer Ballance</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Troubleshooting and managing issues</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/04.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Toni Kovar</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Backup and restore</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/06.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Tara Arrington</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Errors and how to fix them</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/05.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Jennifer Ballance</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Template features & Services</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/06.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Tara Arrington</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-topic.html" class="hover:text-indigo-600 text-lg">Techwind includes the ability to create a better of sites by using the multisite feature.</a>
                                                    <p class="text-slate-400 font-normal">This forum is for our announcements. Only our staff can create new topics.</p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                        <td class="text-center p-4">10</td>
                                        <td class="p-4">
                                            <div class="flex items-center">
                                                <img src="@/assets/images/client/06.jpg" class="h-10 rounded-full shadow dark:shadow-slate-800" alt="">
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="" class="hover:text-indigo-600 font-semibold">Tara Arrington</a>
                                                    <p class="text-slate-400 text-sm font-normal"><i class="uil uil-clock"></i> May 2022</p>
                                                </div>
                                            </div>
                                        </td>
                                    </tr><!--end topic content-->
                                </tbody>
                            </table>
                        </div>
                    </div>

                    <div class="lg:col-span-4 md:col-span-6">
                        <div class="sticky top-20">
                            <h5 class="text-lg font-semibold bg-gray-50 dark:bg-slate-800 shadow dark:shadow-gray-800 rounded-md p-2 text-center">Sign In</h5>
                            <form class="ltr:text-left rtl:text-right mt-8">
                                <div class="grid grid-cols-1">
                                    <div class="mb-4">
                                        <label class="font-semibold" for="LoginEmail">Email Address:</label>
                                        <input id="LoginEmail" type="email" class="form-input mt-3" placeholder="name@example.com">
                                    </div>
    
                                    <div class="mb-4">
                                        <label class="font-semibold" for="LoginPassword">Password:</label>
                                        <input id="LoginPassword" type="password" class="form-input mt-3" placeholder="Password:">
                                    </div>
    
                                    <div class="flex justify-between mb-4">
                                        <label for="RememberMe" class="inline-flex items-center">
                                            <input type="checkbox" class="form-checkbox border dark:border-gray-700 rounded text-indigo-600">
                                            <span class="text-slate-400 ml-2">Remember me</span>
                                        </label>
                                        <p class="text-slate-400 mb-0"><a href="auth-re-password.html" class="text-slate-400">Forgot password ?</a></p>
                                    </div>
    
                                    <div class="mb-4">
                                        <input type="submit" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md w-full" value="Login / Sign in">
                                    </div>
    
                                    <div class="text-center">
                                        <span class="text-slate-400 ltr:mr-2 rtl:ml-2">Don't have an account ?</span> <a href="auth-signup.html" class="text-black dark:text-white font-bold inline-block">Sign Up</a>
                                    </div>
                                </div>
                            </form>

                            <h5 class="text-lg font-semibold bg-gray-50 dark:bg-slate-800 shadow dark:shadow-gray-800 rounded-md p-2 text-center mt-8">Recent Reply</h5>
                            <div class="flex items-center mt-8">
                                <img src="@/assets/images/blog/06.jpg" class="h-16 rounded-md shadow dark:shadow-gray-800" alt="">

                                <div class="ltr:ml-3 rtl:mr-3">
                                    <a href="" class="font-semibold hover:text-indigo-600">Consultant Business</a>
                                    <p class="text-sm text-slate-400">1st May 2022</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center mt-4">
                                <img src="@/assets/images/blog/07.jpg" class="h-16 rounded-md shadow dark:shadow-gray-800" alt="">

                                <div class="ltr:ml-3 rtl:mr-3">
                                    <a href="" class="font-semibold hover:text-indigo-600">Grow Your Business</a>
                                    <p class="text-sm text-slate-400">1st May 2022</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center mt-4">
                                <img src="@/assets/images/blog/08.jpg" class="h-16 rounded-md shadow dark:shadow-gray-800" alt="">

                                <div class="ltr:ml-3 rtl:mr-3">
                                    <a href="" class="font-semibold hover:text-indigo-600">Look On The Glorious Balance</a>
                                    <p class="text-sm text-slate-400">1st May 2022</p>
                                </div>
                            </div>

                            <h5 class="text-lg font-semibold bg-gray-50 dark:bg-slate-800 shadow dark:shadow-gray-800 rounded-md p-2 text-center mt-8">Social sites</h5>
                            <ul class="list-none text-center mt-8">
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="facebook" class="h-4 w-4"></i></a></li>
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="instagram" class="h-4 w-4"></i></a></li>
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="twitter" class="h-4 w-4"></i></a></li>
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="linkedin" class="h-4 w-4"></i></a></li>
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="github" class="h-4 w-4"></i></a></li>
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="youtube" class="h-4 w-4"></i></a></li>
                                <li class="inline"><a href="" class="btn btn-icon btn-sm border border-gray-100 dark:border-gray-800 rounded-md text-slate-400 hover:border-indigo-600 hover:text-white hover:bg-indigo-600"><i data-feather="gitlab" class="h-4 w-4"></i></a></li>
                            </ul><!--end icon-->

                            <h5 class="text-lg font-semibold bg-gray-50 dark:bg-slate-800 shadow dark:shadow-gray-800 rounded-md p-2 text-center mt-8">Tagscloud</h5>
                            <ul class="list-none text-center mt-8">
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Business</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Finance</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Marketing</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Fashion</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Bride</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Lifestyle</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Travel</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Beauty</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Video</a></li>
                                <li class="inline-block m-2"><a href="" class="px-3 py-1 text-slate-400 hover:text-white dark:hover:text-white bg-gray-50 dark:bg-slate-800 text-sm hover:bg-indigo-600 dark:hover:bg-indigo-600 rounded-md shadow dark:shadow-gray-800 transition-all duration-500 ease-in-out">Audio</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div><!--end container-->
        </section><!--end section-->
        <!-- End -->
</template>