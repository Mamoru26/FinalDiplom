<template>
  <section class="h-full bg-white md:h-screen">
    
    <div class="xl:w-12/12 h-full">
       <nuxt-link to="/logining">
       <div class="px-14 py-2">
        <a class="nav-link px-8 py-3 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-green-700  transition duration-150 ease-in-out w-full mb-3 bg-green-300" href="#">Назад</a>
        </div>
        </nuxt-link>
        <div class="block ">
            
            
          <div class="lg:flex bg-white lg:flex-wrap g-0 px-12 py-6">
            
            <div class="lg:w-8/12 py-2 px-2 w-full">
                
            
                
                <p class="text_stile px-4 py-2">Владислав Разин</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">Возраст: 19 лет</p>
                <p class="text_stile px-4 py-2">Ключевые навыки:</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">JavaScript • Git • PostgreSQL • Docker • Node.js • Веб-разработка • React</p>
                <p class="text_stile px-4 py-2">Опыт работы 2 года и 4 месяца</p>
                <div class="py-1">
                <div class="px-4 py-1  bg-blue-200 rounded-lg">
                <p >Health Samurai</p>
                <p >Санкт-Петербург</p>
                <p >Junior full stack developer. Сентябрь 2020 — По настоящее время (1 год и 10 месяцев)</p>
                <p>JavaScript • Git • PostgreSQL • Docker • React • Node.js • Kubernetes</p>
                </div>
                </div>
                <div class="py-1">
                <div class="px-4 py-1  bg-blue-200 rounded-lg">
                <p >Dotsolution</p>
                <p >Сургут</p>
                <p >Backend разработчик. Март 2020 — Август 2020 (6 месяцев). Разработка микросервисов</p>
                <p>JavaScript • Node.js • PostgreSQL • MySQL • Python • Docker • Flask • Базы данных • SQLalchemy</p>
                </div>
                </div>
                
                </div>
                
                

            <!-- Конец левой части -->

            <!-- Начало правой -->
            <div class="lg:w-3/12 py-2 px-2 w-full">
                <p class="text_stile px-4 py-2">Информация для связи:</p>
                <div class="py-1">
                <p class="px-4 py-1  bg-blue-200 rounded-lg">razin36986@gmail.com</p>
                </div>
                <div class="py-1">
                <p class="px-4 py-1  bg-blue-200 rounded-lg">@VladosCocos418</p>
                </div>
                <div class="py-1">
                <p class="px-4 py-1  bg-blue-200 rounded-lg">https://github.com/VladosCocos</p>
                </div>
                
                <p class="text_stile px-4 py-2">Желаемая ЗП:</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">От 150 000р.</p>
                <p class="text_stile px-4 py-2">Обо мне:</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">Молодой и перспективный сотрудник. Ищу новые возможности и новые направления</p>

            </div>
            </div>
          </div>
          </div>
        
   
  </section>
</template>

<script>
export default {
layout: 'login',
}
</script>
    
<style scoped>
.text_stile {
    font-family: Georgia, 'Times New Roman', Times, serif;
    @apply font-semibold}

</style>