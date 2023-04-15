<template>
    <div class="bg-gray-200 dark:bg-gray-800">



      <nav class="fixed top-0 z-50 w-full bg-white border-b border-gray-200 dark:bg-gray-800 dark:border-gray-700">
         <div class="px-3 py-3 lg:px-5 lg:pl-3">
            <div class="flex items-center justify-between">
            <div class="flex items-center justify-start">
               <button data-drawer-target="logo-sidebar" data-drawer-toggle="logo-sidebar" aria-controls="logo-sidebar" type="button" class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600">
                  <span class="sr-only">Open sidebar</span>
                  <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                     <path clip-rule="evenodd" fill-rule="evenodd" d="M2 4.75A.75.75 0 012.75 4h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 4.75zm0 10.5a.75.75 0 01.75-.75h7.5a.75.75 0 010 1.5h-7.5a.75.75 0 01-.75-.75zM2 10a.75.75 0 01.75-.75h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 10z"></path>
                  </svg>
               </button>
               <a href="https://flowbite.com" class="flex ml-2 md:mr-24">
                  <img class="h-8 mr-3" alt="FlowBite Logo" src="./../assets/logo.png" />
                  <span class="self-center text-xl font-semibold sm:text-2xl whitespace-nowrap dark:text-white">JKUAT TIMES</span>
               </a>
            </div>
            <div class="flex items-center">
                  <div class="flex items-center ml-3">
                  <div>
                     <button type="button" class="flex text-sm bg-gray-800 rounded-full focus:ring-4 focus:ring-gray-300 dark:focus:ring-gray-600" aria-expanded="false" data-dropdown-toggle="dropdown-user">
                        <span class="sr-only">Open user menu</span>
                        <img class="w-8 h-8 rounded-full" src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="user photo">
                     </button>
                  </div>
                  <div class="z-50 hidden my-4 text-base list-none bg-white divide-y divide-gray-100 rounded shadow dark:bg-gray-700 dark:divide-gray-600" id="dropdown-user">
                     <div class="px-4 py-3" role="none">
                        <p class="text-sm text-gray-900 dark:text-white" role="none">
                        Neil Sims
                        </p>
                        <p class="text-sm font-medium text-gray-900 truncate dark:text-gray-300" role="none">
                        neil.sims@flowbite.com
                        </p>
                     </div>
                     <ul class="py-1" role="none">
                        <li>
                        <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:text-gray-300 dark:hover:bg-gray-600 dark:hover:text-white" role="menuitem">Dashboard</a>
                        </li>
                        <li>
                        <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:text-gray-300 dark:hover:bg-gray-600 dark:hover:text-white" role="menuitem">Settings</a>
                        </li>
                        <li>
                        <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:text-gray-300 dark:hover:bg-gray-600 dark:hover:text-white" role="menuitem">Earnings</a>
                        </li>
                        <li>
                        <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:text-gray-300 dark:hover:bg-gray-600 dark:hover:text-white" role="menuitem">Sign out</a>
                        </li>
                     </ul>
                  </div>
                  </div>
               </div>
            </div>
         </div>
      </nav>

      <div class="flex flex-row">
         <!-- Sidebar left-->
         <div class="basis-0 md:basis-1/5 overflow-hidden">
            <aside id="logo-sidebar" class="fixed top-0 left-0 z-40 w-1/5 h-screen pt-20 transition-transform -translate-x-full bg-white border-r border-gray-200 md:translate-x-0 dark:bg-gray-800 dark:border-gray-700" aria-label="Sidebar">
               <div class="h-full px-3 pb-4 overflow-y-auto bg-white dark:bg-gray-800">
                  <ul class="space-y-2 font-medium">
                     <li>
                        <a href="#" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                           <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM11 13a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"></path></svg>
                           <span class="flex-1 ml-3 whitespace-nowrap">Favourites</span>
                        </a>
                     </li>
                     <li>
                        <a href="#" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                           <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M8.707 7.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l2-2a1 1 0 00-1.414-1.414L11 7.586V3a1 1 0 10-2 0v4.586l-.293-.293z"></path><path d="M3 5a2 2 0 012-2h1a1 1 0 010 2H5v7h2l1 2h4l1-2h2V5h-1a1 1 0 110-2h1a2 2 0 012 2v10a2 2 0 01-2 2H5a2 2 0 01-2-2V5z"></path></svg>
                           <span class="flex-1 ml-3 whitespace-nowrap">Inbox</span>
                           <span class="inline-flex items-center justify-center w-3 h-3 p-3 ml-3 text-sm font-medium text-blue-800 bg-blue-100 rounded-full dark:bg-blue-900 dark:text-blue-300">3</span>
                        </a>
                     </li>
                     <li>
                        <a href="#" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                           <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd"></path></svg>
                           <span class="flex-1 ml-3 whitespace-nowrap">Podcasts</span>
                        </a>
                     </li>
                     <li>
                        <a href="#" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                           <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 2a4 4 0 00-4 4v1H5a1 1 0 00-.994.89l-1 9A1 1 0 004 18h12a1 1 0 00.994-1.11l-1-9A1 1 0 0015 7h-1V6a4 4 0 00-4-4zm2 5V6a2 2 0 10-4 0v1h4zm-6 3a1 1 0 112 0 1 1 0 01-2 0zm7-1a1 1 0 100 2 1 1 0 000-2z" clip-rule="evenodd"></path></svg>
                           <span class="flex-1 ml-3 whitespace-nowrap">Settings</span>
                        </a>
                     </li>
                     <li>
                        <a href="#" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                           <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 3a1 1 0 00-1 1v12a1 1 0 102 0V4a1 1 0 00-1-1zm10.293 9.293a1 1 0 001.414 1.414l3-3a1 1 0 000-1.414l-3-3a1 1 0 10-1.414 1.414L14.586 9H7a1 1 0 100 2h7.586l-1.293 1.293z" clip-rule="evenodd"></path></svg>
                           <span class="flex-1 ml-3 whitespace-nowrap">Sign In</span>
                        </a>
                     </li>
                     <li>
                        <a href="#" class="flex items-center p-2 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                           <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5 4a3 3 0 00-3 3v6a3 3 0 003 3h10a3 3 0 003-3V7a3 3 0 00-3-3H5zm-1 9v-1h5v2H5a1 1 0 01-1-1zm7 1h4a1 1 0 001-1v-1h-5v2zm0-4h5V8h-5v2zM9 8H4v2h5V8z" clip-rule="evenodd"></path></svg>
                           <span class="flex-1 ml-3 whitespace-nowrap">Sign Up</span>
                        </a>
                     </li>
                  </ul>
               </div>
            </aside>
         </div>

         <!-- Sidebar mid-->
         <div class="basis-full md:basis-4/5 overflow-auto">

            <!-- Section: Design Block -->
            <section class="text-gray-800 dark:text-gray-200 text-center md:text-left p-6">

                  <h2 class="text-3xl font-bold mb-12 text-center">Latest articles</h2>

                  <div class="flex flex-wrap mb-6">
                     <div class="grow-0 shrink-0 basis-auto w-full md:w-3/12 px-3 mb-6 md:mb-0 ml-auto">
                        <div class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover ripple shadow-lg rounded-lg mb-6"
                              data-mdb-ripple="true" data-mdb-ripple-color="light">
                              <img src="https://mdbootstrap.com/img/new/standard/city/018.jpg" class="w-full" alt="Louvre" />
                              <a href="#!">
                                 <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                                    style="background-color: rgba(251, 251, 251, 0.2)"></div>
                              </a>
                        </div>
                     </div>

                     <div class="grow-0 shrink-0 basis-auto w-full md:w-9/12 xl:w-7/12 px-3 mb-6 md:mb-0 mr-auto">
                        <h5 class="text-lg font-bold mb-3">Welcome to California</h5>
                        <div class="mb-3 text-red-600 font-medium text-sm flex items-center justify-center md:justify-start">
                              <svg class="w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512">
                                 <path fill="currentColor"
                                    d="M248 8C111.03 8 0 119.03 0 256s111.03 248 248 248 248-111.03 248-248S384.97 8 248 8zm82.29 357.6c-3.9 3.88-7.99 7.95-11.31 11.28-2.99 3-5.1 6.7-6.17 10.71-1.51 5.66-2.73 11.38-4.77 16.87l-17.39 46.85c-13.76 3-28 4.69-42.65 4.69v-27.38c1.69-12.62-7.64-36.26-22.63-51.25-6-6-9.37-14.14-9.37-22.63v-32.01c0-11.64-6.27-22.34-16.46-27.97-14.37-7.95-34.81-19.06-48.81-26.11-11.48-5.78-22.1-13.14-31.65-21.75l-.8-.72a114.792 114.792 0 0 1-18.06-20.74c-9.38-13.77-24.66-36.42-34.59-51.14 20.47-45.5 57.36-82.04 103.2-101.89l24.01 12.01C203.48 89.74 216 82.01 216 70.11v-11.3c7.99-1.29 16.12-2.11 24.39-2.42l28.3 28.3c6.25 6.25 6.25 16.38 0 22.63L264 112l-10.34 10.34c-3.12 3.12-3.12 8.19 0 11.31l4.69 4.69c3.12 3.12 3.12 8.19 0 11.31l-8 8a8.008 8.008 0 0 1-5.66 2.34h-8.99c-2.08 0-4.08.81-5.58 2.27l-9.92 9.65a8.008 8.008 0 0 0-1.58 9.31l15.59 31.19c2.66 5.32-1.21 11.58-7.15 11.58h-5.64c-1.93 0-3.79-.7-5.24-1.96l-9.28-8.06a16.017 16.017 0 0 0-15.55-3.1l-31.17 10.39a11.95 11.95 0 0 0-8.17 11.34c0 4.53 2.56 8.66 6.61 10.69l11.08 5.54c9.41 4.71 19.79 7.16 30.31 7.16s22.59 27.29 32 32h66.75c8.49 0 16.62 3.37 22.63 9.37l13.69 13.69a30.503 30.503 0 0 1 8.93 21.57 46.536 46.536 0 0 1-13.72 32.98zM417 274.25c-5.79-1.45-10.84-5-14.15-9.97l-17.98-26.97a23.97 23.97 0 0 1 0-26.62l19.59-29.38c2.32-3.47 5.5-6.29 9.24-8.15l12.98-6.49C440.2 193.59 448 223.87 448 256c0 8.67-.74 17.16-1.82 25.54L417 274.25z" />
                              </svg>Travels
                        </div>
                        <p class="text-gray-800 dark:text-gray-200 mb-6">
                              <small>Published <u>13.01.2022</u> by
                                 <a href="" class="text-gray-800 dark:text-gray-200">Anna Maria Doe</a></small>
                        </p>
                        <p class="text-gray-800 dark:text-gray-200">
                              Ut pretium ultricies dignissim. Sed sit amet mi eget urna
                              placerat vulputate. Ut vulputate est non quam dignissim
                              elementum. Donec a ullamcorper diam.
                        </p>
                     </div>
                  </div>

                  <div class="flex flex-wrap mb-6">
                     <div class="grow-0 shrink-0 basis-auto w-full md:w-3/12 px-3 mb-6 md:mb-0 ml-auto">
                        <div class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover ripple shadow-lg rounded-lg mb-6"
                              data-mdb-ripple="true" data-mdb-ripple-color="light">
                              <img src="https://mdbootstrap.com/img/new/standard/city/032.jpg" class="w-full" alt="Louvre" />
                              <a href="#!">
                                 <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                                    style="background-color: rgba(251, 251, 251, 0.2)"></div>
                              </a>
                        </div>
                     </div>

                     <div class="grow-0 shrink-0 basis-auto w-full md:w-9/12 xl:w-7/12 px-3 mb-6 md:mb-0 mr-auto">
                        <h5 class="text-lg font-bold mb-3">Exhibition in Paris</h5>
                        <div class="mb-3 text-blue-600 font-medium text-sm flex items-center justify-center md:justify-start">
                              <svg class="w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                 <path fill="currentColor"
                                    d="M204.3 5C104.9 24.4 24.8 104.3 5.2 203.4c-37 187 131.7 326.4 258.8 306.7 41.2-6.4 61.4-54.6 42.5-91.7-23.1-45.4 9.9-98.4 60.9-98.4h79.7c35.8 0 64.8-29.6 64.9-65.3C511.5 97.1 368.1-26.9 204.3 5zM96 320c-17.7 0-32-14.3-32-32s14.3-32 32-32 32 14.3 32 32-14.3 32-32 32zm32-128c-17.7 0-32-14.3-32-32s14.3-32 32-32 32 14.3 32 32-14.3 32-32 32zm128-64c-17.7 0-32-14.3-32-32s14.3-32 32-32 32 14.3 32 32-14.3 32-32 32zm128 64c-17.7 0-32-14.3-32-32s14.3-32 32-32 32 14.3 32 32-14.3 32-32 32z" />
                              </svg>Art
                        </div>
                        <p class="text-gray-800 dark:text-gray-200 mb-6">
                              <small>Published <u>12.01.2022</u> by
                                 <a href="" class="text-gray-800 dark:text-gray-200">Halley Frank</a></small>
                        </p>
                        <p class="text-gray-800 dark:text-gray-200">
                              Suspendisse in volutpat massa. Nulla facilisi. Sed aliquet diam
                              orci, nec ornare metus semper sed. Integer volutpat ornare erat
                              sit amet rutrum.
                        </p>
                     </div>
                  </div>

                  <div class="flex flex-wrap mb-6">
                     <div class="grow-0 shrink-0 basis-auto w-full md:w-3/12 px-3 mb-6 md:mb-0 ml-auto">
                        <div class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover ripple shadow-lg rounded-lg mb-6"
                              data-mdb-ripple="true" data-mdb-ripple-color="light">
                              <img src="https://mdbootstrap.com/img/new/standard/city/059.jpg" class="w-full" alt="Louvre" />
                              <a href="#!">
                                 <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                                    style="background-color: rgba(251, 251, 251, 0.2)"></div>
                              </a>
                        </div>
                     </div>

                     <div class="grow-0 shrink-0 basis-auto w-full md:w-9/12 xl:w-7/12 px-3 mb-6 md:mb-0 mr-auto">
                        <h5 class="text-lg font-bold mb-3">Stock market boom</h5>
                        <div class="mb-3 text-yellow-500 font-medium text-sm flex items-center justify-center md:justify-start">
                              <svg class="w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512">
                                 <path fill="currentColor"
                                    d="M608 64H32C14.33 64 0 78.33 0 96v320c0 17.67 14.33 32 32 32h576c17.67 0 32-14.33 32-32V96c0-17.67-14.33-32-32-32zM48 400v-64c35.35 0 64 28.65 64 64H48zm0-224v-64h64c0 35.35-28.65 64-64 64zm272 176c-44.19 0-80-42.99-80-96 0-53.02 35.82-96 80-96s80 42.98 80 96c0 53.03-35.83 96-80 96zm272 48h-64c0-35.35 28.65-64 64-64v64zm0-224c-35.35 0-64-28.65-64-64h64v64z" />
                              </svg>Business
                        </div>
                        <p class="text-gray-800 dark:text-gray-200 mb-6">
                              <small>Published <u>10.01.2022</u> by
                                 <a href="" class="text-gray-800 dark:text-gray-200">Joe Svan</a></small>
                        </p>
                        <p class="text-gray-800 dark:text-gray-200">
                              Curabitur tristique, mi a mollis sagittis, metus felis mattis
                              arcu, non vehicula nisl dui quis diam. Mauris ut risus eget
                              massa volutpat feugiat. Donec.
                        </p>
                     </div>
                  </div>

                  <div class="flex flex-wrap mb-6">
                     <div class="grow-0 shrink-0 basis-auto w-full md:w-3/12 px-3 mb-6 md:mb-0 ml-auto">
                        <div class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover ripple shadow-lg rounded-lg mb-6"
                              data-mdb-ripple="true" data-mdb-ripple-color="light">
                              <img src="https://mdbootstrap.com/img/new/standard/city/059.jpg" class="w-full" alt="Louvre" />
                              <a href="#!">
                                 <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                                    style="background-color: rgba(251, 251, 251, 0.2)"></div>
                              </a>
                        </div>
                     </div>

                     <div class="grow-0 shrink-0 basis-auto w-full md:w-9/12 xl:w-7/12 px-3 mb-6 md:mb-0 mr-auto">
                        <h5 class="text-lg font-bold mb-3">Stock market boom</h5>
                        <div class="mb-3 text-yellow-500 font-medium text-sm flex items-center justify-center md:justify-start">
                              <svg class="w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512">
                                 <path fill="currentColor"
                                    d="M608 64H32C14.33 64 0 78.33 0 96v320c0 17.67 14.33 32 32 32h576c17.67 0 32-14.33 32-32V96c0-17.67-14.33-32-32-32zM48 400v-64c35.35 0 64 28.65 64 64H48zm0-224v-64h64c0 35.35-28.65 64-64 64zm272 176c-44.19 0-80-42.99-80-96 0-53.02 35.82-96 80-96s80 42.98 80 96c0 53.03-35.83 96-80 96zm272 48h-64c0-35.35 28.65-64 64-64v64zm0-224c-35.35 0-64-28.65-64-64h64v64z" />
                              </svg>Business
                        </div>
                        <p class="text-gray-800 dark:text-gray-200 mb-6">
                              <small>Published <u>10.01.2022</u> by
                                 <a href="" class="text-gray-800 dark:text-gray-200">Joe Svan</a></small>
                        </p>
                        <p class="text-gray-800 dark:text-gray-200">
                              Curabitur tristique, mi a mollis sagittis, metus felis mattis
                              arcu, non vehicula nisl dui quis diam. Mauris ut risus eget
                              massa volutpat feugiat. Donec.
                        </p>
                     </div>
                  </div>

                  <div class="flex flex-wrap mb-6">
                     <div class="grow-0 shrink-0 basis-auto w-full md:w-3/12 px-3 mb-6 md:mb-0 ml-auto">
                        <div class="relative overflow-hidden bg-no-repeat bg-cover relative overflow-hidden bg-no-repeat bg-cover ripple shadow-lg rounded-lg mb-6"
                              data-mdb-ripple="true" data-mdb-ripple-color="light">
                              <img src="https://mdbootstrap.com/img/new/standard/city/059.jpg" class="w-full" alt="Louvre" />
                              <a href="#!">
                                 <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-100 transition duration-300 ease-in-out"
                                    style="background-color: rgba(251, 251, 251, 0.2)"></div>
                              </a>
                        </div>
                     </div>

                     <div class="grow-0 shrink-0 basis-auto w-full md:w-9/12 xl:w-7/12 px-3 mb-6 md:mb-0 mr-auto">
                        <h5 class="text-lg font-bold mb-3">Stock market boom</h5>
                        <div class="mb-3 text-yellow-500 font-medium text-sm flex items-center justify-center md:justify-start">
                              <svg class="w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512">
                                 <path fill="currentColor"
                                    d="M608 64H32C14.33 64 0 78.33 0 96v320c0 17.67 14.33 32 32 32h576c17.67 0 32-14.33 32-32V96c0-17.67-14.33-32-32-32zM48 400v-64c35.35 0 64 28.65 64 64H48zm0-224v-64h64c0 35.35-28.65 64-64 64zm272 176c-44.19 0-80-42.99-80-96 0-53.02 35.82-96 80-96s80 42.98 80 96c0 53.03-35.83 96-80 96zm272 48h-64c0-35.35 28.65-64 64-64v64zm0-224c-35.35 0-64-28.65-64-64h64v64z" />
                              </svg>Business
                        </div>
                        <p class="text-gray-800 dark:text-gray-200 mb-6">
                              <small>Published <u>10.01.2022</u> by
                                 <a href="" class="text-gray-800 dark:text-gray-200">Joe Svan</a></small>
                        </p>
                        <p class="text-gray-800 dark:text-gray-200">
                              Curabitur tristique, mi a mollis sagittis, metus felis mattis
                              arcu, non vehicula nisl dui quis diam. Mauris ut risus eget
                              massa volutpat feugiat. Donec.
                        </p>
                     </div>
                  </div>

            </section>
            <!-- Section: Design Block -->

         </div>

         <!-- Sidebar right-->
         <div class="basis-0 md:basis-1/5 overflow-hidden">
            <aside id="logo-sidebar" class="fixed top-0 right-0 z-40 w-1/5 h-screen pt-20 transition-transform translate-x-full md:translate-x-0 bg-white border-l border-gray-200 dark:bg-gray-800 dark:border-gray-700" aria-label="Sidebar">
               <div class="h-full px-3 pb-4 overflow-y-auto bg-white dark:bg-gray-800">
                  <span>
                     <!--Trending-->
                     <p>
                        <span class="ml-2 text-sm font-medium dark:text-white">Recently Viewed</span>
                     </p>
                  </span>
                  <ul class="space-y-2 font-medium text-xs">
                     <li class="py-2">
                        <p class="text-gray-800 dark:text-gray-200 ml-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati tempora corporis fugit quaerat odio reiciendis, mollitia esse, quam consequuntur possimus et, consectetur eum aliquam quo nisi. Fugit molestias architecto iste.
                        </p>
                     </li>

                     <li class="py-2">
                        <p class="text-gray-800 dark:text-gray-200 ml-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati tempora corporis fugit quaerat odio reiciendis, mollitia esse, quam consequuntur possimus et, consectetur eum aliquam quo nisi. Fugit molestias architecto iste.
                        </p>
                     </li>

                     <li class="py-2">
                        <p class="text-gray-800 dark:text-gray-200 ml-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati tempora corporis fugit quaerat odio reiciendis, mollitia esse, quam consequuntur possimus et, consectetur eum aliquam quo nisi. Fugit molestias architecto iste.
                        </p>
                     </li>

                     <li class="py-2">
                        <p class="text-gray-800 dark:text-gray-200 ml-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati tempora corporis fugit quaerat odio reiciendis, mollitia esse, quam consequuntur possimus et, consectetur eum aliquam quo nisi. Fugit molestias architecto iste.
                        </p>
                     </li>

                  </ul>
               </div>
            </aside>
         </div>
      </div>

    </div>
</template>


