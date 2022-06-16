<template>

<section class="h-full gradient-form bg-gray-200 md:h-screen">
  <div class="container py-6 px-10  h-full">
    <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800 ">
      <div class="xl:w-10/12">
        <div class="block bg-white shadow-lg rounded-lg">
          <div class="lg:flex lg:flex-wrap g-0">
            <div class="lg:w-6/12 px-4 md:px-0">
              <div class="md:p-12 md:mx-6">
                <div class="text-center">
                  <nuxt-link to="/">
                  <img
                    class="mx-auto w-58"
                    src="@/static/image/Logo.jpg"
                    alt="logo"
                  /></nuxt-link>
                  
                  <h4 class="text-xl font-semibold mt-1 mb-12 pb-1">Добро пожаловать</h4>
                </div>
                <form>
                  <p class="mb-4">Пожалуйста введите данные для авторизации</p>
                  <div class="mb-4">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Логин"
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
                  <div class="text-center pt-1 mb-12 pb-1">
                    <nuxt-link to="/logining">
                    <button
                      class=" px-6 py-2.5 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700  transition duration-150 ease-in-out w-full mb-3 bg-blue-300"
                      type="button"
                      data-mdb-ripple="true"
                      data-mdb-ripple-color="light"
                      style="
                        background:cadetblue;
                      "
                    >
                      Вход
                    </button>
                    </nuxt-link>
                    <a class="text-gray-500" href="/reminder">Забыли пароль?</a>
                  </div>
                  <div class="flex items-center justify-between pb-6">
                    <p class="mb-0 mr-2">Еще не зарегистрированы?</p>
                    <nuxt-link to="/registr">
                    <button
                      type="button"
                      class="inline-block px-6 py-2 border-2 border-green-600 text-green-600 font-medium text-xs leading-tight uppercase rounded hover:bg-black hover:bg-opacity-5 focus:outline-none focus:ring-0 transition duration-150 ease-in-out"
                      data-mdb-ripple="true"
                      data-mdb-ripple-color="light"
                    >
                      Регистрация
                    </button>
                    </nuxt-link>
                  </div>
                </form>
              </div>
            </div>
            
            <div
              class="lg:w-6/12 flex items-center lg:rounded-r-lg rounded-b-lg lg:rounded-bl-none border-4 border-green-400 rounded-3xl bg-green-500"
              
            >
            
              <div class="text-white px-4 py-6 md:p-12 md:mx-6">
                <h1 class="text-x1 font-semibold mb-6">О компании:</h1>
                <p>
                  1. Потребность в найме — это что и зачем? Хорошо, когда в компании существует стратегический план по найму сотрудников на год, пять и больше лет вперед. В этом случае рекрутеры заранее знают, какие ресурсы им понадобятся в каждый отрезок времени. В небольших организациях подбор обычно ситуативный и закрывает текущие потребности. Например, замена сотрудника, который уходит в декрет или длительный отпуск, подбор нового человека на место уволившегося. Существует больше десятка способов оценить потребность в персонале. На нее влияет рынок в регионе, скорость и план развития компании, эффективность текущих сотрудников и другие факторы. В зависимости от кадровой политики компания может привлекать новые кадры или обучать персонал. Или сокращать. Знание потребности в подборе персонала помогает: Составить план закрытия
                </p>
                
              </div>
              
            </div>
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
