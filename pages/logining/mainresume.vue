<template>
  <section class="h-full bg-white md:h-screen">
    
    <div class="xl:w-12/12 h-full">
       <nuxt-link to="/logining">
       <div class="px-14 py-2">
        <a class="nav-link px-8 py-3 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-green-700  transition duration-150 ease-in-out w-full mb-3 bg-green-300" href="/logining">Назад</a>
        </div>
        </nuxt-link>
        <div class="block ">
            
            
          <div class="lg:flex bg-white lg:flex-wrap g-0 px-12 py-6">
            
            <div class="lg:w-6/12 py-2 px-2 w-full ">
                
            
                
                <p class="text_stile px-4 py-2">О себе:</p>

                <div class="bg-blue-200 rounded-lg py-2">
                <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full ">
                    <div class="mb-4">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Имя"
                    />
                  </div>
                  <div class="mb-4 px-2">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Фамилия"
                    />
                  </div>
                </div>

                <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full">
                    <div class="mb-4">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Город проживания"
                    />
                  </div>
                  <div class="mb-4 px-2">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Гражданство"
                    />
                  </div>
                </div>

                <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full">
                    <div class="mb-4">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Дата рождения"
                    />
                  </div>
                  <div class="check px-4">
                    <p class="text_stile px-2 py-2">Пол:</p>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Мужской
                    </label>
                    </div>
                    <div class="form-check">
                    <input class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer" type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label inline-block text-gray-800" for="flexCheckDefault">
                        Женский
                    </label>
                    </div>
                    
                    
                </div>
                </div>



                </div>

                <p class="text_stile px-4 py-2">Специальность:</p>

                <div class="bg-blue-200 rounded-lg py-2">
                <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full ">
                    <div class="mb-4 w-full">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Желаемая спцеиальность"
                    />
                  </div>
                  <div class="mb-4 ">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Заработная плата"
                    />
                  </div>
                  <div class="mb-4 px-2">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Валюта"
                    />
                  </div>
                </div>

                </div>

                <p class="text_stile px-4 py-2">Образование:</p>

                <div class="bg-blue-200 rounded-lg py-2">
                <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full ">
                    <div class="mb-4 w-full">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Наименование университета"
                    />
                  </div>
                  <div class="mb-4 w-full">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Направление"
                    />
                  </div>
                  <div class="mb-4 w-full">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Спцеиальность"
                    />
                  </div>
                </div>

                </div>





                
               
                
                </div>
                
                

            <!-- Конец левой части -->

            <!-- Начало правой -->
            <div class="lg:w-6/12 py-2 px-2 w-full">
                
                    
                
                <p class="text_stile px-4 py-2">Опыт работы:</p>

                <div class="bg-blue-200 rounded-lg py-2">
                    <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full ">
                        <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="Наименование организации"
                        />
                    </div>
                    <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="Должность"
                        />
                    </div>
                    <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="Время"
                        />
                    </div>
                    </div>

                </div>
                <div class="py-6">
                <a class="nav-link px-8 py-3 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700  transition duration-150 ease-in-out mb-3 bg-blue-300" href="#">Добавить место работы</a>
                 </div>   


                <p class="text_stile px-4 py-2">Дополнительная инфорамция</p>

                <div class="bg-blue-200 rounded-lg py-2">
                    <div class="lg:flex  lg:flex-wrap g-0 px-4 py-0 w-full ">
                        
                        <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="Email"
                        />
                    </div>
                    <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="Телеграмм"
                        />
                    </div>
                    <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="GitHub"
                        />
                    </div>
                    <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="LinkedIn"
                        />
                    </div>
                    <div class="mb-4 w-full">
                        <input
                        type="text"
                        class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                        id="exampleFormControlInput1"
                        placeholder="Кратко о себе"
                        />
                    </div>
                    </div>

                </div>


            </div>
            </div>
          </div>
            <nuxt-link to="/redir">
       <div class="save px-14">
        <a class="nav-link px-8 py-3 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-green-700  transition duration-150 ease-in-out w-full mb-3 bg-green-300" href="/redir">Сохранить и опубликовать</a>
        </div>
            </nuxt-link>
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