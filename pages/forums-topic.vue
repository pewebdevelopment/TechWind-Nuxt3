<template>
    
        <!-- Start Hero -->
        <section class="relative table w-full py-32 lg:py-40 bg-gray-50 dark:bg-slate-800">
            <div class="container">
                <div class="grid grid-cols-1 text-center mt-10">
                    <h3 class="text-3xl leading-normal font-medium">Techwind Announcements</h3>
                </div><!--end grid-->
            </div><!--end container-->
            
            <div class="absolute text-center z-10 bottom-5 right-0 left-0 mx-3">
                <ul class="breadcrumb tracking-[0.5px] mb-0 inline-block">
                    <li class="inline breadcrumb-item uppercase text-[13px] font-bold duration-500 ease-in-out hover:text-indigo-600"><a href="index.html">Techwind</a></li>
                    <li class="inline breadcrumb-item uppercase text-[13px] font-bold duration-500 ease-in-out hover:text-indigo-600"><a href="index-forums.html">Forum</a></li>
                    <li class="inline breadcrumb-item uppercase text-[13px] font-bold text-indigo-600" aria-current="page">Techwind Announcements</li>
                </ul>
            </div>
        </section><!--end section-->
        <div class="relative">
            <div class="shape absolute right-0 sm:-bottom-px -bottom-[2px] left-0 overflow-hidden z-1 text-white dark:text-slate-900">
                <svg class="w-full h-auto" viewBox="0 0 2880 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0 48H1437.5H2880V0H2160C1442.5 52 720 0 720 0H0V48Z" fill="currentColor"></path>
                </svg>
            </div>
        </div>
        <!-- End Hero -->

        <!-- Start -->
        <section class="relative md:py-24 py-16">
            <div class="container">
                <div class="grid lg:grid-cols-12 grid-cols-1 gap-[30px]">
                    <div class="lg:col-span-8">
                        <div class="relative overflow-x-auto block w-full bg-white dark:bg-slate-900 rounded-md border border-gray-100 dark:border-slate-800">
                            <table class="w-full ltr:text-left rtl:text-right">
                                <thead class="text-lg border-b border-gray-100 dark:border-slate-800">
                                    <tr>
                                        <th class="py-6 px-4 font-semibold min-w-[300px]">Topics</th>
                                        <th class="text-center py-6 px-4 font-semibold min-w-[160px]">Comments</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-comments.html" class="hover:text-indigo-600 text-lg">Changelog</a>
                                                    <p class="text-slate-400 font-normal">Write by: <a href="" class="text-indigo-600">Calvin Carlo</a></p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">3</td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-comments.html" class="hover:text-indigo-600 text-lg">Documentation</a>
                                                    <p class="text-slate-400 font-normal">Write by: <a href="" class="text-indigo-600">Alia Reddy</a></p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">5</td>
                                    </tr><!--end topic content-->
                                    
                                    <tr class="border-b border-gray-100 dark:border-slate-800">
                                        <th class="p-4">
                                            <div class="flex">
                                                <i class="uil uil-comment text-indigo-600 text-2xl"></i>
    
                                                <div class="ltr:ml-2 rtl:mr-2">
                                                    <a href="forum-comments.html" class="hover:text-indigo-600 text-lg">Components</a>
                                                    <p class="text-slate-400 font-normal">Write by: <a href="" class="text-indigo-600">Cristino Murphy</a></p>
                                                </div>
                                            </div>
                                        </th>
                                        <td class="text-center p-4">2</td>
                                    </tr><!--end topic content-->
                                </tbody>
                            </table>
                        </div>
                    </div><!--end col-->

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