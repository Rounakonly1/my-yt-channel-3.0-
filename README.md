<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Editzz | Content Creator</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        .gradient-text {
            background: linear-gradient(90deg, #4f46e5, #ec4899);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .vanta-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
    </style>
</head>
<body class="bg-gray-900 text-white font-sans">
    <div id="vanta-bg" class="vanta-bg"></div>
    
    <!-- Navigation -->
    <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
        <div class="text-2xl font-bold gradient-text">Editzz</div>
        <div class="hidden md:flex space-x-8">
            <a href="#about" class="hover:text-pink-500 transition">About</a>
            <a href="#youtube" class="hover:text-pink-500 transition">YouTube</a>
            <a href="#contact" class="hover:text-pink-500 transition">Contact</a>
        </div>
        <button class="md:hidden">
            <i data-feather="menu"></i>
        </button>
    </nav>

    <!-- Hero Section -->
    <section class="container mx-auto px-6 py-20 text-center">
        <div data-aos="fade-up">
            <h1 class="text-5xl md:text-7xl font-bold mb-6">Hey, I'm <span class="gradient-text">Editzz</span></h1>
            <p class="text-xl md:text-2xl text-gray-300 mb-8 max-w-2xl mx-auto">
                Content Creator | Video Editor | Digital Artist
            </p>
            <div class="flex justify-center space-x-4">
                <a href="#youtube" class="bg-pink-600 hover:bg-pink-700 text-white px-6 py-3 rounded-full font-medium transition">
                    <i data-feather="youtube" class="inline mr-2"></i> My Channel
                </a>
                <a href="#contact" class="border border-pink-500 text-pink-500 hover:bg-pink-500 hover:text-white px-6 py-3 rounded-full font-medium transition">
                    <i data-feather="message-square" class="inline mr-2"></i> Contact Me
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container mx-auto px-6 py-20">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center gradient-text" data-aos="fade-up">About Me</h2>
            <div class="flex flex-col md:flex-row items-center gap-8">
                <div class="w-full md:w-1/3" data-aos="fade-right">
                    <img src="http://static.photos/technology/640x360/42" alt="Profile" class="rounded-xl shadow-2xl">
                </div>
                <div class="w-full md:w-2/3" data-aos="fade-left">
                    <p class="text-lg text-gray-300 mb-6">
                        Hi there! I'm Editzz, a passionate video editor. I love creating engaging content that entertains and inspires people.
                    </p>
                    <div class="flex items-center space-x-4">
                        <div class="bg-gray-800 p-4 rounded-lg">
                            <i data-feather="film" class="text-pink-500 w-8 h-8 mb-2"></i>
                            <p class="font-medium">Video Editing</p>
                        </div>
                        <div class="bg-gray-800 p-4 rounded-lg">
                            <i data-feather="image" class="text-pink-500 w-8 h-8 mb-2"></i>
                            <p class="font-medium">Graphic Design</p>
                        </div>
                        <div class="bg-gray-800 p-4 rounded-lg">
                            <i data-feather="code" class="text-pink-500 w-8 h-8 mb-2"></i>
                            <p class="font-medium">Motion Graphics</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- YouTube Section -->
    <section id="youtube" class="bg-gray-800 py-20">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center gradient-text" data-aos="fade-up">My YouTube Channel</h2>
            <div class="max-w-4xl mx-auto">
                
                <!-- Featured Shorts -->
                <h3 class="text-2xl font-bold mb-8 text-center gradient-text" data-aos="fade-up">Featured Shorts</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-12">
                    <div class="aspect-w-9 aspect-h-16" data-aos="fade-up">
                        <iframe class="w-full h-full rounded-xl shadow-xl" src="https://www.youtube.com/embed/7PGL0kNjcKg" frameborder="0" allowfullscreen></iframe>
                    </div>
                    <div class="aspect-w-9 aspect-h-16" data-aos="fade-up" data-aos-delay="200">
                        <iframe class="w-full h-full rounded-xl shadow-xl" src="https://www.youtube.com/embed/sEzRPraST_8" frameborder="0" allowfullscreen></iframe>
                    </div>
                </div>

                <div class="text-center" data-aos="fade-up">
                    <a href="http://www.youtube.com/@editzz-r1-10" target="_blank" class="inline-flex items-center bg-red-600 hover:bg-red-700 text-white px-8 py-4 rounded-full font-bold text-lg transition">
                        <i data-feather="youtube" class="w-6 h-6 mr-2"></i> Subscribe to my Channel
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container mx-auto px-6 py-20">
        <div class="max-w-2xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center gradient-text" data-aos="fade-up">Get In Touch</h2>
            <div class="bg-gray-800 p-8 rounded-xl shadow-xl" data-aos="zoom-in">
                <form id="contactForm" class="space-y-6">
                    <div>
                        <label for="name" class="block text-gray-300 mb-2">Your Name</label>
                        <input type="text" id="name" name="name" required 
                               class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-2 focus:ring-pink-500 focus:border-transparent">
                    </div>
                    <div>
                        <label for="email" class="block text-gray-300 mb-2">Email (optional)</label>
                        <input type="email" id="email" name="email" 
                               class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-2 focus:ring-pink-500 focus:border-transparent">
                    </div>
                    <div>
                        <label for="message" class="block text-gray-300 mb-2">Your Message</label>
                        <textarea id="message" name="message" rows="4" required
                                  class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-2 focus:ring-pink-500 focus:border-transparent"></textarea>
                    </div>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4">
                            <a href="https://discord.com/users/pe4c_e" target="_blank" class="bg-indigo-600 hover:bg-indigo-700 text-white p-3 rounded-full transition">
                                <i data-feather="message-circle" class="w-6 h-6"></i>
                            </a>
                            <span class="text-gray-400">Discord: pe4c_e</span>
                        </div>
                        <button type="submit" class="bg-pink-600 hover:bg-pink-700 text-white px-6 py-3 rounded-lg font-medium transition">
                            Send Message
                        </button>
                    </div>
                </form>
                <div id="formResponse" class="hidden mt-4 p-4 rounded-lg"></div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 py-8 border-t border-gray-800">
        <div class="container mx-auto px-6 text-center">
            <div class="flex justify-center space-x-6 mb-6">
                <a href="http://www.youtube.com/@editzz-r1-10" target="_blank" class="text-gray-400 hover:text-red-500 transition">
                    <i data-feather="youtube" class="w-6 h-6"></i>
                </a>
                <a href="https://discord.com/users/pe4c_e" target="_blank" class="text-gray-400 hover:text-indigo-500 transition">
                    <i data-feather="message-circle" class="w-6 h-6"></i>
                </a>
            </div>
            <p class="text-gray-500">© 2023 Editzz. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <script>
        VANTA.GLOBE({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0xec4899,
            backgroundColor: 0x111827,
            size: 0.8
        });
        
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });
        
        feather.replace();

        // Contact form handling
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const form = e.target;
            const formData = new FormData(form);
            const responseDiv = document.getElementById('formResponse');
            
            // Simulate form submission (in a real app, you'd send to a server)
            responseDiv.classList.remove('hidden', 'bg-red-500', 'bg-green-500');
            responseDiv.innerHTML = '<div class="animate-pulse">Sending message...</div>';
            
            setTimeout(() => {
                responseDiv.innerHTML = `
                    <div class="flex items-center">
                        <i data-feather="check-circle" class="text-green-400 mr-2"></i>
                        <span>Message sent! I'll get back to you soon.</span>
                    </div>
                `;
                responseDiv.classList.add('bg-green-500');
                form.reset();
                feather.replace();
            }, 1500);
        });
        
        // Mobile menu toggle
        document.querySelector('button.md\\:hidden').addEventListener('click', function() {
            const menu = document.querySelector('.md\\:flex.space-x-8');
            menu.classList.toggle('hidden');
            menu.classList.toggle('flex');
            menu.classList.toggle('flex-col');
            menu.classList.toggle('absolute');
            menu.classList.toggle('top-16');
            menu.classList.toggle('right-6');
            menu.classList.toggle('bg-gray-900');
            menu.classList.toggle('p-4');
            menu.classList.toggle('rounded-lg');
            menu.classList.toggle('shadow-xl');
            menu.classList.toggle('space-y-4');
            menu.classList.toggle('space-x-0');
        });
    </script>
</body>
</html>
