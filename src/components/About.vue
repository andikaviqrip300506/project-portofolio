<template>
    <div class="m-14">
    </div>
    <div class="m-14">
        <h4 class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-gray-900 md:text-5xl lg:text-2xl dark:text-white"><u>ABOUT ME</u><span class="underline underline-offset-3 decoration-8 decoration-blue-400 dark:decoration-blue-600"></span></h4>
    </div>
     <div class="grid grid-cols-2 gap-2 m-14">
        <div>
        <a href="#" class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
    <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg" src="../assets/poto.jpg" alt="">
    <div class="flex flex-col justify-between p-4 leading-normal">
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Profile</h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400"> Andika Viqri Pratama, 17 years old, was born in Indonesia Bandung Jawa Barat </p>
   </div>
   </a>
   </div>
   <div>
    <a href="#" class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
    <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg" src="https://smkassalaambandung.sch.id/img/logo-custom.png" alt="">
    <div class="flex flex-col justify-between p-4 leading-normal">
        <br>
        <br>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">School</h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Study at Assalaam High School, grade 12, majoring in software engineering</p>
        <br>
        <br>
        <br>
        
   </div>
   </a>
   </div>
     </div>
     <div class="grid grid-cols-1 gap-1 m-14">
        <div>
        <a href="#" class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
    <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg" src="data:image/png;base64,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" alt="">
    <div class="flex flex-col justify-between p-4 leading-normal">
        <br>
        <br>
        <br>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">&nbsp; &nbsp; &nbsp;Hobby</h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400"> &nbsp; &nbsp; &nbsp; Enjoy playing mobile legends </p>
        <br>
    <br>
    <br>
   </div>
   </a>
   </div>
  </div>
  <svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 160" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(0, 0, 0, 1)" offset="0%"></stop><stop stop-color="rgba(114.159, 114.159, 114.159, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,144L60,0L120,112L180,80L240,96L300,0L360,80L420,48L480,64L540,128L600,112L660,32L720,48L780,96L840,32L900,0L960,48L1020,128L1080,144L1140,0L1200,144L1260,144L1320,16L1380,128L1440,96L1440,160L1380,160L1320,160L1260,160L1200,160L1140,160L1080,160L1020,160L960,160L900,160L840,160L780,160L720,160L660,160L600,160L540,160L480,160L420,160L360,160L300,160L240,160L180,160L120,160L60,160L0,160Z"></path></svg>
</template>