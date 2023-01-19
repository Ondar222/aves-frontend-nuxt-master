<template>
  <section>
    <header class="text-gray-600 body-font">
      <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
        <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
          <svg xmlns="" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
            <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
          </svg>
          <span class="ml-3 text-xl">Сделки</span>
        </a>
        <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
          <a class="mr-5 hover:text-gray-900">Воронка</a>
          <a class="mr-5 hover:text-gray-900">Список</a>
          <a class="mr-5 hover:text-gray-900">Дела</a>
          <a class="mr-5 hover:text-gray-900">Календарь</a>
          <a class="pl-5 mr-5 hover:text-gray-900 sm:py-3 sm:border-l ">Продажи</a>
          <a class="mr-5 hover:text-gray-900">Аналитика</a>
          <a class="mr-5 hover:text-gray-900">Интеграции</a>
          <a class="mr-5 hover:text-gray-900">Настройки</a>
          <a class="mr-5 hover:text-gray-900">Еще</a>
        </nav>
        <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Button
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </div>
      </header>
    <div class="container mx-auto py-big grid grid-columns-3 grid-flow-col gap-1 pt-10 pl-3 text-center">
      <div class=" w-5/5 h-[830px] border-dashed border-black border-2">
        <h1 class="w-full h-10 bg-blue-300 p-2 2 font-bold">Новая(0)</h1>
        <h1 class="flex justify-center text-3xl">0 ₽</h1>
        <div class="bg-blue-300 py-2 px-2 rounded-xs hover:bg-blue-600 text-white">+ Быстрая сделка</div>
       </div>

      <div class=" w-5/5 h-[830px] border-dashed border-black border-2">
        <h1 class="w-full h-10 bg-blue-300 p-2 2 font-bold">Подготовка документов</h1>
        <h1 class="flex justify-center text-3xl">0 ₽</h1>
        <div class="bg-blue-300 py-2 px-2 rounded-xs hover:bg-blue-600 text-white">+ </div>
      </div>
      <div class=" w-5/5 h-[830px] border-dashed border-black border-2">
        <h1 class="w-full h-10 bg-blue-300 p-2 2 font-bold">Счет на предоплату</h1>
        <h1 class="flex justify-center text-3xl">0 ₽</h1>
        <div class="bg-blue-300 py-2 px-2 rounded-xs hover:bg-blue-600 text-white">+ </div>
      </div>
      <div class=" w-5/5 h-[830px] border-dashed border-black border-2">
        <h1 class="w-full h-10 bg-blue-300 p-2 2 font-bold">В работе</h1>
        <h1 class="flex justify-center text-3xl">0 ₽</h1>
        <div class="bg-blue-300 py-2 px-2 rounded-xs hover:bg-blue-600 text-white">+ </div>
      </div>
      <div class=" w-5/5 h-[830px] border-dashed border-black border-2">
        <h1 class="w-full h-10 bg-blue-300 p-2 2 font-bold">Финальный счет</h1>
        <h1 class="flex justify-center text-3xl">0 ₽</h1>
        <div class="bg-blue-300 py-2 px-2 rounded-xs hover:bg-blue-600 text-white">+ </div>
      </div>

</div>

  </section>
  </template>
