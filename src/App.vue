<template>
 
  <div class="relative flex min-h-screen">
    <div
      class="color bg-cyan-600 text-cyan-100 w-50 space-y-6 px-2 py-4 absolute inset-y-0 left-0 md:relative md:-translate-x-0 transform -translate-x-full transition duration-200 ease-in-out"
      :class="{ 'relative -translate-x-0': showSidebar }"
    >
      <a href="" class="flex items-center">
        <!-- <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
  <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
</svg> -->
        <span class="text-2xl font-extrabold text-white"><span class="bg-gray-700">PAY</span> AXETAG</span>
      </a>
      <nav>
        <a
          href="/home"
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
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
              d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300"
            >Tableau de bord</span
          >
        </a>
        <a
          href="/rechargement"
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
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
          <span class="text-white group-hover:text-cyan-300">Rechargement</span>
        </a>
        <a
          href="/depot"
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300"
            >Envoyer de l'argent</span
          >
        </a>
        <a
          href="/retrait"
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
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
              d="M9 17v-2m3 2v-4m3 4v-6m2 10H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300">Retrait</span>
        </a>
        <!-- <a
          href="/transaction"
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
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
              d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300">Transaction</span>
        </a> -->
        <a
          href="/RapportTransaction"
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
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
              d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300"
            >Rapport de transaction</span
          >
        </a>
        <a
          href=""
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 hover:text-cyan-300 transition duration-200"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
            />
            <path
              fill-rule="evenodd"
              d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
              clip-rule="evenodd"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300">Paiement</span>
        </a>
        <a
          href=""
          class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
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
              d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
            />
          </svg>
          <span class="text-white group-hover:text-cyan-300"
            >Rappport de paiement</span
          >
        </a>
      </nav>
    </div>

    
    <div class="flex-1">
      <div class="bg-white">
    <header>
      <nav class="bg-yellow  rounded dark:bg-gray-900">
        <div
          class="container flex flex-wrap justify-between items-center mx-auto"
        >
          <button
            @click="this.showSidebar = !this.showSidebar"
            data-collapse-toggle="mobile-menu-language-select"
            type="button"
            class="button inline-flex p-2 ml-1 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
            aria-controls="mobile-menu-language-select"
            aria-expanded="false"
          >
            <span class="sr-only">Open main menu</span>
            <svg
              class="w-6 h-6"
              aria-hidden="true"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </button>
          <!-- <a href="https://flowbite.com/" class="flex items-center">
            <img src="@/assets/re.png" alt="MTN" class="mr-3 h-16 sm:h-19" />
          </a> -->
          <div class="flex items-center md:order-2">
            <label for="" class="mr-5  "><span class="text-gray-700 text-sm ">solde</span>: <span class="font-bold">10000fcfa</span> </label>
            <div class="dropdown mr-5 z-10 ">
  <label tabindex="0" class="btn bg-white border-white m-1 text-gray-900 hover:bg-white">fr<svg class="ml-2 w-4 h-4" aria-hidden="true" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg></label>
  <!-- <ul  class="dropdown-content menu p-2 shadow bg-base-100 rounded-box w-52">
    <li><a>Fr</a></li>
    <li><a>Ang</a></li>
  </ul> -->
  <ul tabindex="0" class=" dropdown-content menu p-2 shadow bg-base-100  py-1 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownDefault">
      <li>
        <a href="#" class="block py-2 px-4 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Francais</a>
      </li>
      <li>
        <a href="#" class="block py-2 px-4 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Anglais</a>
      </li>
      <!-- <li>
        <a href="#" class="block py-2 px-4 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Earnings</a>
      </li>
      <li>
        <a href="#" class="block py-2 px-4 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Sign out</a>
      </li> -->
     
    </ul>
  
</div>
            <div class="dropdown dropdown-end">
  
              <label
                tabindex="0"
                class="btn btn-ghost rounded-full bg-cyan-600  mr-5"
              >
              
                <!-- <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  width="24"
                  height="24"
                >
                  <path fill="none" d="M0 0h24v24H0z" />
                  <path
                    d="M4 22a8 8 0 1 1 16 0H4zm8-9c-3.315 0-6-2.685-6-6s2.685-6 6-6 6 2.685 6 6-2.685 6-6 6z"
                  />
                </svg> -->
                <span class="text-white">{{mm.charAt(0)}}{{ms.charAt(0)}}</span></label
              >

              <ul
                tabindex="0"
                class="menu dropdown-content p-2 shadow bg-base-100 rounded-box w-52 mt-4"
              >
                <li>
                  <a
                    href="/compte"
                    class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                      stroke-width="2"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z"
                      />
                    </svg>
                    <span> Mon compte </span></a
                  >
                </li>
                <li>
                  <a
                    href="/profile"
                    class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
                  >
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
  <path stroke-linecap="round" stroke-linejoin="round" d="M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L10.582 16.07a4.5 4.5 0 01-1.897 1.13L6 18l.8-2.685a4.5 4.5 0 011.13-1.897l8.932-8.931zm0 0L19.5 7.125M18 14v4.75A2.25 2.25 0 0115.75 21H5.25A2.25 2.25 0 013 18.75V8.25A2.25 2.25 0 015.25 6H10" />
</svg>

                    <span class="">Mon Profile</span>
                  </a>
                </li>
                <!-- <li>
        <a href="#" class="block py-2 px-4 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Earnings</a>
      </li> -->
                <div class="py-1">
                  <a
                    href="#"
                    class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
                  >
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9 8.25H7.5a2.25 2.25 0 00-2.25 2.25v9a2.25 2.25 0 002.25 2.25h9a2.25 2.25 0 002.25-2.25v-9a2.25 2.25 0 00-2.25-2.25H15m0-3l-3-3m0 0l-3 3m3-3V15" />
</svg>

                    <span @click="Login()">deconnexion</span>
                  </a>
                </div>
              </ul>
            </div>

            <!-- Dropdown -->
            <div
              class="z-50 my-4 text-base list-none bg-white rounded divide-y divide-gray-100 shadow dark:bg-gray-700 block"
              id="language-dropdown-menu"
              data-popper-reference-hidden=""
              data-popper-escaped=""
              data-popper-placement="bottom"
              style="
                position: absolute;
                inset: 0px auto auto 0px;
                margin: 0px;
                transform: translate(588px, 84px);
              "
            ></div>
            <!-- <button
              data-collapse-toggle="mobile-menu-language-select"
              type="button"
              class="button inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
              aria-controls="mobile-menu-language-select"
              aria-expanded="false"
            >
              <span class="sr-only">Open main menu</span>
              <svg
                class="w-6 h-6"
                aria-hidden="true"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </button> -->
          </div>
          <div
            class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1 gauche"
            id="mobile-menu-language-select"
          ></div>
        </div>
      </nav>
    </header>
  </div>
      <router-view />
      <Footer />
    </div>
  </div>
</template>
<script>
import Footer from "@/components/Footer.vue";
import { ref } from "vue";

export default {
  components: {
    Footer,
  },
  setup() {
    const showSidebar = ref(false);
    return {
      showSidebar,
    };
  },

  methods: {
    drawSide() {
      this.showSidebar = !this.showSidebar;
    },
  },
  data(){
    return{
      mm:"m ",
      ms:"seye"
    }
  }
};
</script>
<style></style>
