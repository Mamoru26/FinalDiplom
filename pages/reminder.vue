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
                  <p class="mb-4">Введите e-mail адрес на который регистрировали аккаунт</p>
                  <div class="mb-4">
                    <input
                      type="text"
                      class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                      id="exampleFormControlInput1"
                      placeholder="Email"
                    />
                  </div>
                  
                  <div class="text-center pt-1 mb-12 pb-1">
                    <nuxt-link to="/remainredir">
                    <button
                      class=" px-6 py-2.5 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700  transition duration-150 ease-in-out w-full mb-3 bg-blue-300"
                      type="button"
                      data-mdb-ripple="true"
                      data-mdb-ripple-color="light"
                      style="
                        background:cadetblue;
                      "
                    >
                      Отправить
                    </button>
                  </nuxt-link>
                  </div>
                  
                </form>
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
