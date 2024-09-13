<template>
  <div class="w-screen bg-white sticky top-0  z-10">
    <nav class="h-[110px] items-center justify-between px-[42px] max-w-[1440px] mx-auto hidden md:flex bg-white opacity-100">
    <div class="flex gap-[74px]">
        <div class="flex gap-2 items-center">
            <img src="../assets/logo.png" alt="" class="size-10">
            <span class="font-bold text-lg">edvanta</span>
        </div>
        <ul class="flex gap-[33px] items-center font-semibold ">
            <li><a href="" class="flex items-center gap-2">Service <img src="../assets/down.png" alt=""></a></li>
            <li><a href="" class="flex items-center gap-2">Agency <img src="../assets/down.png" alt=""></a></li>
            <li><a href="" class="flex items-center gap-2">Case study <img src="../assets/down.png" alt=""></a></li>
            <li><a href="" class="flex items-center gap-2">Resources <img src="../assets/down.png" alt=""></a></li>
            <li><a href="">Contact</a></li>
        </ul>
    </div>
    <div class="flex gap-3">
        <button class="border-2 border-black text-black font-semibold px-[30px] shrink-0 py-[13px] rounded-full">Get Started</button>
        <button class="bg-black text-white px-[13px] py-[13px] rounded-full shrink-0"><img src="../assets/bell.png" alt=""></button>
    </div>
  </nav>
  </div>
  <nav class="h-[110px] flex items-center justify-between px-[42px] max-w-[1440px] mx-auto md:hidden sticky top-0 bg-white opacity-100 z-10">
    <div class="flex gap-5 justify-between w-full">
        <div class="flex gap-2 items-center z-[999]">
            <img src="../assets/logo.png" alt="" class="size-10">
            <span class="font-bold text-lg">edvanta</span>
        </div>
        <button class="size-8 z-[101] " @click="toggleMenu"><img src="../assets/menu.png" alt=""></button>
        <ul :class="menuOpen ?'flex':'hidden'" class="flex-col items-center justify-between py-[200px] font-semibold inset-0 h-screen fixed bg-white z-[100]">
            <li><a href="" class="flex items-center gap-2">Service <img src="../assets/down.png" alt=""></a></li>
            <li><a href="" class="flex items-center gap-2">Agency <img src="../assets/down.png" alt=""></a></li>
            <li><a href="" class="flex items-center gap-2">Case study <img src="../assets/down.png" alt=""></a></li>
            <li><a href="" class="flex items-center gap-2">Resources <img src="../assets/down.png" alt=""></a></li>
            <li><a href="">Contact</a></li>
        </ul>

    </div>  
  </nav>
</template>

<script>
export default {
  data(){
    return {
      menuOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen;
    }
  }
}
</script>