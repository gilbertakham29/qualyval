<template>
    <main class="grid grid-cols-1 gap-8 px-2 py-12 mx-auto mb-5 sm:grid-cols-2 max-w-screen-2xl sm:py-16">

<div class="order-2 sm:pl-8 place-self-center sm:order-1">
    <div class="px-5 py-2 my-10 border-l-8 border-l-green-500">
        <p class="font-medium text-gray-500 S sm:text-lg">Earlier this month my team implemented their first automation.Concept to implementation was less than 60 days and ROI will exceed 600%! Most importantly, it eliminates repetitive daily tasks to drive better customer and employee experience. A huge thank you to <span class="text-primary-500">Pramod Rai</span>  and the fantastic team at <span class="text-primary-500"> Qualyval</span> !.</p>
        <div class="flex items-center gap-5 mt-8">
              <img src="https://www.qualyval.com/images/companies/review-profile.webp" alt="review-image" clas="w-14"/>
              <div>
                <span class="font-bold sm:">Paul Croke</span>
                <p class="text-xs text-gray-900 sm:text-xs">
                    President at Hinrichs Estimating
                </p>
              </div>
        </div>
    </div>
    <button type="button" data-modal-target="authentication-modal" data-modal-toggle="authentication-modal" class="flex items-center w-auto px-8 py-3 mx-auto font-medium text-center text-white rounded-lg sm:mt-12 sm:ml-20 bg-green-500 sm:w-fit hover:bg-primary-800 focus:ring-4 focus:outline-none">
        Discover More
    </button>
</div>
<div class="flex flex-col items-center order-1 gap-5 sm:order-2">
    <div class="flex flex-wrap items-center w-full gap-3 sm:gap-7">
        <div class="flex gap-1 px-4 py-1 items-center text-xs font-medium border rounded-full text-green-500 bg-green-100 border-green-500">
            <span class="text-lg text-green-500 ">
                <iconify-icon icon="mdi:robot"></iconify-icon>
            </span>AI
        </div>
        <div class="flex gap-1 px-4 py-1 items-center text-xs font-medium border rounded-full text-green-500 bg-green-100 border-green-500">
            <span class="text-lg w-4 h-5 text-green-500 ">
                <iconify-icon icon="ep:setting"></iconify-icon>
            </span>Automation
        </div>
        <div class="flex gap-1 px-4 py-1 items-center text-xs font-medium border rounded-full text-green-500 bg-green-100 border-green-500">
            <span class="text-lg w-4 h-5 text-green-500 ">
                <iconify-icon icon="carbon:tool-kit"></iconify-icon>
            </span>Integration
        </div>
        <div class="flex gap-1 px-4 py-1 items-center text-xs font-medium border rounded-full text-green-500 bg-green-100 border-green-500">
            <span class="text-lg w-4 h-5 text-green-500 ">
                <iconify-icon icon="uit:circuit"></iconify-icon>
            </span>Digital Products
        </div>
        <div class="flex flex-col max-w-2xl my-5">
            <h1 class="text-3xl sm:text-[2.75rem] font-bold leading-tight lg:text-6xl">Boost Productivity with AI & Automation</h1>
            <p class="w-full mt-10 font-medium text-gray-500 sm:text-lg sm:w-3/4 lg:w-11/12">
                We assist businesses in achieving growth, solving problems, enhancing productivity, and optimising efficiency through the application of AI, Automation, and Digital technologies.
            </p>
        </div>
        <div class="grid w-full grid-cols-2 gap-5 font-bold">
            <div class="flex items-center gap-1 text-gray-500 sm:text-lg">
                <svg class="w-[40px] sm:w-6 h-[40px] sm:h-6 text-green-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m7 10 2 2 4-4m6 2a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
  </svg>200+ Processes automated
            </div>
            <div class="flex items-center gap-1 text-gray-500 sm:text-lg">
                <svg class="w-[40px] sm:w-6 h-[40px] sm:h-6 text-green-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m7 10 2 2 4-4m6 2a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
  </svg>10+ Digital Products delivered
            </div>
            <div class="flex items-center gap-1 text-gray-500 sm:text-lg">
                <svg class="w-[40px] sm:w-6 h-[40px] sm:h-6 text-green-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m7 10 2 2 4-4m6 2a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
  </svg>100+ Systems integrated
            </div>
            <div class="flex items-center gap-1 text-gray-500 sm:text-lg">
                <svg class="w-[40px] sm:w-6 h-[40px] sm:h-6 text-green-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m7 10 2 2 4-4m6 2a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
  </svg>50+ Clients
            </div>
        </div>
    </div>
    <div id="Contact-modal" tabindex="-1" class="fixed left-0 right-0 z-50 w-full max-h-full p-4 overflow-x-hidden overflow-y-auto bg-gray-100 top-[12.5%] md:top-0 md:inset-0 bg-opacity-20 justify-center items-center hidden" aria-hidden="true">
        <div></div>
    </div>
</div>
<div id="authentication-modal" tabindex="-1" aria-hidden="true" class="fixed left-0 right-0 z-50 w-full max-h-full p-4 overflow-x-hidden overflow-y-auto bg-gray-100 top-[12.5%] md:top-0 md:inset-0 bg-opacity-20 justify-center items-center hidden">
    <div class="relative w-full max-w-md max-h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow ">
            <button type="button" class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 ml-auto inline-flex justify-center items-center" data-modal-hide="authentication-modal">
                <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
                </svg>
                <span class="sr-only">Close modal</span>
            </button>
            <div class="px-6 py-6 lg:px-8">
                <h3 class="mb-4 text-xl font-medium text-gray-900 dark:text-white">Contact us</h3>
                <form class="space-y-6" action="#">
                    <div class="col-span-1">
                        <label for="Name" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Name</label>
                        <input type="text" id="name" class="block w-full p-3 text-sm text-gray-900 border border-gray-300 rounded-lg shadow-sm bg-gray-50 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Let us know your name" required>
                    </div>
                    <div class="col-span-1">
                        <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Email</label>
                        <input type="email" id="email" placeholder="name@company.com" class="block w-full p-3 text-sm text-gray-900 border-2 border-gray-300 rounded-lg shadow-sm bg-gray-50 focus:ring-white focus:border-primary-500" required>
                        <span class="invisible text-sm font-medium text-red-50">Email is not valid</span>
                    </div>
                    <div class="sm:col-span-2">
                        <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-400">Message</label>
                        <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" required placeholder="Please leave a message.defineEmits.defineEmits."></textarea>
                    </div>
                    <div class="flex justify-center w-full sm:col-span-2">
                        
                    <button type="submit" class="flex items-center px-5 py-3 text-sm font-medium text-center text-white rounded-lg bg-green-700 sm:w-fit hover:bg-green-800 focus:ring-4 focus:outline-none">
                        <span>Send Message</span>
                    </button>    
                    </div>
                    
                </form>
            </div>
        </div>
    </div>
</div>
    </main>
    <section class="px-4 mx-auto max-w-screen-2xl md:px-8">
        <div class="flex flex-col items-center w-full gap-5 py-6 border-t border-b md:gap-0 border-t-gray-200 border-b-gray-200">
            <h5 class="max-w-l text-xl font-semibold text-center sm:text-3xl">Trusted by fast-moving companies and teams around the world</h5>
            <div class="flex flex-wrap items-center justify-around w-full gap-5 font-semibold">
                <img class="w-20 duration-200 lg:hover:scale-110" src="https://www.qualyval.com/images/companies/fendi.webp" alt="fendi"/>
                <img class="duration-200 w-28 lg:hover:scale-110" alt="pernod_richard" src="https://www.qualyval.com/images/companies/pernod_richerd.webp"/>
                <img class="duration-200 w-36 lg:hover:scale-110" alt="world_duty_free" src="https://www.qualyval.com/images/companies/world_duyy_free.webp"/>
                <img class="duration-200 w-28 lg:hover:scale-110" alt="sleek" src="https://www.qualyval.com/images/companies/SLEEK.webp"/>
                <img class="duration-200 w-28 lg:hover:scale-110" alt="viadex" src="https://www.qualyval.com/images/companies/viadex.webp"/>
            </div>
        </div>
    </section>
</template>

<script>

</script>

<style  scoped>

</style>