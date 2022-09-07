<template>
 
  

      <!-- content -->
      <div class="p-3 text-cyan-700 font-extrabold">
        <bradcrumb parentTitle="Accueil" subParentTitle="Rechargement" />
            <div class="p-4 font-extrabold">
      <div class="p-4 w-full  bg-white  border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700">
    <h5 class="mb-2 text-3xl font-bold text-gray-900 dark:text-white">Rechargement</h5>
    <!-- <p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">Stay up to date and move work forward with Flowbite on iOS &amp; Android. Download the app today.</p> 
    -->
     <form>
            <div class="grid gap-6 mb-6 md:grid-cols-3">
              <div>
                <label
                  for="email"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                  >email client</label
                >
                <input
                  type="email"
                  id="email"
                  class="bg-white-50 border border-cyan-700 text-black text-sm focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                  placeholder="name@axe-tag.fr"
                  required
                />
              </div>
              <div>
                <label
                  for="montant"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                  >Montant</label
                >
                <input
                  type="text"
                  id="montant"
                  class="bg-white-50 border border-cyan-700 text-black text-sm focus:ring-black-500 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                  placeholder="$56478"
                  required
                />
              </div>
              <div>
                <label
                  for="Afficher"
                  class="block mb-2 text-sm font-medium text-black-900 dark:text-black-300"
                  >Valider:</label
                >
                <button @click="showText=!showText"
                  type="button"
                  class="py-2.5 px-5 mr-2 mb-2 text-sm font-medium text-black-900 focus:outline-none bg-white border border-cyan-700 hover:bg-cyan-700 hover:text-white focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
                >
                  Afficher
                </button>
              </div>
            </div>
            <div class=" " v-if="showText">
              <p>email:mseye@gmail.com</p>
              <p>nom:seye</p>
              <p>prenom:max</p>
              <p>n°compte:1234567</p>
              <p>   solde:$34567432</p>
            </div>
          </form>
          <div class="flex">
           
          </div>
    </div>
    </div>
        <div class="p-4 font-extrabold">
      <div class="p-4 w-full  bg-white  border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700">
   <div
                  class="breadcrumb flex items-end border-b border-gray-300 pb-4 mb-6"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-6 w-6"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    stroke-width="2"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15"
                    />
                  </svg>
                  <p class="text-xl ml-2 font-semibold dark:text-white">
                    Derniére rechargement effectuer
                  </p>
                </div>
     <div
              class="p-4 w-full bg-white   shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
            >
              <div class="flex-1 items-center justify-center">
               

                <div class="overflow-x-auto relative">
                  <table
                    class="w-full text-sm text-left text-gray-500 dark:text-gray-400"
                  >
                    <thead
                      class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
                    >
                      <tr>
                        <th scope="col" class="py-3 px-6">N°</th>
                        <th scope="col" class="py-3 px-6">client</th>
                        <th scope="col" class="py-3 px-6">Montant</th>
                        <th scope="col" class="py-3 px-6">Date</th>
                        <th scope="col" class="py-3 px-6">Code</th>
                        <th scope="col" class="py-3 px-6">Commentaire</th>
                        <th scope="col" class="py-3 px-6">Nouveau solde</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr
                        class="bg-white border-b dark:bg-gray-800 dark:border-gray-700"
                      >
                        <td class="py-4 px-6">1</td>
                        <td class="py-4 px-6">name@axe-tag.fr</td>
                        <td class="py-4 px-6">$2999</td>

                        <td class="py-4 px-6">10/10/2022</td>
                        <td class="py-4 px-6">c456NB</td>
                        <td class="py-4 px-6">Solde avant rech:$1999</td>

                        <td
                          scope="row"
                          class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                        >
                          $100.000
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
            </div>
    </div>
    </div>

  
      </div>
  
  <div>
 
  </div>
</template>

<script>
// @ is an alias to /src



import bradcrumb from "@/components/bradcrumb.vue";

import { ref } from "vue";

export default {
  name: "HomeView",
  components: {
  
    bradcrumb,
   
  },
  setup() {
    const isLoading = ref(false);
    return {
      isLoading,
    };
  },
  data(){
return{
showText:false
}
  },
  methods: {
    onSubmit() {
      this.isLoading = true;
      console.log("loading");
      setTimeout(() => {
        this.isLoading = false;
        this.$router.push("/compteVerifier");
      }, 1000);
    },
  },
};
</script>
<style>
.left {
  float: left;
  width: 48%;
}
.ml {
  margin-left: 35%;
}
</style>
