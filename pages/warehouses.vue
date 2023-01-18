<template>
<section>
      <header class="container mx-auto px-5 md:px-0 mt-5">
          <div class="flex justify-between pt-big">
             <span class="pl-5 font-bold text-3xl">Товары и Склады</span>

             <div class="space-x-5">
              <a href="" class="hover:underline">Помощь</a>
              <a href="" class="bg-blue-900 py-2 px-4 rounded-full hover:bg-blue-500 text-white">Рабочий кабинет</a>
             </div>
          </div>
          <div class="flex justify-center">
            <input
              type="text"
              name="search"
              class="w-1-2 rounded pl-8 pr-4 py-2.5 text-md font-light bg-gray-100 text-gray-500 placeholder-gray-500 focus:outline-none focus:ring-1 focus:ring-gray-500 focus:bg-gray-300"
              placeholder="поиск"
            />
            <button class="rounded bg-blue-900 px-3 text-white">
              Найти
            </button>
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
