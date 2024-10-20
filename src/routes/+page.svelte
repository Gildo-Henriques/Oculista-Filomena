<script>
	import Contactos from "$lib/Contactos.svelte";
import FaQ from "$lib/FaQ.svelte";
  import Footer from "$lib/Footer.svelte";
  import Produtos from "$lib/Produtos.svelte";
 
import Servicos from "$lib/Servicos.svelte";

</script>

<header class="overflow-hidden h-[40rem]">
  <div
    class="w-full bg-center  bg-cover h-[38rem] "
    style="background-image: url('hero.jpg');"
  >
    <div
      class="flex items-end justify-start w-full h-full lg:px-20 px-5 py-20 bg-gray-900/40"
    >
      <div class="text-start lg:w-1/2 w-full flex flex-col  space-y-10 z-20">
        <h1 class="text-3xl font-bold text-white lg:text-4xl">
          O que você nunca viu, você verá na <span class="text-green-500 before:content[''] before:w-full before:h-full before:z-20 relative before:absolute  before:border-t-4 before:border-green-500 before:top-10 before:-rotate-3">Oculista Filomena</span>
        </h1>
        <p class="text-white text-lg">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa
          similique aperiam mollitia excepturi a vero eveniet ut molestias, ex
          delectus sit dolores cum exercitationem neque sed quibusdam animi
          perferendis porro.
        </p>

		<a href="" class="bg-white px-5 py-2 w-auto self-start">Agendar Comsulta</a>
      </div>
    </div>
  </div>
</header>
<!--  -->
<section class="bg-white g-gray-900">
    <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-gray-800 capitalize lg:text-3xl ext-white">O que saber <br> sobre <span class="text-green-500">Oculista Filomena</span></h1>

        
        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-12 xl:gap-12 md:grid-cols-2">
            <div class="p-6 border-2 rounded-xl border-green-500 order-gray-700">
                <div class="md:flex md:items-start md:-mx-4">
                    <span class="inline-block p-2 text-green-500 bg-green-100 rounded-xl md:mx-4 ext-white g-blue-500">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
                        </svg>
                    </span>

                    <div class="mt-4 md:mx-4 md:mt-0">
                        <h1 class="text-xl font-medium text-gray-700 capitalize ext-white">Copy & paste components</h1>

                        <p class="mt-3 text-gray-500 ext-gray-300">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet
                        </p>
                    </div>
                </div>
            </div>

            <div class="p-6 border rounded-xl border-r-gray-200 order-gray-700">
                <div class="md:flex md:items-start md:-mx-4">
                    <span class="inline-block p-2 text-green-500 bg-green-100 rounded-xl md:mx-4 ext-white g-blue-500">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
                        </svg>
                    </span>

                    <div class="mt-4 md:mx-4 md:mt-0">
                        <h1 class="text-xl font-medium text-gray-700 capitalize ext-white">Zero Configuration</h1>

                        <p class="mt-3 text-gray-500 ext-gray-300">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet
                        </p>
                    </div>
                </div>
            </div>

            <div class="p-6 border rounded-xl border-r-gray-200 order-gray-700">
                <div class="md:flex md:items-start md:-mx-4">
                    <span class="inline-block p-2 text-green-500 bg-green-100 rounded-xl md:mx-4 ext-white g-blue-500">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z" />
                        </svg>
                    </span>

                    <div class="mt-4 md:mx-4 md:mt-0">
                        <h1 class="text-xl font-medium text-gray-700 capitalize ext-white">elegant Ode</h1>

                        <p class="mt-3 text-gray-500 ext-gray-300">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet
                        </p>
                    </div>
                </div>
            </div>

            <div class="p-6 border rounded-xl border-r-gray-200 order-gray-700">
                <div class="md:flex md:items-start md:-mx-4">
                    <span class="inline-block p-2 text-green-500 bg-green-100 rounded-xl md:mx-4 ext-white g-blue-500">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z" />
                        </svg>
                    </span>

                    <div class="mt-4 md:mx-4 md:mt-0">
                        <h1 class="text-xl font-medium text-gray-700 capitalize ext-white">Simple & clean designs</h1>

                        <p class="mt-3 text-gray-500 ext-gray-300">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident ab nulla quod dignissimos vel non corrupti doloribus voluptatum eveniet
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<!-- SERVIÇOS -->

 <Servicos />
 <!-- SEU ESTILO -->
 <section class="bg-gray-800 mt-20">
    <div class="container px-6 py-10 mx-auto">
        <div class="xl:flex xl:items-center xL:-mx-4">
            <div class="xl:w-1/2 xl:mx-4">
                <h1 class="text-3xl font-semibold text-white capitalize lg:text-3xl ">Seu estilo é nossa obrigação</h1>

                <p class="max-w-2xl mt-4 text-gray-500 ext-gray-300">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo incidunt ex placeat modi magni quia error alias, adipisci rem similique, at omnis eligendi optio eos harum.
                </p>
            </div>

            <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-0 xl:mx-4 xl:w-1/2 md:grid-cols-2">
                <div>
                    <img class="object-cover rounded-xl aspect-square" src="seu estilo é nossa obrigação.jpg" alt="">

                    
                </div>

                <div>
                    <img class="object-cover rounded-xl aspect-square" src="veja.jpg" alt="">

                   
                </div>
            </div>
        </div>
    </div>
</section>
<!-- FAQ -->
 <FaQ />
 <!-- Produtos -->
  <Produtos />

<!-- MARCAS -->
<section class="w-full flex flex-col  gap-y-5 items-center">
	<h2 class="text-3xl font-semibold text-black capitalize lg:text-3xl ">Marcas</h2>
	<div class="flex w-full lg:flex-row flex-wrap px-5 gap-10 justify-around">
		<div class="text-6xl font-black text-gray-400 text-center">
			<span>GUCCI</span>
		</div>
		<div class="text-6xl font-black text-gray-400 text-center">
			<span>RAY-BAN</span>
		</div>
		<div class="text-6xl font-black text-gray-400 text-center">
			<span>PRADA</span>
		</div>
		<div class="text-6xl font-black text-gray-400 text-center">
			<span>ACUVUE</span>
		</div>
		<div class="text-6xl font-black text-gray-400 text-center">
			<span>ALCON</span>
		</div>
		<div class="text-6xl font-black text-gray-400 text-center">
			<span>OAKLEY</span>
		</div>
	 </div>
</section>
<Contactos />
<Footer />