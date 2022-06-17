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
                
            
                
                <p class="text_stile px-4 py-2">Никита Гайденко</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">Возраст: 19 лет</p>
                <p class="text_stile px-4 py-2">Ключевые навыки:</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">Git • Linux • PostgreSQL • SQL • Nginx • Docker • React • JavaScript • Redux • HTML</p>
                <p class="text_stile px-4 py-2">Опыт работы: 1 год и 4 месяца</p>
                <div class="py-1">
                <div class="px-4 py-1  bg-blue-200 rounded-lg">
                <p >SecretOrg</p>
                <p >Москва</p>
                <p >Frontend Developer. Апрель 2022 — По настоящее время (3 месяца). Разработка сайта, связанного с blockchain тематикой - https://secretcalendar.org/</p>
                <p>JavaScript • React • TypeScript • Redux</p>
                </div>
                </div>
                <div class="py-1">
                <div class="px-4 py-1  bg-blue-200 rounded-lg">
                <p >Айбим</p>
                <p >Москва</p>
                <p >Frontend Developer. Ноябрь 2021 — По настоящее время (8 месяцев)</p>
                <p>React • JavaScript • Redux</p>
                </div>
                </div>
                <div class="py-1">
                <div class="px-4 py-1  bg-blue-200 rounded-lg">
                <p >ФГБУ "Акваинфотека"</p>
                <p >Москва</p>
                <p >Март 2021 — По настоящее время (1 год и 4 месяца)
                        Разработка телефонного справочника и service-desk. Разрабатывал на следующих технологиях:

                        Backend - Django(DRF), celery, redis, postgreSQL

                        Frontend - React, Redux, Typescript

                        Deploy - Heroku, AWS, Nginx, Gunicorn</p>
                <p>JavaScript • React • Redux • Django • Python • PostgreSQL • Nginx</p>
                </div>
                </div>
                <div class="py-1">
                <div class="px-4 py-1  bg-blue-200 rounded-lg">
                <p >Qenetex</p>
                <p >Москва</p>
                <p >Fullstack Developer
                  Октябрь 2021 — Октябрь 2021 (1 месяц)
                  Разработка крипто кошелька, для обмена криптовалютами.</p>
                <p>Python • AIOHTTP • React • Redux • TypeScript</p>
                </div>
                </div>


                </div>
                
                

            <!-- Конец левой части -->

            <!-- Начало правой -->
            <div class="lg:w-3/12 py-2 px-2 w-full">
                <p class="text_stile px-4 py-2">Информация для связи:</p>
                <div class="py-1">
               <p class="px-4 py-1  bg-blue-200 rounded-lg">brookenik@yandex.ru</p>
                </div>
                <div class="py-1">
                <p class="px-4 py-1  bg-blue-200 rounded-lg">t.me/nikita99</p>
                </div>
                <div class="py-1">
                <p class="px-4 py-1  bg-blue-200 rounded-lg">https://github.com/broooke</p>
                </div>
                
                <p class="text_stile px-4 py-2">Желаемая ЗП:</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">От 160 000р.</p>
                <p class="text_stile px-4 py-2">Обо мне:</p>
                <p class="px-4 py-1  bg-blue-200 rounded-lg">Frontend:

                  TypeScript, JavaScript (ES6+)
                  ReactJS
                  Redux, Redux Thunk,  Redux Toolkit
                  Formik, React Hook Form
                  ESLint, Prettier
                  SCSS / styled-components
                  Material UI, Bootstrap
                  Jest
                  Backend:

                  Node.JS / Nest.JS
                  Sequalize / MongoDB / Mongoose
                  JWT
                  Другие скиллы:

                  Git / GitHub / Bitbucket / GitLab
                  MySQL / NoSQL
                  JSON
                  Jira, Confluence</p>
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