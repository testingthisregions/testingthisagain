<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Just Well Be Traders - Your Trading Journey Starts Here</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7fafc;
            color: #2d3748;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Navigation Bar -->
    <nav class="sticky top-0 z-50 bg-white bg-opacity-90 backdrop-blur-sm p-4 shadow-md">
        <div class="container mx-auto flex justify-between items-center">
            <!-- Logo/Site Title -->
            <a href="#" class="flex items-center space-x-2 text-2xl font-bold text-gray-800">
                <!-- Custom SVG for a different logo -->
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-teal-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
                </svg>
                <span>Just Well Be Traders</span>
            </a>

            <!-- Navigation Links (Hidden on mobile) -->
            <div class="hidden md:flex space-x-6">
                <a href="#home" class="text-gray-600 hover:text-teal-500 transition duration-300">Home</a>
                <a href="#about" class="text-gray-600 hover:text-teal-500 transition duration-300">About Us</a>
                <a href="#courses" class="text-gray-600 hover:text-teal-500 transition duration-300">Courses</a>
                <a href="#testimonials" class="text-gray-600 hover:text-teal-500 transition duration-300">Testimonials</a>
            </div>

            <!-- Mobile Menu Button -->
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-800 focus:outline-none">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white mt-4 rounded-md shadow-lg">
            <a href="#home" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 transition duration-300">Home</a>
            <a href="#about" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 transition duration-300">About Us</a>
            <a href="#courses" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 transition duration-300">Courses</a>
            <a href="#testimonials" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 transition duration-300">Testimonials</a>
        </div>
    </nav>

    <main>
        <!-- Hero Section -->
        <section id="home" class="relative min-h-screen flex items-center justify-center text-center px-4 overflow-hidden bg-white">
            <!-- Background pattern or image placeholder -->
            <div class="absolute inset-0 bg-cover bg-center opacity-10" style="background-image: url('https://placehold.co/1920x1080/f7fafc/e2e8f0?text=Abstract+Lines');"></div>
            
            <div class="relative z-10 max-w-4xl py-20">
                <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-gray-900 leading-tight">
                    Your Path to Financial Freedom Starts Here
                </h1>
                <p class="mt-4 text-lg sm:text-xl text-gray-600">
                    Discover a smarter way to trade with our proven strategies and supportive trading community.
                </p>
                <a href="#courses" class="mt-8 inline-block px-10 py-4 text-lg font-semibold text-white bg-teal-500 rounded-full hover:bg-teal-600 transition duration-300 shadow-xl transform hover:-translate-y-1">
                    Start Your Journey
                </a>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-16 md:py-24 bg-gray-100 container mx-auto rounded-xl px-4 my-10 shadow-lg">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2">
                    <img src="https://placehold.co/600x400/cbd5e0/2d3748?text=Team+of+Traders" alt="Team of Traders" class="rounded-lg shadow-xl w-full h-auto">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">About Just Well Be Traders</h2>
                    <p class="text-base md:text-lg text-gray-600 mb-4">
                        We are a collective of experienced traders and educators dedicated to demystifying the financial markets. Our mission is to equip you with practical knowledge, not just theories, so you can build a consistent and sustainable trading career.
                    </p>
                    <p class="text-base md:text-lg text-gray-600">
                        Our approach is built on clarity, discipline, and a deep understanding of market psychology. We provide personalized mentorship and a community where you can grow alongside fellow aspiring traders.
                    </p>
                </div>
            </div>
        </section>

        <!-- Courses Section -->
        <section id="courses" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-12">Our Educational Programs</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Course Card 1 -->
                    <div class="bg-gray-100 p-8 rounded-lg shadow-md transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">The Foundational Trader</h3>
                        <p class="text-gray-600 text-sm">
                            Master the core concepts of market structure, risk management, and trading psychology.
                        </p>
                        <a href="#" class="mt-4 inline-block text-teal-500 hover:text-teal-600 font-semibold transition duration-300">Learn More &rarr;</a>
                    </div>

                    <!-- Course Card 2 -->
                    <div class="bg-gray-100 p-8 rounded-lg shadow-md transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Advanced Strategy Mastery</h3>
                        <p class="text-gray-600 text-sm">
                            Build and backtest your own trading systems with advanced technical and quantitative analysis.
                        </p>
                        <a href="#" class="mt-4 inline-block text-teal-500 hover:text-teal-600 font-semibold transition duration-300">Learn More &rarr;</a>
                    </div>
                    
                    <!-- Course Card 3 -->
                    <div class="bg-gray-100 p-8 rounded-lg shadow-md transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">The Mentorship Program</h3>
                        <p class="text-gray-600 text-sm">
                            Work directly with our experts to refine your skills and achieve consistent profitability.
                        </p>
                        <a href="#" class="mt-4 inline-block text-teal-500 hover:text-teal-600 font-semibold transition duration-300">Learn More &rarr;</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials" class="py-16 md:py-24 bg-gray-50 container mx-auto rounded-xl px-4 my-10 shadow-lg">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-12">Hear from Our Community</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial Card 1 -->
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <p class="text-lg text-gray-600 italic">"The clarity and personalized support I received were invaluable. I've never felt more confident in my trades."</p>
                    <div class="flex items-center mt-6">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://placehold.co/100x100/e2e8f0/2d3748?text=JS" alt="Student Jane Smith">
                        </div>
                        <div class="ml-4">
                            <div class="text-base font-semibold text-gray-900">Jane Smith</div>
                            <div class="text-sm text-gray-600">Student</div>
                        </div>
                    </div>
                </div>

                <!-- Testimonial Card 2 -->
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <p class="text-lg text-gray-600 italic">"I finally have a system that works. The course content is well-structured and easy to apply."</p>
                    <div class="flex items-center mt-6">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://placehold.co/100x100/e2e8f0/2d3748?text=ML" alt="Student Mike Lee">
                        </div>
                        <div class="ml-4">
                            <div class="text-base font-semibold text-gray-900">Mike Lee</div>
                            <div class="text-sm text-gray-600">Student</div>
                        </div>
                    </div>
                </div>

                <!-- Testimonial Card 3 -->
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <p class="text-lg text-gray-600 italic">"This is more than just a course; it's a community. The mentorship has been a game changer for my results."</p>
                    <div class="flex items-center mt-6">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://placehold.co/100x100/e2e8f0/2d3748?text=RA" alt="Student Rachel Adams">
                        </div>
                        <div class="ml-4">
                            <div class="text-base font-semibold text-gray-900">Rachel Adams</div>
                            <div class="text-sm text-gray-600">Student</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 py-8">
        <div class="container mx-auto px-4 text-center text-gray-400">
            <p>&copy; 2024 Just Well Be Traders. All rights reserved.</p>
            <div class="flex justify-center space-x-4 mt-4">
                <a href="#" class="text-gray-400 hover:text-teal-500 transition duration-300">Twitter</a>
                <a href="#" class="text-gray-400 hover:text-teal-500 transition duration-300">Facebook</a>
                <a href="#" class="text-gray-400 hover:text-teal-500 transition duration-300">LinkedIn</a>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu -->
    <script>
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
