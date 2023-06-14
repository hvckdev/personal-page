<template>
  <main>
    <div class="flex items-center justify-center h-[80vh]">
      <div class="max-w-md m-auto p-6 text-center bg-black bg-opacity-25 backdrop-blur-md rounded-xl fade-in">
        <div class="hs-tooltip">
          <div class="hs-tooltip-toggle mb-4 text-4xl font-bold">hvck</div>
          <span
              class="hs-tooltip-content hs-tooltip-shown:opacity-100 hs-tooltip-shown:visible opacity-0 transition-opacity inline-block absolute invisible z-10 py-1 px-2 text-xs font-medium text-white rounded-md shadow-sm bg-neutral-900 bg-opacity-25"
              role="tooltip"
          >
                 pronounces as hack
              </span>
        </div>

        <p class="pl-4 mb-4 text-lg border-l-4 text-left">
          Hello, I'm
          <span class="hs-tooltip">
            <span
                class="hs-tooltip-toggle"
            >
              hvck,
               <span
                   class="hs-tooltip-content hs-tooltip-shown:opacity-100 hs-tooltip-shown:visible opacity-0 transition-opacity inline-block absolute invisible z-10 py-1 px-2 text-xs font-medium text-white rounded-md shadow-sm bg-neutral-900 bg-opacity-25"
                   role="tooltip"
               >
                 pronounces as hack
              </span>
            </span>
          </span>
          I'm a backend developer, I'm deeply committed to designing robust, scalable systems, leveraging my expertise
          in PHP, Laravel, Symfony, and Kafka. My passion for technology doesn't stop at work. I enjoy delving into new
          technologies, always eager to unearth their hidden gems.
          <br>
          From an early age, I embarked on my coding journey with C++, a path that nurtured my fondness for the
          aesthetic appeal of computers and the rhythm of typing code. Alongside my tech pursuits, I explore psychology,
          enriching my professional productivity and personal well-being through insightful literature.
        </p>

        <div class="flex justify-center mb-4 space-x-4">
          <a href="https://t.me/hvckdev"><i class="fa-brands fa-telegram"></i></a>
          <a href="https://t.me/hvckxm"><i class="fa-solid fa-brain"></i></a>
          <a href="https://git.hvck.dev/hvck"><i class="fa-brands fa-gitlab"></i></a>
          <a href="mailto:i@hvck.dev"><i class="fa-solid fa-envelope"></i></a>
        </div>

        <p class="text-sm">Made with 💖</p>
        <p class="text-sm">2023</p>
      </div>
    </div>
  </main>
</template>
<script setup>
</script>