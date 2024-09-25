<template>
  <div class="bg-gray-100 min-h-screen">
    <!-- Header Section -->
    <header class="bg-white p-4 shadow-lg">
      <div class="container mx-auto flex justify-between items-center">
        <div class="text-2xl font-bold">Dungss</div>
        <nav>
          <ul class="flex space-x-4 text-gray-600">
            <li><a href="#home" class="hover:text-yellow-500">Home</a></li>
            <li><a href="#about" class="hover:text-yellow-500">About Me</a></li>
            <li><a href="#services" class="hover:text-yellow-500">Services</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-white py-16 text-center">
      <div class="container mx-auto">
        <h1 class="text-5xl font-bold text-yellow-500">Hello I'am Gading Wahyu Sejati</h1>
        <p class="text-gray-600 mt-4">I'am a UI/UX Designer and project manager</p>
        <div class="mt-8">
          <!-- Pastikan gambar profile adalah persegi -->
          <img src="./assets/photo-profile.jpg" alt="Profile Picture" class="mx-auto h-48 w-48 rounded-full shadow-lg">
        </div>
      </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="bg-gray-50 py-16">
      <div class="container mx-auto">
        <h2 class="text-3xl font-bold text-center mb-8">About Me</h2>
        <div class="flex flex-col items-center">
          <p class="text-gray-600 max-w-3xl text-center">
            I am a UI & UX designer with a passion for creating functional and visually appealing designs.
          </p>
          <div class="mt-8 w-full max-w-lg">
            <div class="flex justify-between mb-2">
              <span class="text-gray-600">Website Design</span>
              <span class="text-gray-600">90%</span>
            </div>
            <div class="bg-gray-300 rounded-full h-2">
              <div class="bg-yellow-500 h-2 rounded-full w-[90%]"></div>
            </div>
          </div>
          <div class="mt-8 w-full max-w-lg">
            <div class="flex justify-between mb-2">
              <span class="text-gray-600">App Design</span>
              <span class="text-gray-600">85%</span>
            </div>
            <div class="bg-gray-300 rounded-full h-2">
              <div class="bg-yellow-500 h-2 rounded-full w-[85%]"></div>
            </div>
          </div>
          <div class="mt-8 w-full max-w-lg">
            <div class="flex justify-between mb-2">
              <span class="text-gray-600">Graphic Design</span>
              <span class="text-gray-600">95%</span>
            </div>
            <div class="bg-gray-300 rounded-full h-2">
              <div class="bg-yellow-500 h-2 rounded-full w-[95%]"></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-white py-16">
      <div class="container mx-auto">
        <h2 class="text-3xl font-bold text-center mb-8">Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="text-center bg-gray-50 p-8 rounded-lg shadow-lg">
            <div class="text-6xl text-yellow-500 mb-4">🎨</div>
            <h3 class="text-xl font-bold">UI/UX Design</h3>
            <p class="text-gray-600 mt-2">Beautiful user interfaces and experiences.</p>
          </div>
          <div class="text-center bg-gray-50 p-8 rounded-lg shadow-lg">
            <div class="text-6xl text-yellow-500 mb-4">🖌️</div>
            <h3 class="text-xl font-bold">Graphics Design</h3>
            <p class="text-gray-600 mt-2">Creative graphic solutions for your brand.</p>
          </div>
          <div class="text-center bg-gray-50 p-8 rounded-lg shadow-lg">
            <div class="text-6xl text-yellow-500 mb-4">💻</div>
            <h3 class="text-xl font-bold">Web Design</h3>
            <p class="text-gray-600 mt-2">Modern and responsive web design services.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
      <p>&copy; 2024 Dungss. All rights reserved.</p>
    </footer>
  </div>
</template>

<script setup>
// Tidak perlu script tambahan.
</script>

<style scoped>
/* Gaya tambahan bisa diatur di sini jika diperlukan */
</style>
