<template>
  <div class="grid grid-cols-2 gap-4 overflow-hidden">
    <div
      class="h-screen relative bg-cover"
      style="background-image: url(https://i.imgur.com/u54GoQN.jpg)"
    >
      <div class="absolute inset-0 flex justify-center items-center z-10">
        <img src="../assets/TexteBlanc.png" class="w-1/2 drop-shadow-md" />
      </div>
    </div>

    <!-- Left and Right Panels -->

    <div style="background-color: white" class="p-10 w-full">
      <div style="background-color: white">
        <img src="../assets/Logo.png" class="w-40 mx-auto mb-10" />
        <h1 class="font-semibold text-[#1C1C1C] leading-tight text-4xl mb-3">
          Se connecter
        </h1>
        <h3 class="font-semibold text-[#5B5B5B] leading-tight text-2xl mb-7">
          Connectez-vous avec votre compte Outside pour accéder à votre tableau
          de bord.
        </h3>
        <div class="grid grid-cols-1">
          <button
            type="button"
            class="mx-auto text-gray-900 bg-white hover:bg-gray-100 border border-gray-300 active:bg-gray-300 font-semibold rounded-full text-sm px-5 py-2.5 inline-flex items-center"
          >
            <svg
              class="mr-2 -ml-1 w-5 h-5"
              xmlns="http://www.w3.org/2000/svg"
              height="24"
              viewBox="0 0 24 24"
              width="24"
            >
              <path
                d="M22.56 12.25c0-.78-.07-1.53-.2-2.25H12v4.26h5.92c-.26 1.37-1.04 2.53-2.21 3.31v2.77h3.57c2.08-1.92 3.28-4.74 3.28-8.09z"
                fill="#4285F4"
              />
              <path
                d="M12 23c2.97 0 5.46-.98 7.28-2.66l-3.57-2.77c-.98.66-2.23 1.06-3.71 1.06-2.86 0-5.29-1.93-6.16-4.53H2.18v2.84C3.99 20.53 7.7 23 12 23z"
                fill="#34A853"
              />
              <path
                d="M5.84 14.09c-.22-.66-.35-1.36-.35-2.09s.13-1.43.35-2.09V7.07H2.18C1.43 8.55 1 10.22 1 12s.43 3.45 1.18 4.93l2.85-2.22.81-.62z"
                fill="#FBBC05"
              />
              <path
                d="M12 5.38c1.62 0 3.06.56 4.21 1.64l3.15-3.15C17.45 2.09 14.97 1 12 1 7.7 1 3.99 3.47 2.18 7.07l3.66 2.84c.87-2.6 3.3-4.53 6.16-4.53z"
                fill="#EA4335"
              />
              <path d="M1 1h22v22H1z" fill="none" />
            </svg>
            Continuer avec Google
          </button>
        </div>
        <div
          class="flex items-center mt-10 before:flex-1 before:border-t-2 before:border-gray-300 before:mt-0.5 after:flex-1 after:border-t-2 after:border-gray-300 after:mt-0.5"
        >
          <p class="text-center font-semibold mx-4 text-[#5B5B5B]">
            Ou connectez-vous avec votre email
          </p>
        </div>
        <div class="p-20 -mt-10">
          <p
            class="font-semibold text-[#5B5B5B] leading-tight text-2xl mb-1 ml-1"
          >
            Email
          </p>
          <div class="mb-6">
            <input
              type="text"
              class="py-4 form-control w-full px-4 text-xl font-normal text-gray-700 bg-white bg-clip-padding border-[2px] border-solid border-gray-300 rounded-[12px] transition ease-in-out focus:text-gray-700 focus:bg-white focus:border-green-600 focus:outline-none"
              id="emailInput"
              placeholder="adresse@mail.com"
            />
          </div>
          <p
            class="font-semibold text-[#5B5B5B] leading-tight text-2xl mb-1 ml-1"
          >
            Mot de passe
          </p>
          <div class="mb-6">
            <input
              type="password"
              class="py-4 form-control w-full px-4 text-xl font-normal text-gray-700 bg-white bg-clip-padding border-[2px] border-solid border-gray-300 rounded-[12px] transition ease-in-out focus:text-gray-700 focus:bg-white focus:border-green-600 focus:outline-none"
              id="passwordInput"
              placeholder="••••••••"
            />
          </div>

          <div class="flex justify-between items-center mb-6">
            <div class="form-check">
              <input
                class="form-check-input h-4 w-4 mt-1 float-left mr-2 cursor-pointer"
                type="checkbox"
                value=""
                id="rememberCheck"
              />
              <label
                class="form-check-label inline-block text-gray-800 cursor-pointer"
                for="rememberCheck"
              >
                Se souvenir de moi
              </label>
            </div>
            <a
              href="#!"
              class="text-[#78b242] hover:text-[#608e34] active:text-[#4c7129] duration-200 transition ease-in-out"
              >Mot de passe oublié ?</a
            >
          </div>

          <!-- Submit button -->
          <button
            type="submit"
            class="inline-block rounded-full px-7 py-3 bg-[#78b242] text-white font-semibold text-2xl leading-snug shadow-md hover:bg-[#608e34] hover:shadow-lg active:bg-[#4c7129] active:shadow-lg transition duration-150 ease-in-out w-full"
          >
            Se connecter
          </button>
        </div>
        <p class="bottom text-center font-semibold text-base text-[#5B5B5B] -mb-3">
          Pour créer un compte, rendez-vous sur l'application mobile.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "login",
  data() {
    return {
      imageUrl: "./assets/Illu-A4.jpg",
    };
  },
};

//style="background-color: blue;"
</script>
<style>
body {
  font-family: "Poppins", sans-serif;
}
</style>
