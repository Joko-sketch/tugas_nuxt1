<template>
  <div class="min-h-screen bg-gray-50 text-gray-800 font-sans">
    <!-- Header -->
    <header class="bg-gradient-to-r from-blue-900 to-indigo-900 text-white p-6 shadow-md">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-4xl font-bold">jokssz</h1>
        <nav>
          <ul class="flex space-x-6 text-lg">
            <li><a href="#home" class="hover:underline hover:text-gold transition duration-300">Home</a></li>
            <li><a href="#about" class="hover:underline hover:text-gold transition duration-300">About</a></li>
            <li><a href="#experience" class="hover:underline hover:text-gold transition duration-300">Experience</a></li>
            <li><a href="#hobbies" class="hover:underline hover:text-gold transition duration-300">Hobbies</a></li>
            <li><a href="#contact" class="hover:underline hover:text-gold transition duration-300">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Home Section -->
    <section id="home" class="bg-cover bg-center h-screen" style="background-image: url('https://i.pinimg.com/originals/cc/42/24/cc42240fec087fae4b809c197d960d27.jpg');">
      <div class="bg-black bg-opacity-60 h-full flex items-center justify-center">
        <div class="text-center text-white">
          <h2 class="text-6xl font-extrabold mb-4 animate-fade-in-up">Welcome to My CV</h2>
          <p class="text-2xl mb-6">Hello! I am <span class="font-semibold text-gold">Joko Priambodo</span>, a passionate software engineer.</p>
          <a href="#about" class="bg-gold text-blue-900 px-6 py-3 rounded-full text-lg font-semibold shadow-lg hover:bg-yellow-600 transition duration-300">Learn More</a>
        </div>
      </div>
    </section>

    <!-- About Section with Image -->
    <section id="about" class="py-16 bg-gray-100">
      <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 items-center gap-8">
        <!-- About Text -->
        <div class="text-center md:text-left ms-14">
          <h2 class="text-4xl font-bold text-blue-900 mb-4 animate-fade-in-up">About Me</h2>
          <p class="text-lg text-gray-700 mb-6">
            I am a dedicated software developer with a strong passion for web development and modern technologies.
            I enjoy learning new technologies and continuously looking for innovative ways to solve problems.
          </p>
          <p class="text-lg text-gray-700">
            I specialize in building responsive and interactive websites with the latest technologies, focusing on delivering high-quality user experiences.
          </p>
        </div>

        <!-- About Image -->
        <div class="flex justify-center">
          <img src="./assets/foto-profil.jpg" alt="Profile Picture" class="rounded-full w-64 h-64 shadow-lg transform hover:scale-105 transition duration-300">
        </div>
      </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-16 bg-white">
      <div class="container mx-auto text-center">
        <h2 class="text-4xl font-bold text-blue-900 mb-12">Experience</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <!-- Card 1 -->
          <div class="bg-white rounded-lg shadow-lg p-8 transition duration-300 transform hover:scale-105 hover:shadow-2xl">
            <h3 class="text-2xl font-semibold mb-2 text-blue-900">Perusahaan A</h3>
            <p class="font-medium text-gold">Software Engineer</p>
            <p class="mt-4">Developing web applications using modern technologies such as Vue.js and Node.js.</p>
            <p class="mt-2 text-sm text-gray-500">2020 - Present</p>
          </div>

          <!-- Card 2 -->
          <div class="bg-white rounded-lg shadow-lg p-8 transition duration-300 transform hover:scale-105 hover:shadow-2xl">
            <h3 class="text-2xl font-semibold mb-2 text-blue-900">Perusahaan B</h3>
            <p class="font-medium text-gold">Frontend Developer</p>
            <p class="mt-4">Building interactive user interfaces using JavaScript technologies.</p>
            <p class="mt-2 text-sm text-gray-500">2018 - 2020</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Hobbies Section -->
<section id="hobbies" class="py-16 bg-gray-100">
  <div class="container mx-auto text-center">
    <h2 class="text-4xl font-bold text-blue-900 mb-12">Hobbies</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
      <!-- Hobby 1 -->
      <div class="bg-white rounded-lg shadow-lg p-6 transition duration-300 transform hover:scale-105 hover:shadow-2xl flex flex-col">
        <h3 class="text-2xl font-semibold mb-2 text-blue-900">Drawing</h3>
        <p class="text-gray-700 mb-4">I like drawing because I can express my feelings and thoughts.</p>
        <div class="flex justify-center mt-auto">
          <img src="https://i.pinimg.com/originals/44/d5/6e/44d56e1abff38a7e51674c0c554cd37d.jpg" alt="Coding" class="w-52 h-52 rounded-md shadow-md">
        </div>
      </div>

      <!-- Hobby 2 -->
      <div class="bg-white rounded-lg shadow-lg p-6 transition duration-300 transform hover:scale-105 hover:shadow-2xl flex flex-col">
        <h3 class="text-2xl font-semibold mb-2 text-blue-900">Photography</h3>
        <p class="text-gray-700 mb-4">Capturing moments and nature through my lens is one of my favorite pastimes.</p>
        <div class="flex justify-center mt-auto">
          <img src="https://i.pinimg.com/originals/7f/32/43/7f3243298c85462be532a252d37bf5fe.jpg" alt="Photography" class="w-52 h-52 rounded-md shadow-md">
        </div>
      </div>

      <!-- Hobby 3 -->
      <div class="bg-white rounded-lg shadow-lg p-6 transition duration-300 transform hover:scale-105 hover:shadow-2xl flex flex-col">
        <h3 class="text-2xl font-semibold mb-2 text-blue-900">Traveling</h3>
        <p class="text-gray-700 mb-4">Exploring new places and cultures inspires my creativity and broadens my perspective.</p>
        <div class="flex justify-center mt-auto">
          <img src="https://i.pinimg.com/564x/7d/83/c5/7d83c5b60ee45f5949183aa587b665c4.jpg" alt="Traveling" class="w-52 h-52 rounded-md shadow-md">
        </div>
      </div>
    </div>
  </div>
</section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
      <div class="container mx-auto text-center">
        <h2 class="text-4xl font-bold text-blue-900 mb-8">Contact me</h2>
        <form class="max-w-lg mx-auto bg-white shadow-lg rounded-lg p-8 transition duration-300 hover:shadow-2xl">
          <div class="mb-4">
            <label class="block text-left text-lg mb-2">Name:</label>
            <input type="text" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-900" placeholder="Your Name" />
          </div>
          <div class="mb-4">
            <label class="block text-left text-lg mb-2">Email:</label>
            <input type="email" class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-900" placeholder="Your Email" />
          </div>
          <div class="mb-4">
            <label class="block text-left text-lg mb-2">Message:</label>
            <textarea class="w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-900" placeholder="Your Message"></textarea>
          </div>
          <button type="submit" class="w-full bg-blue-900 text-white py-3 rounded-lg hover:bg-blue-700 transition duration-300">Send Message</button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-900 text-white py-6">
      <div class="container mx-auto text-center">
        &copy; 2024 Joko Priambodo. All rights reserved.
      </div>
    </footer>
  </div>
</template>

<script setup>
// No additional JavaScript needed
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

body {
  font-family: 'Poppins', sans-serif;
}

.text-gold {
  color: #FFD700;
}

.bg-gold {
  background-color: #FFD700;
}

.animate-fade-in-up {
  animation: fadeInUp 1s ease-in-out;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
