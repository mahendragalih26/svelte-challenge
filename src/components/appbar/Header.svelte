<script>
    import Icon from "../../assets/logo.svg"
    import Avatar from "../../assets/dashboard/profile.svg"
</script>

<header>
    <nav class="bg-white border-gray-200 px-4 lg:px-6 py-2.5 ">
        <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl">
            <a href="https://flowbite.com" class="flex items-center">
                <img src={Icon} class="mr-3 h-5 sm:h-5" alt="column9 Logo" />
                <!-- <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">Column</span> -->
            </a>
            <div class="flex items-center lg:order-2">
                <img class="inline-block h-12 w-12 rounded-full ring-2 ring-white" src="{Avatar}" alt="{"Avatar"}"/>
                <button data-collapse-toggle="mobile-menu-2" type="button" class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg lg:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="mobile-menu-2" aria-expanded="false">
                    <span class="sr-only">Open main menu</span>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
                    <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                </button>
            </div>
            <div class="hidden justify-between items-center w-full lg:flex lg:w-auto lg:order-1" id="mobile-menu-2">
                <ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0">
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900" aria-current="page">Home</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900">Courses</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900">Instructors</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900">Schedules</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pr-4 pl-3 px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900">Contac Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</header>