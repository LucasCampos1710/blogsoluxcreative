<template>
  <Layout>
    <div class="hero container-inner mx-auto py-16">
      <div class="mt-8 sm:mt-0">
        <g-image
          src="../../static/mind_map.svg"
          width="800"
          alt="Logo Solux Omni"
          class="mx-auto sm:mx-0"
        />
      </div>
    </div>
    <!-- end hero -->

    <div class="container-inner mx-auto">
      <h2 class="text-green-800 font-bold mb-6 text-lg">Conceito OMNI</h2>
      <div class="container-inner mx-auto mb-2">
        <p class="text-lg sm:text-xl">
          A palavra Omni vem do latim ominis/omne e significa todo, inteiro, de todo tipo.
          Portanto, este conceito nada mais é que estar presente em todos os canais que o cliente esteja, mas de uma forma integrada e concisa, simples, objetiva.
        </p>
      </div>
      <div class="container-inner mx-auto mb-2">
        <p class="text-lg sm:text-xl">
          O Omnichannel é uma tendência do varejo que se baseia na convergência de todos os canais utilizados por uma empresa. Trata-se da possibilidade de fazer com que
          o consumidor não veja diferença entre o mundo online e o offline. O omnichannel integra lojas físicas, virtuais e compradores. Pensando nisso, a Solux Omni foi
          criada a partir da Solux Creative, com a intenção de atender seus clientes e parceiros, desde a contratação de serviços de Contabilidade, Sistema ERP, Loja Virtual,
          Marketing Digital, Cursos e Treinamentos, Equipamentos de Tecnologia, Serviços e Marketing, tudo sem precisar falar com várias empresas ou prestadores de serviços.
        </p>
      </div>
      <div class="container-inner mx-auto mb-2">
        <p
          class="text-lg sm:text-xl"
        >A Solux Omni veio para facilitar o entendimento e a contratação das parcerias tudo dentro da mesma plataforma.</p>
      </div>
      <!-- Logos parceiros da solux Omni -->
      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/mind_map.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/code_review.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div
        class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative"
      >
        <h2 class="font-bold mb-6" id="projects">Alguns de nossos clientes:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div>
              <a href="https://www.centralaviamentos.com.br">Central Aviamentos</a>
            </div>
            <div
              class="text-lg text-gray-600"
            >Loja especializada em linhas e produtos para costura e artesanato, uma das maiores da região de caraguatuba.</div>
          </li>
          <li class="checkmark">
            <div>
              <a href="https://www.tribosurf.com.br">Tribo Surf</a>
            </div>
            <div
              class="text-lg text-gray-600"
            >Loja especializada em pranchas e equipamentos para Surf, localizada em Ubatuba com fabricação propria das prachas utilizanda sua marca Tribo Surf e atende cliente do Brasil.</div>
          </li>
          <li class="checkmark">
            <div>
              <a href="https://www.bluelord.com.br">Blue Lord</a>
            </div>
            <div
              class="text-lg text-gray-600"
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui ab nam animi iure nemo exercitationem a, eius non culpa itaque!</div>
          </li>
          <li class="checkmark">
            <div>
              <a href="https://www.lojayumipesca.com.br">Yumi Pesca</a>
            </div>
            <div
              class="text-lg text-gray-600"
            >Loja especializada em artigos para pesca, camping e caça, a Yumi Pesca conta com parceria com o club Frete Pesca para pescas em alto mar.</div>
          </li>
          <li class="checkmark">
            <div>
              <a href="https://www.lojacentraldoces.com.br">Central Doces</a>
            </div>
            <div
              class="text-lg text-gray-600"
            >Loja especializada em vendas de produtos para confeitaria como chocolates, formas e moldes entre outros.</div>
          </li>
        </ul>
      </div>
      <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-1" id="about">Alexandre Bavoso</h2>
        <h4 class="font-medium mb-6" id="about">Comercial</h4>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div>
            <g-image
              src="../../static/avatar.jpg"
              alt="avatar"
              class="w-32 h-32 rounded-full mb-8 lg:mb-0"
            />
          </div>
          <div
            class="flex-1 text-lg sm:text-xl ml-6"
          >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum quae architecto minus molestias iusto ducimus fuga quo quia libero dignissimos, fugiat modi assumenda debitis laboriosam.</div>
        </div>
      </div>
      <!-- end get-to-know me -->

      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-1" id="about">Lucas Campos</h2>
        <h4 class="font-medium mb-6" id="about">Suporte e Desenvolvimento</h4>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div>
            <g-image
              src="../../static/avatar.jpg"
              alt="avatar"
              class="w-32 h-32 rounded-full mb-8 lg:mb-0"
            />
          </div>
          <div
            class="flex-1 text-lg sm:text-xl ml-6"
          >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum quae architecto minus molestias iusto ducimus fuga quo quia libero dignissimos, fugiat modi assumenda debitis laboriosam.</div>
        </div>
      </div>
      <!-- end get-to-know me -->

      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-1" id="about">Monique Bavoso</h2>
        <h4 class="font-medium mb-6" id="about">Suporte</h4>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div>
            <g-image
              src="../../static/avatar.jpg"
              alt="avatar"
              class="w-32 h-32 rounded-full mb-8 lg:mb-0"
            />
          </div>
          <div
            class="flex-1 text-lg sm:text-xl ml-6"
          >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum quae architecto minus molestias iusto ducimus fuga quo quia libero dignissimos, fugiat modi assumenda debitis laboriosam.</div>
        </div>
      </div>
      <!-- end get-to-know me -->
    </div>
  </Layout>
</template>


<script>
export default {
  metaInfo: {
    title: "Solux Omni"
  }
};
</script>
                                