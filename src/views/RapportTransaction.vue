<template>
     <div class="p-3 text-cyan-700 font-extrabold">
        <bradcrumb parentTitle="Accueil" subParentTitle=" Rapport de transactoin" />
      </div>
         <div class="p-4 font-extrabold">

            <div class="p-4 w-full  bg-white  border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700">
                 <form>
    <div class="grid gap-6 mb-6 md:grid-cols-4">
        <div>
            <label for="expediteur" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Date du(aaaa/mm/jj)</label>
            <input type="text" id="expediteur" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="12/12/2021" required="">
        </div>
       <div>
            <label for="phone1" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">au(aaaa/mm/jj)</label>
            <input type="tel" id="phone1" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="12/07/2022" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required="">
        </div>
        <div>
            <label for="receveur" class="block mb-2 text-sm font-medium text-white-50 dark:text-gray-300">Valider</label>
            <button type="button" @click=" showTables()" class="py-2.5 px-8 mr-2 mb-2 text-sm font-medium text-cyan-700 focus:outline-none bg-white  border border-cyan-700 hover:bg-cyan-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">Afficher</button>
        </div>
        </div>
        </form >
    <h5 class="mb-2 text-xl font-bold text-gray-900 dark:text-white" >Rapport  de transaction envoyé date du 12/12/2021 au 12/07/2022</h5>
    <p class="pb-10">Ceci est une liste des dernières transactions</p>
   <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
    <table v-if="showTable" class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
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
                      <label for="recu-modal">recu</label>
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
         </div>

<input type="checkbox" id="recu-modal" class="modal-toggle" />
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

 
</div>


</template>

<script>

import bradcrumb from '@/components/bradcrumb.vue';

export default {
components:{
    bradcrumb
},
data(){
    return{
        showTable:false
    }
},
methods:{
    showTables(){
        this.showTable=!this.showTable
    }
}
}
</script>

<style>

</style>