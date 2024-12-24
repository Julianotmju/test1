<template>
    <MainLayout>  




        <div class="py-8 px-4 mx-auto max-w-screen-xl text-left lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                PLOTAGEM EM VEÍCULOS</h1>
        </div>
 







        <div>
                <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 grid lg:grid-cols-2 gap-8 lg:gap-16">
                    <div>
                    <img class="rounded-t-lg" src="/PLOTAGEM_1.webp" alt="">
                    </div>
                    <div class="flex flex-col justify-center">
                        <h3 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-300 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                            PLOTAGEM DE COMUNICAÇÃO VISUAL</h3>
                        <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                            Plotagem de comunicação visual  o envelopamento do veículo com vinil automotivo para impressão. 
                            A tecnologia dos materiais permite a moldagem às curvas e sua durabilidade pode variar de 3 a 4 anos. 
                            O processo de aplicação pela BH Plotter pode ser feito através do acabamento 3M ou o acabamento completo, escondendo a cor do veículo.</p>
                        <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                        <button type="button" @click="navigateTo('/ploter')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Veja mais</button>
                        </div>
                    </div>
                    
                </div>
        </div>











        <div class="py-8 px-8 mx-auto max-w-screen-xl lg:py-16 flex items-center justify-center">
            <div class="grid md:grid-cols-2 gap-8">  



                <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <a data-modal-target="default-modal1" data-modal-toggle="default-modal1">
                        <img class="rounded-t-lg" src="/PLOTAGEM_T.webp" alt="" />
                    </a>
                    <div class="p-5 text-center">
                        <a href="#">
                            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Plotagem Total</h5>
                        </a>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">O material cobre 100% da lataria do veículo.</p>
                        <button data-modal-target="default-modal1" data-modal-toggle="default-modal1" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2" type="button">
                            Veja mais
                        </button>
                    </div>
                </div>


                <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <a data-modal-target="default-modal2" data-modal-toggle="default-modal2">
                        <img class="rounded-t-lg" src="/PLOTAGEM_p.webp" alt="" />
                    </a>
                    <div class="p-5 text-center">
                        <a href="#">
                            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Plotagem Parcial</h5>
                        </a>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">O material cobre até 70% da lataria do veículo.</p>
                        <button data-modal-target="default-modal2" data-modal-toggle="default-modal2" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2" type="button">
                            Veja mais
                        </button>
                    </div>
                </div>



            </div>
        </div>
















     </MainLayout>  
  
  </template>








<style>
.carousel__item {
  min-height: 300px;
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/50001.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.carousel__item_2 {
  min-height: 300px;
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/50001.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.back_title {
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/back_title.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

</style>






  
  <script setup>
  import MainLayout from '~/layouts/MainLayout.vue';

  
  
  
  

  </script>

  <script>
</script>