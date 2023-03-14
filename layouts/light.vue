<template>
    <div dir="ltr">

        <nav id="topnav" class="defaultscroll is-sticky">
            <div class="container">
                <!-- Logo container-->
                <a class="logo" href="/">
                    <span class="inline-block dark:hidden">
                        <img src="@/assets/images/logo-dark.png" class="l-dark" height="24" alt="">
                        <img src="@/assets/images/logo-light.png" class="l-light" height="24" alt="">
                    </span>
                    <img src="@/assets/images/logo-light.png" height="24" class="hidden dark:inline-block" alt="">
                </a>

                <!-- End Logo container-->
                <div class="menu-extras">
                    <div class="menu-item">
                        <!-- Mobile menu toggle-->
                        <a class="navbar-toggle" id="isToggle" onclick="toggleMenu()">
                            <div class="lines">
                                <span></span>
                                <span></span>
                                <span></span>
                            </div>
                        </a>
                        <!-- End mobile menu toggle-->
                    </div>
                </div>

                <!--Login button Start-->
                <ul class="buy-button list-none mb-0">
                    <li class="inline mb-0">
                        <a href="/">
                            <span class="login-btn-primary"><span class="btn btn-icon rounded-full bg-indigo-600/5 hover:bg-indigo-600 border-indigo-600/10 hover:border-indigo-600 text-indigo-600 hover:text-white"><i data-feather="settings" class="h-4 w-4"></i></span></span>
                            <span class="login-btn-light"><span class="btn btn-icon rounded-full bg-gray-50 hover:bg-gray-200 dark:bg-slate-900 dark:hover:bg-gray-700 hover:border-gray-100 dark:border-gray-700 dark:hover:border-gray-700"><i data-feather="settings" class="h-4 w-4"></i></span></span>
                        </a>
                    </li>
            
                    <li class="inline ltr:pl-1 rtl:pr-1 mb-0">
                        <a href="/https://1.envato.market/techwind" target="_blank">
                            <div class="login-btn-primary"><span class="btn btn-icon rounded-full bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white"><i data-feather="shopping-cart" class="h-4 w-4"></i></span></div>
                            <div class="login-btn-light"><span class="btn btn-icon rounded-full bg-gray-50 hover:bg-gray-200 dark:bg-slate-900 dark:hover:bg-gray-700 hover:border-gray-100 dark:border-gray-700 dark:hover:border-gray-700"><i data-feather="shopping-cart" class="h-4 w-4"></i></span></div>
                        </a>
                    </li>
                </ul>
                <!--Login button End-->

                <div id="navigation">
                    <!-- Navigation Menu-->   
                    <ul class="navigation-menu nav-light">
                        <li><a href="/" class="sub-menu-item">Home</a></li>
                
                        <li class="has-submenu parent-parent-menu-item">
                            <a href="/javascript:void(0)">Landings</a><span class="menu-arrow"></span>

                            <ul class="submenu megamenu">
                                <li>
                                    <ul>
                                        <li><a href="/index-saas" class="sub-menu-item">Saas <span class="bg-emerald-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Animation</span></a></li>
                                        <li><a href="/index-classic-saas" class="sub-menu-item">Classic Saas </a></li>
                                        <li><a href="/index-modern-saas" class="sub-menu-item">Modern Saas </a></li>
                                        <li><a href="/index-apps" class="sub-menu-item">Application</a></li>
                                        <li><a href="/index-classic-app" class="sub-menu-item">Classic App </a></li>
                                        <li><a href="/index-smartwatch" class="sub-menu-item">Smartwatch</a></li>
                                        <li><a href="/index-marketing" class="sub-menu-item">Marketing</a></li>
                                        <li><a href="/index-seo" class="sub-menu-item">SEO Agency </a></li>
                                        <li><a href="/index-payment" class="sub-menu-item">Payments</a></li>
                                        <li><a href="/index-charity" class="sub-menu-item">Charity <span class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></a></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li><a href="/index-it-solution" class="sub-menu-item">IT Solution</a></li>
                                        <li><a href="/index-it-solution-two" class="sub-menu-item">It Solution Two </a></li>
                                        <li><a href="/index-digital-agency" class="sub-menu-item">Digital Agency</a></li>
                                        <li><a href="/index-job" class="sub-menu-item">Job</a></li>
                                        <li><a href="/index-restaurent" class="sub-menu-item">Restaurent</a></li>
                                        <li><a href="/index-hosting" class="sub-menu-item">Hosting</a></li>
                                        <li><a href="/index-nft" class="sub-menu-item">NFT Marketplace</a></li>
                                        <li><a href="/index-hotel" class="sub-menu-item">Hotel & Resort</a></li>
                                        <li><a href="/index-gym" class="sub-menu-item">Gym <span class="bg-black dark:bg-slate-50 inline-block text-white dark:text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Dark</span></a></li>
                                        <li><a href="/javascript:void(0)" class="sub-menu-item">Yoga <span class="bg-cyan-500 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Comingsoon</span></a></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li><a href="/index-startup" class="sub-menu-item">Startup</a></li>
                                        <li><a href="/index-business" class="sub-menu-item">Business</a></li>
                                        <li><a href="/index-corporate" class="sub-menu-item">Corporate</a></li>
                                        <li><a href="/index-corporate-two" class="sub-menu-item">Corporate Two </a></li>
                                        <li><a href="/index-real-estate" class="sub-menu-item">Real Estate</a></li>
                                        <li><a href="/index-consulting" class="sub-menu-item">Consulting </a></li>
                                        <li><a href="/index-insurance" class="sub-menu-item">Insurance </a></li>
                                        <li><a href="/index-construction" class="sub-menu-item">Construction </a></li>
                                        <li><a href="/index-law" class="sub-menu-item">Law Firm <span class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></a></li>
                                        <li><a href="/index-video" class="sub-menu-item">Video <span class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></a></li>
                                    </ul>
                                </li>
                        
                                <li>
                                    <ul>
                                        <li><a href="/index-personal" class="sub-menu-item">Personal</a></li>
                                        <li><a href="/index-portfolio" class="sub-menu-item">Portfolio</a></li>
                                        <li><a href="/index-photography" class="sub-menu-item">Photography <span class="bg-black dark:bg-slate-50 inline-block text-white dark:text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Dark</span></a></li>
                                        <li><a href="/index-studio" class="sub-menu-item">Studio</a></li>
                                        <li><a href="/index-coworking" class="sub-menu-item">Co-Woriking</a></li>
                                        <li><a href="/index-course" class="sub-menu-item">Online Courses </a></li>
                                        <li><a href="/index-event" class="sub-menu-item">Event/Conference </a></li>
                                        <li><a href="/index-hospital" class="sub-menu-item">Hospital</a></li>
                                        <li><a href="/javascript:void(0)" class="sub-menu-item">Covid Care <span class="bg-cyan-500 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Comingsoon</span></a></li>
                                        <li><a href="/index-forums" class="sub-menu-item">Forums <span class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></a></li>
                                    </ul>
                                </li>
                        
                                <li>
                                    <ul>
                                        <li><a href="/index-crypto" class="sub-menu-item">Cryptocurrency  <span class="bg-black dark:bg-slate-50 inline-block text-white dark:text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Dark</span></a></li>
                                        <li><a href="/index-landing-one" class="sub-menu-item">Landing One</a></li>
                                        <li><a href="/index-landing-two" class="sub-menu-item">Landing Two</a></li>
                                        <li><a href="/index-landing-three" class="sub-menu-item">Landing Three</a></li>
                                        <li><a href="/index-landing-four" class="sub-menu-item">Landing Four</a></li>
                                        <li><a href="/index-service" class="sub-menu-item">Service Provider</a></li>
                                        <li><a href="/index-food-blog" class="sub-menu-item">Food Blog </a></li>
                                        <li><a href="/index-blog" class="sub-menu-item">Blog </a></li>
                                        <li><a href="/javascript:void(0)" class="sub-menu-item">Furniture <span class="bg-cyan-500 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Comingsoon</span></a></li>
                                        <li><a href="/index-landing-five" class="sub-menu-item">Landing Five <span class="bg-green-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Onepage</span></a></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>

                        <li class="has-submenu parent-parent-menu-item">
                            <a href="/javascript:void(0)">Pages</a><span class="menu-arrow"></span>
                            <ul class="submenu">
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Company </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/page-aboutus" class="sub-menu-item"> About Us</a></li>
                                        <li><a href="/page-services" class="sub-menu-item">Services</a></li>
                                        <li><a href="/page-team" class="sub-menu-item"> Team</a></li>
                                        <li><a href="/page-pricing" class="sub-menu-item">Pricing</a></li>
                                        <li><a href="/page-testimonial" class="sub-menu-item">Testimonial </a></li>
                                    </ul> 
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Accounts</a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/user-profile" class="sub-menu-item">User Profile</a></li>
                                        <li><a href="/user-billing" class="sub-menu-item">Billing</a></li>
                                        <li><a href="/user-payment" class="sub-menu-item">Payment</a></li>
                                        <li><a href="/user-invoice" class="sub-menu-item">Invoice</a></li>
                                        <li><a href="/user-social" class="sub-menu-item">Social</a></li>
                                        <li><a href="/user-notification" class="sub-menu-item">Notification</a></li>
                                        <li><a href="/user-setting" class="sub-menu-item">Setting</a></li>
                                    </ul> 
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Real Estate</a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/property-listing" class="sub-menu-item">Listing</a></li>
                                        <li><a href="/property-detail" class="sub-menu-item">Property Detail</a></li>
                                    </ul> 
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Courses </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/course-listing" class="sub-menu-item">Course Listing</a></li>
                                        <li><a href="/course-detail" class="sub-menu-item">Course Detail</a></li>
                                    </ul> 
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> NFT Market </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/nft-explore" class="sub-menu-item">Explore</a></li>
                                        <li><a href="/nft-auction" class="sub-menu-item">Auction</a></li>
                                        <li><a href="/nft-collection" class="sub-menu-item">Collections</a></li>
                                        <li><a href="/nft-creators" class="sub-menu-item">Creators</a></li>
                                        <li><a href="/nft-wallet" class="sub-menu-item">Wallet</a></li>
                                        <li><a href="/nft-create-item" class="sub-menu-item">Create NFT</a></li>
                                        <li><a href="/nft-detail" class="sub-menu-item">Single NFT</a></li>
                                    </ul> 
                                </li>
                                <li><a href="/food-recipe" class="sub-menu-item">Food Recipe </a></li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Photography </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/photography-about" class="sub-menu-item">About Us</a></li>
                                        <li><a href="/photography-portfolio" class="sub-menu-item">Portfolio</a></li>
                                    </ul> 
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Job / Careers </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/page-job-grid" class="sub-menu-item">All Jobs</a></li>
                                        <li><a href="/page-job-detail" class="sub-menu-item">Job Detail</a></li>
                                        <li><a href="/page-job-apply" class="sub-menu-item">Job Apply</a></li>
                                        <li><a href="/page-job-candidates" class="sub-menu-item">Job Candidates</a></li>
                                        <li><a href="/page-job-candidate-detail" class="sub-menu-item">Candidate Detail</a></li>
                                        <li><a href="/page-job-companies" class="sub-menu-item">All Companies</a></li>
                                        <li><a href="/page-job-company-detail" class="sub-menu-item">Company Detail</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Forums <span class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/forums-topic" class="sub-menu-item">Forum Topic</a></li>
                                        <li><a href="/forums-comments" class="sub-menu-item">Forum Comments</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Helpcenter </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/helpcenter" class="sub-menu-item">Overview</a></li>
                                        <li><a href="/helpcenter-faqs" class="sub-menu-item">FAQs</a></li>
                                        <li><a href="/helpcenter-guides" class="sub-menu-item">Guides</a></li>
                                        <li><a href="/helpcenter-support" class="sub-menu-item">Support</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Blog </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/blog" class="sub-menu-item">Blogs</a></li>
                                        <li><a href="/blog-sidebar" class="sub-menu-item">Blogs & Sidebar</a></li>
                                        <li><a href="/blog-detail" class="sub-menu-item">Blog Detail</a></li>
                                        <li class="has-submenu child-menu-item"><a href="/javascript:void(0)"> Blog Posts </a><span class="submenu-arrow"></span>
                                            <ul class="submenu">
                                                <li><a href="/blog-standard-post" class="sub-menu-item">Standard Post</a></li>
                                                <li><a href="/blog-slider-post" class="sub-menu-item">Slider Post</a></li>
                                                <li><a href="/blog-gallery-post" class="sub-menu-item">Gallery Post</a></li>
                                                <li><a href="/blog-youtube-post" class="sub-menu-item">Youtube Post</a></li>
                                                <li><a href="/blog-vimeo-post" class="sub-menu-item">Vimeo Post</a></li>
                                                <li><a href="/blog-audio-post" class="sub-menu-item">Audio Post</a></li>
                                                <li><a href="/blog-blockquote-post" class="sub-menu-item">Blockquote</a></li>
                                                <li><a href="/blog-left-sidebar-post" class="sub-menu-item">Left Sidebar</a></li>
                                            </ul>  
                                        </li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Email Template</a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/email-confirmation" class="sub-menu-item">Confirmation</a></li>
                                        <li><a href="/email-password-reset" class="sub-menu-item">Reset Password</a></li>
                                        <li><a href="/email-alert" class="sub-menu-item">Alert</a></li>
                                        <li><a href="/email-invoice" class="sub-menu-item">Invoice</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Auth Pages </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/auth-login" class="sub-menu-item">Login</a></li>
                                        <li><a href="/auth-signup" class="sub-menu-item">Signup</a></li>
                                        <li><a href="/auth-re-password" class="sub-menu-item">Reset Password</a></li>
                                        <li><a href="/auth-lock-screen" class="sub-menu-item">Lock Screen</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Utility </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/page-terms" class="sub-menu-item">Terms of Services</a></li>
                                        <li><a href="/page-privacy" class="sub-menu-item">Privacy Policy</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Special</a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/page-comingsoon" class="sub-menu-item">Coming Soon</a></li>
                                        <li><a href="/page-maintenance" class="sub-menu-item">Maintenance</a></li>
                                        <li><a href="/page-error" class="sub-menu-item">Error</a></li>
                                        <li><a href="/page-thankyou" class="sub-menu-item">Thank you</a></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Contact </a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/contact-detail" class="sub-menu-item">Contact Detail</a></li>
                                        <li><a href="/contact-one" class="sub-menu-item">Contact One</a></li>
                                        <li><a href="/contact-two" class="sub-menu-item">Contact Two</a></li>
                                    </ul>  
                                </li>
                                <li class="has-submenu parent-menu-item"><a href="/javascript:void(0)"> Multi Level Menu</a><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><a href="/javascript:void(0)" class="sub-menu-item">Level 1.0</a></li>
                                        <li class="has-submenu child-menu-item"><a href="/javascript:void(0)"> Level 2.0 </a><span class="submenu-arrow"></span>
                                            <ul class="submenu">
                                                <li><a href="/javascript:void(0)" class="sub-menu-item">Level 2.1</a></li>
                                                <li><a href="/javascript:void(0)" class="sub-menu-item">Level 2.2</a></li>
                                            </ul>  
                                        </li>
                                    </ul>  
                                </li>
                            </ul>
                        </li>

                        <li class="has-submenu parent-parent-menu-item">
                            <a href="/javascript:void(0)">Portfolio</a><span class="menu-arrow"></span>
                            <ul class="submenu megamenu">
                                <li>
                                    <ul>
                                        <li class="megamenu-head">Modern Portfolio</li>
                                        <li><a href="/portfolio-modern-two" class="sub-menu-item">Two Column</a></li>
                                        <li><a href="/portfolio-modern-three" class="sub-menu-item">Three Column</a></li>
                                        <li><a href="/portfolio-modern-four" class="sub-menu-item">Four Column</a></li>
                                        <li><a href="/portfolio-modern-five" class="sub-menu-item">Five Column</a></li>
                                        <li><a href="/portfolio-modern-six" class="sub-menu-item">Six Column</a></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li class="megamenu-head">Classic Portfolio</li>
                                        <li><a href="/portfolio-classic-two" class="sub-menu-item">Two Column</a></li>
                                        <li><a href="/portfolio-classic-three" class="sub-menu-item">Three Column</a></li>
                                        <li><a href="/portfolio-classic-four" class="sub-menu-item">Four Column</a></li>
                                        <li><a href="/portfolio-classic-five" class="sub-menu-item">Five Column</a></li>
                                        <li><a href="/portfolio-classic-six" class="sub-menu-item">Six Column</a></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li class="megamenu-head">Creative Portfolio</li>
                                        <li><a href="/portfolio-creative-two" class="sub-menu-item">Two Column</a></li>
                                        <li><a href="/portfolio-creative-three" class="sub-menu-item">Three Column</a></li>
                                        <li><a href="/portfolio-creative-four" class="sub-menu-item">Four Column</a></li>
                                        <li><a href="/portfolio-creative-five" class="sub-menu-item">Five Column</a></li>
                                        <li><a href="/portfolio-creative-six" class="sub-menu-item">Six Column</a></li>
                                    </ul>
                                </li>
                        
                                <li>
                                    <ul>
                                        <li class="megamenu-head">Masonry Portfolio</li>
                                        <li><a href="/portfolio-masonry-two" class="sub-menu-item">Two Column</a></li>
                                        <li><a href="/portfolio-masonry-three" class="sub-menu-item">Three Column</a></li>
                                        <li><a href="/portfolio-masonry-four" class="sub-menu-item">Four Column</a></li>
                                        <li><a href="/portfolio-masonry-five" class="sub-menu-item">Five Column</a></li>
                                        <li><a href="/portfolio-masonry-six" class="sub-menu-item">Six Column</a></li>
                                    </ul>
                                </li>
                        
                                <li>
                                    <ul>
                                        <li class="megamenu-head">Portfolio Detail</li>
                                        <li><a href="/portfolio-detail-one" class="sub-menu-item">Portfolio One</a></li>
                                        <li><a href="/portfolio-detail-two" class="sub-menu-item">Portfolio Two</a></li>
                                        <li><a href="/portfolio-detail-three" class="sub-menu-item">Portfolio Three</a></li>
                                        <li><a href="/portfolio-detail-four" class="sub-menu-item">Portfolio Four</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>

                        <li class="has-submenu parent-menu-item">
                            <a href="/javascript:void(0)">Docs</a><span class="menu-arrow"></span>
                            <ul class="submenu">
                                <li><a href="/documentation" class="sub-menu-item">Documentation</a></li>
                                <li><a href="/changelog" class="sub-menu-item">Changelog</a></li>
                                <li><a href="/widget" class="sub-menu-item">Widget</a></li>
                            </ul>
                        </li>
                
                        <li><a href="/contact-one" class="sub-menu-item">Contact</a></li>
                    </ul><!--end navigation menu-->
                </div><!--end navigation-->
            </div><!--end container-->
        </nav>
        <div>
            <slot />
        </div>
        <footer class="footer bg-dark-footer relative text-gray-200 dark:text-gray-200">
            <div class="container">
                <div class="grid grid-cols-12">
                    <div class="col-span-12">
                        <div class="py-[60px] px-0">
                            <div class="grid md:grid-cols-12 grid-cols-1 gap-[30px]">
                                <div class="lg:col-span-4 md:col-span-12">
                                    <NuxtLink href="//#" class="text-[22px] focus:outline-none">
                                        <img src="@/assets/images/logo-light.png" alt="">
                                    </NuxtLink>
                                    <p class="mt-6 text-gray-300">Start working with Tailwind CSS that can provide
                                        everything you need to generate awareness, drive traffic, connect.</p>
                                    <ul class="list-none mt-6">
                                        <li class="inline"><NuxtLink href="//https://1.envato.market/techwind" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-shopping-cart align-middle" title="Buy Now"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//https://dribbble.com/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-dribbble align-middle" title="dribbble"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//https://www.behance.net/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-behance" title="Behance"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//http://linkedin.com/company/shreethemes"
                                                target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-linkedin" title="Linkedin"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//https://www.facebook.com/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-facebook-f align-middle" title="facebook"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//https://www.instagram.com/shreethemes/" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-instagram align-middle" title="instagram"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//https://twitter.com/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-twitter align-middle" title="twitter"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//mailto:support@shreethemes.in"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-envelope align-middle" title="email"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="//https://forms.gle/QkTueCikDGqJnbky9" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-file align-middle" title="customization"></i></NuxtLink></li>
                                    </ul><!--end icon-->
                                </div><!--end col-->

                                <div class="lg:col-span-2 md:col-span-4">
                                    <h5 class="tracking-[1px] text-gray-100 font-semibold">Company</h5>
                                    <ul class="list-none footer-list mt-6">
                                        <li><NuxtLink href="//page-aboutus"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> About us</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//page-services"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Services</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//page-team"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Team</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//page-pricing"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Pricing</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//portfolio-creative-four"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Project</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//blog"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Blog</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//auth-login"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Login</NuxtLink></li>
                                    </ul>
                                </div><!--end col-->

                                <div class="lg:col-span-3 md:col-span-4">
                                    <h5 class="tracking-[1px] text-gray-100 font-semibold">Usefull Links</h5>
                                    <ul class="list-none footer-list mt-6">
                                        <li><NuxtLink href="//page-terms"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Terms of Services</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//page-privacy"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Privacy Policy</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//documentation"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Documentation</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//changelog"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Changelog</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="//widget"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Widget</NuxtLink></li>
                                    </ul>
                                </div><!--end col-->

                                <div class="lg:col-span-3 md:col-span-4">
                                    <h5 class="tracking-[1px] text-gray-100 font-semibold">Newsletter</h5>
                                    <p class="mt-6">Sign up and receive the latest tips via email.</p>
                                    <form>
                                        <div class="grid grid-cols-1">
                                            <div class="foot-subscribe my-3">
                                                <label class="form-label">Write your email <span
                                                        class="text-red-600">*</span></label>
                                                <div class="form-icon relative mt-2">
                                                    <i data-feather="mail"
                                                        class="w-4 h-4 absolute top-3 ltr:left-4 rtl:right-4"></i>
                                                    <input type="email"
                                                        class="form-input bg-gray-800 border border-gray-800 text-gray-100 ltr:pl-12 rtl:pr-12 focus:shadow-none"
                                                        placeholder="Email" name="email" required="false">
                                                </div>
                                            </div>

                                            <button type="submit" id="submitsubscribe" name="send"
                                                class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md">Subscribe</button>
                                        </div>
                                    </form>
                                </div><!--end col-->
                            </div><!--end grid-->
                        </div><!--end col-->
                    </div>
                </div><!--end grid-->
            </div><!--end container-->

            <div class="py-[30px] px-0 border-t border-slate-800">
                <div class="container text-center">
                    <div class="grid md:grid-cols-2 items-center">
                        <div class="ltr:md:text-left rtl:md:text-right text-center">
                            <p class="mb-0">© Techwind. Design with <i class="mdi mdi-heart text-red-600"></i> by <NuxtLink
                                    href="//https://shreethemes.in/" target="_blank" class="text-reset">Shreethemes</NuxtLink>.</p>
                        </div>

                        <ul class="list-none ltr:md:text-right rtl:md:text-left text-center mt-6 md:mt-0">
                            <li class="inline"><NuxtLink href="//"><img src="@/assets/images/payments/american-ex.png"
                                        class="max-h-6 inline" title="American Express" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="//"><img src="@/assets/images/payments/discover.png"
                                        class="max-h-6 inline" title="Discover" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="//"><img src="@/assets/images/payments/master-card.png"
                                        class="max-h-6 inline" title="Master Card" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="//"><img src="@/assets/images/payments/paypal.png"
                                        class="max-h-6 inline" title="Paypal" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="//"><img src="@/assets/images/payments/visa.png"
                                        class="max-h-6 inline" title="Visa" alt=""></NuxtLink></li>
                        </ul>
                    </div><!--end grid-->
                </div><!--end container-->
            </div>
        </footer>
    </div>
</template>
