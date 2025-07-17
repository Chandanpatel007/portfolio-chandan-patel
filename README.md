# portfolio.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio.</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-sky-100 text-gray-900 font-sans scroll-smooth">

  <!-- Navbar -->
  <header class="bg-white shadow fixed top-0 w-full z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center px-6 py-4">
      <h1 class="text-2xl font-bold text-blue-600">Chandan Patel</h1>
      <nav class="space-x-4 text-gray-700 font-medium">
        <a href="#home" class="hover:text-blue-600">Home</a>
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#skills" class="hover:text-blue-600">Skills</a>
        <a href="#projects" class="hover:text-blue-600">Projects</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Home -->
  <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-br from-blue-100 to-white pt-20">
    <div class="text-center relative">
      <img src="images/WIN_20250715_16_13_07_Pro.jpg" alt="profile photo" class ="max-auto w-64 h-64 rounded-full mb-8 shadow-lg border-4 border-yellow-600 mx-auto">
      <h2 class="text-4xl md:text-5xl font-bold mb-4">Hi, I'm <span class="text-blue-600">Chandan Patel</span></h2>
      <p class="text-lg md:text-xl mb-6">Python Developer</p>
      <a href="#projects" class="inline-block bg-blue-600 text-white px-6 py-3 rounded-full hover:bg-blue-700 transition"></a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-16 px-4 bg-white">
    <div class="max-w-5xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">About Me</h3>
      <p class="text-lg text-gray-700 leading-relaxed">
        I'm a self-motivated developer with a passion for coding and solving problems. I specialize in building responsive and accessible web applications using modern tools and frameworks. I love turning ideas into reality using code.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-16 px-4 bg-gray-100">
    <div class="max-w-5xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Skills</h3>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-lg text-gray-800">
        <div class="bg-white p-4 rounded shadow">HTML</div>
        <div class="bg-white p-4 rounded shadow">CSS</div>
        <div class="bg-white p-4 rounded shadow">JavaScript</div>
        <div class="bg-white p-4 rounded shadow">Python</div>
        <div class="bg-white p-4 rounded shadow">Django</div>
        <div class="bg-white p-4 rounded shadow">Git & GitHub</div>
        <div class="bg-white p-4 rounded shadow">Node.js</div>
        <div class="bg-white p-4 rounded shadow">SQL</div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-16 px-4 bg-white">
    <div class="max-w-6xl mx-auto">
      <h3 class="text-3xl font-bold mb-10 text-center">Projects</h3>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Project 1 -->
        <div class="bg-gray-100 shadow-md rounded-xl p-5">
          <h4 class="text-xl font-semibold mb-2">Vegetable Disease Detection using Cloud AI</h4>
          <p class="text-gray-700 mb-4">Enabled early detection and classification of diseases in crops using "vegetable plant images".</p>
          <p class="text-gray-700 mb-4">Created a forntend(Android/Web)to allow users to upload plant images and view predictions.</p>
          <p class="text-gray-700 mb-4"> Android app or web forntend to upload plant image.</p>
          <a href="#" class="text-blue-600 hover:underline">View Project</a>
        </div>

        <!-- Project 2 -->
        <div class="bg-gray-100 shadow-md rounded-xl p-5">
          <h4 class="text-xl font-semibold mb-2">Face Mask Detection</h4>
          <p class="text-gray-700 mb-4">Developed a CNN model to accurately detect face mask in real-time video streams.</p>
          <p class="text-gray-700 mb-4">Used OpenCV and TensorFlow/keras for model training and live video stream analysis.</p>
          <p class="text-gray-700 mb-4">Integrated the solution into a simple web interface for demo purposes.</p>
          <a href="#" class="text-blue-600 hover:underline">View Project</a>
        </div>

        <!-- Project 3 -->
        <div class="bg-gray-100 shadow-md rounded-xl p-5">
          <h4 class="text-xl font-semibold mb-2">E-commerce</h4>
          <p class="text-gray-700 mb-4">E-kart project is allow users to browse,purchase and tracks the projects.</p>
          <p class="text-gray-700 mb-4">It features real-time inventory updates,secure payments and order tracking.</p>
          <p class="text-gray-700 mb-4">Built with react, Node JS and MongoDB, it ensures scalability and security.</p>
          <a href="#" class="text-blue-600 hover:underline">View Project</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-4 bg-gray-100">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Contact Me</h3>
      <form class="space-y-6 max-w-xl mx-auto">
        <input type="text" placeholder="Your Name" class="w-full p-3 border border-gray-300 rounded" required />
        <input type="email" placeholder="Your Email" class="w-full p-3 border border-gray-300 rounded" required />
        <textarea rows="5" placeholder="Your Message" class="w-full p-3 border border-gray-300 rounded" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded hover:bg-blue-700 transition">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white text-center py-6 text-sm text-gray-600">
    © 2025 Chandan Patel. All rights reserved.
  </footer>

</body>
</html>
