<template>
  <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle=" Retrait d'argent-code" />
  </div>

  <div
    class="m-1 p-4 text-center bg-white border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
  >
    <h5 class="mb-2 text-xl font-bold text-gray-900 dark:text-white">
      Veuillez choisir votre mode de paiement
    </h5>

    <div class="justify-center items-center sm:flex sm:space-y-0 sm:space-x-4">
      <div
        class="left w-40 h-40 bg-white border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="    " src="@/assets/orange1.png" alt="" />
        </a>

        <div class="p-5">
          <label for="my-modal" class="">Orange money</label>
        </div>
      </div>
      <div
        class="left w-40 h-40 bg-white border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="   " src="@/assets/mtn.jpg" alt="" />
        </a>
        <div class="p-5">
          <label for="my-modal" class="">mtn money</label>
        </div>
      </div>
      <div
        class="left h-40 w-40 bg-white border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="h-20" src="@/assets/wave.jpg" alt="" />
        </a>
        <div class="p-5">
          <label for="my-modal" class="">Wave money</label>
        </div>
      </div>
     
      <div
        class="left h-40 w-40 bg-white border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700"
      >
      <label for="my-modal" class="ml-6 mb-10">
        <a href="#">
          <img class="cursor-pointer  " src="@/assets/ecobank.jpg" alt="" />
        </a>
        <p>Ecobank</p>
        </label>
        <!-- <div class="p-5">
          <label for="my-modal" class="ml-6 mb-10">Ecobank</label>
        </div> -->
      </div>
  
      <div
        class="left w-40 h-40 bg-white border border-gray-200 shadow-md dark:bg-gray-800 dark:border-gray-700"
      >
        <a href="#">
          <img class="" src="@/assets/PAY.png" alt="" />
        </a>
        <div class="p-5">
         
        </div>
      </div>
    </div>
  </div>

  <!-- The button to open modal -->

  <!-- Put this part before </body> tag -->
  <input type="checkbox" id="my-modal" class="modal-toggle" />
  <div class="modal justify-center items-center">
    <div
      id="my-modal"
      tabindex="-1"
      aria-hidden="true"
      class="justify-center items-center flex relative overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 w-full md:inset-0 h-modal md:h-full"
    >
      <div class="relative p-4 w-full max-w-md h-full md:h-auto">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <label
            for="my-modal"
            class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-800 dark:hover:text-white"
            data-modal-toggle="crypto-modal"
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
          <!-- Modal body -->
          <div class="p-6">
            <p class="text-sm font-normal text-gray-500 dark:text-gray-400">
              Veuillez entrez le montant à récupérer et le code de transaction
            </p>
            <ul class="my-4 space-y-3">
              <li>
                <div>
                  <label
                    for="expediteur"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Montant(Min..675.00FCA):</label
                  >
                  <input
                    type="text"
                    id="expediteur"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="expediteur"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >code d'envoi/nuemro de compte jeton:</label
                  >
                  <input
                    type="text"
                    id="expediteur"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <button
                    type="button"
                    class="w-full py-2.5 px-8 mr-2 mb-2 text-sm font-medium text-white focus:outline-none bg-cyan-700 border border-cyan-700 hover:bg-cyan-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
                  >
                    <label for="table-modal" class=""> Afficher</label>
                  </button>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <input type="checkbox" id="my-modal" class="modal-toggle" />
  <div class="modal justify-center items-center">
    <div
      id="my-modal"
      tabindex="-1"
      aria-hidden="true"
      class="justify-center items-center flex relative overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 w-full md:inset-0 h-modal md:h-full"
    >
      <div class="relative p-4 w-full max-w-md h-full md:h-auto">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <label
            for="my-modal"
            class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-800 dark:hover:text-white"
            data-modal-toggle="crypto-modal"
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
              Connect wallet
            </h3>
          </div>
          <!-- Modal body -->
          <div class="p-6">
            <p class="text-sm font-normal text-gray-500 dark:text-gray-400">
              Connect with one of our available wallet providers or create a new
              one.
            </p>
            <ul class="my-4 space-y-3">
              <li>
                <div>
                  <label
                    for="expediteur"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Montant(Min..675.00FCA):</label
                  >
                  <input
                    type="text"
                    id="expediteur"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="expediteur"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >code d'envoi/nuemro de compte jeton:</label
                  >
                  <input
                    type="text"
                    id="expediteur"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <button
                    type="button"
                    class="w-full py-2.5 px-8 mr-2 mb-2 text-sm font-medium text-white focus:outline-none bg-cyan-700 border border-cyan-700 hover:bg-cyan-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
                  >
                    <label for="table-modal" class=""> Afficher</label>
                  </button>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <input type="checkbox" id="table-modal" class="modal-toggle" />
  <div class="modal justify-center items-center">
    <div
      id="table-modal"
      tabindex="-1"
      aria-hidden="true"
      class="justify-center items-center flex relative overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 w-full md:inset-0 h-modal md:h-full"
    >
      <div class="relative p-4 w-full h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <label
            for="table-modal"
            class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-800 dark:hover:text-white"
            data-modal-toggle="crypto-modal"
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
              Retrait en attente de validation
            </h3>
          </div>
          <!-- Modal body -->
          <div class="p-6">
            <p class="text-sm font-normal text-gray-500 dark:text-gray-400">
              Connect with one of our available wallet providers or create a new
              one.
            </p>
            <ul class="my-4 space-y-3">
              <li>
                <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
                  <table
                    class="w-full text-sm text-left text-gray-500 dark:text-gray-400"
                  >
                    <thead
                      class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
                    >
                      <tr>
                        <th scope="col" class="py-3 px-6">Expediteur</th>
                        <th scope="col" class="py-3 px-6">Cont Expediteur</th>

                        <th scope="col" class="py-3 px-6">Receveur</th>
                        <th scope="col" class="py-3 px-6">Cont receveur</th>
                        <th scope="col" class="py-3 px-6">Montant</th>
                        <th scope="col" class="py-3 px-6">Code d'envoi</th>
                        <th scope="col" class="py-3 px-6">Date d'envoi</th>
                        <th scope="col" class="py-3 px-6">Action</th>
                        <!-- <th scope="col" class="py-3 px-6">
                    Action
                </th> -->
                      </tr>
                    </thead>
                    <tbody>
                      <tr
                        class="bg-white border-b dark:bg-gray-900 dark:border-gray-700"
                      >
                        <th
                          scope="row"
                          class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                        >
                          Martin
                        </th>
                        <td class="py-4 px-6">229234342</td>
                        <td class="py-4 px-6">Martine</td>
                        <td class="py-4 px-6">2298765645</td>
                        <td class="py-4 px-6">$2235</td>
                        <td class="py-4 px-6">C78GFRDE</td>
                        <td class="py-4 px-6">12/12/2022</td>
                        <td class="py-4 px-6">
                          <label for="valid-modal" class="">
                            <span
                              class="bg-cyan-100 text-cyan-700 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-cyan-200 dark:text-cyan-700"
                              >Valider</span
                            >
                          </label>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </div>

                <div>
                  <!-- <button
              type="button"
            
              class=" w-full py-2.5 px-8 mr-2 mb-2 text-sm font-medium text-white focus:outline-none bg-cyan-700 border border-cyan-700 hover:bg-cyan-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
            >
              Afficher
            </button> -->
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>

  <input type="checkbox" id="valid-modal" class="modal-toggle" />
  <div class="modal justify-center items-center">
    <div
      id="valid-modal"
      tabindex="-1"
      aria-hidden="true"
      class="justify-center items-center flex relative overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 w-full md:inset-0 h-modal md:h-full"
    >
      <div class="relative p-4 w-full max-w-md h-full md:h-auto">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
          <label
            for="valid-modal"
            class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-800 dark:hover:text-white"
            data-modal-toggle="crypto-modal"
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
              Connect wallet
            </h3>
          </div>
          <!-- Modal body -->
          <div class="p-6">
            <p class="text-sm font-normal text-gray-500 dark:text-gray-400">
              Connect with one of our available wallet providers or create a new
              one.
            </p>
            <ul class="my-4 space-y-3">
              <li>
                <div>
                  <label
                    for="montant"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Montant à payer</label
                  >
                  <input
                    type="text"
                    id="montant"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder="$2235"
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="Benefice"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Bénéfice à additionner</label
                  >
                  <input
                    type="text"
                    id="Benefice"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder="$22"
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="Prenom"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Prenom</label
                  >
                  <input
                    type="text"
                    id="Prenon"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder="Martin"
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="date"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Date et lieu de naissance</label
                  >
                  <input
                    type="date"
                    id="date"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="piéce"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Type de piéce</label
                  >
                  <input
                    type="text"
                    id="piéce"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="numero"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >N° de la piéce</label
                  >
                  <input
                    type="text"
                    id="numero"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="contact"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Contact</label
                  >
                  <input
                    type="text"
                    id="contact"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div>
                  <label
                    for="addresse"
                    class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                    >Addresse</label
                  >
                  <input
                    type="text"
                    id="addresse"
                    class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder=""
                    required=""
                  />
                </div>
              </li>
              <li>
                <div class="mt-4">
                  <button
                    type="button"
                    class="w-full py-2.5 px-5 mr-2 mb-2 text-sm font-medium text-gray-900 focus:outline-none bg-cyan-700 rounded-lg border border-gray-200 hover:bg-cyan-700 hover:text-white-50 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
                  >
                    Valider les infos du retrait
                  </button>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import bradcrumb from "@/components/bradcrumb.vue";

export default {
  components: {
    bradcrumb,
  },
  data() {
    return {
      showTable: false,
    };
  },
  methods: {
    showTables() {
      this.showTable = !this.showTable;
    },
  },
};
</script>

<style>
.left {
  float: left;
  margin: 5px;
}

</style>
