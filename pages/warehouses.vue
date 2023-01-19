<template>
<section>
  <header class="text-gray-600 body-font">
    <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
      <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
          <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
        </svg>
        <span class="ml-3 text-xl">Товары и Склады</span>
      </a>
    </div>
  </header>
      <main class="container mx-auto py-big px-3 sm:px-0">
      <h1 class="text-center text-3xl font-bold mt-5">Каталог товаров</h1>
        <table class="w-full ml-5 mt-5">
          <thead class="bg-gray-50 border-b-2 border-gray-200">
          <tr>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Товар</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Картинки галереи</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Доступный остаток</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Ед.измерения</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Розничная цена</th>
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
              </tr>
            </tbody>
        </table>
        <div class="flex justify-end">
          <a href="" class="bg-blue-900 py-2 px-4 hover:bg-blue-500 text-white">Создать</a>
         </div>
        <h1 class="text-center text-3xl font-bold mt-10">Документы прихода</h1>
        <table class="w-full ml-5 mt-5">
          <thead class="bg-gray-50 border-b-2 border-gray-200">
          <tr>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Название</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Номер документа основания</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Тип</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Статус</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Дата изменения</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Ответственный</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Поставщик</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Сумма</th>
              <th class="p-3 text-sm font-semibold tracking-wide text-left">Склады</th>
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
                <td class="p-3 text-sm text-gray-700">10000</td>
                <td class="p-3 text-sm text-gray-700">Москва</td>
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
                <td class="p-3 text-sm text-gray-700">10000</td>
                <td class="p-3 text-sm text-gray-700">Москва</td>
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
                <td class="p-3 text-sm text-gray-700">10000</td>
                <td class="p-3 text-sm text-gray-700">Москва</td>
              </tr>

            </tbody>
        </table>
        <div class="flex justify-end">
          <a href="" class="bg-blue-900 py-2 px-4 hover:bg-blue-500 text-white">Создать</a>
         </div>
      </main>

</section>
</template>
