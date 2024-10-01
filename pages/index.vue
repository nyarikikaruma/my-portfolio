<template>
    <div style="background-color: #050816;">
        <nav class="bg-white border-gray-200 dark:bg-gray-900">
            <div class="flex flex-wrap justify-between mx-auto p-4">
                <a href="https://flowbite.com/" class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img src="/assets/img/profile.png" class="h-8 rounded-full" alt="Flowbite Logo" />
                    <span
                        class="self-center text-base md:text-2xl font-semibold whitespace-nowrap dark:text-white">George
                        Karuma | Fullstack Developer</span>
                </a>
                <button data-collapse-toggle="navbar-default" type="button"
                    class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                    aria-controls="navbar-default" aria-expanded="false">
                    <span class="sr-only">Open main menu</span>
                    <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                        viewBox="0 0 17 14">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M1 1h15M1 7h15M1 13h15" />
                    </svg>
                </button>
                <div class="hidden w-full md:block md:w-auto" id="navbar-default">
                    <ul
                        class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
                        <li>
                            <a href="#"
                                class="block py-2 px-3 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white md:dark:text-blue-500"
                                aria-current="page">Home</a>
                        </li>
                        <li>
                            <a href="#"
                                class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">About</a>
                        </li>
                        <li>
                            <a href="#"
                                class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Services</a>
                        </li>
                        <li>
                            <a href="#"
                                class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Pricing</a>
                        </li>
                        <li>
                            <a href="#"
                                class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- HERO SECTION -->
        <div class="mb-12 text-white mt-8">
            <div class="pl-8">
                <div class="font-extrabold text-4xl md:text-5xl my-4">Hi, I'm George</div>
                <div class="max-w-64 md:max-w-96 text-xl md:text-3xl">I make software that works. Blending front-end
                    magic with
                    backend logic
                    to
                    bring ideas to life.
                </div>
            </div>
        </div>
        <!-- INTRODUCTION -->
        <div class="mt-12 ml-8 text-white">
            <div class="text-slate-400 text-lg">INTRODUCTION</div>
            <div class="text-5xl font-extrabold text-gray-50 mb-8 mt-2">Summary</div>
            <div class="w-1/2 text-white text-lg">Greetings! I'm George Karuma, a passionate and experienced Full
                Stack Developer
                with
                over 3 years of
                industry experience. My expertise lies in crafting robust, scalable, and user-centric web applications
                using cutting-edge technologies.</div>
            <div class="text-slate-400 text-base">
                <p>Phone: +254714837245</p>
                <p>Email: nyarikikaruma@gmail.com</p>
            </div>
            <div class="flex flex-col md:flex-row mt-3 space-y-3 md:space-y-0 md:space-x-3">
                <button type="button"
                    class="text-white bg-purple-700 hover:bg-purple-800 focus:outline-none focus:ring-4 focus:ring-purple-300 font-medium rounded-full text-sm px-5 py-2.5 text-center dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">
                    <a href="https://www.linkedin.com/in/george-karuma/" target="_blank">LinkedIn</a>
                </button>
                <button type="button"
                    class="text-white bg-purple-700 hover:bg-purple-800 focus:outline-none focus:ring-4 focus:ring-purple-300 font-medium rounded-full text-sm px-5 py-2.5 text-center dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">
                    <a href="https://www.github.com/nyarikikaruma/" target="_blank">Github Profile</a>
                </button>
                <button
                    class="text-white bg-purple-700 hover:bg-purple-800 focus:outline-none focus:ring-4 focus:ring-purple-300 font-medium rounded-full text-sm px-5 py-2.5 text-center dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">
                    <a target="_blank" href="/pdf/resume.pdf" width="1440px" height="900px">Download Resume</a>
                </button>
            </div>

        </div>
        <!-- TECH STACK -->
        <div class="m-10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 justify-items-center">
            <div
                class="w-64 mb-4 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <div class="flex flex-col items-center p-10">
                    <img class="w-24 h-24 mb-3 rounded-full shadow-lg" src="/assets/img/vue.svg" alt="Vue image" />
                    <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Vue Js</h5>
                    <span class="text-sm text-gray-500 dark:text-gray-400">Developer</span>
                </div>
            </div>
            <div
                class="w-64 mb-4 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <div class="flex flex-col items-center p-10">
                    <img class="w-24 h-24 mb-3 shadow-lg" src="/assets/img/laravel.svg" alt="Laravel image" />
                    <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Laravel</h5>
                    <span class="text-sm text-gray-500 dark:text-gray-400">Developer</span>
                </div>
            </div>
            <div
                class="w-64 mb-4 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <div class="flex flex-col items-center p-10">
                    <img class="w-24 h-24 mb-3 rounded-full shadow-lg" src="/assets/img/node.svg" alt="Node image" />
                    <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Node Js</h5>
                    <span class="text-sm text-gray-500 dark:text-gray-400">Developer</span>
                </div>
            </div>
            <div
                class="w-64 mb-4 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <div class="flex flex-col items-center p-10">
                    <img class="w-24 h-24 mb-3 rounded-full shadow-lg" src="/assets/img/tailwind.svg"
                        alt="Tailwind image" />
                    <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Tailwind CSS</h5>
                    <span class="text-sm text-gray-500 dark:text-gray-400">Developer</span>
                </div>
            </div>
        </div>

        <!-- WORK EXPERIENCE -->
        <div class="mt-10">
            <div class="flex justify-center">
                <div class="text-center">
                    <div class="text-slate-400 text-lg">WHAT I HAVE DONE SO FAR</div>
                    <div class="font-extrabold text-5xl text-white">Work Experience</div>
                </div>
            </div>

            <!-- First Row -->
            <div class="grid grid-cols-1 md:grid-cols-12 gap-4 mt-5">
                <div
                    class="md:col-start-3 md:col-span-3 p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <a href="#">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Senior Frontend
                            Developer</h5>
                    </a>
                    <p class="text-white"><a href="https://nathandigital.com/">Nathan Digital</a></p>
                    <p class="md:hidden text-slate-400 text-lg"> August 2024 - Present</p>
                    <p class="md:col-span-3 mb-3 font-normal text-gray-700 dark:text-gray-400">
                        Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological
                        order.
                    </p>
                </div>
                <div class="hidden md:flex justify-center items-center md:col-span-1">
                    <div class="w-2 bg-slate-300 h-64"></div>
                </div>
                <div class="hidden md:contents md:col-span-12">
                    <p class="text-slate-400 text-lg md:col-span-5"> August 2024 - Present</p>
                </div>
            </div>

            <!-- Second Row -->
            <div class="grid grid-cols-1 md:grid-cols-12 gap-4 mt-5">
                <div class="hidden md:contents md:col-span-2">
                    <p class="text-slate-400 text-lg md:col-start-4 md:col-span-5">Feb 2024
                        - Aug 2024</p>
                </div>
                <div class="hidden md:flex justify-center items-center md:col-span-1">
                    <div class="w-2 bg-slate-300 h-64"></div>
                </div>
                <div
                    class="md:col-span-3 p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <a href="#">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Fullstack
                            Developer</h5>
                    </a>
                    <p class="text-slate-400 text-lg md:hidden">Feb 2024 - Aug 2024</p>
                    <p class="text-white"><a href="https://zuri-labs.vercel.app/">Zuri Labs Africa</a></p>
                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
                        Developed and maintained full stack web applications using Laravel, Vue.js, and Nuxt.js.
                    </p>
                </div>
            </div>

            <!-- Third Row -->
            <div class="grid grid-cols-1 md:grid-cols-12 gap-4 mt-5">
                <div
                    class="md:col-start-3 md:col-span-3 p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <a href="#">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Fullstack
                            Developer</h5>
                    </a>
                    <p class="text-white"><a href="https://goatmentor.tech/">Goatmentor Technologies</a></p>
                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
                        Developed and maintained full stack web applications using Laravel, Vue.js, and Nuxt.js.
                        Collaborated with UI/UX developers to craft user-friendly applications.
                    </p>
                </div>
                <div class="hidden md:flex justify-center items-center md:col-span-1">
                    <div class="w-2 bg-slate-300 h-64"></div>
                </div>
                <div class="md:col-span-2">
                    <p class="text-slate-400 text-lg"> April 2022 - Feb 2024</p>
                </div>
            </div>

            <!-- Fourth Row -->
            <div class="grid grid-cols-1 md:grid-cols-12 gap-4 mt-5">
                <div class="md:col-span-2 md:col-start-4">
                    <p class="text-slate-400 text-lg"> May 2019 - Aug 2019
                    </p>
                </div>
                <div class="hidden md:flex justify-center items-center md:col-span-1">
                    <div class="w-2 bg-slate-300 h-64"></div>
                </div>
                <div
                    class="md:col-span-3 p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <a href="#">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Web Developer
                            Intern</h5>
                    </a>
                    <p class="text-white">Zalego Institute of Technology</p>
                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
                        I created e-commerce applications using Vanilla PHP and gained great knowledge in programming.
                    </p>
                </div>
            </div>
        </div>

        <div class="mt-10">
            <div class="flex justify-center">
                <div class="text-center">
                    <div class="text-slate-400 text-lg">TOOLS</div>
                    <div class="font-extrabold text-5xl text-white">Skills</div>
                </div>
            </div>
            <div class="m-5 grid md:grid-cols-6 grid-cols-2 gap-4">
                <img src="/assets/img/php.svg" alt="" class="h-24">
                <img src="/assets/img/javascript.svg" alt="" class="h-24">
                <img src="/assets/img/node.svg" alt="" class="h-24 bg-green-300 rounded-md">
                <img src="/assets/img/laravel.svg" alt="" class="h-24">
                <img src="/assets/img/vue.svg" alt="" class="h-24 bg-green-400 rounded-md">
                <img src="/assets/img/nuxt.svg" alt="" class="h-24">
                <img src="/assets/img/tailwind.svg" alt="" class="h-24">
                <img src="/assets/img/mongo.svg" alt="" class="h-24">
                <img src="/assets/img/mysql.svg" alt="" class="h-24">
            </div>
        </div>

    </div>
</template>

<script setup>

</script>

<style></style>