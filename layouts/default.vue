<template>
    <div dir="ltr">

        <nav id="topnav" class="defaultscroll is-sticky">
            <div class="container">
                <!-- Logo container-->
                <NuxtLink class="logo" href="/">
                    <img src="@/assets/images/logo-dark.png" class="inline-block dark:hidden" alt="">
                    <img src="@/assets/images/logo-light.png" class="hidden dark:inline-block" alt="">
                </NuxtLink>

                <!-- End Logo container-->
                <div class="menu-extras">
                    <div class="menu-item">
                        <!-- Mobile menu toggle-->
                        <NuxtLink class="navbar-toggle" id="isToggle" onclick="toggleMenu()">
                            <div class="lines">
                                <span></span>
                                <span></span>
                                <span></span>
                            </div>
                        </NuxtLink>
                        <!-- End mobile menu toggle-->
                    </div>
                </div>

                <!--Login button Start-->
                <ul class="buy-button list-none mb-0">
                    <li class="inline mb-0">
                        <a href="/"
                            class="btn btn-icon rounded-full bg-indigo-600/5 hover:bg-indigo-600 border-indigo-600/10 hover:border-indigo-600 text-indigo-600 hover:text-white"><i
                                data-feather="settings" class="h-4 w-4"></i></a>
                    </li>

                    <li class="inline ltr:pl-1 rtl:pr-1 mb-0">
                        <a href="/https://1.envato.market/techwind" target="_blank"
                            class="btn btn-icon rounded-full bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white"><i
                                data-feather="shopping-cart" class="h-4 w-4"></i></a>
                    </li>
                </ul>
                <!--Login button End-->

                <div id="navigation">
                    <!-- Navigation Menu-->
                    <ul class="navigation-menu">
                        <li><NuxtLink href="/" class="sub-menu-item">Home</NuxtLink></li>

                        <li class="has-submenu parent-parent-menu-item">
                            <NuxtLink href="javascript:void(0)">Landings</NuxtLink><span class="menu-arrow"></span>

                            <ul class="submenu megamenu">
                                <li>
                                    <ul>
                                        <li><NuxtLink href="/index-saas" class="sub-menu-item">Saas <span
                                                    class="bg-emerald-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Animation</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-classic-saas" class="sub-menu-item">Classic Saas </NuxtLink></li>
                                        <li><NuxtLink href="/index-modern-saas" class="sub-menu-item">Modern Saas </NuxtLink></li>
                                        <li><NuxtLink href="/index-apps" class="sub-menu-item">Application</NuxtLink></li>
                                        <li><NuxtLink href="/index-classic-app" class="sub-menu-item">Classic App </NuxtLink></li>
                                        <li><NuxtLink href="/index-smartwatch" class="sub-menu-item">Smartwatch</NuxtLink></li>
                                        <li><NuxtLink href="/index-marketing" class="sub-menu-item">Marketing</NuxtLink></li>
                                        <li><NuxtLink href="/index-seo" class="sub-menu-item">SEO Agency </NuxtLink></li>
                                        <li><NuxtLink href="/index-payment" class="sub-menu-item">Payments</NuxtLink></li>
                                        <li><NuxtLink href="/index-charity" class="sub-menu-item">Charity <span
                                                    class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></NuxtLink>
                                        </li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li><NuxtLink href="/index-it-solution" class="sub-menu-item">IT Solution</NuxtLink></li>
                                        <li><NuxtLink href="/index-it-solution-two" class="sub-menu-item">It Solution Two </NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-digital-agency" class="sub-menu-item">Digital Agency</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-job" class="sub-menu-item">Job</NuxtLink></li>
                                        <li><NuxtLink href="/index-restaurent" class="sub-menu-item">Restaurent</NuxtLink></li>
                                        <li><NuxtLink href="/index-hosting" class="sub-menu-item">Hosting</NuxtLink></li>
                                        <li><NuxtLink href="/index-nft" class="sub-menu-item">NFT Marketplace</NuxtLink></li>
                                        <li><NuxtLink href="/index-hotel" class="sub-menu-item">Hotel & Resort</NuxtLink></li>
                                        <li><NuxtLink href="/index-gym" class="sub-menu-item">Gym <span
                                                    class="bg-black dark:bg-slate-50 inline-block text-white dark:text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Dark</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="javascript:void(0)" class="sub-menu-item">Yoga <span
                                                    class="bg-cyan-500 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Comingsoon</span></NuxtLink>
                                        </li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li><NuxtLink href="/index-startup" class="sub-menu-item">Startup</NuxtLink></li>
                                        <li><NuxtLink href="/index-business" class="sub-menu-item">Business</NuxtLink></li>
                                        <li><NuxtLink href="/index-corporate" class="sub-menu-item">Corporate</NuxtLink></li>
                                        <li><NuxtLink href="/index-corporate-two" class="sub-menu-item">Corporate Two </NuxtLink></li>
                                        <li><NuxtLink href="/index-real-estate" class="sub-menu-item">Real Estate</NuxtLink></li>
                                        <li><NuxtLink href="/index-consulting" class="sub-menu-item">Consulting </NuxtLink></li>
                                        <li><NuxtLink href="/index-insurance" class="sub-menu-item">Insurance </NuxtLink></li>
                                        <li><NuxtLink href="/index-construction" class="sub-menu-item">Construction </NuxtLink></li>
                                        <li><NuxtLink href="/index-law" class="sub-menu-item">Law Firm <span
                                                    class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-video" class="sub-menu-item">Video <span
                                                    class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></NuxtLink>
                                        </li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li><NuxtLink href="/index-personal" class="sub-menu-item">Personal</NuxtLink></li>
                                        <li><NuxtLink href="/index-portfolio" class="sub-menu-item">Portfolio</NuxtLink></li>
                                        <li><NuxtLink href="/index-photography" class="sub-menu-item">Photography <span
                                                    class="bg-black dark:bg-slate-50 inline-block text-white dark:text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Dark</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-studio" class="sub-menu-item">Studio</NuxtLink></li>
                                        <li><NuxtLink href="/index-coworking" class="sub-menu-item">Co-Woriking</NuxtLink></li>
                                        <li><NuxtLink href="/index-course" class="sub-menu-item">Online Courses </NuxtLink></li>
                                        <li><NuxtLink href="/index-event" class="sub-menu-item">Event/Conference </NuxtLink></li>
                                        <li><NuxtLink href="/index-hospital" class="sub-menu-item">Hospital</NuxtLink></li>
                                        <li><NuxtLink href="javascript:void(0)" class="sub-menu-item">Covid Care <span
                                                    class="bg-cyan-500 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Comingsoon</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-forums" class="sub-menu-item">Forums <span
                                                    class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></NuxtLink>
                                        </li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li><NuxtLink href="/index-crypto" class="sub-menu-item">Cryptocurrency <span
                                                    class="bg-black dark:bg-slate-50 inline-block text-white dark:text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Dark</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-landing-one" class="sub-menu-item">Landing One</NuxtLink></li>
                                        <li><NuxtLink href="/index-landing-two" class="sub-menu-item">Landing Two</NuxtLink></li>
                                        <li><NuxtLink href="/index-landing-three" class="sub-menu-item">Landing Three</NuxtLink></li>
                                        <li><NuxtLink href="/index-landing-four" class="sub-menu-item">Landing Four</NuxtLink></li>
                                        <li><NuxtLink href="/index-service" class="sub-menu-item">Service Provider</NuxtLink></li>
                                        <li><NuxtLink href="/index-food-blog" class="sub-menu-item">Food Blog </NuxtLink></li>
                                        <li><NuxtLink href="/index-blog" class="sub-menu-item">Blog </NuxtLink></li>
                                        <li><NuxtLink href="javascript:void(0)" class="sub-menu-item">Furniture <span
                                                    class="bg-cyan-500 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Comingsoon</span></NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/index-landing-five" class="sub-menu-item">Landing Five <span
                                                    class="bg-green-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">Onepage</span></NuxtLink>
                                        </li>
                                    </ul>
                                </li>
                            </ul>
                        </li>

                        <li class="has-submenu parent-parent-menu-item">
                            <NuxtLink href="javascript:void(0)">Pages</NuxtLink><span class="menu-arrow"></span>
                            <ul class="submenu">
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Company </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/page-aboutus" class="sub-menu-item"> About Us</NuxtLink></li>
                                        <li><NuxtLink href="/page-services" class="sub-menu-item">Services</NuxtLink></li>
                                        <li><NuxtLink href="/page-team" class="sub-menu-item"> Team</NuxtLink></li>
                                        <li><NuxtLink href="/page-pricing" class="sub-menu-item">Pricing</NuxtLink></li>
                                        <li><NuxtLink href="/page-testimonial" class="sub-menu-item">Testimonial </NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Accounts</NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/user-profile" class="sub-menu-item">User Profile</NuxtLink></li>
                                        <li><NuxtLink href="/user-billing" class="sub-menu-item">Billing</NuxtLink></li>
                                        <li><NuxtLink href="/user-payment" class="sub-menu-item">Payment</NuxtLink></li>
                                        <li><NuxtLink href="/user-invoice" class="sub-menu-item">Invoice</NuxtLink></li>
                                        <li><NuxtLink href="/user-social" class="sub-menu-item">Social</NuxtLink></li>
                                        <li><NuxtLink href="/user-notification" class="sub-menu-item">Notification</NuxtLink></li>
                                        <li><NuxtLink href="/user-setting" class="sub-menu-item">Setting</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Real Estate</NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/property-listing" class="sub-menu-item">Listing</NuxtLink></li>
                                        <li><NuxtLink href="/property-detail" class="sub-menu-item">Property Detail</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Courses </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/course-listing" class="sub-menu-item">Course Listing</NuxtLink></li>
                                        <li><NuxtLink href="/course-detail" class="sub-menu-item">Course Detail</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> NFT Market </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/nft-explore" class="sub-menu-item">Explore</NuxtLink></li>
                                        <li><NuxtLink href="/nft-auction" class="sub-menu-item">Auction</NuxtLink></li>
                                        <li><NuxtLink href="/nft-collection" class="sub-menu-item">Collections</NuxtLink></li>
                                        <li><NuxtLink href="/nft-creators" class="sub-menu-item">Creators</NuxtLink></li>
                                        <li><NuxtLink href="/nft-wallet" class="sub-menu-item">Wallet</NuxtLink></li>
                                        <li><NuxtLink href="/nft-create-item" class="sub-menu-item">Create NFT</NuxtLink></li>
                                        <li><NuxtLink href="/nft-detail" class="sub-menu-item">Single NFT</NuxtLink></li>
                                    </ul>
                                </li>
                                <li><NuxtLink href="/food-recipe" class="sub-menu-item">Food Recipe </NuxtLink></li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Photography </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/photography-about" class="sub-menu-item">About Us</NuxtLink></li>
                                        <li><NuxtLink href="/photography-portfolio" class="sub-menu-item">Portfolio</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Job / Careers
                                    </NuxtLink><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/page-job-grid" class="sub-menu-item">All Jobs</NuxtLink></li>
                                        <li><NuxtLink href="/page-job-detail" class="sub-menu-item">Job Detail</NuxtLink></li>
                                        <li><NuxtLink href="/page-job-apply" class="sub-menu-item">Job Apply</NuxtLink></li>
                                        <li><NuxtLink href="/page-job-candidates" class="sub-menu-item">Job Candidates</NuxtLink></li>
                                        <li><NuxtLink href="/page-job-candidate-detail" class="sub-menu-item">Candidate
                                                Detail</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/page-job-companies" class="sub-menu-item">All Companies</NuxtLink></li>
                                        <li><NuxtLink href="/page-job-company-detail" class="sub-menu-item">Company Detail</NuxtLink>
                                        </li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Forums <span
                                            class="bg-orange-600 inline-block text-white text-[10px] font-bold px-2.5 py-0.5 rounded h-5 ltr:ml-1 rtl:mr-1">New</span></NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/forums-topic" class="sub-menu-item">Forum Topic</NuxtLink></li>
                                        <li><NuxtLink href="/forums-comments" class="sub-menu-item">Forum Comments</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Helpcenter </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/helpcenter" class="sub-menu-item">Overview</NuxtLink></li>
                                        <li><NuxtLink href="/helpcenter-faqs" class="sub-menu-item">FAQs</NuxtLink></li>
                                        <li><NuxtLink href="/helpcenter-guides" class="sub-menu-item">Guides</NuxtLink></li>
                                        <li><NuxtLink href="/helpcenter-support" class="sub-menu-item">Support</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Blog </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/blog" class="sub-menu-item">Blogs</NuxtLink></li>
                                        <li><NuxtLink href="/blog-sidebar" class="sub-menu-item">Blogs & Sidebar</NuxtLink></li>
                                        <li><NuxtLink href="/blog-detail" class="sub-menu-item">Blog Detail</NuxtLink></li>
                                        <li class="has-submenu child-menu-item"><NuxtLink href="javascript:void(0)"> Blog Posts
                                            </NuxtLink><span class="submenu-arrow"></span>
                                            <ul class="submenu">
                                                <li><NuxtLink href="/blog-standard-post" class="sub-menu-item">Standard
                                                        Post</NuxtLink>
                                                </li>
                                                <li><NuxtLink href="/blog-slider-post" class="sub-menu-item">Slider Post</NuxtLink>
                                                </li>
                                                <li><NuxtLink href="/blog-gallery-post" class="sub-menu-item">Gallery Post</NuxtLink>
                                                </li>
                                                <li><NuxtLink href="/blog-youtube-post" class="sub-menu-item">Youtube Post</NuxtLink>
                                                </li>
                                                <li><NuxtLink href="/blog-vimeo-post" class="sub-menu-item">Vimeo Post</NuxtLink></li>
                                                <li><NuxtLink href="/blog-audio-post" class="sub-menu-item">Audio Post</NuxtLink></li>
                                                <li><NuxtLink href="/blog-blockquote-post" class="sub-menu-item">Blockquote</NuxtLink>
                                                </li>
                                                <li><NuxtLink href="/blog-left-sidebar-post" class="sub-menu-item">Left
                                                        Sidebar</NuxtLink>
                                                </li>
                                            </ul>
                                        </li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Email
                                        Template</NuxtLink><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/email-confirmation" class="sub-menu-item">Confirmation</NuxtLink></li>
                                        <li><NuxtLink href="/email-password-reset" class="sub-menu-item">Reset Password</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/email-alert" class="sub-menu-item">Alert</NuxtLink></li>
                                        <li><NuxtLink href="/email-invoice" class="sub-menu-item">Invoice</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Auth Pages </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/auth-login" class="sub-menu-item">Login</NuxtLink></li>
                                        <li><NuxtLink href="/auth-signup" class="sub-menu-item">Signup</NuxtLink></li>
                                        <li><NuxtLink href="/auth-re-password" class="sub-menu-item">Reset Password</NuxtLink></li>
                                        <li><NuxtLink href="/auth-lock-screen" class="sub-menu-item">Lock Screen</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Utility </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/page-terms" class="sub-menu-item">Terms of Services</NuxtLink></li>
                                        <li><NuxtLink href="/page-privacy" class="sub-menu-item">Privacy Policy</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Special</NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/page-comingsoon" class="sub-menu-item">Coming Soon</NuxtLink></li>
                                        <li><NuxtLink href="/page-maintenance" class="sub-menu-item">Maintenance</NuxtLink></li>
                                        <li><NuxtLink href="/page-error" class="sub-menu-item">Error</NuxtLink></li>
                                        <li><NuxtLink href="/page-thankyou" class="sub-menu-item">Thank you</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Contact </NuxtLink><span
                                        class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="/contact-detail" class="sub-menu-item">Contact Detail</NuxtLink></li>
                                        <li><NuxtLink href="/contact-one" class="sub-menu-item">Contact One</NuxtLink></li>
                                        <li><NuxtLink href="/contact-two" class="sub-menu-item">Contact Two</NuxtLink></li>
                                    </ul>
                                </li>
                                <li class="has-submenu parent-menu-item"><NuxtLink href="javascript:void(0)"> Multi Level
                                        Menu</NuxtLink><span class="submenu-arrow"></span>
                                    <ul class="submenu">
                                        <li><NuxtLink href="javascript:void(0)" class="sub-menu-item">Level 1.0</NuxtLink></li>
                                        <li class="has-submenu child-menu-item"><NuxtLink href="javascript:void(0)"> Level 2.0
                                            </NuxtLink><span class="submenu-arrow"></span>
                                            <ul class="submenu">
                                                <li><NuxtLink href="javascript:void(0)" class="sub-menu-item">Level 2.1</NuxtLink></li>
                                                <li><NuxtLink href="javascript:void(0)" class="sub-menu-item">Level 2.2</NuxtLink></li>
                                            </ul>
                                        </li>
                                    </ul>
                                </li>
                            </ul>
                        </li>

                        <li class="has-submenu parent-parent-menu-item">
                            <NuxtLink href="javascript:void(0)">Portfolio</NuxtLink><span class="menu-arrow"></span>
                            <ul class="submenu megamenu">
                                <li>
                                    <ul>
                                        <li class="megamenu-head">Modern Portfolio</li>
                                        <li><NuxtLink href="/portfolio-modern-two" class="sub-menu-item">Two Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-modern-three" class="sub-menu-item">Three Column</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-modern-four" class="sub-menu-item">Four Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-modern-five" class="sub-menu-item">Five Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-modern-six" class="sub-menu-item">Six Column</NuxtLink></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li class="megamenu-head">Classic Portfolio</li>
                                        <li><NuxtLink href="/portfolio-classic-two" class="sub-menu-item">Two Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-classic-three" class="sub-menu-item">Three Column</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-classic-four" class="sub-menu-item">Four Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-classic-five" class="sub-menu-item">Five Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-classic-six" class="sub-menu-item">Six Column</NuxtLink></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li class="megamenu-head">Creative Portfolio</li>
                                        <li><NuxtLink href="/portfolio-creative-two" class="sub-menu-item">Two Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-creative-three" class="sub-menu-item">Three Column</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-creative-four" class="sub-menu-item">Four Column</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-creative-five" class="sub-menu-item">Five Column</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-creative-six" class="sub-menu-item">Six Column</NuxtLink></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li class="megamenu-head">Masonry Portfolio</li>
                                        <li><NuxtLink href="/portfolio-masonry-two" class="sub-menu-item">Two Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-masonry-three" class="sub-menu-item">Three Column</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-masonry-four" class="sub-menu-item">Four Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-masonry-five" class="sub-menu-item">Five Column</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-masonry-six" class="sub-menu-item">Six Column</NuxtLink></li>
                                    </ul>
                                </li>

                                <li>
                                    <ul>
                                        <li class="megamenu-head">Portfolio Detail</li>
                                        <li><NuxtLink href="/portfolio-detail-one" class="sub-menu-item">Portfolio One</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-detail-two" class="sub-menu-item">Portfolio Two</NuxtLink></li>
                                        <li><NuxtLink href="/portfolio-detail-three" class="sub-menu-item">Portfolio Three</NuxtLink>
                                        </li>
                                        <li><NuxtLink href="/portfolio-detail-four" class="sub-menu-item">Portfolio Four</NuxtLink>
                                        </li>
                                    </ul>
                                </li>
                            </ul>
                        </li>

                        <li class="has-submenu parent-menu-item">
                            <NuxtLink href="javascript:void(0)">Docs</NuxtLink><span class="menu-arrow"></span>
                            <ul class="submenu">
                                <li><NuxtLink href="/documentation" class="sub-menu-item">Documentation</NuxtLink></li>
                                <li><NuxtLink href="/changelog" class="sub-menu-item">Changelog</NuxtLink></li>
                                <li><NuxtLink href="/widget" class="sub-menu-item">Widget</NuxtLink></li>
                            </ul>
                        </li>

                        <li><NuxtLink href="/contact-one" class="sub-menu-item">Contact</NuxtLink></li>
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
                                    <NuxtLink href="/#" class="text-[22px] focus:outline-none">
                                        <img src="@/assets/images/logo-light.png" alt="">
                                    </NuxtLink>
                                    <p class="mt-6 text-gray-300">Start working with Tailwind CSS that can provide
                                        everything you need to generate awareness, drive traffic, connect.</p>
                                    <ul class="list-none mt-6">
                                        <li class="inline"><NuxtLink href="/https://1.envato.market/techwind" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-shopping-cart align-middle" title="Buy Now"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/https://dribbble.com/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-dribbble align-middle" title="dribbble"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/https://www.behance.net/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-behance" title="Behance"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/http://linkedin.com/company/shreethemes"
                                                target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-linkedin" title="Linkedin"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/https://www.facebook.com/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-facebook-f align-middle" title="facebook"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/https://www.instagram.com/shreethemes/" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-instagram align-middle" title="instagram"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/https://twitter.com/shreethemes" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-twitter align-middle" title="twitter"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/mailto:support@shreethemes.in"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-envelope align-middle" title="email"></i></NuxtLink></li>
                                        <li class="inline"><NuxtLink href="/https://forms.gle/QkTueCikDGqJnbky9" target="_blank"
                                                class="btn btn-icon btn-sm border border-gray-800 rounded-md hover:border-indigo-600 dark:hover:border-indigo-600 hover:bg-indigo-600 dark:hover:bg-indigo-600"><i
                                                    class="uil uil-file align-middle" title="customization"></i></NuxtLink></li>
                                    </ul><!--end icon-->
                                </div><!--end col-->

                                <div class="lg:col-span-2 md:col-span-4">
                                    <h5 class="tracking-[1px] text-gray-100 font-semibold">Company</h5>
                                    <ul class="list-none footer-list mt-6">
                                        <li><NuxtLink href="/page-aboutus"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> About us</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/page-services"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Services</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/page-team"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Team</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/page-pricing"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Pricing</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/portfolio-creative-four"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Project</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/blog"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Blog</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/auth-login"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Login</NuxtLink></li>
                                    </ul>
                                </div><!--end col-->

                                <div class="lg:col-span-3 md:col-span-4">
                                    <h5 class="tracking-[1px] text-gray-100 font-semibold">Usefull Links</h5>
                                    <ul class="list-none footer-list mt-6">
                                        <li><NuxtLink href="/page-terms"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Terms of Services</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/page-privacy"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Privacy Policy</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/documentation"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Documentation</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/changelog"
                                                class="text-gray-300 hover:text-gray-400 duration-500 ease-in-out"><i
                                                    class="uil uil-angle-right-b"></i> Changelog</NuxtLink></li>
                                        <li class="mt-[10px]"><NuxtLink href="/widget"
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
                                    href="/https://shreethemes.in/" target="_blank" class="text-reset">Shreethemes</NuxtLink>.</p>
                        </div>

                        <ul class="list-none ltr:md:text-right rtl:md:text-left text-center mt-6 md:mt-0">
                            <li class="inline"><NuxtLink href="/"><img src="@/assets/images/payments/american-ex.png"
                                        class="max-h-6 inline" title="American Express" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="/"><img src="@/assets/images/payments/discover.png"
                                        class="max-h-6 inline" title="Discover" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="/"><img src="@/assets/images/payments/master-card.png"
                                        class="max-h-6 inline" title="Master Card" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="/"><img src="@/assets/images/payments/paypal.png"
                                        class="max-h-6 inline" title="Paypal" alt=""></NuxtLink></li>
                            <li class="inline"><NuxtLink href="/"><img src="@/assets/images/payments/visa.png"
                                        class="max-h-6 inline" title="Visa" alt=""></NuxtLink></li>
                        </ul>
                    </div><!--end grid-->
                </div><!--end container-->
            </div>
        </footer>
    </div>
</template>

<style></style>