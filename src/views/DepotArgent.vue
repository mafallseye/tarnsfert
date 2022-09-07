<template>
  
 <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle="Envoi-D'argent" />
  </div>
     <div class="p-4 font-extrabold">
      <div class="p-4 w-full  bg-white  border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700">
    <h5 class="mb-2 text-xl font-bold text-gray-900 dark:text-white">Information de l'expéditeur</h5>
    <!-- <p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">Stay up to date and move work forward with Flowbite on iOS &amp; Android. Download the app today.</p> 
    -->
    
<form>
    <div class="grid gap-6 mb-6 md:grid-cols-4">
        <div>
            <label for="expediteur" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Nom</label>
            <input type="text" id="expediteur" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="expiditeur" required="">
        </div>
         <div>
             <label for="expéditeur1" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Prenom</label>
             <input type="text" id="expéditeur1" class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ringcyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Receveur" required="">
         </div>  
       <div>
            <label for="phone1" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Téléphone</label>
            <input type="tel" id="phone1" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required="">
        </div>
        <div>
            <label for="date" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Date de naissance</label>
            <input type="date" id="date" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required="">
        </div>
       
       
        <div>
            <label for="nationalité" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Nationalité</label>
            <input type="text" id="nationalité" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Destinantion" required="">
        </div>
        <div>
            <label for="ville" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">ville</label>
            <input type="text" id="ville" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="FCA" required="">
        </div>
        <div>
            <label for="pays" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Pays</label>
            <input type="text" id="pays" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="FCA" required="">
        </div>
        <div>
            <label for="piéce" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Piéce à fournir</label>
            <input type="text" id="piéce" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="FCA" required="">
        </div>
           <div>
            <label for="numero" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Numéro de la piéce</label>
            <input type="text" id="numero" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="C75FM87NG" required="">
        </div>
        <div>
            <label for="condition" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Condition de Retrait</label>
            <input type="text" id="codnition" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="C75FM87NG" required="">
        </div>
        <div>
            <label for="sms" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Envoyer un sms?</label>
            <input type="text" id="sms" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="oui ou non" required="">
        </div>
    </div>
     
  
  
  
   
    <!-- <button type="submit" class="text-cyan-700  focus:ring-4 focus:outline-none focus:ring-cyan-700 font-medium  text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-cyan-700 dark:hover:bg-cyan-700 dark:focus:ring-cyan-700">
      <span class="  bg-white-100 text-cyan-700 text-xs font-extrabold rounded dark:bg-cyan-200 dark:text-cyan-700"> Envoyer</span>
     </button> -->
</form>
    <h5 class="mb-2 text-xl font-bold text-gray-900 dark:text-white">Information du receveur/bénéficaire</h5>
    <!-- <p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">Stay up to date and move work forward with Flowbite on iOS &amp; Android. Download the app today.</p> 
    -->
    
<form>
    <div class="grid gap-6 mb-6 md:grid-cols-4">
        <div>
            <label for="expediteur" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Nom</label>
            <input type="text" id="expediteur" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="expiditeur" required="">
        </div>
         <div>
             <label for="expéditeur1" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Prenom</label>
             <input type="text" id="expéditeur1" class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ringcyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Receveur" required="">
         </div>  
       <div>
            <label for="phone1" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Téléphone</label>
            <input type="tel" id="phone1" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required="">
        </div>
       
       
       
       
        <div>
            <label for="ville" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">ville</label>
            <input type="text" id="ville" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="FCA" required="">
        </div>
     
          
       
       
    </div>
     
  
  
  
   
    <!-- <button type="submit" class="text-cyan-700  focus:ring-4 focus:outline-none focus:ring-cyan-700 font-medium  text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-cyan-700 dark:hover:bg-cyan-700 dark:focus:ring-cyan-700">
      <span class="  bg-white-100 text-cyan-700 text-xs font-extrabold rounded dark:bg-cyan-200 dark:text-cyan-700"> Envoyer</span>
     </button> -->
</form>
    <h5 class="mb-2 text-xl font-bold text-gray-900 dark:text-white">Destination & montant de la transaction</h5>
    <!-- <p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">Stay up to date and move work forward with Flowbite on iOS &amp; Android. Download the app today.</p> 
    -->
    
<form>
    <div class="grid gap-6 mb-6 md:grid-cols-4">
        <div>
            <label for="destination" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Pays de destination</label>
            <input type="text" id="destination" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="expiditeur" required="">
        </div>
         <div>
             <label for="montant" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Montant à envoyer</label>
             <input type="text" id="motant" class="bg-white-50 border border-gray-900 text-gray-900 text-sm focus:ringcyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Receveur" required="">
         </div>  

       
       
       
       
        <div>
            <label for="ville" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">ville</label>
            <input type="text" id="ville" class="bg-white-50 border border-gray-900 text-gray-900 text-sm  focus:ring-cyan-700 focus:border-cyan-700 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="FCA" required="">
        </div>
     
          
       
       
    </div>
     
  
  
  
   
    <button type="submit" class="text-cyan-700  focus:ring-4 focus:outline-none focus:ring-cyan-700 font-medium  text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-cyan-700 dark:hover:bg-cyan-700 dark:focus:ring-cyan-700">
      <span class="  bg-white-100 text-cyan-700 text-xs font-extrabold rounded dark:bg-cyan-200 dark:text-cyan-700"> Envoyer</span>
     </button>
</form>

</div>
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
    const showSidebar = ref(false);
    return {
      showSidebar,
    };
  },
};
</script>
<style>
.section {
  border: 1px solid red;
  margin-left: 25%;
}
.left {
  float: left;
  margin: 10px;
}
</style>
