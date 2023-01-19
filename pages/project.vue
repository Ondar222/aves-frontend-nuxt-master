<template>
  <section>
    <header class="text-gray-600 body-font">
      <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
        <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
          <svg xmlns="" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
            <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
          </svg>
          <span class="ml-3 text-xl">Задачи и Проекты</span>
        </a>
        <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
          <a class="mr-5 hover:text-gray-900">Задачи</a>
          <a class="mr-5 hover:text-gray-900">Делаю</a>
          <a class="mr-5 hover:text-gray-900">Помогаю</a>
          <a class="mr-5 hover:text-gray-900">Поручил</a>
          <a class="mr-5 hover:text-gray-900">Наблюдаю</a>
          <a class="pl-5 mr-5 hover:text-gray-900 sm:py-3 sm:border-l ">Проекты</a>
          <a class="mr-5 hover:text-gray-900">Скрам</a>
          <a class="mr-5 hover:text-gray-900">Эффективность</a>
          <a class="mr-5 hover:text-gray-900">Маркет</a>
          <a class="mr-5 hover:text-gray-900">Еще</a>
        </nav>
        <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Button
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </div>
      </header>

  <h1 class="text-center text-3xl font-bold mt-10">Мои задачи</h1>
  <table class="w-full ml-5 mt-5">
    <thead class="bg-gray-50 border-b-2 border-gray-200">
    <tr>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Название</th>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Активность</th>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Крайний срок</th>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Постановщик</th>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Ответственный</th>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Проект</th>
        <th class="p-3 text-sm font-semibold tracking-wide text-left">Теги</th>

      </tr>
      </thead>
      <tbody>
        <tr class="bg-white">
          <td class="p-3 text-sm text-gray-700">
            <a href="#" class="font-bold text-blue-900 hover:underline">12345</a>
          </td>
          <td class="p-3 text-sm text-gray-700">
            Первый
          </td>
          <td class="p-3 text-sm text-gray-700">9999</td>
          <td class="p-3 text-sm text-gray-700">$</td>
          <td class="p-3 text-sm text-gray-700">99999</td>
          <td class="p-3 text-sm text-gray-700">И.Иванов</td>
          <td class="p-3 text-sm text-gray-700">П.Андрей</td>

        </tr>
        <tr class="bg-gray-50">
          <td class="p-3 text-sm text-gray-700">
            <a href="#" class="font-bold text-blue-900 hover:underline">12345</a>
          </td>
          <td class="p-3 text-sm text-gray-700">
            Второй
          </td>
          <td class="p-3 text-sm text-gray-700">9999</td>
          <td class="p-3 text-sm text-gray-700">$</td>
          <td class="p-3 text-sm text-gray-700">99999</td>
          <td class="p-3 text-sm text-gray-700">И.Иванов</td>
          <td class="p-3 text-sm text-gray-700">П.Андрей</td>

        </tr>
        <tr class="bg-white">
          <td class="p-3 text-sm text-gray-700">
            <a href="#" class="font-bold text-blue-900 hover:underline">12345</a>
          </td>
          <td class="p-3 text-sm text-gray-700">
            Третий
          </td>
          <td class="p-3 text-sm text-gray-700">9999</td>
          <td class="p-3 text-sm text-gray-700">$</td>
          <td class="p-3 text-sm text-gray-700">99999</td>
          <td class="p-3 text-sm text-gray-700">И.Иванов</td>
          <td class="p-3 text-sm text-gray-700">П.Андрей</td>

        </tr>

      </tbody>
  </table>
  <div class="flex justify-end">
    <a href="" class="bg-blue-900 py-2 px-4 hover:bg-blue-500 text-white">Создать</a>
   </div>

  </section>
</template>
