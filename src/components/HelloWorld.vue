<template>
  <!-- Navbar -->

  <nav class="bg-white-100 shadow">
    <div class="container mx-auto px-6 py-3">
      <div class="flex items-center justify-between">
        <!-- <div class="flex items-center">
          <h1 class="text-lg font-bold text-black font-montserrat">
            Logo Carsas
          </h1>
        </div> -->

        <div class="flex items-center">
          <img
            src="https://files.fm/thumb_show.php?i=qdz3uyzwz"
            alt="Logo Carsas"
            class="h-10"
          />
        </div>

        <div class="flex items-center ml-20">
          <h1 class="text-lg font-bold text-black font-montserrat">
            +59 9999996
          </h1>
        </div>

        <div class="flex md:hidden">
          <button
            @click="showMenu = !showMenu"
            class="
              border border-gray-500
              rounded
              px-3
              py-2
              text-black
              mr-2
              focus:outline-none
            "
          >
            <i class="fas fa-bars"></i>
          </button>
        </div>
        <div class="hidden md:flex md:items-center">
          <a class="text-lg text-black font-roboto mr-4" href="#">Inicio</a>
          <a class="text-lg text-black font-roboto mr-4" href="#">Servicios</a>
          <a class="text-lg text-black font-roboto mr-4" href="#metodologia"
            >Metodologia</a
          >
          <a class="text-lg text-black font-roboto" href="#contacto"
            >Contacto</a
          >
        </div>
      </div>
      <div class="md:hidden" :class="{ block: showMenu, hidden: !showMenu }">
        <a
          class="
            block
            text-lg text-black
            font-roboto
            py-2
            px-4
            hover:bg-purple-800
          "
          href="#"
          >Inicio</a
        >
        <a
          class="
            block
            text-lg text-black
            font-roboto
            py-2
            px-4
            hover:bg-purple-800
          "
          href="#servicios"
          >Servicios</a
        >
        <a
          class="
            block
            text-lg text-black
            font-roboto
            py-2
            px-4
            hover:bg-purple-800
          "
          href="#metodologia"
          >Metodologia</a
        >
        <a
          class="
            block
            text-lg text-black
            font-roboto
            py-2
            px-4
            hover:bg-purple-800
          "
          href="#contacto"
          >Contacto</a
        >
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section
    class="bg-gradient-to-br from-purple-700 to-indigo-800 py-12"
    style="
      background-image: url('https://p4.wallpaperbetter.com/wallpaper/551/635/701/abstract-graphic-design-purple-wavy-lines-wallpaper-preview.jpg');
      background-size: cover;
      background-position: center;
    "
  >
    <div class="container mx-auto px-4">
      <div
        class="
          flex flex-col
          md:flex-row
          items-center
          justify-center
          md:justify-between
        "
      >
        <div class="md:w-1/2 lg:w-1/3 text-center md:text-left">
          <h2 class="text-4xl font-bold text-white leading-tight mb-4">
            CARSAS: Escuela de Rentistas - Renta de Autos
          </h2>
          <p class="text-xl text-purple-300 mb-8">
            En <span class="text-blue-400 font-bold">CARSAS</span> te ofrecemos
            una escuela de rentistas especializada en el negocio de renta de
            autos. Ofrecemos soluciones a medida para tu negocio, desde el
            asesoramiento en la gestión de flotas hasta la capacitación de
            personal. ¡Impulsa tu negocio de renta de autos con
            <span class="text-blue-400 font-bold">CARSAS</span>!
          </p>
          <div class="flex justify-center md:justify-start">
            <a
              href="#"
              class="
                bg-white
                hover:bg-gray-100
                text-purple-700
                font-bold
                py-2
                px-4
                rounded-lg
                mr-4
              "
              >Contáctanos</a
            >
            <a
              href="#"
              class="
                text-white
                hover:text-gray-200
                font-bold
                py-2
                px-4
                rounded-lg
              "
              >Nuestros servicios</a
            >
          </div>
        </div>
        <div class="md:w-1/2 lg:w-2/3 mt-8 md:mt-0">
          <img
            src="https://assets.stickpng.com/images/580b585b2edbce24c47b2c0f.png"
            alt="CARSAS: Escuela de Rentistas / Renta de Autos"
            class="rounded-lg shadow-md"
          />
        </div>
      </div>
    </div>
  </section>

  <!-- Sección de proceso o metodología de trabajo -->
  <section
    class="bg-gradient-to-br from-purple-700 to-indigo-800 py-8"
    style="
      background-image: url('');
      background-size: cover;
      background-position: center;
    "
  >
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-bold text-black mb-8">
        CARSAS: Escuela de Rentistas y Renta de Autos
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-purple-500 rounded-lg overflow-hidden shadow-md">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="rounded-full bg-purple-800 text-white px-4 py-3">
                <i class="fas fa-graduation-cap"></i>
              </div>
              <div class="ml-4">
                <h3 class="text-lg font-semibold text-white">
                  Capacitación Rentistas
                </h3>
              </div>
            </div>
            <p class="text-white leading-relaxed">
              En esta fase, brindamos capacitación especializada para rentistas,
              ayudándoles a desarrollar habilidades y conocimientos en el
              negocio de la renta de autos.
            </p>
          </div>
        </div>
        <div class="bg-purple-500 rounded-lg overflow-hidden shadow-md">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="rounded-full bg-purple-800 text-white px-4 py-3">
                <i class="fas fa-car"></i>
              </div>
              <div class="ml-4">
                <h3 class="text-lg font-semibold text-white">
                  Diseño de Flotas
                </h3>
              </div>
            </div>
            <p class="text-white leading-relaxed">
              Con base en tus necesidades y objetivos, creamos diseños
              personalizados para tus flotas de autos, asegurando una imagen
              atractiva y profesional.
            </p>
          </div>
        </div>
        <div class="bg-purple-500 rounded-lg overflow-hidden shadow-md">
          <div class="p-6">
            <div class="flex items-center mb-4">
              <div class="rounded-full bg-purple-800 text-white px-4 py-3">
                <i class="fas fa-calendar-alt"></i>
              </div>
              <div class="ml-4">
                <h3 class="text-lg font-semibold text-white">
                  Plataforma de Reservas
                </h3>
              </div>
            </div>
            <p class="text-white leading-relaxed">
              Nuestro equipo de desarrollo crea una plataforma de reservas
              personalizada, asegurando una experiencia fluida y eficiente para
              tus clientes.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <a
    href="https://wa.me/+2664255928"
    target="_blank"
    rel="noopener"
    class="
      fixed
      bottom-8
      right-7
      bg-green-500
      hover:bg-green-600
      text-white
      rounded-full
      px-3
      py-2
    "
  >
    <i class="fab fa-whatsapp fa-2x"></i>
  </a>

  <footer class="bg-gray-900 text-white">
    <div class="container mx-auto py-8 px-6">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="md:col-span-2">
          <h3 class="text-2xl font-bold mb-4">Sobre Carsas</h3>
          <p class="mb-4">
            Somos una escuela de rentistas especializada en el negocio de renta
            de autos. Nuestro objetivo es brindar soluciones a medida para tu
            negocio, desde el asesoramiento en la gestión de flotas hasta la
            capacitación de personal.
          </p>
          <p class="mb-4">
            Nos enfocamos en ofrecerte el conocimiento y las herramientas
            necesarias para impulsar tu negocio de renta de autos y lograr el
            éxito en este sector.
          </p>
        </div>
        <div>
          <h3 class="text-2xl font-bold mb-4">Contáctanos</h3>
          <ul class="mb-4">
            <li>
              <i class="fas fa-map-marker-alt mr-2"></i>Buenos Aires, Argentina
            </li>
            <li><i class="fas fa-phone-alt mr-2"></i>+51 999 999 999</li>
            <li><i class="fas fa-envelope mr-2"></i>info@carsas.com</li>
          </ul>
          <h3 class="text-2xl font-bold mb-4">Síguenos</h3>
          <div class="flex">
            <a href="#" class="mr-4"><i class="fab fa-facebook fa-2x"></i></a>
            <a href="#" class="mr-4"><i class="fab fa-twitter fa-2x"></i></a>
            <a href="#" class="mr-4"><i class="fab fa-instagram fa-2x"></i></a>
            <a href="#" class="mr-4"><i class="fab fa-linkedin fa-2x"></i></a>
          </div>
        </div>
      </div>
      <hr class="border-gray-600 my-8" />
      <div class="text-center">
        <p class="text-gray-500 mb-4">
          © 2023 Carsas. Todos los derechos reservados.
        </p>
        <!-- <a href="#" class="text-purple-500 font-bold hover:underline">Política de privacidad</a> -->
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  data() {
    return {
      showMenu: false,
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.whatsapp-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 100;
  padding: 10px;
  background-color: #25d366;
  color: white;
  border-radius: 50%;
  font-size: 24px;
  text-align: center;
  box-shadow: 2px 2px 3px rgba(0, 0, 0, 0.4);
}

.whatsapp-float i {
  margin-top: 6px;
}
</style>
