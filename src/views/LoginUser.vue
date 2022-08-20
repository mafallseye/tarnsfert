v<template>
 

<div id="authentication-modal" tabindex="-1" class="  main overflow-y-auto overflow-x-hidden fixed top-0 right-0 left-0 z-50 w-full md:inset-0 h-modal md:h-full justify-center items-center flex" aria-modal="true" role="dialog">
    <div class="relative pt-10 p-10 w-full max-w-md h-full md:h-auto ">
      
        <div class="relative bg-white  shadow dark:bg-gray-700">
       
            <div class="py-6 px-6 lg:px-8">
                <h3 class="mb-4 text-xl font-medium text-gray-900 dark:text-white mt-10 px-10 text-center">
                    <img src="@/assets/re.png" alt="">
                </h3>
                <form class="space-y-6" action="#">
                    <div>
                     
                       
<label for="input-group-1" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Email</label>
<div class="relative mb-6">
  <div class="flex absolute inset-y-0 left-0 items-center pl-3 pointer-events-none">
    <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path></svg>
  </div>
  <input type="text" id="input-group-1" class="bg-white-50 border border-cyan-700 text-black-900 text-sm rounded-lg focus:ring-cyan-600 focus:border-cyan-700 block w-full pl-10 p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="name@axe-tag.fr">
</div>
<label for="input-group-2" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Mot de passe</label>
<div class="relative mb-6">
  <div class="flex absolute inset-y-0 left-0 items-center pl-3 pointer-events-none">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
  <path d="M10 2a5 5 0 00-5 5v2a2 2 0 00-2 2v5a2 2 0 002 2h10a2 2 0 002-2v-5a2 2 0 00-2-2H7V7a3 3 0 015.905-.75 1 1 0 001.937-.5A5.002 5.002 0 0010 2z" />
</svg>
  </div>
  <input type="password" id="input-group-2" class="bg-white-50 border border-cyan-700 text-black-900 text-sm rounded-lg focus:ring-cyan-600 focus:border-cyan-700 block w-full pl-10 p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="........">
</div>


                    </div>
                   
                    <div class="flex justify-between">
                       
                        <a href="#" class="text-sm text-cyan-700 hover:underline dark:text-cyan-500">mot de passe oublié?</a>
                    </div>
                    <button type="button" class="w-full text-white bg-cyan-700 hover:bg-cyan-700 focus:ring-4 focus:outline-none focus:ring-cyan-700 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800" @click="showLogin()">Se connecter</button>
                    <div class="text-sm font-medium text-gray-500 dark:text-gray-300">
                        pas de compte? <a href="#" class="text-cyan-700 hover:underline dark:text-cyan-500">Creer ici</a>
                    </div>
                </form>
            </div>
        </div>
    </div>
</div> 

</template>

<script>

export default {
data(){
    return{
       
    }
},
methods:{
    showLogin(){
          this.isLoading=true
       setTimeout(() => {
  this.isLoading=false
  this.$router.push('/home')
}, 1000) 
    }
}
   
}
</script>
<style  >
.main {
    background-color:#0088A3
 
}
</style>

