<template>
  <div :class="{ 'dark': isDarkMode }">
    <!-- Navbar -->
    <nav class="flex items-center justify-between px-4 py-3 bg-gray-900 text-white">
      <div class="text-xl font-bold">My Name is Test Portfolio</div>
    </nav>

    <!-- Content -->
    <div class="container mx-auto py-8 px-4">
      <h1 class="text-4xl font-bold mb-4">Welcome to My Portfolio</h1>
      <p class="text-lg mb-6">This is a showcase of my work and skills.</p>

      <!-- Mockup Profile Section -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <!-- Profile Image -->
        <div class="col-span-1 md:col-span-1">
          <img src="/testProfile.jpg" alt="Profile Image" class="rounded-full mx-auto w-48 h-48 object-cover shadow-lg">
        </div>
        <!-- Profile Details -->
        <div class="col-span-2 md:col-span-2">
          <h2 class="text-2xl font-bold mb-2">About Me</h2>
          <p class="mb-4">I am a passionate developer with expertise in web development. I love to build creative and innovative solutions to solve real-world problems.</p>
          <h3 class="text-xl font-bold mb-2">Skills</h3>
          <ul class="list-disc pl-4">
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>Vue.js</li>
            <li>Nuxt.js</li>
            <li>Tailwind CSS</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-4 text-center">
      <p>© 2024 Your Name. All rights reserved.</p>
    </footer>
  </div>
</template>
