<template>
  <section>
    <header class="text-gray-600 body-font">
      <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
        <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
            <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
          </svg>
          <span class="ml-3 text-xl">Складской учёт</span>
        </a>
        <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
          <a class="mr-5 hover:text-gray-900">Приход</a>
          <a class="mr-5 hover:text-gray-900">Реализация</a>
          <a class="mr-5 hover:text-gray-900">Перемещение</a>
          <a class="mr-5 hover:text-gray-900">Списание</a>
          <a class="mr-5 hover:text-gray-900">Клиенты</a>
          <a class="mr-5 hover:text-gray-900">Товары</a>
          <a class="mr-5 hover:text-gray-900">Аналитика</a>
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
    <div class="flex justify-center">
      <input
        type="text"
        name="search"
        class="w-1-2 rounded pl-8 pr-4 py-2.5 text-md font-light bg-gray-300 text-gray-400 placeholder-gray-500 focus:outline-none focus:ring-1 focus:ring-gray-500 focus:bg-gray-300"
        placeholder="поиск"
      />
      <button class="rounded bg-blue-900 px-3 text-white">
        Найти
      </button>
    </div>
  </section>
</template>


