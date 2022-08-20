<template>
  <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle="Transactoin" />
  </div>

  <div
    class="p-4 w-full bg-white rounded-lg border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
  >
    <form>
      <div class="grid gap-6 mb-6 md:grid-cols-4">
        <div>
          <label
            for="expediteur"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
            >Expéditeur</label
          >
          <input
            type="text"
            id="expediteur"
            class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="expiditeur"
            required=""
          />
        </div>
        <div>
          <label
            for="phone1"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
            >Contact éxpéditeur</label
          >
          <input
            type="tel"
            id="phone1"
            class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="123-45-678"
            pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
            required=""
          />
        </div>
        <div>
          <label
            for="receveur"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
            >Receveur</label
          >
          <input
            type="text"
            id="receveur"
            class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ringcyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="Receveur"
            required=""
          />
        </div>
      </div>
    </form>
    <h5 class="mb-2 text-3xl font-bold text-gray-900 dark:text-white">
      Historique de transaction
    </h5>
    <p class="pb-10">Ceci est une liste des dernières transactions</p>
    <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
      <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
        <thead
          class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
        >
          <tr>
            <th scope="col" class="py-3 px-6">TRANSACTION</th>
            <th scope="col" class="py-3 px-6">DATE & Heure</th>
            <th scope="col" class="py-3 px-6">Montant</th>
            <th scope="col" class="py-3 px-6">STATUS</th>
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
              Paiement de Bonnie Green
            </th>
            <td class="py-4 px-6">Apr 23 ,2021</td>
            <td class="py-4 px-6">$2999</td>
            <td class="py-4 px-6">
              <span
                class="bg-green-100 text-green-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-green-200 dark:text-green-900"
                >Terminé</span
              >
            </td>
          </tr>
          <tr class="bg-gray-50 border-b dark:bg-gray-800 dark:border-gray-700">
            <th
              scope="row"
              class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
            >
              Remboursement du paiement au #00910
            </th>
            <td class="py-4 px-6">Apr 23 ,2021</td>
            <td class="py-4 px-6">$1999</td>
            <td class="py-4 px-6">
              <span
                class="bg-green-100 text-green-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-green-200 dark:text-green-900"
                >Terminé</span
              >
            </td>
          </tr>
          <tr class="bg-white border-b dark:bg-gray-900 dark:border-gray-700">
            <th
              scope="row"
              class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
            >
              Échec du paiement de #087651
            </th>
            <td class="py-4 px-6">Apr 23 ,2021</td>
            <td class="py-4 px-6">$99</td>
            <td class="py-4 px-6">
              <span
                class="bg-red-100 text-red-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-red-200 dark:text-red-900"
                >Suppprimé</span
              >
            </td>
          </tr>
          <tr class="bg-gray-50 border-b dark:bg-gray-800 dark:border-gray-700">
            <th
              scope="row"
              class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
            >
              Paiement de Jese Leos
            </th>
            <td class="py-4 px-6">Apr 23 ,2021</td>
            <td class="py-4 px-6">$799</td>
            <td class="py-4 px-6">
              <span
                class="bg-purple-100 text-purple-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-purple-200 dark:text-purple-900"
                >En cours</span
              >
            </td>
          </tr>
          <tr>
            <th
              scope="row"
              class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
            >
              Paiement de maxe
            </th>
            <td class="py-4 px-6">Apr 23 ,2021</td>
            <td class="py-4 px-6">$999</td>
            <td class="py-4 px-6">
              <span
                class="bg-purple-100 text-purple-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-purple-200 dark:text-purple-900"
                >EN cours</span
              >
            </td>
          </tr>
        </tbody>
      </table>
    </div>
    <div
      class="justify-center items-center space-y-4 sm:flex sm:space-y-0 sm:space-x-4"
    ></div>
  </div>
</template>

<script>
import bradcrumb from "@/components/bradcrumb.vue";
export default {
  components: {
    bradcrumb,
  },
};
</script>

<style></style>
