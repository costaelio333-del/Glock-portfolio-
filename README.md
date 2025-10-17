# Ᏽ𐌋⏱️𐌂𐌊
Proof of work (POW)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ash & Black Gloss Portfolio - [Ᏽ𐌋⏱️𐌂𐌊]</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons for professional graphics -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Define Inter font and set the body background/text colors */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #000000; /* True Black background */
            color: #d1d5db; /* Ash/Gray Text (gray-300) */
        }
        /* Custom scrollbar for a darker aesthetic */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #111;
        }
        ::-webkit-scrollbar-thumb {
            background: #444;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }

        /* Glossy effect for cards and interactive elements */
        .glossy-card {
            background-color: #0a0a0a; /* Slightly off-black for depth */
            transition: all 0.3s ease-in-out;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.7), 0 0 0 1px rgba(100, 100, 100, 0.2); /* Subtle edge ring and deep shadow */
        }
        .glossy-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.9), 0 0 0 1px rgba(150, 150, 150, 0.3); /* Lift and intensify the gloss/shadow on hover */
        }

        /* Smooth scroll behavior */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-black/95 backdrop-blur-sm border-b border-neutral-800">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#home" class="text-xl font-extrabold text-gray-100 hover:text-gray-400 transition">
                [Your Name]
            </a>
            <div class="space-x-4 hidden md:flex">
                <a href="#about" class="text-gray-300 hover:text-gray-100 transition">About</a>
                <a href="#projects" class="text-gray-300 hover:text-gray-100 transition">Projects</a>
                <a href="#skills" class="text-gray-300 hover:text-gray-100 transition">Skills</a>
                <a href="#contact" class="text-gray-300 hover:text-gray-100 transition">Contact</a>
            </div>
            <!-- Mobile Menu Placeholder (simple scroll) -->
            <button class="md:hidden text-gray-300 focus:outline-none" onclick="document.getElementById('mobile-menu').classList.toggle('hidden')">
                <i data-lucide="menu" class="w-6 h-6"></i>
            </button>
        </nav>
        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden border-t border-neutral-800">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-neutral-900">About</a>
                <a href="#projects" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-neutral-900">Projects</a>
                <a href="#skills" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-neutral-900">Skills</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-neutral-900">Contact</a>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto">
        <!-- 1. Hero Section -->
        <section id="home" class="min-h-screen flex items-center justify-center text-center p-8">
            <div class="space-y-6 max-w-4xl">
                <div class="mx-auto w-32 h-32 rounded-full overflow-hidden border-2 border-gray-700/50 shadow-xl mb-4">
                    <!-- Placeholder image URL -->
                    <img src="https://placehold.co/128x128/111/D1D5DB?text=PFP" alt="Profile Picture" class="object-cover w-full h-full" onerror="this.onerror=null;this.src='https://placehold.co/128x128/111/D1D5DB?text=PFP';">
                </div>
                <h1 class="text-5xl sm:text-7xl font-extrabold tracking-tighter text-gray-100">
                    Hello, I'm <span class="text-gray-400">Jane Doe</span>.
                </h1>
                <p class="text-xl sm:text-2xl text-gray-400 font-light">
                    I build responsive, high-performance web applications using modern stacks.
                </p>
                <a href="#projects" class="inline-flex items-center space-x-2 px-6 py-3 bg-gray-900 text-gray-100 font-medium rounded-xl hover:bg-gray-800 transition glossy-card shadow-inner">
                    <span>View My Work</span>
                    <i data-lucide="arrow-right" class="w-5 h-5"></i>
                </a>
            </div>
        </section>

        <!-- 2. About Me Section -->
        <section id="about" class="py-20 px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-100">About Me</h2>
            <div class="max-w-3xl mx-auto p-6 rounded-3xl glossy-card">
                <p class="mb-4 text-gray-300 leading-relaxed">
                    I am a passionate Full Stack Developer with 5+ years of experience transforming complex ideas into elegant digital solutions. My expertise lies in front-end architecture and backend API development, specializing in performance optimization and user experience.
                </p>
                <p class="mb-4 text-gray-300 leading-relaxed">
                    I thrive in dynamic environments and am constantly seeking to master new technologies. This portfolio showcases my commitment to clean code and impactful design, reflecting my dedication to the craft of software engineering.
                </p>
                <p class="text-gray-300 leading-relaxed">
                    When I'm not coding, you can find me exploring the latest trends in UI/UX design or contributing to open-source projects.
                </p>
            </div>
        </section>

        <!-- 3. Projects Section -->
        <section id="projects" class="py-20 px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-100">Recent Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                <!-- Project Card 1 -->
                <div class="p-6 rounded-3xl glossy-card flex flex-col">
                    <i data-lucide="bar-chart-3" class="w-10 h-10 text-gray-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-2 text-gray-100">Data Visualization Dashboard</h3>
                    <p class="text-gray-400 mb-4 flex-grow">
                        A real-time analytics dashboard built with React and D3.js, featuring interactive charts and serverless API integration.
                    </p>
                    <div class="flex flex-wrap gap-2 text-sm mt-4">
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">React</span>
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">D3.js</span>
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">Node.js</span>
                    </div>
                    <div class="mt-6 space-x-4">
                        <a href="#" class="text-gray-400 hover:text-gray-100 transition inline-flex items-center">
                            Live Demo <i data-lucide="external-link" class="w-4 h-4 ml-1"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-gray-100 transition inline-flex items-center">
                            Code <i data-lucide="github" class="w-4 h-4 ml-1"></i>
                        </a>
                    </div>
                </div>

                <!-- Project Card 2 -->
                <div class="p-6 rounded-3xl glossy-card flex flex-col">
                    <i data-lucide="shopping-cart" class="w-10 h-10 text-gray-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-2 text-gray-100">E-Commerce Platform</h3>
                    <p class="text-gray-400 mb-4 flex-grow">
                        A scalable mock e-commerce site with full checkout functionality, user authentication, and admin panel.
                    </p>
                    <div class="flex flex-wrap gap-2 text-sm mt-4">
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">Angular</span>
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">Firebase</span>
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">Tailwind</span>
                    </div>
                    <div class="mt-6 space-x-4">
                        <a href="#" class="text-gray-400 hover:text-gray-100 transition inline-flex items-center">
                            Live Demo <i data-lucide="external-link" class="w-4 h-4 ml-1"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-gray-100 transition inline-flex items-center">
                            Code <i data-lucide="github" class="w-4 h-4 ml-1"></i>
                        </a>
                    </div>
                </div>

                <!-- Project Card 3 -->
                <div class="p-6 rounded-3xl glossy-card flex flex-col">
                    <i data-lucide="gamepad-2" class="w-10 h-10 text-gray-400 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-2 text-gray-100">Casual Mobile Game</h3>
                    <p class="text-gray-400 mb-4 flex-grow">
                        A simple 2D puzzle game built using pure JavaScript and Canvas, optimized for touch interaction.
                    </p>
                    <div class="flex flex-wrap gap-2 text-sm mt-4">
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">JavaScript</span>
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">HTML5 Canvas</span>
                        <span class="bg-neutral-800 text-gray-400 px-3 py-1 rounded-full">Mobile First</span>
                    </div>
                    <div class="mt-6 space-x-4">
                        <a href="#" class="text-gray-400 hover:text-gray-100 transition inline-flex items-center">
                            Live Demo <i data-lucide="external-link" class="w-4 h-4 ml-1"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-gray-100 transition inline-flex items-center">
                            Code <i data-lucide="github" class="w-4 h-4 ml-1"></i>
                        </a>
                    </div>
                </div>

            </div>
        </section>

        <!-- 4. Skills Section -->
        <section id="skills" class="py-20 px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-100">Technical Skills</h2>

            <div class="max-w-4xl mx-auto">
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6">

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="react" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">React & Next.js</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="bar-chart" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">Data Science</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="wrench" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">Python/Django</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="server" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">Serverless (AWS/GCP)</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="database" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">SQL/NoSQL</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="git-fork" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">Git & CI/CD</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="figma" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">UI/UX Design</span>
                    </div>

                    <!-- Skill Item -->
                    <div class="p-4 rounded-xl text-center glossy-card">
                        <i data-lucide="layers" class="w-8 h-8 mx-auto text-gray-400 mb-2"></i>
                        <span class="text-gray-300">Docker & K8s</span>
                    </div>

                </div>
            </div>
        </section>


        <!-- 5. Contact Section -->
        <section id="contact" class="py-20 px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-100">Get In Touch</h2>
            <div class="max-w-2xl mx-auto p-8 rounded-3xl glossy-card">
                <p class="text-center text-gray-400 mb-8">
                    Have a project in mind or just want to say hello? Send me a message, and I'll get back to you as soon as possible.
                </p>

                <form class="space-y-4">
                    <div>
                        <label for="name" class="block text-sm font-medium text-gray-300 mb-1">Name</label>
                        <input type="text" id="name" name="name" class="w-full p-3 rounded-xl bg-neutral-900 border border-neutral-800 text-gray-200 focus:ring-gray-600 focus:border-gray-600 outline-none" placeholder="Your Name">
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-300 mb-1">Email</label>
                        <input type="email" id="email" name="email" class="w-full p-3 rounded-xl bg-neutral-900 border border-neutral-800 text-gray-200 focus:ring-gray-600 focus:border-gray-600 outline-none" placeholder="you@example.com">
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-300 mb-1">Message</label>
                        <textarea id="message" name="message" rows="4" class="w-full p-3 rounded-xl bg-neutral-900 border border-neutral-800 text-gray-200 focus:ring-gray-600 focus:border-gray-600 outline-none" placeholder="Tell me about your project..."></textarea>
                    </div>
                    <button type="submit" class="w-full glossy-card px-6 py-3 bg-gray-900 text-gray-100 font-semibold rounded-xl hover:bg-gray-800 transition shadow-inner">
                        Send Message
                    </button>
                </form>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="mt-20 border-t border-neutral-800 p-8 text-center">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center text-sm text-gray-500">
            <p>&copy; 2025 [Your Name]. All rights reserved.</p>
            <div class="flex space-x-4 mt-4 md:mt-0">
                <a href="#" class="hover:text-gray-300 transition"><i data-lucide="github" class="w-5 h-5"></i></a>
                <a href="#" class="hover:text-gray-300 transition"><i data-lucide="linkedin" class="w-5 h-5"></i></a>
                <a href="mailto:example@domain.com" class="hover:text-gray-300 transition"><i data-lucide="mail" class="w-5 h-5"></i></a>
            </div>
        </div>
    </footer>

    <!-- Initialize Lucide Icons -->
    <script>
        lucide.createIcons();
    </script>
</body>
</html>

