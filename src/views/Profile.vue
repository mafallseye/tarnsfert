<template>
  <!-- content -->
  <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle="Profile" />

    <div
      class="p-4 w-full text-center bg-white rounded-lg border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
    >
      <div class="flex items-center space-x-10 justify-center">
        <div class="avatar">
          <div
            class="w-30 rounded-full ring ring-primary ring-offset-base-100 ring-offset-2"
          >
            <img src="https://placeimg.com/192/192/people" />
          </div>
        </div>
        <div class="font-medium dark:text-white">
          <div>Jese Leos</div>
          <div class="text-sm text-gray-500 dark:text-gray-400">
            Joined in August 2014
          </div>
        </div>
      </div>
    </div>

    <div
      class="left p-4 bg-white rounded-lg border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
    >
      <div class="flex-1 items-center justify-center">
        <div
          class="breadcrumb flex items-end border-b border-gray-300 pb-4 mb-6"
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
          <p class="text-xl ml-2 font-semibold dark:text-white">
            Edite profile
          </p>
        </div>

        <div class="font-medium dark:text-white">
          <form class="space-y-6" action="#">
            <div>
              <label
                for="email"
                class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                >Your email</label
              >
              <input
                type="email"
                name="email"
                id="email"
                class="bg-white-50 border border-black-300 text-black-900 text-sm rounded-lg focus:ring-black-500 focus:border-black-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                placeholder="name@company.com"
                required=""
              />
            </div>
            <div>
              <label
                for="password"
                class="block mb-2 text-sm font-medium text-black-900 dark:text-black-300"
                >Your password</label
              >
              <input
                type="password"
                name="password"
                id="password"
                placeholder="••••••••"
                class="bg-black-50 border border-black-300 text-black-900 text-sm rounded-lg focus:ring-black-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                required=""
              />
            </div>

            <button
              type="submit"
              class="w-30 text-white bg-cyan-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Login
            </button>
          </form>
        </div>
      </div>
    </div>
    <div
      class="left p-4 bg-white rounded-lg border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
    >
      <div class="flex-1 items-center justify-center">
        <div
          class="breadcrumb flex items-end border-b border-gray-300 pb-4 mb-6"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z"
              clip-rule="evenodd"
            />
          </svg>
          <p class="text-xl ml-2 font-semibold dark:text-white">
            Changer mot de passe
          </p>
        </div>

        <div class="font-medium dark:text-white">
          <form class="space-y-6" action="#">
            <div>
              <label
                for="password"
                class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                >Mot de passe actuelle</label
              >
              <input
                type="password"
                name="email"
                id="password"
                class="bg-white-50 border border-black-300 text-black-900 text-sm rounded-lg focus:ring-black-500 focus:border-black-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                placeholder="name@company.com"
                required=""
              />
            </div>
            <div>
              <label
                for="password1"
                class="block mb-2 text-sm font-medium text-black-900 dark:text-black-300"
                >Nouveau mot de passe</label
              >
              <input
                type="password"
                name="password"
                id="password1"
                placeholder="••••••••"
                class="bg-black-50 border border-black-300 text-black-900 text-sm rounded-lg focus:ring-black-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                required=""
              />
            </div>

            <button
              type="submit"
              class="w-30 text-white bg-cyan-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Login
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>

  <div></div>
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
.left {
  float: left;
  width: 48%;
}
</style>
