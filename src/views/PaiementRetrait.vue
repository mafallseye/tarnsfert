<template>
  <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle=" Retrait d'argent-code" />
  </div>
  <div class="p-4 font-extrabold">
    <div
      class="p-4 w-full bg-white border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
    >
      <form>
        <div class="grid gap-6 mb-6 md:grid-cols-4">
          <div>
            <label
              for="expediteur"
              class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
              >code denvoi</label
            >
            <input
              type="text"
              id="expediteur"
              class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
              placeholder=""
              required=""
            />
          </div>

          <div>
            <label
              for="receveur"
              class="block mb-2 text-sm font-medium text-white-50 dark:text-gray-300"
              >Valider</label
            >
            <button
              type="button"
              @click="showTables()"
              class="py-2.5 px-8 mr-2 mb-2 text-sm font-medium text-cyan-700 focus:outline-none bg-white border border-cyan-700 hover:bg-cyan-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
            >
              Afficher
            </button>
          </div>
        </div>
      </form>
      <h5 class="mb-2 text-3xl font-bold text-gray-900 dark:text-white">
        Historique de transaction
      </h5>
      <p class="pb-10">Ceci est une liste des dernières transactions</p>
      <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
        <table
          v-if="showTable"
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
            <tr class="bg-white border-b dark:bg-gray-900 dark:border-gray-700">
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
                <label for="my-modal-3" class="">
                  <span
                    class="bg-cyan-100 text-cyan-700 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-cyan-200 dark:text-cyan-700"
                    >Valider</span
                  >
                </label>
              </td>
            </tr>
            <tr
              class="bg-gray-50 border-b dark:bg-gray-800 dark:border-gray-700"
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
                <label for="my-modal-3" class="">
                  <span
                    class="bg-cyan-100 text-cyan-700 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-cyan-200 dark:text-cyan-700"
                    >Valider</span
                  >
                </label>
              </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-900 dark:border-gray-700">
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
                <label for="my-modal-3" class="">
                  <span
                    class="bg-cyan-100 text-cyan-700 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-cyan-200 dark:text-cyan-700"
                    >Valider</span
                  >
                </label>
              </td>
            </tr>
            <tr
              class="bg-gray-50 border-b dark:bg-gray-800 dark:border-gray-700"
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
                <label for="my-modal-3" class="">
                  <span
                    class="bg-cyan-100 text-cyan-700 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-cyan-200 dark:text-cyan-700"
                    >Valider</span
                  >
                </label>
              </td>
            </tr>
            <tr>
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
                <label for="my-modal-3" class="">
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
    </div>
  </div>

  <!-- The button to open modal -->

  <!-- Put this part before </body> tag -->
  <input type="checkbox" id="my-modal-3" class="modal-toggle" />
  <div class="modal">
    <div class="modal-box relative">
      <label for="my-modal-3" class="absolute right-8 top-4">✕</label>
      <h3 class="text-lg font-bold border-b">Validation d'un retrait</h3>
       <div>
            <label for="montant" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Montant à payer</label>
            <input type="text" id="montant" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="$2235" required="">
        </div>
     <div>
            <label for="Benefice" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Bénéfice à additionner</label>
            <input type="text" id="Benefice" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="$22" required="">
        </div>
       <div>
            <label for="Prenom" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Prenom</label>
            <input type="text" id="Prenon" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Martin" required="">
        </div>
        <div>
            <label for="date" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Date et lieu de naissance</label>
            <input type="date" id="date" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="" required="">
        </div>
       <div>
            <label for="piéce" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Type de piéce</label>
            <input type="text" id="piéce" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="" required="">
        </div>
      <div>
            <label for="numero" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">N° de la piéce</label>
            <input type="text" id="numero" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="" required="">
        </div>
       <div>
            <label for="contact" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Contact</label>
            <input type="text" id="contact" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="" required="">
        </div>
      <div>
            <label for="addresse" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Addresse</label>
            <input type="text" id="addresse" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="" required="">
        </div>
      <div class="mt-4">
        <button
          type="button"
          class="w-full py-2.5 px-5 mr-2 mb-2 text-sm font-medium text-gray-900 focus:outline-none bg-cyan-700 rounded-lg border border-gray-200 hover:bg-cyan-700 hover:text-white-50 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
        >
          Valider les infos du retrait
        </button>
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

<style></style>
