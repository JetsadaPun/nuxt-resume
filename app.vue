import '@fortawesome/fontawesome-free/css/all.min.css';

<template>
  <div class="min-h-screen bg-[#F3F3E0] text-[#133E87] font-sans">
    <header class="flex justify-between items-center py-5 px-10">
      <h1 class="text-2xl font-bold whitespace-nowrap w-fit">
        SR Full Stack Dev.
      </h1>
      <nav class="flex w-full justify-between">
        <ul class="flex space-x-8 text-lg justify-center w-full">
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fas fa-home"></i>
              <span>Home</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fa-solid fa-user-graduate"></i>
              <span>Education</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fa-solid fa-cubes-stacked"></i>
              <span>Tech Stack</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fa-solid fa-diagram-project"></i>
              <span>My Project</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fa-solid fa-certificate"></i>
              <span>My Certificate</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fas fa-phone"></i>
              <span>Contact</span>
            </a>
          </li>
        </ul>
        <ul class="flex space-x-8 text-lg ml-auto">
          <li>
            <a
              href="#"
              class="font-bold hover:text-[#608BC1] flex items-center space-x-2"
            >
              <i class="fas fa-sign-in-alt"></i>
              <span>Login</span>
            </a>
          </li>
        </ul>
      </nav>
    </header>

    <main
      class="flex flex-col lg:flex-row items-center justify-center px-10 py-20 lg:space-x-20"
    >
      <div class="relative w-full max-w-xl group">
        <!-- Background Overlay with Hover Effect -->
        <div
          class="absolute top-4 left-4 w-full h-full bg-black rounded-lg opacity-70 z-0 transition-transform duration-300 group-hover:rotate-12 group-hover:translate-y-1"
        >
          <!-- Add Image Positioned to the Right -->
          <img
            src="/chinjang2-rm.png"
            alt="Background Image"
            class="absolute right-0 top-0 h-full object-cover opacity-50 rounded-lg"
          />
        </div>

        <!-- Main Content with Hover Effect -->
        <div
          class="relative text-center lg:text-left max-w-xl space-y-5 bg-[#CBDCEB] p-10 rounded-lg shadow-lg z-10 transition-transform duration-300 group-hover:-translate-x-60 group-hover:-rotate-12"
        >
          <p class="text-xl text-[#133E87]">Hello, I am</p>
          <p class="text-6xl font-bold">
            <span class="text-[#133E87]">Jetsada </span>
            <span class="text-[#39c56f]">Hongsa</span>
          </p>
          <p class="text-[#608BC1] text-lg">
            I am a professional website developer and designer working for a
            long time.
          </p>

          <!-- Social Media Links -->
          <div class="flex space-x-4 mt-8">
            <a
              href="https://www.instagram.com/pun_jsd/"
              class="text-[#608BC1] hover:text-[#133E87]"
              ><i class="fab fa-instagram"></i
            ></a>
            <a
              href="https://www.facebook.com/profile.php?id=100009082452062"
              class="text-[#608BC1] hover:text-[#133E87]"
              ><i class="fa-brands fa-facebook"></i
            ></a>
            <a href="#" class="text-[#608BC1] hover:text-[#133E87]"
              ><i class="fab fa-linkedin"></i
            ></a>
          </div>
        </div>
      </div>

      <!-- <div class="mt-10 lg:mt-0 bg-[#F3F3E0] p-2 rounded-lg shadow-lg">
        <img
          src="/simpatico.jpg"
          alt="Pun"
          class="rounded-lg w-80 grayscale-0 hover:grayscale-0"
        />
      </div> -->
      <div class="flex flex-col justify-center">
        <div class="group h-96 w-96 [perspective:1000px]">
          <!-- Flip container with front and back sides -->
          <div
            class="relative h-full w-full rounded-xl shadow-xl transition-all duration-1000 [transform-style:preserve-3d] group-hover:[transform:rotateY(180deg)]"
          >
            <div class="absolute inset-0 [backface-visibility:hidden]">
              <img
                class="h-full w-full rounded-xl object-cover shadow-xl shadow-black/40"
                src="/simpatico.jpg"
                alt="Pun"
              />
            </div>

            <div
              class="absolute inset-0 [backface-visibility:hidden] [transform:rotateY(180deg)]"
            >
              <img
                class="h-full w-full rounded-xl object-cover shadow-xl shadow-black/40"
                src="/sideeyehorse.png"
                alt="Back Image"
              />
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>
