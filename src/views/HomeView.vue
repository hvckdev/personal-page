<template>
  <main class="text-white">
    <div class="flex items-center justify-center h-[80vh]">
      <div class="max-w-md m-auto p-6 text-center bg-black bg-opacity-25 backdrop-blur-md rounded-xl fade-in">
        <div class="hs-tooltip">
          <div class="hs-tooltip-toggle mb-4 text-4xl font-bold">hvck</div>
          <span
              class="hs-tooltip-content hs-tooltip-shown:opacity-100 hs-tooltip-shown:visible opacity-0 transition-opacity inline-block absolute invisible z-10 py-1 px-2 text-xs font-medium text-white rounded-md shadow-sm bg-purple-800 bg-opacity-25"
              role="tooltip"
          >
                 pronounces as hack
              </span>
        </div>

        <div class="pl-4 mb-4 text-lg border-l-4 text-left">
          <p>
            Hello, I'm
            <span class="hs-tooltip">
            <span
                class="hs-tooltip-toggle"
            >
              hvck,
               <span
                   class="hs-tooltip-content hs-tooltip-shown:opacity-100 hs-tooltip-shown:visible opacity-0 transition-opacity inline-block absolute invisible z-10 py-1 px-2 text-xs font-medium text-white rounded-md shadow-sm bg-purple-800 bg-opacity-25"
                   role="tooltip"
               >
                 pronounces as hack
              </span>
            </span>
          </span>
            a backend engineer with a passion for creating
            efficient and scalable systems. I'm always eager
            to learn more and improve my skills. In my free time. I enjoy exploring
            new technologies, reading, and hiking. Also i enjoy reading psychology books,
            that improve my productivity.
          </p>
        </div>

        <div class="flex justify-center mb-4 space-x-4 transition-all">
          <a class="hover:text-emerald-400" href="https://t.me/hvckdev"><i class="fa-brands fa-telegram"></i></a>
          <a class="hover:text-emerald-400"  href="https://t.me/hvckxm"><i class="fa-solid fa-brain"></i></a>
          <a class="hover:text-emerald-400"  href="https://github.com/hvckdev"><i class="fa-brands fa-github"></i></a>
          <a class="hover:text-emerald-400"  href="mailto:i@hvck.dev"><i class="fa-solid fa-envelope"></i></a>
        </div>

        <p class="text-sm">Made with 💜</p>
        <p class="text-sm">2023</p>
      </div>
    </div>
  </main>
</template>
<script setup>
</script>