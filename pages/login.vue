<template>
  <div>
    <div class="flex space-x-5">
      <h1 class="font-bold text-2xl m-2 text-red-500">Маркетинг</h1>
      <input type="text" class="w-1-2 h-10 bg-gray-100 pl-5 p-2 m-2 focus:outline-nine rounded-full" placeholder="Фильтр + Поиск">
      <a class="bg-blue-400 text-white m-2 font-bold p-2 text-sm" href="#">Добавить контакт</a>
    </div>
    <div class="flex justify-between">
      <h1 class="text-slate-500 m-5 5">
        Нет контактов, требующих оперативной реакции
      </h1>
      <h1 class="text-slate-500 m-5 5">
        Список
      </h1>
      <h1 class="text-slate-500 m-5 5">
        Отчеты
      </h1>
    </div>
    <div class="container">
      <table class=" border-8">
        <thead>
          <tr class="flex space-x-10">
            <th>Контакт</th>
            <th>Дела</th>
            <th>Ответственный</th>
            <th>Дата создания</th>
          </tr>
        </thead>
          <tr class="flex space-x-4">
            <td>1</td>
            <td>9.1</td>
            <td>Маша Иванова</td>
            <td>Елена Позднякова</td>
            <td>11.03.2018</td>
          </tr>
          <tr class="flex space-x-4">
            <td>1</td>
            <td>9.1</td>
            <td>Маша Иванова</td>
            <td>Елена Позднякова</td>
            <td>11.03.2018</td>
          </tr>
          <tr class="flex space-x-4">
            <td>1</td>
            <td>9.1</td>
            <td>Маша Иванова</td>
            <td>Елена Позднякова</td>
            <td>11.03.2018</td>
          </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default{

}
</script>

<style>

</style>
