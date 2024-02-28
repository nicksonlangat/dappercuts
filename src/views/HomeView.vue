<template>
<main class="mx-auto text-[#878787] font-base pb-5 container">
    <nav class="flex mx-3 lg:mx-0 lg:mt-5 mt-2 items-center justify-between">
        <div class="text-[#c29e3d] flex gap-2 items-center text-2xl lg:text-3xl">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon text-[#c29e3d] icon-tabler h-8 w-8 lg:h-10 lg:w-10 rotate-90 icon-tabler-cut" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                <path d="M7 17m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                <path d="M17 17m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                <path d="M9.15 14.85l8.85 -10.85" />
                <path d="M6 4l8.85 10.85" /></svg>
            DapperCuts
        </div>
        <div class="hidden lg:flex gap-10  text-lg items-center">
            <a href="" class="text-white">Home</a>
            <a href="" class="hover:text-white transition-all duration-300">Services</a>
            <a href="" class="hover:text-white transition-all duration-300">Testimonials</a>
            <a href="" class="hover:text-white transition-all duration-300">Book</a>
        </div>
        <div class="">
            <button class="bg-[#c29e3d] hidden lg:block w-56 py-2 text-white text-center px-6 rounded">Book A Seat Now</button>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 text-white lg:hidden h-8">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
            </svg>

        </div>
    </nav>
    <div class="flex flex-col lg:flex-row mt-10 lg:mt-20">
        <div class="mx-5 lg:mx-0 lg:w-2/3">
            <div class="">
                <h1 class="text-white lg:text-7xl text-4xl leading-16">Upgrade Your Hair Game; <br> Raise The Bar</h1>
                <p class="lg:text-3xl text-xl mt-5 lg:mt-10 text-[#afafaf] leading-10">Experience elite hairstyles at any of our branches country wide and you will never look back!</p>
                <div class="grid lg:mt-12 mt-5 grid-cols-3 divide-x divide-dashed divide-[#878787]">
                    <div class="flex flex-col">
                        <p class="text-[#878787] lg:text-3xl">Active Branches</p>
                        <p class="text-white text-center text-3xl lg:mt-5 mt-3">47</p>
                    </div>
                    <div class="flex flex-col items-center justify-center">
                        <p class="text-[#878787] lg:text-3xl">Total Barbers</p>
                        <p class="text-white text-3xl lg:mt-5 mt-3 text-center">140</p>
                    </div>
                    <div class=" flex flex-col items-center justify-center">
                        <p class="text-[#878787] lg:text-3xl">Services</p>
                        <p class="text-white text-3xl lg:mt-5 mt-3">20</p>
                    </div>
                </div>
                <div class="flex mt-10 lg:mt-20 justify-between">
                    <div class="flex gap-5 w-full items-center">
                        <button class="border border-[#c29e3d] w-full lg:w-56 py-2 text-white text-center px-6 rounded">Book A Seat Now</button>
                        <button class="border  py-2 bg-white w-full lg:w-56 text-[#1e1e1e] text-center px-6 rounded">Contact Us</button>
                    </div>
                    <div class="lg:flex hidden gap-10 text-white text-xl mr-5">
                        <div>
                            <p class="text-[#878787]">Open</p>
                            <p>08:00 AM</p>
                        </div>
                        <div>
                            <p class="text-[#878787]">Close</p>
                            <p>9:00 PM</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="lg:w-1/3 lg:mt-0 mt-10 mx-5 lg:mx-0">
            <img src="https://images.unsplash.com/photo-1567894340315-735d7c361db0?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTF8fGJhcmJlcnxlbnwwfHwwfHx8MA%3D%3D" alt="">
        </div>
    </div>

    <div class="mt-10 mx-5 lg:mx-0">
        <h1 class="text-[#afafaf] text-3xl">Our Services</h1>
        <p class="text-[#828282] mt-2">Our services are top of the range and very affordable.</p>
    </div>
    <div class="grid mx-5 lg:mx-0 lg:grid-cols-3 lg:gap-10">
        <div class="bg-[#272727] pb-16 rounded mt-10">
            <div class="p-5">
                <span class="bg-[#1e1e1e] flex items-center justify-center h-16 w-16 rounded-full text-[#c29e3d]">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-cut" width="28" height="28" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M7 17m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                        <path d="M17 17m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                        <path d="M9.15 14.85l8.85 -10.85" />
                        <path d="M6 4l8.85 10.85" /></svg>
                </span>
                <div class="flex flex-col gap-y-6 lg:gap-y-12 mt-5">
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Classic Haircut</h3>
                            <p class="text-[#c29e3d] text-lg">$20</p>
                        </div>
                        <p class="text-[#828282] mt-3 font- font-extralight">
                            Sit back and enjoy a variety of our classic styles that will blow you away.
                        </p>
                    </div>
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Deluxe Haircut</h3>
                            <p class="text-[#c29e3d] text-lg">$30</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-3">
                            Your style, our commitment. Grab a style that compliments your looks and we'll match it!
                        </p>
                    </div>
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Kids Haircut</h3>
                            <p class="text-[#c29e3d] text-lg">$15</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-3">
                            Because your kids deserve to look good while being disciplined and decent.
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-[#272727] pb-16 rounded mt-10">
            <div class="p-5">
                <span class="bg-[#1e1e1e] flex items-center justify-center h-16 w-16 rounded-full text-[#c29e3d]">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-blade" width="28" height="28" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M17.707 3.707l2.586 2.586a1 1 0 0 1 0 1.414l-.586 .586a1 1 0 0 0 0 1.414l.586 .586a1 1 0 0 1 0 1.414l-8.586 8.586a1 1 0 0 1 -1.414 0l-.586 -.586a1 1 0 0 0 -1.414 0l-.586 .586a1 1 0 0 1 -1.414 0l-2.586 -2.586a1 1 0 0 1 0 -1.414l.586 -.586a1 1 0 0 0 0 -1.414l-.586 -.586a1 1 0 0 1 0 -1.414l8.586 -8.586a1 1 0 0 1 1.414 0l.586 .586a1 1 0 0 0 1.414 0l.586 -.586a1 1 0 0 1 1.414 0z" />
                        <path d="M8 16l3.2 -3.2" />
                        <path d="M12.8 11.2l3.2 -3.2" />
                        <path d="M14 8l2 2" />
                        <path d="M8 14l2 2" />
                        <path d="M12 12m-1 0a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" /></svg>
                </span>
                <div class="flex flex-col gap-y-6 lg:gap-y-12 mt-5">
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Beard Trim</h3>
                            <p class="text-[#c29e3d] text-lg">$20</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-3">
                            Get your beard in check with a unique blend of styles and precison.
                        </p>
                    </div>
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Hot Towel Shave</h3>
                            <p class="text-[#c29e3d] text-lg">$20</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-3">
                            Get a fresh and soothing shave in the company of steamy towel at the right temperature.
                        </p>
                    </div>
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Moustache Trim</h3>
                            <p class="text-[#c29e3d] text-lg">$20</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-3">
                            You deserve a clean, well kept out moustache that compliments your swag.
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-[#272727] pb-16 rounded mt-10">
            <div class="p-5">
                <span class="bg-[#1e1e1e] flex items-center justify-center h-16 w-16 rounded-full text-[#c29e3d]">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-bottle" width="28" height="28" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M10 5h4v-2a1 1 0 0 0 -1 -1h-2a1 1 0 0 0 -1 1v2z" />
                        <path d="M14 3.5c0 1.626 .507 3.212 1.45 4.537l.05 .07a8.093 8.093 0 0 1 1.5 4.694v6.199a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2v-6.2c0 -1.682 .524 -3.322 1.5 -4.693l.05 -.07a7.823 7.823 0 0 0 1.45 -4.537" />
                        <path d="M7 14.803a2.4 2.4 0 0 0 1 -.803a2.4 2.4 0 0 1 2 -1a2.4 2.4 0 0 1 2 1a2.4 2.4 0 0 0 2 1a2.4 2.4 0 0 0 2 -1a2.4 2.4 0 0 1 1 -.805" /></svg>
                </span>
                <div class="flex flex-col gap-y-6 lg:gap-y-12 mt-5">
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Hair Color</h3>
                            <p class="text-[#c29e3d] text-lg">$20</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-2">
                            Whether for the first time or you are a regular, we will touch you hair with class.
                        </p>
                    </div>
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Facial Scrub</h3>
                            <p class="text-[#c29e3d] text-lg">$30</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-2">
                            Your face deserves to glow and what a perfect time to get a scrub!
                        </p>
                    </div>
                    <div>
                        <div class="flex items-center justify-between">
                            <h3 class="text-white text-xl">Hair Wash</h3>
                            <p class="text-[#c29e3d] text-lg">$15</p>
                        </div>
                        <p class="text-[#828282] font- font-extralight mt-2">
                            Clean hair, bright personality and an hygienic lifestyle. We do it all!
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="lg:mt-20 mt-10 mx-5 lg:mx-0">
        <h1 class="text-[#afafaf] text-3xl">Latest Hairstyles</h1>
        <p class="text-[#828282] mt-2">Our work samples.</p>
        <div class="grid mt-5 gap-5 grid-cols-2 lg:grid-cols-4">
            <div>
                <img src="https://images.unsplash.com/photo-1582771498000-8ad44e6c84db?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjN8fGJhcmJlcnxlbnwwfHwwfHx8MA%3D%3D" alt="">
            </div>
            <div>
                <img src="https://images.unsplash.com/photo-1578390432942-d323db577792?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mzh8fGJhcmJlcnxlbnwwfHwwfHx8MA%3D%3D" alt="">
            </div>
            <div>
                <img src="https://images.unsplash.com/photo-1562004760-aceed7bb0fe3?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NTJ8fGJhcmJlcnxlbnwwfHwwfHx8MA%3D%3D" alt="">
            </div>
            <div>
                <img src="https://images.unsplash.com/photo-1605497788044-5a32c7078486?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8YmFyYmVyfGVufDB8fDB8fHww" alt="">
            </div>
        </div>
    </div>
    <div class="lg:mt-28 mt-10 mx-5 lg:mx-0">
        <div class="flex justify-between items-center">
            <div class="text-[#c29e3d] inline-flex">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="m7.848 8.25 1.536.887M7.848 8.25a3 3 0 1 1-5.196-3 3 3 0 0 1 5.196 3Zm1.536.887a2.165 2.165 0 0 1 1.083 1.839c.005.351.054.695.14 1.024M9.384 9.137l2.077 1.199M7.848 15.75l1.536-.887m-1.536.887a3 3 0 1 1-5.196 3 3 3 0 0 1 5.196-3Zm1.536-.887a2.165 2.165 0 0 0 1.083-1.838c.005-.352.054-.695.14-1.025m-1.223 2.863 2.077-1.199m0-3.328a4.323 4.323 0 0 1 2.068-1.379l5.325-1.628a4.5 4.5 0 0 1 2.48-.044l.803.215-7.794 4.5m-2.882-1.664A4.33 4.33 0 0 0 10.607 12m3.736 0 7.794 4.5-.802.215a4.5 4.5 0 0 1-2.48-.043l-5.326-1.629a4.324 4.324 0 0 1-2.068-1.379M14.343 12l-2.882 1.664" />
                </svg>
                <span class="hidden lg:block">-----------------------------------------------------------------------</span>
            </div>
            <h1 class="text-[#fff] text-3xl lg:text-4xl text-center">Meet Our Expert Barbers</h1>
            <div class="text-[#c29e3d] inline-flex">

                <span class="hidden lg:block">-----------------------------------------------------------------------</span>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 rotate-180 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="m7.848 8.25 1.536.887M7.848 8.25a3 3 0 1 1-5.196-3 3 3 0 0 1 5.196 3Zm1.536.887a2.165 2.165 0 0 1 1.083 1.839c.005.351.054.695.14 1.024M9.384 9.137l2.077 1.199M7.848 15.75l1.536-.887m-1.536.887a3 3 0 1 1-5.196 3 3 3 0 0 1 5.196-3Zm1.536-.887a2.165 2.165 0 0 0 1.083-1.838c.005-.352.054-.695.14-1.025m-1.223 2.863 2.077-1.199m0-3.328a4.323 4.323 0 0 1 2.068-1.379l5.325-1.628a4.5 4.5 0 0 1 2.48-.044l.803.215-7.794 4.5m-2.882-1.664A4.33 4.33 0 0 0 10.607 12m3.736 0 7.794 4.5-.802.215a4.5 4.5 0 0 1-2.48-.043l-5.326-1.629a4.324 4.324 0 0 1-2.068-1.379M14.343 12l-2.882 1.664" />
                </svg>
            </div>
        </div>

        <div class="grid lg:mx-10 mt-10 grid-cols-2 lg:grid-cols-4 gap-10">
            <div class="flex flex-col items-center gap-4">
                <img class="w-44 h-44 rounded-full object-cover" src="https://images.unsplash.com/photo-1474176857210-7287d38d27c6?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8dXNlcnMlMjBtZW58ZW58MHx8MHx8fDA%3D" alt="">
                <div class="text-center">
                    <p class="text-[#afafaf] text-lg">Joshua</p>
                    <p class="text-[#878787]">5 years experience</p>
                </div>
            </div>
            <div class="flex flex-col items-center gap-4">
                <img class="w-44 h-44 rounded-full object-cover" src="https://images.unsplash.com/photo-1522075469751-3a6694fb2f61?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDB8fHVzZXJzJTIwbWVufGVufDB8fDB8fHww" alt="">
                <div class="text-center">
                    <p class="text-[#afafaf] text-lg">Andrew</p>
                    <p class="text-[#878787]">6 years experience</p>
                </div>
            </div>
            <div class="flex flex-col items-center gap-4">
                <img class="w-44 h-44 rounded-full object-cover" src="https://images.unsplash.com/photo-1501196354995-cbb51c65aaea?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTcwfHx1c2VycyUyMG1lbnxlbnwwfHwwfHx8MA%3D%3D" alt="">
                <div class="text-center">
                    <p class="text-[#afafaf] text-lg">Tosh</p>
                    <p class="text-[#878787]">3 years experience</p>
                </div>
            </div>
            <div class="flex flex-col items-center gap-4">
                <img class="w-44 h-44 rounded-full object-cover" src="https://images.unsplash.com/photo-1625019030820-e4ed970a6c95?w=700&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjMxfHx1c2VycyUyMG1lbnxlbnwwfHwwfHx8MA%3D%3D" alt="">
                <div class="text-center">
                    <p class="text-[#afafaf] text-lg">Alex</p>
                    <p class="text-[#878787]">8 years experience</p>
                </div>
            </div>
        </div>
    </div>
    <div class="lg:mt-20 mt-10 mx-5 lg:mx-0">
        <h1 class="text-[#afafaf] text-3xl">Testimonials</h1>
        <p class="text-[#828282] mt-2">What our lovely clients say about us.</p>
    </div>
    <div class="grid mt-10 mx-5 lg:mx-0 lg:grid-cols-3 gap-5">
        <div class="bg-[#272727]  rounded">
            <div class="p-5">
                <div class="flex gap-5">
                    <img class="w-16 h-16 rounded-full" src="https://flowbite.com/docs/images/people/profile-picture-1.jpg" alt="">
                    <div class="">
                        <div class="text-[#878787]">
                            <p class="text-[#afafaf]">Scot Moore</p>
                            <span class="text-[#c29e3d] mt-2 gap-3 items-center inline-flex"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
                                    <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                                </svg>
                                5.0</span>

                            <p class="text-xs mt-3">Skilled barbers, friendly atmosphere make each visit a pleasure. Precision cuts to a welcoming vibe, they nail the barbershop experience. Highly recommended for those seeking quality grooming and a touch of style!</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-[#272727] rounded">
            <div class="p-5">
                <div class="flex gap-5">
                    <img class="w-16 h-16 rounded-full" src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="">
                    <div class="">
                        <div class="text-[#878787]">
                            <p class="text-[#afafaf]">Xavier Pitt</p>
                            <span class="text-[#c29e3d] mt-2 gap-3 items-center inline-flex"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
                                    <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                                </svg>
                                5.0</span>

                            <p class="text-xs mt-3">
                                Sharp cuts, great vibes! Dapper Gents is my go-to barbershop. Talented barbers, stylish cuts, and a welcoming atmosphere. Always leave looking and feeling fantastic!
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-[#272727]  rounded">
            <div class="p-5">
                <div class="flex gap-5">
                    <img class="w-16 h-16 rounded-full" src="https://flowbite.com/docs/images/people/profile-picture-3.jpg" alt="">
                    <div class="">
                        <div class="text-[#878787]">
                            <p class="text-[#afafaf]">Austin Loki</p>
                            <span class="text-[#c29e3d] mt-2 gap-3 items-center inline-flex"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
                                    <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                                </svg>
                                5.0</span>

                            <p class="text-xs mt-3">
                                Exceptional cuts, vibrant atmosphere! Dapper Cuts delivers a blend of skill and style. Always leaving with a fresh look and positive vibes. Best barbershop in town!
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="lg:mt-20 mt-10 mx-5 lg:mx-0">
        <div class="grid  lg:grid-cols-2">
            <div class="hidden lg:flex">
                <div class="w-1/3">

                </div>
                <img class="h-[600px] w-3/4" src="../assets/seat.jpg" alt="">
            </div>
            <div class="bg-[#272727] lg:w-5/6 pb-5 lg:pb-0 lg:h-[600px]">
                <div class="p-5">
                    <h1 class="text-white text-3xl">Book A Seat Now</h1>
                    <p class="text-[#878787] mt-3">Fill out the form below and get your seat.</p>
                    <form class="lg:mt-16 mt-10 flex flex-col gap-10">
                        <div class="relative">
                            <input type="text" class="bg-inherit border-[#878787] focus:ring-0 focus:outline-none pl-10 text-white placeholder:text-[#878787] py-2 border rounded w-full" placeholder="Date">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6  text-[#878787] absolute top-2 left-2 h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5m-9-6h.008v.008H12v-.008ZM12 15h.008v.008H12V15Zm0 2.25h.008v.008H12v-.008ZM9.75 15h.008v.008H9.75V15Zm0 2.25h.008v.008H9.75v-.008ZM7.5 15h.008v.008H7.5V15Zm0 2.25h.008v.008H7.5v-.008Zm6.75-4.5h.008v.008h-.008v-.008Zm0 2.25h.008v.008h-.008V15Zm0 2.25h.008v.008h-.008v-.008Zm2.25-4.5h.008v.008H16.5v-.008Zm0 2.25h.008v.008H16.5V15Z" />
                            </svg>

                        </div>
                        <div class="relative">
                            <input type="text" class="bg-inherit border-[#878787] focus:ring-0 focus:outline-none pl-10 text-white placeholder:text-[#878787] py-2 border rounded w-full" placeholder="Time">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 text-[#878787] absolute top-2 left-2  h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                            </svg>

                        </div>
                        <div class="relative">
                            <input type="text" class="bg-inherit border-[#878787] focus:ring-0 focus:outline-none pl-10 text-white placeholder:text-[#878787] py-2 border rounded w-full" placeholder="Branch">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 text-[#878787] absolute top-2 left-2  h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 21h16.5M4.5 3h15M5.25 3v18m13.5-18v18M9 6.75h1.5m-1.5 3h1.5m-1.5 3h1.5m3-6H15m-1.5 3H15m-1.5 3H15M9 21v-3.375c0-.621.504-1.125 1.125-1.125h3.75c.621 0 1.125.504 1.125 1.125V21" />
                            </svg>

                        </div>
                        <div class="relative">
                            <input type="text" class="bg-inherit border-[#878787] focus:ring-0 focus:outline-none pl-10 text-white placeholder:text-[#878787] py-2 border rounded w-full" placeholder="Number of seats">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 text-[#878787] absolute top-2 left-2  h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 0 0 3.741-.479 3 3 0 0 0-4.682-2.72m.94 3.198.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0 1 12 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 0 1 6 18.719m12 0a5.971 5.971 0 0 0-.941-3.197m0 0A5.995 5.995 0 0 0 12 12.75a5.995 5.995 0 0 0-5.058 2.772m0 0a3 3 0 0 0-4.681 2.72 8.986 8.986 0 0 0 3.74.477m.94-3.197a5.971 5.971 0 0 0-.94 3.197M15 6.75a3 3 0 1 1-6 0 3 3 0 0 1 6 0Zm6 3a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Zm-13.5 0a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Z" />
                            </svg>

                        </div>
                        <div>
                            <button class="border border-[#c29e3d] py-2 text-white text-center px-6 rounded">Book Now</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <div class="lg:mt-28 mx-5 lg:mx-0 gap-10 lg:gap-0 mt-10 grid lg:grid-cols-4">
        <div class="text-[#c29e3d] flex gap-2 items-center text-3xl">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon text-[#c29e3d] icon-tabler rotate-90 icon-tabler-cut" width="36" height="36" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                <path d="M7 17m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                <path d="M17 17m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                <path d="M9.15 14.85l8.85 -10.85" />
                <path d="M6 4l8.85 10.85" /></svg>
            DapperCuts
        </div>
        <div>
            <h1 class="text-white text-3xl">Open</h1>
            <ul class="grid mt-2 grid-cols-2 gap-2">
                <li>Monday</li>
                <li>Sunday</li>
                <li>08:00AM</li>
                <li>9:00PM</li>

            </ul>
        </div>
        <div>
            <h1 class="text-white text-3xl">Branches</h1>
            <ul class="grid mt-2 grid-cols-3 gap-2">
                <li>Kericho</li>
                <li>Nairobi</li>
                <li>Nakuru</li>
                <li>Narok</li>
                <li>Bomet</li>
                <li>Nyeri</li>
            </ul>
        </div>
        <div>
            <h1 class="text-white text-3xl">Follow us</h1>
            <ul class="grid mt-2 grid-cols-3 gap-2">
                <li>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-facebook-filled" width="24" height="24" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M18 2a1 1 0 0 1 .993 .883l.007 .117v4a1 1 0 0 1 -.883 .993l-.117 .007h-3v1h3a1 1 0 0 1 .991 1.131l-.02 .112l-1 4a1 1 0 0 1 -.858 .75l-.113 .007h-2v6a1 1 0 0 1 -.883 .993l-.117 .007h-4a1 1 0 0 1 -.993 -.883l-.007 -.117v-6h-2a1 1 0 0 1 -.993 -.883l-.007 -.117v-4a1 1 0 0 1 .883 -.993l.117 -.007h2v-1a6 6 0 0 1 5.775 -5.996l.225 -.004h3z" stroke-width="0" fill="currentColor" /></svg>
                </li>
                <li><svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-x" width="24" height="24" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M4 4l11.733 16h4.267l-11.733 -16z" />
                        <path d="M4 20l6.768 -6.768m2.46 -2.46l6.772 -6.772" /></svg></li>
                <li><svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-instagram" width="24" height="24" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M4 4m0 4a4 4 0 0 1 4 -4h8a4 4 0 0 1 4 4v8a4 4 0 0 1 -4 4h-8a4 4 0 0 1 -4 -4z" />
                        <path d="M12 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
                        <path d="M16.5 7.5l0 .01" /></svg></li>
                <li>Facebook</li>
                <li>X</li>
                <li>Instagram</li>
            </ul>
        </div>
    </div>
</main>
</template>

  
  
<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
    name: 'HomeView',
    components: {
        HelloWorld
    }
}
</script>
  
  
<style>
body,
html {
    background-color: #1e1e1e;
}
</style>
