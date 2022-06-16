<template>

<section class="bg-gradient-form bg-gray-200 md:h-screen">
  <div class="container py-6 px-6 h-full">
    <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">
      <div class="xl:w-6/6">
        <div class="block bg-white shadow-lg rounded-lg">
          <div class="lg:flex lg:flex-wrap g-0">
            <div class="lg:w-6/6 px-4 md:px-0">
              <div class="md:p-6 md:mx-6">
                <div class="text-center">
                  <img
                    class="mx-auto w-40"
                    src="@/static/image/Logo.jpg"
                    alt="logo"
                  />
                </div>
                <form>
                  <p class="mb-4">Пожалуйста введите данные для регистрации</p>
                  <div class="mb-4">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Email"
                    />
                  </div>
                  <div class="mb-4">
                    <input
                      type="password"
                      class="password form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Пароль"
                    />
                  </div>
                  <div class="mb-4">
                    <input
                      type="password"
                      class="password form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Повторите пароль"
                    />
                  </div>
                  <div class="text-center pt-1 mb-12 pb-1">
                    <nuxt-link to="/redirect">
                    <button
                      class=" px-6 py-2.5 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700  transition duration-150 ease-in-out w-full mb-3 bg-blue-300"
                      type="button"
                      data-mdb-ripple="true"
                      data-mdb-ripple-color="light"
                      style="
                        background:cadetblue;
                      "
                    >
                      Регистрация
                    </button>
                  </nuxt-link>
                  </div>
                  
                </form>
              </div>
            </div>
<!--             
            <div
              class="lg:w-6/12 flex items-center lg:rounded-r-lg rounded-b-lg lg:rounded-bl-none border-4 border-green-400 rounded-3xl bg-green-500"
              style="
                background: white;
              "
            >
              <div class="text-white px-4 py-6 md:p-12 md:mx-6">
                <h1 class="text-x1 font-semibold mb-6">О компании:</h1>
                <p>
                  1. Потребность в найме — это что и зачем? Хорошо, когда в компании существует стратегический план по найму сотрудников на год, пять и больше лет вперед. В этом случае рекрутеры заранее знают, какие ресурсы им понадобятся в каждый отрезок времени. В небольших организациях подбор обычно ситуативный и закрывает текущие потребности. Например, замена сотрудника, который уходит в декрет или длительный отпуск, подбор нового человека на место уволившегося. Существует больше десятка способов оценить потребность в персонале. На нее влияет рынок в регионе, скорость и план развития компании, эффективность текущих сотрудников и другие факторы. В зависимости от кадровой политики компания может привлекать новые кадры или обучать персонал. Или сокращать. Знание потребности в подборе персонала помогает: Составить план закрытия
                </p>
                
              </div>
              
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

</template>

<style scoped>

</style>
<script>

export default {
//  layout: 'emty'
}
</script>
