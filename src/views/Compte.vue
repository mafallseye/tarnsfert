<template>
  <!-- header -->

  <!-- content -->
  <div class="p-3 text-cyan-700 font-extrabold">
    <bradcrumb parentTitle="Accueil" subParentTitle="Verification" />

    <div
      class="p-4 bg-white rounded-lg border shadow-md sm:p-8 dark:bg-gray-800 dark:border-gray-700"
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
            compte client
          </p>
        </div>

        <div class="font-medium dark:text-white">
          <div>
            <div>
              <a
                href="https://flowbite.com/"
                class="flex items-center pt-10 justify-center"
              >
                <img
                  src="@/assets/re.png"
                  alt="MTN"
                  class="mr-3 h-16 sm:h-19"
                />
              </a>

              <p>
                Pour voir les détails d'un client, vous devez spécifier le code
                addresse Email ou son contact
              </p>
              <form action="" @submit.prevent="onSubmit">
                <input
                  type="text"
                  placeholder="Entrer ici"
                  class="input input-bordered input-sm w-full mt-5"
                />
                <button
                  @click="onSubmit()"
                  type="button"
                  class="justify-center items-center w-full px-4 py-2 mt-5 text-xs font-medium text-center text-white bg-cyan-700 rounded-lg hover:bg-cyan-600 focus:ring-4 focus:outline-none focus:ring-cyan-600 dark:bg-cyan-600 dark:hover:bg-cyan-700 dark:focus:ring-cyan-800"
                >
                  <div class="text-center">
                    <div role="status">
                      <svg
                        v-show="isLoading"
                        class="absolute ml w-5 h-5 text-gray-200 animate-spin dark:text-gray-600 fill-blue-600"
                        viewBox="0 0 100 101"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          d="M100 50.5908C100 78.2051 77.6142 100.591 50 100.591C22.3858 100.591 0 78.2051 0 50.5908C0 22.9766 22.3858 0.59082 50 0.59082C77.6142 0.59082 100 22.9766 100 50.5908ZM9.08144 50.5908C9.08144 73.1895 27.4013 91.5094 50 91.5094C72.5987 91.5094 90.9186 73.1895 90.9186 50.5908C90.9186 27.9921 72.5987 9.67226 50 9.67226C27.4013 9.67226 9.08144 27.9921 9.08144 50.5908Z"
                          fill="currentColor"
                        />
                        <path
                          d="M93.9676 39.0409C96.393 38.4038 97.8624 35.9116 97.0079 33.5539C95.2932 28.8227 92.871 24.3692 89.8167 20.348C85.8452 15.1192 80.8826 10.7238 75.2124 7.41289C69.5422 4.10194 63.2754 1.94025 56.7698 1.05124C51.7666 0.367541 46.6976 0.446843 41.7345 1.27873C39.2613 1.69328 37.813 4.19778 38.4501 6.62326C39.0873 9.04874 41.5694 10.4717 44.0505 10.1071C47.8511 9.54855 51.7191 9.52689 55.5402 10.0491C60.8642 10.7766 65.9928 12.5457 70.6331 15.2552C75.2735 17.9648 79.3347 21.5619 82.5849 25.841C84.9175 28.9121 86.7997 32.2913 88.1811 35.8758C89.083 38.2158 91.5421 39.6781 93.9676 39.0409Z"
                          fill="currentFill"
                        />
                      </svg>
                      <span class="sr-only">Loading...</span>
                    </div>
                  </div>
                  <span :class="{ invisible: isLoading }"> continuer</span>
                </button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src



import bradcrumb from "@/components/bradcrumb.vue";

import { ref } from "vue";
import Footer from "../components/Footer.vue";
export default {
  name: "HomeView",
  components: {
  
    bradcrumb,

    Footer,
  },
  setup() {
    const isLoading = ref(false);
    return {
      isLoading,
    };
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
