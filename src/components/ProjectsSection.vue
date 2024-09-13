<template>
    <section class="w-full p-3 mt-[35px] ">
        <div class="bg-black rounded-[30px] size-full text-white p-[25px] sm:p-[50px] flex flex-col justify-between gap-10 z-[1] relative overflow-hidden">
            <img src="../assets/bg.png" class="absolute object-cover inset-0 -z-[10]" alt="">
            <h2 class="text-3xl md:text-5xl text-left sm:text-center z-[1]">Real-world examples of how we have helped companies achieve their marketing objectives.</h2>
            <div class="text-4 font-bold flex justify-center gap-6 flex-wrap">
                <button class="min- w-[250px] py-2 hover:bg-[#99CF63] border rounded-full hover:text-black ">All Work[20]</button>
                <button class="min- w-[250px] py-2 hover:bg-[#99CF63] border rounded-full hover:text-black ">UI/UX Design[10]</button>
                <button class="min- w-[250px] py-2 hover:bg-[#99CF63] border rounded-full hover:text-black ">Digital Marketing[5]</button>
                <button class="min- w-[250px] py-2 hover:bg-[#99CF63] border rounded-full hover:text-black ">Branding [5]</button>
            </div>
            <div class="flex gap-10 overflow-auto hide-scrollbar">
                <div class="size-[200px] md:size-[460px] rounded-full bg-gray-400 border-[11px] border-gray-500 relative shrink-0">
                    <span class="size-[163px] bg-[#99CF63] rounded-full grid place-content-center font-bold text-black absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2">See Details</span>
                </div>
                <div class="size-[200px] md:size-[460px] rounded-[35px] bg-gray-400 border-[11px] border-gray-500 relative shrink-0">
                    <div class="flex flex-col justify-between h-full p-5">
                        <div class="flex items-center gap-3">
                            <div class="h-[1px] bg-white w-[54px] "></div><p class="font-semibold text-sm sm:text-[17px]">Ai Corporation. 2023</p>
                        </div>
                        <h3 class="text-sm sm:text-[24px] font-semibold">Ai Wave - Ai Chatbot Mobile App</h3>
                    </div>
                </div>
                <div class="size-[200px] md:size-[460px] rounded-[35px] bg-gray-400 border-[11px] border-gray-500 relative shrink-0">
                    <div class="flex flex-col justify-between h-full p-5">
                        <div class="flex items-center gap-3">
                            <div class="h-[1px] bg-white w-[54px] "></div><p class="font-semibold text-sm sm:text-[17px]">Lancer Corporation. 2023</p>
                        </div>
                        <h3 class="text-sm sm:text-[24px] font-semibold">App Lancer - Freelance Mobile App</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>