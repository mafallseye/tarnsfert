<template>
  <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle=" Rapport de transactoin" />
  </div>

  <!-- <div class="overflow-x-auto relative">
        <div class="p-4 w-full  bg-white  border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700">
          
          <h5 class="mb-2 text-xl font-bold text-gray-900 dark:text-white" >Rapport  de transaction envoyé date du 12/12/2021 au 12/07/2022</h5>
          <p class="pb-10">Ceci est une liste des dernières transactions</p>
         <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
          <table  class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
              <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                  <tr>
                      <th scope="col" class="py-3 px-6">
                        
      TRANSACTION
                      </th>
                      <th scope="col" class="py-3 px-6">
                     DATE & Heure
                      </th>
                      <th scope="col" class="py-3 px-6">
                        Montant
                      </th>
                      <th scope="col" class="py-3 px-6">
                       Frais ret
                      </th>
                      <th scope="col" class="py-3 px-6">
                       Frais env
                      </th>
                      <th scope="col" class="py-3 px-6">
                        STATUS
                      </th>
                      <th scope="col" class="py-3 px-6">
                          Action
                      </th>
                  </tr>
              </thead>
              <tbody>
                  <tr class="bg-white border-b dark:bg-gray-900 dark:border-gray-700">
                      <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                      Paiement de Bonnie Green
                      </th>
                      <td class="py-4 px-6">
                     Apr 23 ,2021
                      </td>
                      <td class="py-4 px-6">
                         $2999
                      </td>
                      <td class="py-4 px-6">
                         $2
                      </td>
                      <td class="py-4 px-6">
                         $2
                      </td>
                      <td class="py-4 px-6">
                        <span class="bg-green-100 text-green-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-green-200 dark:text-green-900">Terminé</span>
                      </td>
                      <td class="py-4 px-6">
                            <label for="my-modal">
                              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
        <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
        <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
      </svg>
      
                            </label>
                      </td>
                     
                  </tr>
                  <tr class="bg-gray-50 border-b dark:bg-gray-800 dark:border-gray-700">
                      <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                      Remboursement du paiement au #00910
                      </th>
                      <td class="py-4 px-6">
                        Apr 23 ,2021
                      </td>
                      <td class="py-4 px-6">
                             $1999
                      </td>
                      <td class="py-4 px-6">
                             $19
                      </td>
                      <td class="py-4 px-6">
                             $19
                      </td>
                      <td class="py-4 px-6">
                       <span class="bg-green-100 text-green-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-green-200 dark:text-green-900">Terminé</span>
                      </td>
                     
                  </tr>
                  <tr class="bg-white border-b dark:bg-gray-900 dark:border-gray-700">
                      <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                         Échec du paiement de #087651
                      </th>
                      <td class="py-4 px-6">
                        Apr 23 ,2021
                      </td>
                      <td class="py-4 px-6">
                          $099
                        
                      </td>
                      <td class="py-4 px-6">
                          $99
                        
                      </td>
                      <td class="py-4 px-6">
                          $99
                        
                      </td>
                      <td class="py-4 px-6">
                         <span class="bg-red-100 text-red-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-red-200 dark:text-red-900">Suppprimé</span> 
                      </td>
                     
                  </tr>
                  <tr class="bg-gray-50 border-b dark:bg-gray-800 dark:border-gray-700">
                      <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                         Paiement de Jese Leos
                      </th>
                      <td class="py-4 px-6">
                       Apr 23 ,2021
                      </td>
                      <td class="py-4 px-6">
                        
                          $799
                      </td>
                      <td class="py-4 px-6">
                        
                          $79
                      </td>
                      <td class="py-4 px-6">
                        
                          $79
                      </td>
                      <td class="py-4 px-6">
                          <span class="bg-purple-100 text-purple-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-purple-200 dark:text-purple-900">En cours</span>
                      </td>
                     
                  </tr>
                  <tr>
                      <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                         Paiement de maxe
                      </th>
                      <td class="py-4 px-6">
                        Apr 23 ,2021
                      </td>
                      <td class="py-4 px-6">
                             $999
                      </td>
                      <td class="py-4 px-6">
                             $9
                      </td>
                      <td class="py-4 px-6">
                             $9
                      </td>
                      <td class="py-4 px-6">
                        <span class="bg-purple-100 text-purple-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-purple-200 dark:text-purple-900">EN cours</span>
                      </td>
                     
                  </tr>
              </tbody>
          </table>
      </div>
          <div class="justify-center items-center space-y-4 sm:flex sm:space-y-0 sm:space-x-4">
              
           
          </div>
      </div>
      </div> -->

  <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
    <div class="flex m-5 justify-between items-center pb-4">
      <div>
        <h1 class="text-2xl">Liste des transactions</h1>
      </div>
      <label for="table-search" class="sr-only">Search</label>
      <div class="relative">
        <div
          class="flex absolute inset-y-0 left-0 items-center pl-3 pointer-events-none"
        >
          <svg
            class="w-5 h-5 text-gray-500 dark:text-gray-400"
            aria-hidden="true"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </div>
        <input
          type="text"
          v-model="filter"
          id="table-search"
          class="block p-2 pl-10 w-80 text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
          placeholder="Search for items"
        />
      </div>
    </div>
    <div v-if="filteredRows.lenght === 0" class="mx-auto">
      <figure class="px-10 pt-10">
        <i class="fa-solid fa-users-slash text-2xl"></i>
      </figure>
      <div class="card-body items-center text-center">
        <h2 class="card-title">Aucun utilisateurs</h2>
      </div>
    </div>
    <table
      v-else
      class="w-full text-sm text-left text-gray-500 dark:text-gray-400"
    >
      <thead
        class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
      >
        <tr>
          <th scope="col" class="py-3 px-6" @click="sort('name')">
            TRANSACTION
          </th>
          <th scope="col" class="py-3 px-6" @click="sort('date')">
            DATE & Heure
          </th>
          <th scope="col" class="py-3 px-6" @click="sort('montant')">
            Montant
          </th>
          <th scope="col" class="py-3 px-6" @click="sort('fraisRetrait')">
            Frais ret
          </th>
          <th scope="col" class="py-3 px-6" @click="sort('fraisEnvoi')">
            Frais env
          </th>
          <th scope="col" class="py-3 px-6">STATUS</th>
          <th scope="col" class="py-3 px-6">Action</th>
        </tr>
      </thead>
      <tbody>
        <tr
          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700"
          v-for="item in filteredRows"
          :key="item"
        >
          <th
            scope="row"
            class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
          >
            {{ item.name }}
          </th>
          <td class="py-4 px-6">
            {{ item.date }}
          </td>
          <td class="py-4 px-6">
            {{ item.montant }}
          </td>
          <td class="py-4 px-6">
            {{ item.fraisRetrait }}
          </td>
          <td class="py-4 px-6">
            {{ item.friasEnvoi }}
          </td>
          <td class="py-4 px-6">
            <span
              class="bg-green-100 text-green-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-green-200 dark:text-green-900"
              >Terminé</span
            >
          </td>
          <td class="py-4 px-6">
            <label for="my-modal">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                />
              </svg>
            </label>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
  <VueTailwindPagination
    :current="currentPage"
    :total="total"
    :per-page="pageSize"
    @page-changed="currentPage = $event"
    text-before-input="Aller à la page"
    text-after-input="Aller"
  />

  <input type="checkbox" id="my-modal" class="modal-toggle" />
  <div class="modal justify-center items-center">
    <div
      id="my-modal"
      tabindex="-1"
      aria-hidden="true"
      class="justify-center items-center flex relative overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 w-full md:inset-0 h-modal md:h-full"
    >
      <div class="relative p-4 w-full max-w-xl h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <label
            for="my-modal"
            class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-800 dark:hover:text-white"
          >
            <svg
              aria-hidden="true"
              class="w-5 h-5"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span class="sr-only">Close modal</span>
          </label>
          <!-- Modal header -->
          <div class="py-4 px-6 rounded-t border-b dark:border-gray-600">
            <h3
              class="text-base font-semibold text-gray-900 lg:text-xl dark:text-white"
            >
              Transaction
            </h3>
          </div>
          <div class="py-1 px-6 rounded-t border-b dark:border-gray-600">
            <h3
              class="text-base font-semibold text-gray-900 lg:text-xl dark:text-white"
            >
              <button
                type="button"
                class="justify-center items-center w-full text-white bg-[#FF9119] hover:bg-[#FF9119]/80 focus:ring-4 focus:outline-none focus:ring-[#FF9119]/50 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:hover:bg-[#FF9119]/80 dark:focus:ring-[#FF9119]/40 mr-2 mb-2"
              >
                <svg
                  class="mr-2 -ml-1 w-4 h-4"
                  aria-hidden="true"
                  focusable="false"
                  data-prefix="fab"
                  data-icon="bitcoin"
                  role="img"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                >
                  <path
                    fill="currentColor"
                    d="M504 256c0 136.1-111 248-248 248S8 392.1 8 256 119 8 256 8s248 111 248 248zm-141.7-35.33c4.937-32.1-20.19-50.74-54.55-62.57l11.15-44.7-27.21-6.781-10.85 43.52c-7.154-1.783-14.5-3.464-21.8-5.13l10.93-43.81-27.2-6.781-11.15 44.69c-5.922-1.349-11.73-2.682-17.38-4.084l.031-.14-37.53-9.37-7.239 29.06s20.19 4.627 19.76 4.913c11.02 2.751 13.01 10.04 12.68 15.82l-12.7 50.92c.76 .194 1.744 .473 2.829 .907-.907-.225-1.876-.473-2.876-.713l-17.8 71.34c-1.349 3.348-4.767 8.37-12.47 6.464 .271 .395-19.78-4.937-19.78-4.937l-13.51 31.15 35.41 8.827c6.588 1.651 13.05 3.379 19.4 5.006l-11.26 45.21 27.18 6.781 11.15-44.73a1038 1038 0 0 0 21.69 5.627l-11.11 44.52 27.21 6.781 11.26-45.13c46.4 8.781 81.3 5.239 95.99-36.73 11.84-33.79-.589-53.28-25-65.99 17.78-4.098 31.17-15.79 34.75-39.95zm-62.18 87.18c-8.41 33.79-65.31 15.52-83.75 10.94l14.94-59.9c18.45 4.603 77.6 13.72 68.81 48.96zm8.417-87.67c-7.673 30.74-55.03 15.12-70.39 11.29l13.55-54.33c15.36 3.828 64.84 10.97 56.85 43.03z"
                  ></path>
                </svg>
                Rembourser
              </button>
            </h3>
          </div>
          <div class="py-1 px-6 rounded-t border-b dark:border-gray-600">
            <h3
              class="text-base font-semibold text-gray-900 lg:text-xl dark:text-white"
            >
              <button
                type="button"
                class="justify-center items-center w-full text-white bg-[#4285F4] hover:bg-[#4285F4]/90 focus:ring-4 focus:outline-none focus:ring-[#4285F4]/50 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-[#4285F4]/55 mr-2 mb-2"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="w-4 h-4 ml-1 mr-2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M6.72 13.829c-.24.03-.48.062-.72.096m.72-.096a42.415 42.415 0 0110.56 0m-10.56 0L6.34 18m10.94-4.171c.24.03.48.062.72.096m-.72-.096L17.66 18m0 0l.229 2.523a1.125 1.125 0 01-1.12 1.227H7.231c-.662 0-1.18-.568-1.12-1.227L6.34 18m11.318 0h1.091A2.25 2.25 0 0021 15.75V9.456c0-1.081-.768-2.015-1.837-2.175a48.055 48.055 0 00-1.913-.247M6.34 18H5.25A2.25 2.25 0 013 15.75V9.456c0-1.081.768-2.015 1.837-2.175a48.041 48.041 0 011.913-.247m10.5 0a48.536 48.536 0 00-10.5 0m10.5 0V3.375c0-.621-.504-1.125-1.125-1.125h-8.25c-.621 0-1.125.504-1.125 1.125v3.659M18 10.5h.008v.008H18V10.5zm-3 0h.008v.008H15V10.5z"
                  />
                </svg>

                Imprimer le recu
              </button>
            </h3>
          </div>
          <!-- Modal body -->
          <div class="">
            <ul class="">
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Caisse</span>
                    <span class="main">Administrateur</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Nom client</span>
                    <span class="main">Maxe</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Tel.Clint</span>
                    <span class="main">+2217777777</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">MOntant XOF</span>
                    <span class="main">100000fcfa</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Devise paiement</span>
                    <span class="main">Fcfa</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Montant paiement</span>
                    <span class="main">100000fcfa</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Frais mobile money</span>
                    <span class="main">-100</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Frais carte Bancaire</span>
                    <span class="main">0</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Frais Total</span>
                    <span class="main">-100</span>
                  </h3>
                </div>
              </li>
              <li class="m-2 bg-gray-600">
                <div
                  class="justify-center items-center text-white py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base text-white p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="text-white">Montant à recevoir</span>
                    <span class="main text-white">-99000XOF</span>
                  </h3>
                </div>
              </li>
              <li class="">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Ref</span>
                    <span class="main">c10140e5dc28091fd957</span>
                  </h3>
                </div>
              </li>
              <li class=" ">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Tel</span> <span class="main"></span>
                  </h3>
                </div>
              </li>
              <li class=" ">
                <div
                  class="justify-center items-center py-1 px-6 rounded-t border-b dark:border-gray-600"
                >
                  <h3
                    class="text-base p-1 text-gray-900 lg:text-md dark:text-white"
                  >
                    <span class="">Par</span>
                    <span class="main">PAY AXETATG</span>
                  </h3>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- <input type="checkbox" id="recu-modal" class="modal-toggle" />
<div class="modal ">
 
    

<div class="  modal-box relative p-4 w-11/12 max-w-4xl  bg-white  border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700">
   <label for="recu-modal" class="absolute right-8 top-4">✕</label>
   
    <h3 class="text-lg font-bold border-b text-center">Recu transfert d'argent</h3>
    
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Nom &prenom: maguette seye</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Code:C78GT45678HJ</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Addresse:Dakar</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Contact:221 77 777 77 77</h5>
   
    <div class=" space-y-4 sm:flex sm:space-y-0 sm:space-x-4 justify-center items-center ">
    
<div class="grid  rounded-lg border border-gray-200 shadow-sm dark:border-gray-700  md:grid-cols-2 w-full  max-w-9xl ">
    <figure class=" flex-col bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-r dark:bg-gray-800 dark:border-gray-700">
        <blockquote class="mx-auto mb-4 max-w-2xl text-gray-500 lg:mb-8 dark:text-gray-400">
            <h3 class="text-lg font-semibold bg-cyan-700 text-gray-900 dark:text-white text-center">Expéditeur</h3>
             <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Nom &prenom: maguette seye</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Code:C78GT45678HJ</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Addresse:Dakar</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Contact:221 77 777 77 77</h5>
        </blockquote>
        
    </figure>
    <figure class="flex-col   bg-white rounded-tr-lg border-b border-gray-200 dark:bg-gray-800 dark:border-gray-700">
           <blockquote class="mx-auto mb-4 max-w-2xl text-gray-500 lg:mb-8 dark:text-gray-400">
            <h3 class="text-lg font-semibold bg-cyan-700 text-gray-900 dark:text-white text-center">Receveur</h3>
             <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Nom &prenom: maguette seye</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Code:C78GT45678HJ</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Pays:Sénégal</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">ville:Dakar,Liberté 6</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Addresse:Dakar</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Contact:221 77 777 77 77</h5>
        </blockquote>
         
    </figure>

 
  
</div>
   

    </div>
       <h3 class="text-lg font-semibold bg-cyan-700 text-gray-900 dark:text-white text-center">Information de la transaction</h3>
             <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Monatant envoyé:$123988.00</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Frais de la transaction:$23456</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Montant à recevoir par le bénéficiaire:$2345879.000</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Numero de la transaction:22177777777</h5>
   <h5 class="mb-2 text-xl font-lg text-gray-900 dark:text-white">Date d'envoi:2022-07-12 22:26:44</h5>
</div>

 
</div> -->
</template>

<script>
import bradcrumb from "@/components/bradcrumb.vue";
import VueTailwindPagination from "@ocrv/vue-tailwind-pagination";
import "@ocrv/vue-tailwind-pagination/styles";

export default {
  components: {
    bradcrumb,
    VueTailwindPagination,
  },
  data() {
    return {
      showTable: false,
      pageSize: 3,
      total: 20,
      currentPage: 1,
      currentSort: "name",
      currentSortDir: "asc",
      partLenth: 10,
      showing: 1,
      filter: "",
      items: [
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de maxe",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "24$",
          friasEnvoi: "22$",
          status: "en cours",
        },
        {
          name: "Paiement de Ngoné",
          date: "Apr 23 ,2021",
          montant: "$2999999",
          fraisRetrait: "14$",
          friasEnvoi: "16$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
        {
          name: "Paiement de Bonnie Green",
          date: "Apr 23 ,2021",
          montant: "$2999",
          fraisRetrait: "2$",
          friasEnvoi: "2$",
          status: "terminé",
        },
      ],
    };
  },
  computed: {
    filteredRows() {
      return this.items
        .filter((row, index) => {
          const user = row.name.toString().toLowerCase();
          const uid = row.date.toString().toLowerCase();
          const category = row.montant.toString().toLowerCase();
          const searchTerm = this.filter.toLowerCase();

          return (
            user.includes(searchTerm) ||
            category.includes(searchTerm) ||
            uid.includes(searchTerm)
          );
        })
        .filter((row, index) => {
          let start = (this.currentPage - 1) * this.pageSize;
          let end = this.currentPage * this.pageSize;
          if (index >= start && index < end) return true;
        })
        .sort((a, b) => {
          let modifier = 1;
          if (this.currentSortDir === "desc") modifier = -1;
          if (a[this.currentSort] < b[this.currentSort]) return -1 * modifier;
          if (a[this.currentSort] > b[this.currentSort]) return 1 * modifier;
          return 0;
        });
    },
  },

  methods: {
    showTables() {
      this.showTable = !this.showTable;
    },
    nextPage() {
      console.log("next");
      if (this.currentPage * this.pageSize < this.items.length) {
        this.currentPage++;
      }
    },
    prevPage() {
      console.log("prev");
      if (this.currentPage > 1) {
        this.currentPage--;
      }
    },

    sort(s) {
      //if s == current sort, reverse
      if (s === this.currentSort) {
        this.currentSortDir = this.currentSortDir === "asc" ? "desc" : "asc";
      }
      this.currentSort = s;
    },
  },
};
</script>

<style>
.main {
  margin-left: 50%;
}
</style>
