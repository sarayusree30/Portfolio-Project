<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarayu Sree - UI/UX Designer Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for social media icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- Google Font: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth; /* Smooth scrolling for anchor links */
        }
        /* Custom scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #888;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-sm py-4 fixed w-full z-10">
        <nav class="container mx-auto flex justify-between items-center px-4">
            <a href="#hero" class="text-2xl font-bold text-gray-900 rounded-lg p-2 hover:bg-gray-100 transition-colors duration-300">Sarayu Sree</a>
            <div class="hidden md:flex space-x-6">
                <a href="#about" class="text-gray-600 hover:text-gray-900 font-medium transition-colors duration-300 rounded-lg p-2 hover:bg-gray-100">About</a>
                <a href="#work" class="text-gray-600 hover:text-gray-900 font-medium transition-colors duration-300 rounded-lg p-2 hover:bg-gray-100">Work</a>
                <a href="#contact" class="text-gray-600 hover:text-gray-900 font-medium transition-colors duration-300 rounded-lg p-2 hover:bg-gray-100">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 focus:outline-none focus:ring-2 focus:ring-gray-300 rounded-md p-2">
                <i class="fas fa-bars text-xl"></i>
            </button>
        </nav>
        <!-- Mobile Menu Overlay -->
        <div id="mobile-menu" class="hidden md:hidden fixed inset-0 bg-white bg-opacity-95 z-20 flex flex-col items-center justify-center space-y-8">
            <button id="close-mobile-menu" class="absolute top-4 right-4 text-gray-600 focus:outline-none focus:ring-2 focus:ring-gray-300 rounded-md p-2">
                <i class="fas fa-times text-2xl"></i>
            </button>
            <a href="#about" class="text-gray-800 text-3xl font-medium hover:text-gray-900 transition-colors duration-300" onclick="document.getElementById('mobile-menu').classList.add('hidden')">About</a>
            <a href="#work" class="text-gray-800 text-3xl font-medium hover:text-gray-900 transition-colors duration-300" onclick="document.getElementById('mobile-menu').classList.add('hidden')">Work</a>
            <a href="#contact" class="text-gray-800 text-3xl font-medium hover:text-gray-900 transition-colors duration-300" onclick="document.getElementById('mobile-menu').classList.add('hidden')">Contact</a>
            <div class="flex space-x-6 mt-8">
                <a href="https://www.linkedin.com/in/sarayu-sree-mandala-a94691275/" target="_blank" rel="noopener noreferrer" class="text-gray-600 hover:text-blue-700 transition-colors duration-300 text-4xl rounded-full p-2 hover:bg-gray-100">
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="https://www.behance.net/sarayusree" target="_blank" rel="noopener noreferrer" class="text-gray-600 hover:text-blue-600 transition-colors duration-300 text-4xl rounded-full p-2 hover:bg-gray-100">
                    <i class="fab fa-behance-square"></i>
                </a>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="relative bg-gradient-to-br from-blue-50 to-indigo-100 min-h-screen flex flex-col justify-center items-center text-center px-4 pt-20">
            <div class="max-w-4xl mx-auto py-16">
                <h1 class="text-5xl md:text-7xl font-extrabold text-gray-900 leading-tight mb-6 animate-fade-in-up">
                    Hello, I'm <span class="text-indigo-600">Sarayu Sree</span>.
                </h1>
                <p class="text-xl md:text-2xl text-gray-700 mb-8 animate-fade-in-up delay-200">
                    A passionate UI/UX Designer crafting intuitive and delightful digital experiences.
                </p>
                <a href="#work" class="inline-block bg-indigo-600 text-white px-8 py-4 rounded-full text-lg font-semibold shadow-lg hover:bg-indigo-700 transition-all duration-300 transform hover:scale-105 animate-fade-in-up delay-400">
                    View My Work <i class="fas fa-arrow-right ml-2"></i>
                </a>
            </div>
        </section>


        <!-- About Section -->
        <section id="about" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4 max-w-4xl">
                <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">About Me</h2>
                <div class="flex flex-col md:flex-row items-center md:space-x-12">
                    <div class="md:w-1/3 mb-8 md:mb-0">
                        <img src="https://placehold.co/400x400/E0E7FF/4F46E5?text=Sarayu+Sree" alt="Sarayu Sree" class="w-full h-auto rounded-xl shadow-lg object-cover">
                    </div>
                    <div class="md:w-2/3 text-lg text-gray-700 leading-relaxed">
                        <p class="mb-4">
                            Hi there! I'm Sarayu Sree, a UI/UX Designer dedicated to creating user-centered designs that are both functional and aesthetically pleasing. My journey in design began with a fascination for how people interact with technology, leading me to explore the principles of usability, accessibility, and visual design.
                        </p>
                        <p class="mb-4">
                            I thrive on solving complex problems through thoughtful design, transforming ideas into intuitive interfaces. My process involves thorough research, wireframing, prototyping, and iterative testing to ensure the final product truly meets user needs and business goals.
                        </p>
                        <p>
                            When I'm not designing, you can find me exploring new design trends, sketching, or enjoying a good book. I'm always eager to learn and grow, and I believe in the power of collaboration to create truly impactful experiences.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Work Section (Projects) -->
        <section id="work" class="py-16 md:py-24 bg-gray-50">
            <div class="container mx-auto px-4 max-w-6xl">
                <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">My Work</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Project Card 1 -->
                    <a href="newweb.html" target="_blank" rel="noopener noreferrer" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transform hover:-translate-y-2 transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Project+1" alt="Project 1 Thumbnail" class="w-full h-64 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">Mobile App Redesign</h3>
                            <p class="text-gray-600">A comprehensive redesign of a popular mobile application focusing on user experience and visual appeal.</p>
                            <span class="text-indigo-600 mt-3 block font-medium">View on Behance &rarr;</span>
                        </div>
                    </a>

                    <!-- Project Card 2 -->
                    <a href="https://www.behance.net/sarayusree" target="_blank" rel="noopener noreferrer" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transform hover:-translate-y-2 transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Project+2" alt="Project 2 Thumbnail" class="w-full h-64 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">E-commerce Website UI</h3>
                            <p class="text-gray-600">Designing an intuitive and engaging user interface for an online retail platform.</p>
                            <span class="text-indigo-600 mt-3 block font-medium">View on Behance &rarr;</span>
                        </div>
                    </a>

                    <!-- Project Card 3 -->
                    <a href="https://www.behance.net/sarayusree" target="_blank" rel="noopener noreferrer" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transform hover:-translate-y-2 transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Project+3" alt="Project 3 Thumbnail" class="w-full h-64 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">Dashboard UX Improvement</h3>
                            <p class="text-gray-600">Enhancing the user experience of a complex data dashboard for better readability and interaction.</p>
                            <span class="text-indigo-600 mt-3 block font-medium">View on Behance &rarr;</span>
                        </div>
                    </a>

                    <!-- Project Card 4 -->
                    <a href="https://www.behance.net/sarayusree" target="_blank" rel="noopener noreferrer" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transform hover:-translate-y-2 transition-all duration-300">
                        <img src="https://placehold.co/600x400/D1D5DB/1F2937?text=Project+4" alt="Project 4 Thumbnail" class="w-full h-64 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">Branding & Identity</h3>
                            <p class="text-gray-600">Developing a cohesive brand identity system, including logo and style guide.</p>
                            <span class="text-indigo-600 mt-3 block font-medium">View on Behance &rarr;</span>
                        </div>
                    </a>

                    <!-- Add more project cards as needed, linking to specific Behance projects -->

                </div>
                <div class="text-center mt-12">
                    <p class="text-lg text-gray-700 mb-4">
                        Chumma why tension:
                    </p>
                    <a href="https://www.behance.net/sarayusree" target="_blank" rel="noopener noreferrer" class="inline-block bg-gray-800 text-white px-8 py-4 rounded-full text-lg font-semibold shadow-lg hover:bg-gray-900 transition-all duration-300 transform hover:scale-105">
                        Visit my Portfolio <i class="fab fa-behance ml-2"></i>
                    </a>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4 max-w-xl text-center">
                <h2 class="text-4xl font-bold text-gray-900 mb-8">Get In Touch</h2>
                <p class="text-lg text-gray-700 mb-8">
                    Have a project in mind or just want to say hello? Feel free to reach out!
                </p>
                <a href="mailto:sarayusree.design@example.com" class="inline-block bg-indigo-600 text-white px-8 py-4 rounded-full text-lg font-semibold shadow-lg hover:bg-indigo-700 transition-all duration-300 transform hover:scale-105">
                    Email Me <i class="fas fa-envelope ml-2"></i>
                </a>
                <p class="text-gray-500 text-sm mt-4">
                    (Note: This is a placeholder email. Please replace with Sarayu Sree's actual email.)
                </p>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 flex flex-col md:flex-row justify-between items-center text-center md:text-left">
            <p class="mb-4 md:mb-0">&copy; <span id="current-year"></span> Sarayu Sree. All rights reserved.</p>
            <div class="flex space-x-6">
                <a href="https://www.linkedin.com/in/sarayu-sree-mandala-a94691275/" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-blue-400 transition-colors duration-300 text-2xl rounded-full p-2 hover:bg-gray-700">
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="https://www.behance.net/sarayusree" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-blue-300 transition-colors duration-300 text-2xl rounded-full p-2 hover:bg-gray-700">
                    <i class="fab fa-behance-square"></i>
                </a>
            </div>
        </div>
    </footer>

    <script>
        // Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Mobile menu toggle functionality
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const closeMobileMenuButton = document.getElementById('close-mobile-menu');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.remove('hidden');
        });

        closeMobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.add('hidden');
        });

        // Close mobile menu when a link is clicked (handled by inline onclick in HTML)
    </script>
</body>
</html>
