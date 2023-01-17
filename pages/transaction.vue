<template>
  <section>
        <header class="container mx-auto px-5 md:px-0 mt-5">
            <div class="flex justify-between pt-big">
               <span class="pl-5 font-bold text-3xl">Сделки</span>

               <div class="space-x-5">
                <a href="" class="hover:underline">Помощь</a>
                <a href="" class="bg-blue-300 py-2 px-4 rounded-full hover:bg-red-300">Рабочий кабинет</a>
               </div>
            </div>
            <div class="flex justify-center">
              <input
                type="text"
                class="w-1-2 rounded pl-8 pr-4 py-2.5 text-md font-light bg-gray-300 text-gray-400 placeholder-gray-500 focus:outline-none focus:ring-1 focus:ring-gray-500 focus:bg-gray-300"
                placeholder="поиск"
              />
            </div>
            <div class="flex justify-content">
              <div class="flex justify-center ml-3 mt-3 rounded-xl bg-gray-300 w-1/3 h-6 space-x-12 text-white">
                <a class="font-bold" href="#">Воронка</a>
                <a class="" href="#">Список</a>
                <a class="" href="#">Дела</a>
                <a class="" href="#">Календарь</a>
              </div>
              <div class="flex justify-center ml-3 mt-3 rounded-xl bg-gray-300 w-1/3 h-6 space-x-12 text-white">
                <a class="font-bold" href="#">Мои:</a>
                <a class="" href="#">Входящие</a>
                <a class="" href="#">Запланированные</a>
                <a class="" href="#">Еще</a>
              </div>
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
