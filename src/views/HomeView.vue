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

        <div class="pl-4 mb-4 text-lg border-l-4 text-left">
          <p>
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
            a backend developer with a passion for creating
            efficient and scalable systems. I have experience in various backend
            technologies such as PHP, Laravel, Symfony, and Kafka. I'm always eager
            to learn more and improve my skills. In my free time, I enjoy exploring
            new technologies, reading, and hiking. Also i enjoy reading psychology books,
            that improve my productivity and alone happiness.
          </p>
          <p class="mt-2">
            <a class="hs-collapse-toggle inline-flex items-center gap-x-2 font-medium hover:text-gray-400 dark:text-gray-400 dark:hover:text-white"
               href="javascript:;"
               id="hs-show-hide-collapse" data-hs-collapse="#hs-show-hide-collapse-heading">
              <span class="hs-collapse-open:hidden">ask a chatgpt to tell about me</span>
              <span class="hs-collapse-open:block hidden">omg hide this plssssss</span>
              <svg class="hs-collapse-open:rotate-180 w-2.5 h-2.5" width="16" height="16" viewBox="0 0 16 16"
                   fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M2 5L8.16086 10.6869C8.35239 10.8637 8.64761 10.8637 8.83914 10.6869L15 5"
                      stroke="currentColor" stroke-width="2" stroke-linecap="round" />
              </svg>
            </a>
          </p>
          <div id="hs-show-hide-collapse-heading"
               class="hs-collapse hidden w-full overflow-hidden transition-[height] duration-300"
               aria-labelledby="hs-show-hide-collapse">
            <p class="text-gray-500">
              Enthusiastically engaged in backend development, I pride myself on my ability to construct powerful,
              scalable
              systems. My technical acumen is bolstered by my proficiency in PHP, Laravel, Symfony, and Kafka. Not just
              limited to using these technologies, I show a consistent curiosity about the inner workings of each
              system,
              regularly dedicating time to dissect existing technologies and understand their underlying mechanisms.
              <br><br>
              My fascination with coding was ignited at a young age, as I ventured into the world of programming through
              the
              gateway of C++. This early start has enabled me to develop an acute sensitivity towards the aesthetics of
              computers and the very act of typing, which I perceive as a symphony of thought transformation into
              action.
              <br><br>
              In addition to my technological pursuits, I have a profound interest in psychology. This parallel passion
              allows me to apply psychological insights to enhance my workflow, boosting both my professional
              productivity
              and personal contentment. With such a unique blend of interests and skills, I bring a balanced,
              well-rounded
              perspective to every project I engage in.
            </p>
          </div>
        </div>

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