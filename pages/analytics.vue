<template>
  <section>
    <header class="text-gray-600 body-font">
      <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
        <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
            <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
          </svg>
          <span class="ml-3 text-xl">Аналитика</span>
        </a>
        <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
          <a class="mr-5 hover:text-gray-900">Мои отчеты</a>
          <a class="mr-5 hover:text-gray-900">Сквозная аналитика</a>
          <a class="mr-5 hover:text-gray-900">Складской учёт</a>
          <a class="mr-5 hover:text-gray-900">Статистика звонков</a>
          <a class="mr-5 hover:text-gray-900">Статистика диалогов</a>
        </nav>
        <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Button
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </div>
    </header>
        <main class="container mx-auto py-big px-3 sm:px-0">
        <h1 class="text-left text-3xl font-bold pl-5">Источники обращений</h1>
          <div class="m-3 flex justify-center w-1/2 min-h-1/2 bg-gray-50 mt-5">
            <div class="flex bg-white shadow-lg rounded-xl">
              <div class="py-6 border-r border-gray-100">
                <ul class="flex flex-col text-xs">
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Последние 7 дней
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Последние 14 дней
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Последние 30 дней
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Последние 3 месяца
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Последние 12 месяцев
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Месяц до сегодняшнего дня
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Квартал до сегодняшнего дня
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                     За всё время
                    </button>
                  </li>
                  <li>
                    <button
                      class="px-6 py-1.5 w-full leading-5 hover:bg-gray-50 hover:text-blue-600 text-left"
                    >
                      Обычно
                    </button>
                  </li>
                </ul>
              </div>
              <div class="flex flex-col">
                <div class="flex divide-x">
                  <div class="flex flex-col px-6 pt-5 pb-6 border-b border-gray-100">
                    <div class="flex items-center justify-between">
                      <button
                        class="flex items-center justify-center p-2 rounded-xl hover:bg-gray-50"
                      >
                        <svg class="w-6 h-6 text-gray-900 stroke-current" fill="none">
                          <path
                            d="M13.25 8.75L9.75 12l3.5 3.25"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                          />
                        </svg>
                      </button>
                      <div class="text-sm font-semibold">Февраль</div>
                      <button
                        class="flex items-center justify-center p-2 rounded-xl hover:bg-gray-50"
                      >
                        <svg class="w-6 h-6 text-gray-900 stroke-current" fill="none">
                          <path
                            d="M10.75 8.75l3.5 3.25-3.5 3.25"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                          />
                        </svg>
                      </button>
                    </div>
                    <div class="grid grid-cols-7 text-xs text-center text-gray-900">
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Пн
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Вт
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Ср
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Чт
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Пт
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Сб
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Вс
                      </span>

                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        1
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        2
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        3
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        4
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        5
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        6
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        7
                      </span>

                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">8</span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg bg-gray-50"
                      >
                        9
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        10
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        11
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        12
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        13
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        14
                      </span>

                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        15
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        16
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        17
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-white bg-blue-900 rounded-l-lg"
                      >
                        18
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        19
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        20
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none rounded-tr-lg bg-gray-50"
                      >
                        21
                      </span>

                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none rounded-l-lg bg-gray-50"
                      >
                        22
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        23
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        24
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        25
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        26
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none bg-gray-50"
                      >
                        27
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold text-blue-600 rounded-none rounded-br-lg bg-gray-50"
                      >
                        28
                      </span>

                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        1
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        2
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        3
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        4
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        5
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        6
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        7
                      </span>
                    </div>
                  </div>
                  <div class="flex flex-col px-6 pt-5 pb-6 border-b border-gray-100">
                    <div class="flex items-center justify-between">
                      <button
                        class="flex items-center justify-center p-2 rounded-xl hover:bg-gray-50"
                      >
                        <svg class="w-6 h-6 text-gray-900 stroke-current" fill="none">
                          <path
                            d="M13.25 8.75L9.75 12l3.5 3.25"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                          />
                        </svg>
                      </button>
                      <div class="text-sm font-semibold">Март</div>
                      <button
                        class="flex items-center justify-center p-2 rounded-xl hover:bg-gray-50"
                      >
                        <svg class="w-6 h-6 text-gray-900 stroke-current" fill="none">
                          <path
                            d="M10.75 8.75l3.5 3.25-3.5 3.25"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                          />
                        </svg>
                      </button>
                    </div>
                    <div class="grid grid-cols-7 text-xs text-center text-gray-900">
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Пн
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Вт
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Ср
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Чт
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Пт
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Сб
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 font-semibold rounded-lg"
                      >
                        Вс
                      </span>

                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none rounded-tl-lg bg-gray-50"
                      >
                        1
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        2
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        3
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        4
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        5
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        6
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        7
                      </span>

                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none rounded-bl-lg bg-gray-50"
                      >
                        8
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        9
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-blue-600 rounded-none bg-gray-50"
                      >
                        10
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-white bg-blue-900 rounded-r-lg"
                      >
                        11
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        12
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        13
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        14
                      </span>

                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        15
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        16
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        17
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        18
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        19
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        20
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        21
                      </span>

                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        22
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        23
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        24
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        25
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        26
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        27
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        28
                      </span>

                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        29
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        30
                      </span>
                      <span class="flex items-center justify-center w-10 h-10 rounded-lg">
                        31
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        1
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        2
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        3
                      </span>
                      <span
                        class="flex items-center justify-center w-10 h-10 text-gray-700 rounded-lg"
                      >
                        4
                      </span>
                    </div>
                  </div>
                </div>
                <div class="flex items-center justify-between px-6 py-4">
                  <div class="flex items-center">
                    <input
                      type="text"
                      class="flex items-center w-32 px-4 py-2 text-sm text-gray-900 rounded-lg bg-gray-50 focus:bg-white focus:ring-1 focus:ring-blue-900 focus:outline-none"
                      placeholder="18 / 02 / 2022"
                    />
                    <div class="p-1">
                      <svg class="w-6 h-6 text-gray-900 stroke-current" fill="none">
                        <path
                          d="M6.738 12.012h10.5m-4.476 4.25l4.5-4.25-4.5-4.25"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </svg>
                    </div>
                    <input
                      type="text"
                      class="flex items-center w-32 px-4 py-2 text-sm text-gray-900 rounded-lg bg-gray-50 focus:bg-white focus:ring-1 focus:ring-blue-900 focus:outline-none"
                      placeholder="11 / 03 / 2022"
                    />
                  </div>
                  <div class="flex items-center space-x-2">
                    <button
                      class="px-4 py-2 text-sm rounded-lg bg-gray-50 focus:outline-none focus:ring-1 focus:ring-blue-900 hover:bg-gray-100"
                    >
                      Отмена
                    </button>
                    <button
                      class="px-4 py-2 text-sm text-white bg-blue-900 rounded-lg focus:outline-none focus:ring-1 focus:ring-blue-900 hover:bg-blue-700"
                    >
                      Готово
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </main>
        <div>
          <h1 class="font-bold text-3xl m-3">Среднее время ответа</h1>
          <div class="m-3 flex justify-center items-center w-1/2 bg-slate-200 h-[50px] text-slate-900">
            Нет данных
          </div>
        </div>
  </section>
  </template>
