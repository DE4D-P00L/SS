<template>
    <section class="p-3">
        <div class="p-10 md:px-[80px] md:py-[50px] bg-white rounded-3xl grid grid-cols-1 lg:grid-cols-2 gap-10">
            <div class="flex flex-col gap-[40px]">
                <h3 class="text-[48px] font-semibold">Digital Marketing FAQs</h3>
                <p class="font-light text-[20px]">As a leading digital marketing agency, we are dedicated to providing comprehensive educational resources and answering frequently asked questions to help our clients.</p>
                <div class="flex sm:flex-row flex-col gap-5 font-semibold">
                <button class=" text-black border border-black px-10 py-3 rounded-full space-x-4">
                    More Questions
                </button>
                <button class="underline underline-offset-2">Contact Us</button>
            </div>
            </div>
            <div>
                <!-- Accordion Item 1 -->
                <div class="border-b border-slate-200">
                    <button @click="toggleAccordion(1)" class="w-full flex justify-between items-center py-5 text-slate-800">
                        <span class="font-semibold text-[24px] text-left">Why is digital marketing important for my business?</span>
                        <span id="icon-1" class="text-slate-800 transition-transform duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4">
                            <path d="M8.75 3.75a.75.75 0 0 0-1.5 0v3.5h-3.5a.75.75 0 0 0 0 1.5h3.5v3.5a.75.75 0 0 0 1.5 0v-3.5h3.5a.75.75 0 0 0 0-1.5h-3.5v-3.5Z" />
                        </svg>
                        </span>
                    </button>
                    <div id="content-1" class="max-h-0 overflow-hidden transition-all duration-300 ease-in-out accordian">
                        <div class="pb-5 text-sm text-slate-500">
                            Digital marketing allows businesses to reach and engage with a wider audience, generate leads, drive website traffic, and increase brand visibility. It provides measurable results, allows for targeted marketing efforts, and enables businesses to adapt and optimize their strategies based on data and insights.
                        </div>
                    </div>
                    </div>
                    
                    <!-- Accordion Item 2 -->
                    <div class="border-b border-slate-200">
                    <button @click="toggleAccordion(2)" class="w-full flex justify-between items-center py-5 text-slate-800">
                        <span class="font-semibold text-[24px] text-left">How can digital marketing help improve my website's visibility?</span>
                        <span id="icon-2" class="text-slate-800 transition-transform duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4">
                            <path d="M8.75 3.75a.75.75 0 0 0-1.5 0v3.5h-3.5a.75.75 0 0 0 0 1.5h3.5v3.5a.75.75 0 0 0 1.5 0v-3.5h3.5a.75.75 0 0 0 0-1.5h-3.5v-3.5Z" />
                        </svg>
                        </span>
                    </button>
                    <div id="content-2" class="max-h-0 overflow-hidden transition-all duration-300 ease-in-out accordian">
                        <div class="pb-5 text-sm text-slate-500 text-[16px]">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam incidunt ducimus sint sequi aliquam fugit nam tempora! Veniam, eius quasi aspernatur obcaecati asperiores consequuntur at inventore reprehenderit, repellat odio corporis!
                        </div>
                    </div>
                    </div>
                    
                    <!-- Accordion Item 3 -->
                    <div class="border-b border-slate-200">
                    <button @click="toggleAccordion(3)" class="w-full flex justify-between items-center py-5 text-slate-800">
                        <span class="font-semibold text-[24px] text-left">How long does it take to see results from digital marketing efforts?</span>
                        <span id="icon-3" class="text-slate-800 transition-transform duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4">
                            <path d="M8.75 3.75a.75.75 0 0 0-1.5 0v3.5h-3.5a.75.75 0 0 0 0 1.5h3.5v3.5a.75.75 0 0 0 1.5 0v-3.5h3.5a.75.75 0 0 0 0-1.5h-3.5v-3.5Z" />
                        </svg>
                        </span>
                    </button>
                    <div id="content-3" class="max-h-0 overflow-hidden transition-all duration-300 ease-in-out accordian">
                        <div class="pb-5 text-sm text-slate-500 text-[16px]">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam incidunt ducimus sint sequi aliquam fugit nam tempora! Veniam, eius quasi aspernatur obcaecati asperiores consequuntur at inventore reprehenderit, repellat odio corporis!
                        </div>
                    </div>
                </div>

                <!-- Accordion Item 4 -->
                <div class="border-b border-slate-200">
                    <button @click="toggleAccordion(4)" class="w-full flex justify-between items-center py-5 text-slate-800">
                        <span class="font-semibold text-[24px] text-left">How do you measure the success of digital marketing campaigns?</span>
                        <span id="icon-4" class="text-slate-800 transition-transform duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4">
                            <path d="M8.75 3.75a.75.75 0 0 0-1.5 0v3.5h-3.5a.75.75 0 0 0 0 1.5h3.5v3.5a.75.75 0 0 0 1.5 0v-3.5h3.5a.75.75 0 0 0 0-1.5h-3.5v-3.5Z" />
                        </svg>
                        </span>
                    </button>
                    <div id="content-4" class="max-h-0 overflow-hidden transition-all duration-300 ease-in-out accordian">
                        <div class="pb-5 text-slate-500 text-[16px]">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam incidunt ducimus sint sequi aliquam fugit nam tempora! Veniam, eius quasi aspernatur obcaecati asperiores consequuntur at inventore reprehenderit, repellat odio corporis!
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
  export default{
    methods:{
        toggleAccordion(index) {
            const content = document.getElementById(`content-${index}`);
            const icon = document.getElementById(`icon-${index}`);
            const accordianArray = document.getElementsByClassName("accordian");
        
            const minusSVG = `
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4">
                <path d="M3.75 7.25a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5h-8.5Z" />
            </svg>
            `;
        
            const plusSVG = `
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4">
                <path d="M8.75 3.75a.75.75 0 0 0-1.5 0v3.5h-3.5a.75.75 0 0 0 0 1.5h3.5v3.5a.75.75 0 0 0 1.5 0v-3.5h3.5a.75.75 0 0 0 0-1.5h-3.5v-3.5Z" />
            </svg>
            `;
            
            for(let acc of accordianArray){
                let i = acc.id.charAt(acc.id.length - 1);
                if(Number(i)!==index){
                    acc.style.maxHeight = '0';
                    let icon = document.getElementById(`icon-${i}`);
                    icon.innerHTML = plusSVG;
                }
            }

            // Toggle the content's max-height for smooth opening and closing
            if (content.style.maxHeight && content.style.maxHeight !== '0px') {
            content.style.maxHeight = '0';
            icon.innerHTML = plusSVG;
            } else {
            content.style.maxHeight = content.scrollHeight + 'px';
            icon.innerHTML = minusSVG;
            }
        }
    }
  }
</script>