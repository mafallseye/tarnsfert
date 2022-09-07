<template>
   <div class="bg-white shadow">
    <header>
      <nav class="bg-yellow border-gray-200 rounded dark:bg-gray-900">
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
          <a href="https://flowbite.com/" class="flex items-center">
            <img src="@/assets/re.png" alt="MTN" class="mr-3 h-16 sm:h-19" />
          </a>
          <div class="flex items-center md:order-2">
            <div class="dropdown dropdown-end">
              <label for="" class="text-xl font-bold mr-4">solde:$123456</label>
              <label
                tabindex="0"
                class="btn btn-ghost rounded-full bg-cyan-700"
              >
              
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
                      class="h-6 w-6"
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
                    <span> Mon espace </span></a
                  >
                </li>
                <li>
                  <a
                    href="/profile"
                    class="group flex items-center space-x-2 py-3 px-4 hover:bg-cyan-700 rounded hover:text-cyan-300 transition duration-200"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-5 w-5"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-6-3a2 2 0 11-4 0 2 2 0 014 0zm-2 4a5 5 0 00-4.546 2.916A5.986 5.986 0 0010 16a5.986 5.986 0 004.546-2.084A5 5 0 0010 11z"
                        clip-rule="evenodd"
                      />
                    </svg>
                    <span class=""> Profile</span>
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
                        d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1"
                      /></svg
                    ><span @click="Login()">deconnexion</span>
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
</template>

<script>
export default {

}
</script>

<style>

</style>