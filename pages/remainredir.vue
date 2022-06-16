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
                    <div class="text-center pt-1 mb-12 pb-1">
                  <p class="mb-4">На указанный вами e-mail было отправлено сообщение с паролем</p>
                  <p class="mb-4">В течении 5 секунд вы перейдете на главную страницу сайта</p>
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
   created: function() {

    setTimeout(() => {
    this.$router.push('/');
}, 5000);
  }

}
</script>
}