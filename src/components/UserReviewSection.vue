<template>
    <section class="p-3 sm:p-[80px]">
        <h3 class="text-2xl sm:text-[36px] font-semibold leading-tight">"{{ reviews[index].review }}"</h3>
        <div class="flex flex-col sm:justify-between sm:flex-row mt-[80px] items-center sm:items-start w-full gap-y-5">
            <div class="flex items-center gap-4">
                <div class="size-[70px] rounded-full bg-gray-300 shrink-0"></div>
                <div class="flex flex-col">
                    <span class="text-[20px] font-bold">{{ reviews[index].userName }}</span>
                    <span class="text-[16px]">{{ reviews[index].designation }}</span>
                </div>
            </div>
            <div class="flex items-center gap-5">
                <button @click="previousReview" class="px-8 py-4 rounded-full hover:text-white hover:bg-black text-3xl border-black text-black border ">←</button>
                <span class="text-[16px]">
                    <span class="font-bold underline">0{{ index+1 }}</span>
                    <span class="opacity-40">/0{{ reviews.length }}</span>
                </span>
                <button @click="nextReview" class="px-8 py-4 rounded-full hover:text-white hover:bg-black text-3xl border-black text-black border">→</button>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data(){
            return {
                index:0,
                reviews:[
                    {
                        userName: "Michael Kaizer",
                        designation: "CEO of Basecamp Corp",
                        review: "They thoroughly analyze our industry and target audience, allowing them to develop customized campaigns that effectively reach and engage our customers. Their creative ideas and cutting-edge techniques have helped us stay ahead of the competition."
                    },
                    {
                        userName: "John Doe",
                        designation: "Software Engineer",
                        review: "This product has exceeded my expectations in every way. It's incredibly user-friendly and highly efficient, making my work much easier and more enjoyable. I've been using it for several weeks now, and I'm completely satisfied with its performance. The features are intuitive and easy to navigate, even for someone who isn't particularly tech-savvy. I would highly recommend this product to anyone looking for a reliable and effective tool."
                    },
                    {
                        userName: "Jane Smith",
                        designation: "Product Manager",
                        review: "I'm impressed with the quality and performance of this product. It's a game-changer for our team. The features are intuitive and easy to use, and it has helped us streamline our workflow significantly. We've seen a noticeable increase in productivity and efficiency since implementing this product. I would definitely recommend it to anyone looking for a reliable and effective solution."
                    },
                    {
                        userName: "Alex Johnson",
                        designation: "Marketing Specialist",
                        review: "The product has helped us increase our sales and improve customer satisfaction. It's a great investment. I've been recommending it to my colleagues and clients, and they've all had positive experiences. The product is easy to use and provides excellent value for money. I'm confident that it will continue to be a valuable asset to our business."
                    }
                ]
            }
        },
        methods:{
            nextReview(){
                this.index = (this.index+1) % this.reviews.length;
            },
            
            previousReview(){
                if(this.index == 0) this.index = this.reviews.length
                this.index = this.index-1
            }
        }
    }
</script>