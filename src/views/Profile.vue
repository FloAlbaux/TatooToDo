<template>
  <div>
    <navbar-component></navbar-component>
    <main class="profile-page">
      <section class="relative block" style="height: 500px">
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="
            background-image: url('https://images.unsplash.com/photo-1499336315816-097655dcfbda?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=2710&amp;q=80');
          "
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-50 bg-black"
          ></span>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
          style="height: 70px"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-gray-300 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </section>
      <section class="relative py-16 bg-gray-300">
        <div class="container mx-auto px-4">
          <div
            class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-xl rounded-lg -mt-64"
          >
            <div class="px-6">
              <div class="flex flex-wrap justify-center">
                <div
                  class="w-full lg:w-3/12 px-4 lg:order-2 flex justify-center"
                >
                  <div class="relative">
                    <img
                      alt="..."
                      src="../assets/img/team-2-800x800.jpg"
                      class="shadow-xl rounded-full h-auto align-middle border-none absolute -m-16 -ml-20 lg:-ml-16"
                      style="max-width: 150px"
                    />
                  </div>
                </div>
              </div>
              <div class="text-center mt-12">
                <h1
                  class="text-4xl font-semibold leading-normal pt-12 mb-2 text-gray-800 mb-2"
                >
                  Zep
                </h1>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase"
                >
                  <i
                    class="fas fa-map-marker-alt mr-2 text-lg text-gray-500"
                  ></i>
                  Clamart
                </div>
                <div class="mb-2 text-gray-700">
                  <i class="fas fa-briefcase mr-2 text-lg text-gray-500"></i
                  >Tatoueur mahchine hand poke
                </div>
                <div class="mb-2 text-gray-700">
                  <i class="fas fa-palette mr-2 text-lg text-gray-500"></i
                  >artiste créateur
                </div>
              </div>

              <div class="mt-10 py-10 border-t border-gray-300 text-center">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                  <div class="px-4">
                    <p class="mb-4 text-lg leading-relaxed text-gray-800">
                      Louise Michel Écouter, alias « Enjolras », née le 29 mai
                      1830 à
                      <span
                        class="bg-purple-100 text-purple-800 text-sm font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-purple-900 dark:text-purple-300"
                        >Vroncourt-la-Côte</span
                      >
                      (Haute-Marne) et morte le 9 janvier 1905 à Marseille, est
                      une institutrice, écrivaine, militante anarchiste,
                      franc-maçonne française aux idées féministes et l’une des
                      figures majeures de la Commune de Paris durant laquelle
                      elle s'implique tant politiquement que militairement en
                      intégrant les rangs de la Garde nationale. Elle est aussi
                      une des représentantes les plus célèbres de la part prise
                      par les
                      <span
                        class="bg-purple-100 text-purple-800 text-sm font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-purple-900 dark:text-purple-300"
                        >femmes</span
                      >
                      dans la Commune de Paris. Préoccupée très tôt par
                      l'éducation, elle enseigne quelques années avant de se
                      rendre à Paris en 1856. À 26 ans, elle y développe une
                      importante activité littéraire, pédagogique et politique
                      et se lie avec plusieurs personnalités révolutionnaires
                      blanquistes de Paris des années 1860.
                    </p>
                  </div>
                  <img class="rounded-lg" src="../assets/img/wallpaper.jpg" />
                </div>
              </div>

              <div class="mt-10 py-10 border-t border-gray-300 text-center">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                  <img class="rounded-lg" src="../assets/img/wallpaper.jpg" />
                  <div class="px-4">
                    <p class="mb-4 text-lg leading-relaxed text-gray-800">
                      En 1871, elle participe activement aux événements de la
                      <span
                        class="bg-purple-100 text-purple-800 text-sm font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-purple-900 dark:text-purple-300"
                        >Commune de Paris</span
                      >, autant en première ligne qu'en soutien. S'étant livrée
                      en mai pour faire libérer sa mère, elle est déportée en
                      Nouvelle-Calédonie où elle se convertit à la pensée
                      anarchiste. Elle revient en Métropole en 1880, et, très
                      populaire, multiplie les manifestations et réunions en
                      faveur des prolétaires. Elle reste surveillée par la
                      police et est emprisonnée à plusieurs reprises, mais
                      poursuit son militantisme politique dans toute la France,
                      jusqu'à sa mort à l'âge de 74 ans à Marseille. Elle
                      demeure une figure révolutionnaire et anarchiste de
                      premier plan dans l'imaginaire collectif. Première à
                      arborer <span
                        class="bg-purple-100 text-purple-800 text-sm font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-purple-900 dark:text-purple-300"
                        >emprisonnée</span
                      > , elle popularise celui-ci au sein
                      du mouvement libertaire.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer-component></footer-component>
  </div>
</template>
<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
export default {
  name: "profile-page",
  components: {
    NavbarComponent,
    FooterComponent,
  },
};
</script>
