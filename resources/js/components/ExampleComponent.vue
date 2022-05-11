<template>
  <main class="font-medium text-gray-700 bg-white">
    <!-- header block -->
    <header
      class="flex justify-between max-w-screen-xl px-6 py-4 mx-auto lg:px-8 xl:px-4 lg:py-6"
    >
      <a href="#">
        <span class="sr-only">Labsdel</span>
        <svg class="h-8 mb-2" xmlns="http://www.w3.org/2000/svg" fill="none">
          <g>
            <title>Labsdel</title>
            <path
              id="svg_11"
              fill="#4f46e5"
              d="m29.31432,0c3.0357,0 5.4965,2.47421 5.4965,5.52632l0,23.94738c0,3.0521 -2.4608,5.5263 -5.4965,5.5263l-23.81788,0c-3.03559,0 -5.49644,-2.4742 -5.49644,-5.5263l0,-23.94738c0,-3.05211 2.46085,-5.52632 5.49644,-5.52632l23.81788,0zm-0.2882,23.741l-0.8026,0c-0.5922,0 -1.0724,-0.5517 -1.0724,-1.2322l0,-9.8659c0,-0.7641 0.5393,-1.3839 1.2044,-1.3839l0.6706,0c0.665,0 1.2043,0.6198 1.2043,1.3839l0,9.7143c0,0.7641 -0.5393,1.3838 -1.2043,1.3838zm-17.7176,4.8116l0.8025,0c0.665,0 1.2043,-0.6197 1.2043,-1.3839l0,-19.33747c0,-0.76416 -0.5393,-1.38386 -1.2043,-1.38386l-0.6706,0c-0.6651,0 -1.2044,0.6197 -1.2044,1.38386l0,19.48917c0,0.6804 0.4802,1.2322 1.0725,1.2322zm12.0792,0l-0.8026,0c-0.5922,0 -1.0723,-0.5518 -1.0723,-1.2322l0,-19.48917c0,-0.76416 0.5393,-1.38386 1.2043,-1.38386l0.6706,0c0.6651,0 1.2044,0.6197 1.2044,1.38386l0,19.33747c0,0.7642 -0.5393,1.3839 -1.2044,1.3839zm-17.71768,-4.8116l0.80257,0c0.66507,0 1.20436,-0.6197 1.20436,-1.3838l0,-9.7143c0,-0.7641 -0.53929,-1.3839 -1.20436,-1.3839l-0.67066,0c-0.66498,0 -1.20427,0.6198 -1.20427,1.3839l0,9.8659c0,0.6805 0.48021,1.2322 1.07236,1.2322zm12.07938,0.3914l-0.8026,0c-0.5922,0 -1.0724,-0.5517 -1.0724,-1.2323l0,-9.5901c0,-0.7644 0.5392,-1.3838 1.2043,-1.3838l0.6707,0c0.6649,0 1.2042,0.6194 1.2042,1.3838l0,9.4385c0,0.7642 -0.5393,1.3839 -1.2042,1.3839z"
              clip-rule="evenodd"
              fill-rule="evenodd"
            ></path>
            <text
              font-weight="bold"
              xml:space="preserve"
              text-anchor="start"
              font-family="'Josefin Sans'"
              font-size="24"
              stroke-width="0"
              id="svg_13"
              y="25.25"
              x="40.74999"
              fill="#374151"
            >
              Labsdel
            </text>
          </g>
        </svg>
      </a>
      <!-- <nav class="flex items-center space-x-4">
        <a
          href="#"
          class="inline-block px-5 py-2 font-semibold text-white rounded-lg bg-gradient-to-br from-indigo-600 to-indigo-700 hover:from-indigo-500 hover:to-indigo-700"
          >Sign in</a
        >
      </nav> -->
    </header>
    <!--/ header block -->

    <div wire:id="P4L4AlrlyCe3qkd9bJ6z" class="py-12 bg-gray-100 md:py-24">
      <div
        class="grid max-w-screen-xl px-6 mx-auto lg:px-8 xl:px-4 md:grid-cols-4 xl:grid-cols-5 gap-x-12 lg:gap-x-20"
      >
        <div class="self-center order-2 col-span-2 mt-12 md:order-1 md:mt-0">
          <h1
            class="mb-2 text-3xl font-bold text-gray-800 md:text-4xl lg:text-5xl md:mb-4 lg:mb-8"
          >
            Votre assistant en gestion commerciale
          </h1>
          <p class="mb-6 text-lg text-gray-600 xl:text-xl lg:mb-8 xl:mb-10">
            Labsdel est un logiciel de gestion pour suivre vos ventes, votre
            stock, vos services, vos clients et vos partenaires.
          </p>
          <div class="flex mb-6 space-x-4">
            <input
              type="text"
              placeholder="Entrez votre email..."
              class="flex-1 px-4 py-4 leading-none border border-gray-200 rounded-lg focus:outline-none"
            />
            <button
              class="inline-block px-5 py-2 font-semibold text-white rounded-lg focus:outline-none bg-gradient-to-br from-indigo-600 to-indigo-700 hover:from-indigo-500 hover:to-indigo-700"
            >
              Reclamez maintenant
            </button>
          </div>
        </div>
        <div class="order-1 col-span-2 md:order-2 xl:col-span-3">
          <VueSlickCarousel arrows dots autoplay>
            <img src="/img/1.png" class="rounded-lg shadow-2xl" alt="" />
            <img src="/img/2.png" class="rounded-lg shadow-2xl" alt="" />
            <img src="/img/3.png" class="rounded-lg shadow-2xl" alt="" />
            <img src="/img/4.png" class="rounded-lg shadow-2xl" alt="" />
            <img src="/img/5.png" class="rounded-lg shadow-2xl" alt="" />
          </VueSlickCarousel>
        </div>
      </div>
    </div>

    <!-- This example requires Tailwind CSS v2.0+ -->
    <div class="bg-white mb-10">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="lg:text-center">
          <p
            class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl"
          >
            Les fonctionnalités
          </p>
          <p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto">
            <span class="text-yellow-800">LABSdel.Gescom 1.0</span> facilité
            l’opérationnalisation en une touche répondant ainsi à besoin exprimé
            par l’utilisateur. Avec plusieurs ramifications, ces fonctionnalités
            sont multiples et voici les plus usuels
          </p>
        </div>

        <div class="mt-10">
          <dl
            class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10"
          >
            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/globe-alt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Gestion du stock (Produits et services)
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Groupes, familles d’articles, références, codifications, coût,
                quantités, qualité, etc.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/scale -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Gestion de vente et trésorerie
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                La facturation, caisse, banque,&nbsp;avances ou dettes
                clients/fournisseurs encaissement/décaissement.
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/lightning-bolt -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13 10V3L4 14h7v7l9-11h-7z"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Gestion de l’approvisionnement
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Stock d’alerte et traitement des commandes, prévention des
                ruptures de stock
              </dd>
            </div>

            <div class="relative">
              <dt>
                <div
                  class="absolute flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <!-- Heroicon name: outline/annotation -->
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"
                    ></path>
                  </svg>
                </div>
                <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                  Gestion de la relation client
                </p>
              </dt>
              <dd class="mt-2 ml-16 text-base text-gray-500">
                Carnet d’adresse pour les relances clients, les SAV, les
                livraisons
              </dd>
            </div>
          </dl>
        </div>
      </div>
    </div>

    <!-- pricing block -->
    <div
      class="max-w-screen-xl px-6 mx-auto mb-12 lg:px-8 xl:px-4 lg:mb-16 xl:mb-24"
    >
      <div class="mb-6 text-center md:mb-8">
        <h2
          class="mb-2 text-3xl font-bold text-gray-800 md:text-4xl lg:text-5xl md:mb-4"
        >
          Combien coûte t'il?
        </h2>
        <p class="text-lg text-gray-600 xl:text-xl">
          Pour les petites, moyennes et grandes entreprises.
        </p>
      </div>

      <div class="flex justify-center mb-8 md:mb-20 lg:mb-24">
        <nav
          class="inline-flex overflow-hidden text-sm bg-indigo-100 rounded-lg"
        >
          <button
            @click="period = 'annually'"
            :class="{
              'px-6 py-3 font-bold text-white focus:outline-none bg-gradient-to-br from-indigo-600 to-indigo-700 hover:from-indigo-500 hover:to-indigo-700':
                period == 'annually',
              'px-6 py-3 font-bold text-indigo-500 focus:outline-none hover:bg-indigo-50':
                period != 'annually',
            }"
          >
            Abonnement annuel
          </button>
          <button
            @click="period = 'lifetime'"
            :class="{
              'px-6 py-3 font-bold text-white focus:outline-none bg-gradient-to-br from-indigo-600 to-indigo-700 hover:from-indigo-500 hover:to-indigo-700':
                period != 'annually',
              'px-6 py-3 font-bold text-indigo-500 focus:outline-none hover:bg-indigo-50':
                period == 'annually',
            }"
          >
            Abonnement à vie
          </button>
        </nav>
      </div>
      <div
        class="mx-auto w-full max-w-screen-sm rounded-lg bg-gray-200 shadow my-12 p-4"
      >
        <form action="#" method="POST">
          <div class="shadow overflow-hidden sm:rounded-md">
            <div class="px-4 py-5 bg-white sm:p-6">
              <div class="grid grid-cols-6 gap-6">
                <div class="col-span-6">
                  <label
                    for="country"
                    class="block text-sm font-medium text-gray-700"
                    >Nombre de poste</label
                  >
                  <select
                    v-model="desk"
                    class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm"
                  >
                    <option value="2" selected>2 postes</option>
                    <option value="3-5">3 à 5 postes</option>
                    <option value="6-10">6 à 10 postes</option>
                    <option value="11-20">11 à 20 postes</option>
                    <option value="21+">21+ postes</option>
                  </select>
                </div>
              </div>
            </div>
          </div>
        </form>
      </div>

      <div class="grid items-start md:grid-cols-3 gap-x-8 gap-y-8">
        <div
          class="p-4 bg-white border-2 border-indigo-100 rounded-lg md:p-8 md:border-white"
        >
          <div class="flex items-baseline justify-between mb-4">
            <h4 class="text-xl font-bold lg:text-2xl">Classique</h4>
          </div>
          <div
            class="block px-5 py-3 mb-8 font-bold text-center border rounded-lg lg:px-8 bg-gradient-to-br hover:from-indigo-500 hover:to-indigo-700 hover:text-white"
          >
            {{ getPrice("classic") }}
          </div>
          <ul class="space-y-4 text-lg text-gray-600">
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de clients</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de fournisseurs</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Caisse ventes</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Tableau de bord détaillé</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de services</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de stock</span>
            </li>
            <li class="flex items-center space-x-2 opacity-25">
              <div class="w-6 h-6">&nbsp;</div>
              <span>Sauvegarde et disponibilité en ligne</span>
            </li>
            <li class="flex items-center space-x-2 opacity-25">
              <div class="w-6 h-6">&nbsp;</div>
              <span>Notification par mail</span>
            </li>
          </ul>
        </div>
        <div
          class="p-4 bg-white border-2 border-indigo-100 rounded-lg md:p-8 lg:py-12 md:transform md:-translate-y-10 md:-mb-10 md:shadow-md md:hover:shadow-xl md:transition-all md:duration-500 md:border"
        >
          <div class="flex items-baseline justify-between mb-4">
            <h4 class="text-xl font-bold lg:text-2xl">Excelium</h4>
          </div>
          <div
            class="block px-5 py-3 mb-8 font-bold text-center text-white border rounded-lg lg:px-8 bg-gradient-to-br from-indigo-600 to-indigo-700 hover:from-indigo-500 hover:to-indigo-700"
          >
            {{ getPrice("excelium") }}
          </div>
          <ul class="space-y-4 text-lg text-gray-600">
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de clients</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de fournisseurs</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Caisse ventes</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Tableau de bord détaillé</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de services</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de stock</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Notification par mail</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span
                >Sauvegarde et disponibilité en ligne <br />
                ({{ getFeaturePrice() }} / mois)</span
              >
            </li>
          </ul>
        </div>
        <div
          class="p-4 bg-white border-2 border-indigo-100 rounded-lg md:p-8 md:border-white"
        >
          <div class="flex items-baseline justify-between mb-4">
            <h4 class="text-xl font-bold lg:text-2xl">Premium</h4>
          </div>
          <div
            class="block px-5 py-3 mb-8 font-bold text-center border rounded-lg lg:px-8 bg-gradient-to-br hover:from-indigo-500 hover:to-indigo-700 hover:text-white"
          >
            {{ getPrice("premium") }}
          </div>
          <ul class="space-y-4 text-lg text-gray-600">
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de clients</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de fournisseurs</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Caisse ventes</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Tableau de bord détaillé</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de services</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span>Gestion de stock</span>
            </li>
            <li class="flex items-center space-x-2">
              <div class="w-6 h-6">
                <svg
                  class="text-green-500"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="3"
                    d="M5 13l4 4L19 7"
                  ></path>
                </svg>
              </div>
              <span
                >Sauvegarde et disponibilité en ligne <br />
                ({{ getFeaturePrice() }} / mois)</span
              >
            </li>
            <li class="flex items-center space-x-2 opacity-25">
              <div class="w-6 h-6">&nbsp;</div>
              <span>Notification par mail</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!--/ pricing block -->

    <!-- Livewire Component wire-end:P4L4AlrlyCe3qkd9bJ6z -->
    <!-- footer block -->
    <footer class="py-12 text-gray-600 bg-white xl:pb-24">
      <div class="max-w-screen-xl px-6 mx-auto mb-12 lg:px-8 xl:px-4 lg:mb-16">
        <svg class="h-8 mb-2" xmlns="http://www.w3.org/2000/svg" fill="none">
          <g>
            <title>Labsdel</title>
            <path
              id="svg_11"
              fill="#4f46e5"
              d="m29.31432,0c3.0357,0 5.4965,2.47421 5.4965,5.52632l0,23.94738c0,3.0521 -2.4608,5.5263 -5.4965,5.5263l-23.81788,0c-3.03559,0 -5.49644,-2.4742 -5.49644,-5.5263l0,-23.94738c0,-3.05211 2.46085,-5.52632 5.49644,-5.52632l23.81788,0zm-0.2882,23.741l-0.8026,0c-0.5922,0 -1.0724,-0.5517 -1.0724,-1.2322l0,-9.8659c0,-0.7641 0.5393,-1.3839 1.2044,-1.3839l0.6706,0c0.665,0 1.2043,0.6198 1.2043,1.3839l0,9.7143c0,0.7641 -0.5393,1.3838 -1.2043,1.3838zm-17.7176,4.8116l0.8025,0c0.665,0 1.2043,-0.6197 1.2043,-1.3839l0,-19.33747c0,-0.76416 -0.5393,-1.38386 -1.2043,-1.38386l-0.6706,0c-0.6651,0 -1.2044,0.6197 -1.2044,1.38386l0,19.48917c0,0.6804 0.4802,1.2322 1.0725,1.2322zm12.0792,0l-0.8026,0c-0.5922,0 -1.0723,-0.5518 -1.0723,-1.2322l0,-19.48917c0,-0.76416 0.5393,-1.38386 1.2043,-1.38386l0.6706,0c0.6651,0 1.2044,0.6197 1.2044,1.38386l0,19.33747c0,0.7642 -0.5393,1.3839 -1.2044,1.3839zm-17.71768,-4.8116l0.80257,0c0.66507,0 1.20436,-0.6197 1.20436,-1.3838l0,-9.7143c0,-0.7641 -0.53929,-1.3839 -1.20436,-1.3839l-0.67066,0c-0.66498,0 -1.20427,0.6198 -1.20427,1.3839l0,9.8659c0,0.6805 0.48021,1.2322 1.07236,1.2322zm12.07938,0.3914l-0.8026,0c-0.5922,0 -1.0724,-0.5517 -1.0724,-1.2323l0,-9.5901c0,-0.7644 0.5392,-1.3838 1.2043,-1.3838l0.6707,0c0.6649,0 1.2042,0.6194 1.2042,1.3838l0,9.4385c0,0.7642 -0.5393,1.3839 -1.2042,1.3839z"
              clip-rule="evenodd"
              fill-rule="evenodd"
            ></path>
            <text
              font-weight="bold"
              xml:space="preserve"
              text-anchor="start"
              font-family="'Josefin Sans'"
              font-size="24"
              stroke-width="0"
              id="svg_13"
              y="25.25"
              x="40.74999"
              fill="#374151"
            >
              Labsdel
            </text>
          </g>
        </svg>
      </div>
      <div
        class="flex flex-col items-center justify-between max-w-screen-xl px-6 mx-auto mt-16 space-y-4 lg:px-8 xl:px-4 md:flex-row lg:mt-20"
      >
        <div class="space-y-4 text-sm text-center md:space-y-1 md:text-left">
          <p>©2021 Labsdel.Tout droits reservés</p>
        </div>
        <a
          href="#"
          class="inline-block px-5 py-4 font-semibold text-white rounded-lg bg-gradient-to-br from-indigo-600 to-indigo-700 hover:from-indigo-500 hover:to-indigo-700 lg:px-8 md:transform md:-translate-y-2"
          >Commencer maintenant</a
        >
      </div>
      <div
        class="flex flex-col items-center justify-between max-w-screen-xl px-6 mx-auto mt-8 space-y-4 lg:px-8 xl:px-4 md:flex-row lg:mt-12"
      >
        <nav class="flex flex-wrap justify-center space-x-6"></nav>
        <nav class="flex items-center space-x-2">
          <a href="#" class="text-gray-500 hover:text-gray-600">
            <span class="sr-only">Facebook</span>
            <svg
              class="w-6 h-6"
              aria-hidden="true"
              fill="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                fill-rule="evenodd"
                d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
          <a href="#" class="text-gray-500 hover:text-gray-600">
            <span class="sr-only">Instagram</span>
            <svg
              class="w-6 h-6"
              aria-hidden="true"
              fill="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                fill-rule="evenodd"
                d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
          <a href="#" class="text-gray-500 hover:text-gray-600">
            <span class="sr-only">Twitter</span>
            <svg
              class="w-6 h-6"
              aria-hidden="true"
              fill="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
              ></path>
            </svg>
          </a>
        </nav>
      </div>
    </footer>
    <!--/ footer block -->
  </main>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
export default {
  components: { VueSlickCarousel },
  /* head() {
    return {
      title: "Labsdel | Votre assistant en gestion commerciale.",
    };
  }, */
  data() {
    return {
      settings: {
        arrows: true,
        dots: true,
      },
      period: "lifetime",
      cloud: false,
      mail: false,
      desk: "2",
    };
  },
  methods: {
    getPrice(type = "classic") {
      if (this.period == "annually") {
        switch (type) {
          case "classic":
            switch (this.desk) {
              case "2":
                return "70 000 FCFA";
                break;
              case "3-5":
                return "100 000 FCFA";
                break;
              case "6-10":
                return "150 000 FCFA";
                break;
              case "11-20":
                return "240 000 FCFA";
                break;
              case "21+":
                return "600 000 FCFA";
                break;

              default:
                return "70 000 FCFA";
                break;
            }

          case "premium":
            switch (this.desk) {
              case "2":
                return "80 000 FCFA";
                break;
              case "3-5":
                return "110 000 FCFA";
                break;
              case "6-10":
                return "170 000 FCFA";
                break;
              case "11-20":
                return "260 000 FCFA";
                break;
              case "21+":
                return "800 000 FCFA";
                break;

              default:
                return "80 000 FCFA";
                break;
            }
          case "excelium":
            switch (this.desk) {
              case "2":
                return "90 000 FCFA";
                break;
              case "3-5":
                return "120 000 FCFA";
                break;
              case "6-10":
                return "200 000 FCFA";
                break;
              case "11-20":
                return "300 000 FCFA";
                break;
              case "21+":
                return "1 000 000 FCFA";
                break;

              default:
                return "1 000 000 FCFA";
                break;
            }
          default:
            return "$49.99";
        }
      } else {
        switch (type) {
          case "classic":
            switch (this.desk) {
              case "2":
                return "350 000 FCFA";
                break;
              case "3-5":
                return "500 000 FCFA";
                break;
              case "6-10":
                return "750 000 FCFA";
                break;
              case "11-20":
                return "1 200 000 FCFA";
                break;
              case "21+":
                return "3 000 000 FCFA";
                break;

              default:
                return "3 000 000 FCFA";
                break;
            }

          case "premium":
            switch (this.desk) {
              case "2":
                return "400 000 FCFA";
                break;
              case "3-5":
                return "550 000 FCFA";
                break;
              case "6-10":
                return "850 000 FCFA";
                break;
              case "11-20":
                return "1 300 000 FCFA";
                break;
              case "21+":
                return "4 000 000 FCFA";
                break;

              default:
                return "4 000 000 FCFA";
                break;
            }
          case "excelium":
            switch (this.desk) {
              case "2":
                return "450 000 FCFA";
                break;
              case "3-5":
                return "600 000 FCFA";
                break;
              case "6-10":
                return "1 000 000 FCFA";
                break;
              case "11-20":
                return "1 500 000 FCFA";
                break;
              case "21+":
                return "5 000 000 FCFA";
                break;

              default:
                return "5 000 000 FCFA";
                break;
            }
          default:
            return "$49.99";
        }
      }
    },
    getFeaturePrice() {
      switch (this.desk) {
        case "2":
          return "5 000 FCFA";
          break;
        case "3-5":
          return "10 000 FCFA";
          break;
        case "6-10":
          return "15 000 FCFA";
          break;
        case "11-20":
          return "20 000 FCFA";
          break;
        case "21+":
          return "50 000 FCFA";
          break;

        default:
          return "50 000 FCFA";
          break;
      }
    },
  },
};
</script>

