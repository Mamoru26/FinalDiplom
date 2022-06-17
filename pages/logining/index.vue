<template>
<section class="h-full gradient-form bg-gray-200 md:h-screen">
    <div class="xl:w-12/12 h-full">
        <div class="block  shadow-lg rounded-lg">
          <div class="lg:flex bg-white lg:flex-wrap g-0 px-2 py-2">
            <!-- Начало фильтров -->
            <div class="lg:w-2/12 px-2 py-2 ">
                <!-- <div class="filter text-center py-8 px-4 text-white bg-green-500 border-2 border-green-500 rounded-3xl">
                        <p>Фильтры:</p>
                    </div> -->
                <ul class="filte_folow border-2 border-blue-400 rounded-2xl">
                <!-- <li> -->
                    
                    <!-- </li> -->
                    <li class="id_folow flex items-center ">
                <div class="check px-4 py-4">
                    <p class="text_stile px-2 py-2">Ключевое направление:</p>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        FrontEnd
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        BackEnd
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        BigDate
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        Testing
                    </label>
                    </div>
                </div>
                </li>
                <li class="id_folow flex items-center ">
                <div class="check px-4 py-4">
                    <p class="text_stile px-2 py-2">Ключевые навыки:</p>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Elixir
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        .NET
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        PHP
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        Vue.js
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        C++
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        C#
                    </label>
                    </div>
                </div>
                </li>
                <li class="id_folow flex items-center ">
                <div class="check px-4 py-4">
                    <p class="text_stile px-2 py-2">Опыт работы:</p>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Меньше года
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        1 год
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        2 года
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Более 2-ух лет
                    </label>
                    </div>
                </div>
                </li>
                <li class="id_folow flex items-center  ">
                <div class="check px-4 py-4">
                    <p class="text_stile px-2 py-2">Образование:</p>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Нет
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Средне-специальное
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Высшее
                    </label>
                    </div>
                    
                </div>
                </li>
                <li class="id_folow flex items-center ">
                <div class="check px-4 py-4">
                    <p class="text_stile px-2 py-2">Город:</p>
                    <div class="mb-2 py-2">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Населенный пункт"
                    />
                  </div>
                    
                </div>
                </li>
                <li class="id_folow flex items-center ">
                <div class="check px-4 py-4">
                    <p class="text_stile px-2 py-2">Занятось:</p>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Полная
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        Гибкий график
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        Частичная
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckChecked" >
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckChecked">
                        Удаленная работа
                    </label>
                    </div>
                </div>
                </li>
                </ul>
                </div>

            <!-- Конец фильтров -->

            <!-- Начало таблицы вакансий -->
            <div
              class="lg:w-10/12 lg:rounded-r-lg rounded-b-lg lg:rounded-bl-none border-2 border-green-400 rounded-lg px-2 py-1  "
              style="
                background: white;
              "
            >
            <div class="headerboard underline text-black px-2 py-2">
                <h1 class="text-x2 font-semibold mb-6">Найдено 4 вакансий</h1>
            </div>
            <ul class="overflow-auto">
                <nuxt-link to="/logining/resume/resume1">
                        <li class="id_folow flex items-center  px-4 ">
                            <div class="check_table   w-full">
                                <div class="xl:w-12/12 w-full">
                    <div class="block  shadow-lg rounded-lg">
                    <div class="lg:flex  lg:flex-wrap g-0 px-2 py-0.5">
                        
                        <div class="lg:w-6/12 px-2 py-1 ">
                        <p class="text_stile text-left">Юрий Новиков. Backend Developer • Бэкенд разработчик • Средний (Middle)</p> 
                        <p class="text_sile_old text-left py-1">Опыт работы: 1 год и 9 месяцев</p>
                        <p class="text_stile text-left py-2">Ключевые навыки:</p>
                        <p class="text_sile_old text-left py-1">.NET Core • ASP.NET WEB API </p>
                            <p class="text_sile_old text-left ">C# • Node.js • NestJS • TypeScript</p>
                        </div>
                        <div class="lg:w-6/12 px-2 py-1 ">
                            <p class="text_stile text-right py-6">Москвоский технологический университет</p>
                            <p class="text_stile text-right py-8">Активно ищу работу!</p>
                        </div>
                    </div>
                    </div>
                    </div>                
                            </div>
                            </li>
                            </nuxt-link>
                            <nuxt-link to="/logining/resume/resume2">
            <li class="id_folow flex items-center  px-4 ">
                            <div class="check_table  w-full">
                                <div class="xl:w-12/12 w-full">
                    <div class="block  shadow-lg rounded-lg">
                    <div class="lg:flex  lg:flex-wrap g-0 px-2 py-2">
                        
                        <div class="lg:w-6/12 px-2 py-1 ">
                        <p class="text_stile text-left">Георгий Худяков. Бэкенд разработчик • Фронтенд разработчик • Middle</p> 
                        <p class="text_sile_old text-left py-1">Опыт работы: 4 года и 6 месяцев</p>
                        <p class="text_stile text-left py-2">Ключевые навыки:</p>
                        <p class="text_sile_old text-left py-1">Vue.js • HTML • CSS • JavaScript </p>
                            <p class="text_sile_old text-left ">• Адаптивная верстка • PHP • MySQL</p>
                        </div>
                        <div class="lg:w-6/12 px-2 py-1 ">
                            <p class="text_stile text-right py-6">Санкт-Петербургский университет технологий управления и экономики</p>
                            <p class="text_stile text-right py-8">Активно ищу работу!</p>
                        </div>
                    </div>
                    </div>
                    </div>                
                            </div>
                            </li>
                            </nuxt-link>


                            <nuxt-link to="/logining/resume/resume3">
                            <li class="id_folow flex items-center  px-4 ">
                            <div class="check_table  w-full">
                                <div class="xl:w-12/12 w-full">
                    <div class="block  shadow-lg rounded-lg">
                    <div class="lg:flex  lg:flex-wrap g-0 px-2 py-2">
                        
                        <div class="lg:w-6/12 px-2 py-1 ">
                        <p class="text_stile text-left">Никита Гайденко. Frontend Developer • Бэкенд разработчик • Фулстек разработчик • Middle</p> 
                        <p class="text_sile_old text-left py-1">Опыт работы: 1 год и 4 месяца</p>
                        <p class="text_stile text-left py-2">Ключевые навыки:</p>
                        <p class="text_sile_old text-left py-1">Git • Linux • PostgreSQL • SQL • Nginx • Docker </p>
                            <p class="text_sile_old text-left ">• React • JavaScript • Redux • HTML</p>
                        </div>
                        <div class="lg:w-6/12 px-2 py-1 ">
                            <p class="text_stile text-right py-6">РЭУ им. Г.В. Плеханова</p>
                            <p class="text_stile text-right py-8">Активно ищу работу!</p>
                        </div>
                    </div>
                    </div>
                    </div>                
                            </div>
                            </li>
                            </nuxt-link>


                            <nuxt-link to="logining/resume/resume4">
                            <li class="id_folow flex items-center  px-4 ">
                            <div class="check_table w-full">
                                <div class="xl:w-12/12 w-full">
                    <div class="block  shadow-lg rounded-lg">
                    <div class="lg:flex  lg:flex-wrap g-0 px-2 py-2">
                        
                        <div class="lg:w-6/12 px-2  ">
                        <p class="text_stile text-left">Владислав Разин. JS developer • Бэкенд разработчик • Фронтенд разработчик • Middle</p> 
                        <p class="text_sile_old text-left py-1">Опыт работы: 2 года и 4 месяца</p>
                        <p class="text_stile text-left py-2">Ключевые навыки:</p>
                        <p class="text_sile_old text-left py-1">JavaScript • Git • PostgreSQL • Docker </p>
                            <p class="text_sile_old text-left ">• Node.js • Веб-разработка • React</p>
                        </div>
                        <div class="lg:w-6/12 px-2  ">
                            <p class="text_stile text-right py-6">СурГУ • Автоматики и телекоммуникаций</p>
                            <p class="text_stile text-right py-7">Активно ищу работу!</p>
                        </div>
                    </div>
                    </div>
                    </div>                
                            </div>
                            </li>
                            </nuxt-link>


                            
                            </ul>
                            
            


            </div>
            <!-- Конец таблицы -->
          </div>
        </div>
    </div>
</section>



</template>

<style scoped>
.text_stile {
    font-family: Georgia, 'Times New Roman', Times, serif;
    @apply font-semibold
}
.check_table{
    @apply py-2
}
</style>
<script>

export default {
    layout: 'login',
    
}
</script>
