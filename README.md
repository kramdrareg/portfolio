<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mark Gerard S. Andrada - Technical Support Specialist</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 40px rgba(0,0,0,0.1); }
        .skill-bar { transition: width 1s ease-in-out; }
        .animate-fade-in { animation: fadeIn 0.6s ease-in; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .section-active { opacity: 1; transform: translateY(0); }
        .section-hidden { opacity: 0; transform: translateY(30px); }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="fixed top-0 w-full bg-white/90 backdrop-blur-sm shadow-sm z-50">
        <div class="max-w-6xl mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <h1 class="text-xl font-bold text-gray-800">Mark Gerard Andrada</h1>
                <div class="hidden md:flex space-x-6">
                    <a href="#home" class="nav-link text-gray-600 hover:text-blue-600 transition-colors">Home</a>
                    <a href="#about" class="nav-link text-gray-600 hover:text-blue-600 transition-colors">About</a>
                    <a href="#experience" class="nav-link text-gray-600 hover:text-blue-600 transition-colors">Experience</a>
                    <a href="#skills" class="nav-link text-gray-600 hover:text-blue-600 transition-colors">Skills</a>
                    <a href="#contact" class="nav-link text-gray-600 hover:text-blue-600 transition-colors">Contact</a>
                </div>
                <button id="mobile-menu-btn" class="md:hidden text-gray-600">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
            <!-- Mobile Menu -->
            <div id="mobile-menu" class="hidden md:hidden mt-4 pb-4">
                <a href="#home" class="block py-2 text-gray-600 hover:text-blue-600">Home</a>
                <a href="#about" class="block py-2 text-gray-600 hover:text-blue-600">About</a>
                <a href="#experience" class="block py-2 text-gray-600 hover:text-blue-600">Experience</a>
                <a href="#skills" class="block py-2 text-gray-600 hover:text-blue-600">Skills</a>
                <a href="#contact" class="block py-2 text-gray-600 hover:text-blue-600">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg min-h-screen flex items-center pt-16">
        <div class="max-w-6xl mx-auto px-4 text-center text-white">
            <div class="animate-fade-in">
                <div class="w-32 h-32 bg-white/20 rounded-full mx-auto mb-6 flex items-center justify-center">
                    <i class="fas fa-user text-4xl text-white"></i>
                </div>
                <h1 class="text-4xl md:text-6xl font-bold mb-4">Mark Gerard S. Andrada</h1>
                <p class="text-xl md:text-2xl mb-6 text-blue-100">Technical Support Specialist & Claims Examiner</p>
                <p class="text-lg mb-8 max-w-2xl mx-auto text-blue-50">Over a decade of experience delivering exceptional customer service and resolving complex technical issues</p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="#contact" class="bg-white text-blue-600 px-8 py-3 rounded-lg font-semibold hover:bg-blue-50 transition-colors">Get In Touch</a>
                    <a href="#experience" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-blue-600 transition-colors">View Experience</a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Professional Summary</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <p class="text-lg text-gray-600 leading-relaxed">
                        Seasoned Technical Support Specialist and Claims Examiner with over a decade of experience delivering exceptional customer service, resolving complex technical issues, and streamlining operational workflows.
                    </p>
                    <p class="text-lg text-gray-600 leading-relaxed">
                        Adept at troubleshooting security systems, mobile devices, and network configurations. Known for translating technical jargon into clear, actionable guidance and mentoring peers on best practices.
                    </p>
                    <div class="flex items-center space-x-4 text-gray-600">
                        <i class="fas fa-map-marker-alt text-blue-600"></i>
                        <span>Bay, Laguna, Philippines</span>
                    </div>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl">
                    <h3 class="text-xl font-semibold text-gray-800 mb-6">Core Competencies</h3>
                    <div class="grid grid-cols-1 gap-4">
                        <div class="flex items-center space-x-3">
                            <i class="fas fa-wrench text-blue-600"></i>
                            <span class="text-gray-700">Technical Support & Troubleshooting</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <i class="fas fa-clipboard-list text-blue-600"></i>
                            <span class="text-gray-700">Claims Analysis & Verification</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <i class="fas fa-folder text-blue-600"></i>
                            <span class="text-gray-700">Back Office Operations</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <i class="fas fa-brain text-blue-600"></i>
                            <span class="text-gray-700">Subject Matter Expertise</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <i class="fas fa-network-wired text-blue-600"></i>
                            <span class="text-gray-700">Network Configuration & Remote Access</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <i class="fas fa-mobile-alt text-blue-600"></i>
                            <span class="text-gray-700">Mobile App & Device Integration</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-gray-50">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Professional Experience</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
            </div>
            <div class="space-y-8">
                <!-- Experience Item 1 -->
                <div class="bg-white rounded-xl p-8 card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">Technical VA</h3>
                            <p class="text-blue-600 font-medium">Swann Communications LTD</p>
                        </div>
                        <span class="text-gray-500 mt-2 md:mt-0">April 2025 – Present</span>
                    </div>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Provided expert phone support for CCTV systems (DVR/NVR, wired/wireless cameras)</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Assisted with installation, setup, and remote access configuration</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Resolved issues like offline cameras, no video, recording failures, and playback errors</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Supported mobile app setup, notifications, and device pairing</span>
                        </li>
                    </ul>
                </div>

                <!-- Experience Item 2 -->
                <div class="bg-white rounded-xl p-8 card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">Technical Support Expert</h3>
                            <p class="text-blue-600 font-medium">Asurion</p>
                        </div>
                        <span class="text-gray-500 mt-2 md:mt-0">April 2023 – August 2024</span>
                    </div>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Delivered real-time support for mobile devices and electronics</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Simplified complex technical details for customer understanding</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Resolved device functionality, connectivity, and software issues</span>
                        </li>
                    </ul>
                </div>

                <!-- Experience Item 3 -->
                <div class="bg-white rounded-xl p-8 card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">Claims Review Examiner</h3>
                            <p class="text-blue-600 font-medium">Asurion</p>
                        </div>
                        <span class="text-gray-500 mt-2 md:mt-0">August 2017 – March 2023</span>
                    </div>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Reviewed insurance claims for accuracy and compliance</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Investigated documentation and device history for legitimacy</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Coordinated with legal and fraud teams on disputed claims</span>
                        </li>
                    </ul>
                </div>

                <!-- Experience Item 4 -->
                <div class="bg-white rounded-xl p-8 card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">Technical Support Representative (Back Office)</h3>
                            <p class="text-blue-600 font-medium">West Contact Services</p>
                        </div>
                        <span class="text-gray-500 mt-2 md:mt-0">February 2015 – May 2017</span>
                    </div>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Executed high-volume data entry and system updates</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Ensured accuracy across customer records and service requests</span>
                        </li>
                    </ul>
                </div>

                <!-- Experience Item 5 -->
                <div class="bg-white rounded-xl p-8 card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">Technical Support Representative</h3>
                            <p class="text-blue-600 font-medium">STARTEK</p>
                        </div>
                        <span class="text-gray-500 mt-2 md:mt-0">January 2013 – May 2014</span>
                    </div>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Delivered phone-based support for hardware and software issues</span>
                        </li>
                        <li class="flex items-start space-x-2">
                            <i class="fas fa-check-circle text-blue-600 mt-1 text-sm"></i>
                            <span>Logged complaints and tracked resolutions via ticketing systems</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Technical Skills</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- CRM & Support Platforms -->
                <div class="bg-gray-50 p-6 rounded-xl">
                    <h3 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                        <i class="fas fa-desktop text-blue-600 mr-3"></i>
                        CRM & Support Platforms
                    </h3>
                    <div class="space-y-2 text-gray-600">
                        <div>Outlook</div>
                        <div>Horizon</div>
                        <div>ACSS</div>
                        <div>EINSTEIN</div>
                        <div>Citrix</div>
                        <div>Zendesk</div>
                        <div>ClickUp</div>
                    </div>
                </div>

                <!-- Product Knowledge -->
                <div class="bg-gray-50 p-6 rounded-xl">
                    <h3 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                        <i class="fas fa-video text-blue-600 mr-3"></i>
                        Product Knowledge
                    </h3>
                    <div class="space-y-2 text-gray-600">
                        <div>Swann</div>
                        <div>Raysharp</div>
                        <div>HIK Vision</div>
                        <div>V8</div>
                    </div>
                </div>

                <!-- Software & Systems -->
                <div class="bg-gray-50 p-6 rounded-xl">
                    <h3 class="text-lg font-semibold text-gray-800 mb-4 flex items-center">
                        <i class="fas fa-cogs text-blue-600 mr-3"></i>
                        Software & Systems
                    </h3>
                    <div class="space-y-2 text-gray-600">
                        <div>Android</div>
                        <div>iOS</div>
                        <div>Windows</div>
                        <div>macOS</div>
                        <div>Google Workspace</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 gradient-bg">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Get In Touch</h2>
                <div class="w-20 h-1 bg-white mx-auto"></div>
                <p class="text-blue-100 mt-6 max-w-2xl mx-auto">Ready to bring technical expertise and exceptional customer service to your team</p>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-8">
                    <div class="flex items-start space-x-4">
                        <div class="bg-white/20 p-3 rounded-lg">
                            <i class="fas fa-map-marker-alt text-white text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-white font-semibold mb-2">Address</h3>
                            <p class="text-blue-100">Block 2 Lot 17 Talc Street, Cambria Subdivision<br>Santo Domingo, Bay, Laguna 4033</p>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <div class="bg-white/20 p-3 rounded-lg">
                            <i class="fas fa-phone text-white text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-white font-semibold mb-2">Phone</h3>
                            <a href="tel:+639512514379" class="text-blue-100 hover:text-white transition-colors">+63 951 251 4379</a>
                        </div>
                    </div>
                    <div class="flex items-start space-x-4">
                        <div class="bg-white/20 p-3 rounded-lg">
                            <i class="fas fa-envelope text-white text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-white font-semibold mb-2">Email</h3>
                            <a href="mailto:markgerard.andrada@gmail.com" class="text-blue-100 hover:text-white transition-colors">markgerard.andrada@gmail.com</a>
                        </div>
                    </div>
                </div>
                <div class="bg-white/10 backdrop-blur-sm p-8 rounded-xl">
                    <h3 class="text-white text-xl font-semibold mb-6">Send a Message</h3>
                    <form class="space-y-4" onsubmit="handleFormSubmit(event)">
                        <div>
                            <input type="text" placeholder="Your Name" required class="w-full p-3 rounded-lg bg-white/20 text-white placeholder-blue-200 border border-white/30 focus:border-white focus:outline-none">
                        </div>
                        <div>
                            <input type="email" placeholder="Your Email" required class="w-full p-3 rounded-lg bg-white/20 text-white placeholder-blue-200 border border-white/30 focus:border-white focus:outline-none">
                        </div>
                        <div>
                            <textarea placeholder="Your Message" rows="4" required class="w-full p-3 rounded-lg bg-white/20 text-white placeholder-blue-200 border border-white/30 focus:border-white focus:outline-none resize-none"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-white text-blue-600 py-3 rounded-lg font-semibold hover:bg-blue-50 transition-colors">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="max-w-6xl mx-auto px-4 text-center">
            <p>&copy; 2024 Mark Gerard S. Andrada. All rights reserved.</p>
            <p class="text-gray-400 mt-2">Technical Support Specialist | Claims Examiner | Customer Service Expert</p>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // Close mobile menu if open
                    document.getElementById('mobile-menu').classList.add('hidden');
                }
            });
        });

        // Form submission handler
        function handleFormSubmit(event) {
            event.preventDefault();
            const form = event.target;
            const formData = new FormData(form);
            
            // Show success message
            alert('Thank you for your message! This is a demo form. In a real implementation, this would send your message to Mark Gerard.');
            
            // Reset form
            form.reset();
        }

        // Scroll animations
        function animateOnScroll() {
            const elements = document.querySelectorAll('.card-hover, .animate-fade-in');
            elements.forEach(element => {
                const elementTop = element.getBoundingClientRect().top;
                const elementVisible = 150;
                
                if (elementTop < window.innerHeight - elementVisible) {
                    element.classList.add('section-active');
                    element.classList.remove('section-hidden');
                }
            });
        }

        // Initialize scroll animations
        window.addEventListener('scroll', animateOnScroll);
        animateOnScroll(); // Run on page load

        // Active navigation highlighting
        window.addEventListener('scroll', function() {
            const sections = document.querySelectorAll('section[id]');
            const navLinks = document.querySelectorAll('.nav-link');
            
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop - 100;
                if (pageYOffset >= sectionTop) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('text-blue-600');
                link.classList.add('text-gray-600');
                if (link.getAttribute('href') === '#' + current) {
                    link.classList.remove('text-gray-600');
                    link.classList.add('text-blue-600');
                }
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9634438fa419bc4c',t:'MTc1MzIwMTIxMS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
