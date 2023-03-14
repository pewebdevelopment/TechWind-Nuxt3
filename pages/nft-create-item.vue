<template>
    
        <!-- Start Hero -->
        <section class="relative table w-full py-32 lg:py-40 bg-gradient-to-br to-orange-600/20 via-fuchsia-600/20 from-indigo-600/20">
            <div class="container">
                <div class="grid grid-cols-1 text-center mt-10">
                    <h3 class="text-3xl leading-normal font-medium">Create Your Item</h3>
                </div><!--end grid-->
            </div><!--end container-->
            
            <div class="absolute text-center z-10 bottom-5 right-0 left-0 mx-3">
                <ul class="breadcrumb tracking-[0.5px] mb-0 inline-block">
                    <li class="inline breadcrumb-item uppercase text-[13px] font-bold duration-500 ease-in-out hover:text-indigo-600"><a href="/index">Techwind</a></li>
                    <li class="inline breadcrumb-item uppercase text-[13px] font-bold duration-500 ease-in-out hover:text-indigo-600"><a href="/index-nft">NFT</a></li>
                    <li class="inline breadcrumb-item uppercase text-[13px] font-bold text-indigo-600" aria-current="page">Create</li>
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
                <div class="md:flex p-6 bg-white dark:bg-slate-900 rounded-md shadow dark:shadow-gray-800">
                    <div class="lg:w-1/3 md:w-2/5">
                        <p class="font-semibold mb-6">Upload your ART here, Please click "Upload Image" Button.</p>
                        <div class="preview-box flex justify-center rounded-md shadow dark:shadow-gray-800 overflow-hidden bg-gray-50 dark:bg-slate-800 text-slate-400 p-2 text-center small">Supports JPG, PNG and MP4 videos. Max file size : 10MB.</div>
                        <input type="file" id="input-file" name="input-file" accept="image/*" onchange={handleChange()} hidden />
                        <label class="btn-upload btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md w-full mt-6 cursor-pointer" for="input-file">Upload Image</label>
                    </div>

                    <div class="lg:w-2/3 md:w-3/5 mt-8 md:mt-0">
                        <div class="ltr:md:ml-6 rtl:md:mr-6">
                            <form>
                                <div class="grid grid-cols-12 gap-6">
                                    <div class="col-span-12">
                                        <label class="font-semibold">Art Title <span class="text-red-600">*</span></label>
                                        <input name="name" id="name" type="text" class="form-input mt-2" placeholder="Title :">
                                    </div><!--end col-->

                                    <div class="col-span-12">
                                        <label class="font-semibold"> Description : </label>
                                        <textarea name="comments" id="comments" class="form-input mt-2 h-28" placeholder="Description :"></textarea>
                                    </div><!--end col-->

                                    <div class="md:col-span-6 col-span-12">
                                        <label class="font-semibold">Type :</label>
                                        <select class="form-input mt-2">
                                            <option>GIFs</option>
                                            <option>Music</option>
                                            <option>Video</option>
                                            <option>Tech</option>
                                        </select>
                                    </div><!--end col-->

                                    <div class="md:col-span-6 col-span-12">
                                        <label class="font-semibold"> Rate : </label>
                                        <input name="time" type="text" class="form-input mt-2" id="time" value="0.004ETH">
                                    </div><!--end col-->

                                    <div class="col-span-12">
                                        <h6 class="font-semibold text-lg">Auction :</h6>
                                    </div>

                                    <div class="md:col-span-6 col-span-12">
                                        <label class="font-semibold"> Starting Date : </label>
                                        <input name="date" type="text" class="form-input mt-2 start" placeholder="Select date :">
                                    </div><!--end col-->
    
                                    <div class="md:col-span-6 col-span-12">
                                        <label class="font-semibold"> Expiration date : </label>
                                        <input name="date" type="text" class="form-input mt-2 end" placeholder="Select date :">
                                    </div><!--end col-->

                                    <div class="col-span-12">
                                        <button type="submit" class="btn bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-md">Create Item</button>
                                    </div><!--end col-->
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div><!--end container-->
        </section><!--end end section-->
        <!-- End -->
</template>