<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fahad Majeed | Computer Vision Researcher</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
    }
  </script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body class="bg-gray-50 dark:bg-gray-900 text-gray-900 dark:text-gray-100 font-sans transition-colors duration-500">

  <!-- Dark Mode Toggle -->
  <div class="fixed top-4 right-6 z-50">
    <button id="theme-toggle" class="p-2 rounded-full bg-gray-200 dark:bg-gray-800 shadow-lg transition hover:scale-110">
      <span id="theme-toggle-light" class="hidden">🌞</span>
      <span id="theme-toggle-dark">🌙</span>
    </button>
  </div>

  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center 
                 bg-gradient-to-br from-blue-600 via-indigo-700 to-purple-700 text-white">
    <img src="Fahad.png" alt="Fahad Majeed" 
         class="w-40 h-40 rounded-full shadow-2xl mb-6 border-4 border-white animate-bounce">
    <h1 class="text-4xl md:text-6xl font-bold">Fahad Majeed</h1>
    <p class="mt-4 text-xl md:text-2xl">PhD Scholar | Computer Vision Researcher | Sports Video Analyst</p>
    <div class="flex gap-4 mt-6">
      <a href="https://www.linkedin.com/in/fahad-majeed/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
      </a>
      <a href="https://github.com/MrFahad" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
      </a>
      <a href="https://tinyurl.com/38jbwxvx" target="_blank">
        <img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" />
      </a>
    </div>
  </section>

  <!-- About Section -->
  <section class="max-w-5xl mx-auto px-6 py-16" data-aos="fade-up">
    <h2 class="text-3xl font-bold mb-4">👋 About Me</h2>
    <p class="text-lg leading-relaxed">
      I am a <b>PhD Scholar in Computer Vision</b> with over <b>8 years of cross-disciplinary experience</b> in academia and industry.
      My expertise lies in <b>deep learning-based pipelines</b> for <b>sports video analytics</b> and <b>large-scale data processing</b>.
    </p>
  </section>

  <!-- Areas of Interest -->
  <section class="bg-gray-100 dark:bg-gray-800 py-16" data-aos="fade-right">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-6">🎓 Areas of Interest</h2>
      <ul class="space-y-3 text-lg">
        <li>📌 Multi-modal Deep Learning & Graph-based Reasoning</li>
        <li>🧠 Object Detection, Segmentation, GNN, FPN, Temporal Modeling</li>
        <li>⚽ Real-time tracking, ball trajectory prediction</li>
        <li>☁️ Distributed pipelines (Apache Spark, Cloud GPU)</li>
      </ul>
    </div>
  </section>

  <!-- Skills -->
  <section class="max-w-6xl mx-auto px-6 py-16" data-aos="zoom-in">
    <h2 class="text-3xl font-bold mb-8">📈 Key Technical Skills</h2>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="p-6 bg-white dark:bg-gray-700 shadow-xl rounded-2xl hover:scale-105 transition">
        <h3 class="font-bold text-xl mb-3">🧠 ML / DL</h3>
        <p>PyTorch, TensorFlow, CNNs, Transformers, GNNs, Attention, SepFormer</p>
      </div>
      <div class="p-6 bg-white dark:bg-gray-700 shadow-xl rounded-2xl hover:scale-105 transition">
        <h3 class="font-bold text-xl mb-3">📊 Computer Vision</h3>
        <p>YOLO (v3–12, YOLOE), Faster R-CNN, Mask R-CNN, Pose Estimation, Tracking</p>
      </div>
      <div class="p-6 bg-white dark:bg-gray-700 shadow-xl rounded-2xl hover:scale-105 transition">
        <h3 class="font-bold text-xl mb-3">⚙️ Tools & Platforms</h3>
        <p>Python, Docker, LaTeX, Streamlit, Flask, Google Colab, Kaggle</p>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section class="bg-gray-100 dark:bg-gray-800 py-16" data-aos="fade-left">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-6">📚 Projects</h2>
      <div class="space-y-8">
        <div class="p-6 bg-white dark:bg-gray-700 shadow-lg rounded-xl">
          <h3 class="font-bold text-xl">⚽ Intelligent Soccer Analytics Framework</h3>
          <p>Pipeline for player detection, pose-based action recognition, and tactical analysis.</p>
        </div>
        <div class="p-6 bg-white dark:bg-gray-700 shadow-lg rounded-xl">
          <h3 class="font-bold text-xl">📹 Real-time Multi-camera Analytics</h3>
          <p>Calibration, player re-ID, action tube generation for 1000+ hours of soccer data.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Publications -->
  <section class="max-w-5xl mx-auto px-6 py-16" data-aos="fade-up">
    <h2 class="text-3xl font-bold mb-6">🧪 Publications</h2>
    <ul class="list-disc list-inside space-y-3">
      <li>Scientific Reports (Nature), 2025 – Soccer ball–player interactions (GCN)</li>
      <li>VISAPP 2025 – ReST: High-Precision Soccer Player Tracking</li>
      <li>CVPRW 2024 – MV-Soccer: Motion-Vector Augmented Tracking</li>
    </ul>
  </section>

  <!-- Contact -->
  <section class="bg-gradient-to-r from-indigo-600 to-blue-500 text-white py-16" data-aos="fade-in">
    <div class="max-w-5xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold mb-4">📫 Get in Touch</h2>
      <p>Email: <a href="mailto:fahad_majeed@yahoo.com" class="underline">fahad_majeed@yahoo.com</a></p>
      <p>Location: <a href="https://www.google.com/maps/place/Education+City,+Doha,+Qatar" target="_blank" class="underline">Doha, Qatar</a></p>
      <a href="https://mrfahad.github.io" target="_blank">
        <img src="https://img.shields.io/badge/Website-mrfahad.github.io-blue?style=for-the-badge" class="mt-4 mx-auto" />
      </a>
    </div>
  </section>

  <!-- Scripts -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 1000, once: true });

    // Dark Mode Toggle Logic
    const themeToggle = document.getElementById('theme-toggle');
    const lightIcon = document.getElementById('theme-toggle-light');
    const darkIcon = document.getElementById('theme-toggle-dark');

    if (localStorage.theme === 'dark' || 
        (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      document.documentElement.classList.add('dark');
      lightIcon.classList.remove('hidden');
      darkIcon.classList.add('hidden');
    } else {
      document.documentElement.classList.remove('dark');
      darkIcon.classList.remove('hidden');
      lightIcon.classList.add('hidden');
    }

    themeToggle.addEventListener('click', () => {
      document.documentElement.classList.toggle('dark');
      if (document.documentElement.classList.contains('dark')) {
        localStorage.theme = 'dark';
        lightIcon.classList.remove('hidden');
        darkIcon.classList.add('hidden');
      } else {
        localStorage.theme = 'light';
        darkIcon.classList.remove('hidden');
        lightIcon.classList.add('hidden');
      }
    });
  </script>
</body>
</html>
