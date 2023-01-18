<template>
  <section>
    <div class="container mx-auto my-20 w-1/3 border border-blue-900 bg-white">
      <div class="p-5 space-y-5 shadow-xl">
        <h4 class="text-center text-3xl text-black">Обращение</h4>

        <form>
          <div class="grid grid-cols-2 gap-5">
            <input
              type="text"
              class="border border-blue-900 px-4 py-2 focus:outline-none focus:border-blue-500"
              placeholder="Имя"
            />
            <input
              type="text"
              class="border border-blue-900 px-4 py-2 focus:outline-none focus:border-blue-500"
              placeholder="Фамилия"
            />
            <input
              type="email"
              class="border border-blue-900 px-4 py-2 focus:outline-none focus:border-blue-500 col-span-2"
              placeholder="Email"
            />
            <input
              type="tel"
              class="border border-blue-900 px-4 py-2 focus:outline-none focus:border-blue-500 col-span-2"
              placeholder="Номер телефона"
            />
            <textarea
              cols="10"
              rows="5"
              class="border border-blue-900 px-4 py-2 focus:outline-none focus:border-blue-500 col-span-2"
              placeholder="Напишите свое сообщение..."
            ></textarea>
          </div>
          <input
            type="submit"
            value="Отправить сообщение"
            class="focus:outline-none mt-5 bg-blue-900 px-4 py-2 text-white font-bold w-full"
          />
        </form>
      </div>
    </div>
  </section>
</template>


