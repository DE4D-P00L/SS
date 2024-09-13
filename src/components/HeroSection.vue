<template>
    <section class="grid grid-cols-1 xl:grid-cols-2 min-h-[calc(100dvh-110px)] gap-10 p-3">
        <div class="flex flex-col gap-6 justify-center">
            <h2 class="font-semibold text-[40px] md:text-[72px] -tracking-[3%] leading-[3rem] sm:leading-[80px]">Stay ahead of the curve with our forward-thinking </h2>
            <p class="text-sm font-light max-w-[60ch]">An award-winning SEO agency with disciplines in digital marketing, design, and website development. focused on understanding you.</p>
            <div class="flex gap-5 font-semibold flex-wrap">
                <button class="bg-black text-white px-10 py-3 rounded-full space-x-4 w-full sm:w-fit hover:text-black hover:bg-transparent border-2 hover:border-black"><span>Schedule</span> <span>→</span></button>
                <button class="underline underline-offset-2 text-center w-full sm:w-fit sm:text-left ">View Case Study</button>
            </div>
            <div class="flex items-center mt-10 flex-wrap gap-y-3">
                <p class="max-w-[170px] font-semibold">Trusted by the world's biggest brands</p>
                <div class="flex items-center justify-around flex-wrap gap-y-2 flex-grow max-w-[480px]">
                    <img class="h-7" src="../assets/company/afterpay.png" alt="">
                    <img class="h-7" src="../assets/company/Company.png" alt="">
                    <img class="h-7" src="../assets/company/maze.png" alt="">
                </div>
            </div>
        </div>
        <div class="flex-col mx-auto flex lg:w-[600px] gap-5 justify-center items-center h-full ml-auto">
            <div class="flex h-[260px] justify-between gap-5">
                <div class="relative shrink-0 hidden xl:block">
                    <img src="../assets/quater.png" alt="" class="size-full">
                    <img src="../assets/arrow.png" alt="" class="absolute -top-10 right-0">
                </div>
                <div class="bg-[#F0F0F0] w-full xl:w-[300px] h-full rounded-lg shrink-0 flex flex-col justify-center px-6 gap-3">
                    <h3 class="text-center font-bold text-6xl ">230+</h3>
                    <p class="font-light">some big companies that we work with, and trust us very much</p>
                    <div class="flex mt-5">
                        <div class="bg-black h-2 w-[70%]"></div>
                        <div class="bg-[#cecdcd] h-2 w-[30%]"></div>
                    </div>
                </div>
            </div>
            <div class="bg-black rounded-[30px] text-white flex relative z-[1] overflow-hidden">
                <img src="../assets/bg.png" class="absolute object-cover top-0 -z-[1] -left-[300px] rotate-60 scale-125" alt="">
                <div class="flex flex-col justify-center p-5 gap-2">
                    <div class="flex items-center gap-3"><div class="h-[1px] bg-white w-[54px] "></div><p>Drive More Traffic and Sales</p></div>
                    <h3 class="text-3xl font-bold">Drive more traffic and product sales </h3>
                </div>
                <img src="../assets/bars.png" alt="" class="self-end pt-5 pr-5 hidden sm:inline max-w-[250px] ">
            </div>
        </div>
    </section>
</template>