<template class="bg-white">
    <MainLayout>  



<!--Banner-->



    <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-0 drop-shadow-lg">

      
      <!--Plotagem automotiva-->
      <Carousel :autoplay="10000" :wrap-around="true">
          <Slide v-for="slide in 1" :key="slide">
            <div class="carousel__item_2">
                  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-8 grid lg:grid-cols-2 gap-8 lg:gap-8">
                      <div class="flex flex-col justify-center">
                          <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Plotagem de veículos</h1>
                          <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Envelopamento do veículo com vinil automotivo e impressão.</p>
                          <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/ploter')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Veja mais</button>
                          </div>
                      </div>
                      <div>
                        <img class="rounded-t-lg"  width="500" src="/ploter_1.png" alt="">
                      </div>
                  </div>
            </div>
          </Slide>




          <!--Fachadas-->
          <Slide v-for="slide in 1" :key="slide">
            <div class="carousel__item_2">
                  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-8 grid lg:grid-cols-2 gap-8 lg:gap-8">
                      <div class="flex flex-col justify-center">
                          <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Fachada comercial</h1>
                          <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Fachadas arquitetonica .</p>
                          <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/fachada')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Veja mais</button>
                          </div>
                      </div>
                      <div>
                        <img class="rounded-t-lg" width="500"  src="/fachada_1.png" alt="">
                      </div>
                  </div>
            </div>
          </Slide>


          <!--Luminoso-->
          <Slide v-for="slide in 1" :key="slide">
            <div class="carousel__item_2">
                  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-8 grid lg:grid-cols-2 gap-8 lg:gap-8">
                      <div class="flex flex-col justify-center">
                          <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Luminoso</h1>
                          <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">De vida a sua fachada com letras Caixa em Acm, Inox, Acrílico e leds.</p>
                          <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/luminosos')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Veja mais</button>
                          </div>
                      </div>
                      <div>
                        <img class="rounded-t-lg" width="500"  src="/luminoso_1.png" alt="">
                      </div>
                  </div>
            </div>
          </Slide>


      </Carousel>

    </div>


    <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
    
     
    <!-- <div class="bg-gray-50 rounded-lg p-8 md:p-12 mb-8 drop-shadow-lg">
               <h1 class="text-gray-900 dark:text-white text-3xl md:text-5xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Somos a Flex design</h1>
               <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-6">Atuamos no ramo de Comunicação Visual desde o ano 2000. Nossa empresa conta com mão-de-obra especializada e equipamentos de ultima geração, oferecendo serviço de alta qualidade, preço acessível em um curto prazo. O grande diferencial é o nosso atendimento personalizado, visa entender as necessidades de seus clientes, os ajudando com estratégias e posicionamento para atingir o melhor resultado de comunicação, respeitando ás suas exigências de qualidade. O Propósito da Flex Design é sempre desenvolver um relacionamento sólido com seus clientes, executando nosso trabalho de forma transparente, assim transmitindo credibilidade na realização de seus serviços, com isso obtendo á expansão de seus negócios estrategicamente planejada, tornando-se uma empresa atuante no mercado.</p>
           
           </div>-->
           <div class="grid md:grid-cols-3 gap-8 justify-center">
              <div class="bg-blue-950 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12 drop-shadow-lg backdrop-blur-md ">

                   <a  class="bg-purple-100 text-purple-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-purple-400 mb-2">
                       NEON
                   </a>
                   <a class="bg-purple-100 text-purple-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-purple-400 mb-2">
                       LED
                   </a>
                   <img class="rounded-t-lg"  src="/l2.png" alt="Luminoso">
                   <h1 class="text-gray-900 dark:text-white text-3xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                      Luminoso</h1>
                   <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                      Tenha uma ampla visibilidade em seu negócio a qualquer hora do dia e realsse ainda mais a forma da sua logo marca!</p>
                    <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/luminoso')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Ver mais</button>
                          </div>
               </div> 
   
               <div class="bg-blue-950 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12 drop-shadow-lg backdrop-blur-md">
                   <a class="bg-purple-100 text-purple-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-purple-400 mb-2">
                       ACM
                   </a>
                   <a  class="bg-purple-100 text-purple-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-purple-400 mb-2">
                       LETRA CAIXA
                   </a>
                   <img class="rounded-t-lg"  src="/flex_design_3d.png" alt="Fachada">
                   <h2 class="text-gray-900 dark:text-white text-3xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                      Fachada em ACM</h2>
                   <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                      Técnica e criatividade exibidas na porta de entrada do seu comércio,
                      criamos e produzimos as mais belas fachadas da região.
                   </p>
                   <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/fachadas')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Ver mais</button>
                    </div>
               </div> 

               <div class="bg-blue-950 dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded-lg p-8 md:p-12 drop-shadow-lg backdrop-blur-md">
                   <a class="bg-purple-100 text-purple-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-purple-400 mb-2">
                       ADESIVO IMPRESSO
                   </a>
                   <a class="bg-purple-100 text-purple-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-purple-400 mb-2">
                       ADESIVO VINIL
                   </a>
                   <img class="rounded-t-lg"  src="/ploter-auto.png" alt="Plotagem">
                   <h2 class="text-gray-900 dark:text-white text-3xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                      Auto-Plotagem</h2>
                   <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-4 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                      Envelopamento automotivo comercial ou pessoal, trabalhamos com todos os tipos de envelopamento personalizado para empresas.</p>
                      <div class="flex flex-col space-y-8 sm:flex-row sm:space-y-0">
                            <button type="button" @click="navigateTo('/plotagem-auto')" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Ver mais</button>
                    </div>
               </div> 
           </div>
       </div>




<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
              Quem somos</h1>
            <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-400 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
              Flex Design busca levar aos clientes de São Paulo e Região serviços de Comunicação Visual de qualidade, 
              garantindo a criação da Arte em alto padrão de envelopamento e adesivação de alta performance a fachadas para empresas e estruturas para comunicações visuais incríveis.</p>
        </div>
</div>





<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
        <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 quemsomos">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
              Nossos clientes</h1>
              

              <div class="grid grid-cols-4 md:grid-cols-4 gap-4">
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/1.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/2.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/3.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/4.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/5.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/6.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/7.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/8.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/9.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/10.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/11.jpg" alt="">
                </div>
                <div>
                    <img class="h-auto max-w-full rounded-lg" src="/imgs/clientes/12.jpg" alt="">
                </div>
              
            </div>


        </div>
</div>





<!--

<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
    
     
    <div class="bg-gray-50 rounded-lg p-8 md:p-12 mb-8 drop-shadow-lg">
            <h1 class="text-gray-900 dark:text-white text-3xl md:text-5xl font-extrabold mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">Somos a Flex design</h1>
            <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-6">Atuamos no ramo de Comunicação Visual desde o ano 2000. Nossa empresa conta com mão-de-obra especializada e equipamentos de ultima geração, oferecendo serviço de alta qualidade, preço acessível em um curto prazo. O grande diferencial é o nosso atendimento personalizado, visa entender as necessidades de seus clientes, os ajudando com estratégias e posicionamento para atingir o melhor resultado de comunicação, respeitando ás suas exigências de qualidade. O Propósito da Flex Design é sempre desenvolver um relacionamento sólido com seus clientes, executando nosso trabalho de forma transparente, assim transmitindo credibilidade na realização de seus serviços, com isso obtendo á expansão de seus negócios estrategicamente planejada, tornando-se uma empresa atuante no mercado.</p>
        
        </div>
        
        <div class="grid md:grid-cols-2 gap-8">
          <div class="bg-gray-100 rounded-lg backdrop-blur-md">
              <Carousel :autoplay="6000" :wrap-around="true">


                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                         <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>
                  
                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                          <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/faixa_banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>


                  <template #addons>
                  </template>
              </Carousel>
            </div>

            <div class="bg-gray-100 rounded-lg backdrop-blur-md">
              <Carousel :autoplay="6000" :wrap-around="true">


                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                         <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>
                  
                  <Slide v-for="slide in 1" :key="slide">
                    <div class="item_card_1">
                        <figure class="bg-gray-100 rounded-lg backdrop-blur-md">
                          <a href="https://www.flexdesignituoficial.imprimastore.com.br/" ><img class="h-auto max-w-full rounded-lg" src="/faixa_banner_aqui.jpg" alt="image description"></a>
                        </figure>
                    </div>
                  </Slide>


                  <template #addons>
                  </template>
              </Carousel>
            </div>
        </div>
    </div>

  -->




  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
<a href="https://wa.me/5511995103964?text=Oi, gostaria de fazer um orçamento!" style="position:fixed;width:60px;height:60px;bottom:40px;right:40px;background-color:#25d366;color:#FFF;border-radius:50px;text-align:center;font-size:30px;box-shadow: 1px 1px 2px #888;
  z-index:1000;" target="_blank">
<i style="margin-top:16px" class="fa fa-whatsapp"></i>
</a>




     </MainLayout>  
  
  </template>





<script>
import { defineComponent } from 'vue'
import { Carousel, Pagination, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
  name: 'Autoplay',
  components: {
    Carousel,
    Slide,
    Pagination,
  },
})
</script>

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




.item_card_1 {
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url(/flex_design_3d.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

</style>






  
  <script setup>
  import MainLayout from '~/layouts/MainLayout.vue';

  </script>
  