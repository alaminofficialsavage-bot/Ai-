<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Savage Intelligence | AI Automation Agency</title>
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;800&family=Space+Grotesk:wght@300;500;700&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- GSAP & ScrollTrigger -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
    
    <!-- Three.js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Outfit', 'sans-serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#050507',
                            purple: '#7c3aed',
                            cyan: '#06b6d4',
                            accent: '#f472b6'
                        }
                    },
                    backgroundImage: {
                        'gradient-radial': 'radial-gradient(var(--tw-gradient-stops))',
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #050507;
            color: #ffffff;
            overflow-x: hidden;
            cursor: none;
        }

        /* Custom Cursor */
        .cursor-dot,
        .cursor-outline {
            position: fixed;
            top: 0;
            left: 0;
            transform: translate(-50%, -50%);
            border-radius: 50%;
            z-index: 9999;
            pointer-events: none;
        }

        .cursor-dot {
            width: 8px;
            height: 8px;
            background-color: #06b6d4;
        }

        .cursor-outline {
            width: 40px;
            height: 40px;
            border: 1px solid rgba(255, 255, 255, 0.5);
            transition: width 0.2s, height 0.2s, background-color 0.2s;
        }

        body:hover .cursor-outline.hovered {
            width: 80px;
            height: 80px;
            background-color: rgba(6, 182, 212, 0.1);
            border-color: #06b6d4;
            mix-blend-mode: screen;
        }

        /* Noise Overlay */
        .noise {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9000;
            opacity: 0.04;
            background: url('data:image/svg+xml;utf8,%3Csvg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"%3E%3Cfilter id="noiseFilter"%3E%3CfeTurbulence type="fractalNoise" baseFrequency="0.65" numOctaves="3" stitchTiles="stitch"/%3E%3C/filter%3E%3Crect width="100%25" height="100%25" filter="url(%23noiseFilter)"/%3E%3C/svg%3E');
        }

        /* Glassmorphism Utilities */
        .glass-panel {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .glass-card {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.05) 0%, rgba(255, 255, 255, 0.01) 100%);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }

        /* Text Gradients */
        .text-gradient {
            background: linear-gradient(to right, #06b6d4, #7c3aed, #f472b6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* 3D Canvas Container */
        #canvas-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
        }

        /* Marquee Animation */
        .marquee-container {
            overflow: hidden;
            white-space: nowrap;
        }
        .marquee-content {
            display: inline-block;
            animation: marquee 20s linear infinite;
        }
        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }

        /* Loader */
        #loader {
            position: fixed;
            inset: 0;
            background: #050507;
            z-index: 10000;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: opacity 0.8s ease-out;
        }

        /* Floating Orbs */
        .orb {
            position: absolute;
            border-radius: 50%;
            filter: blur(80px);
            opacity: 0.4;
            animation: float 20s infinite ease-in-out;
        }

        @keyframes float {
            0%, 100% { transform: translate(0, 0) scale(1); }
            33% { transform: translate(30px, -50px) scale(1.1); }
            66% { transform: translate(-20px, 20px) scale(0.9); }
        }

        /* Grid Background */
        .grid-bg {
            background-size: 50px 50px;
            background-image: linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                              linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
            mask-image: radial-gradient(ellipse at center, black 40%, transparent 80%);
        }
    </style>
</head>
<body class="antialiased selection:bg-cyan-500 selection:text-white">

    <!-- Loading Screen -->
    <div id="loader">
        <div class="text-center">
            <h1 class="text-4xl font-display font-bold text-white tracking-widest animate-pulse">SAVAGE INTELLIGENCE</h1>
            <div class="mt-4 h-1 w-48 bg-gray-800 mx-auto rounded overflow-hidden">
                <div class="h-full bg-cyan-500 animate-[width_1.5s_ease-in-out_infinite]" style="width: 50%"></div>
            </div>
        </div>
    </div>

    <!-- Custom Cursor Elements -->
    <div class="cursor-dot hidden md:block"></div>
    <div class="cursor-outline hidden md:block"></div>

    <!-- Noise Texture -->
    <div class="noise"></div>

    <!-- 3D Background Canvas -->
    <div id="canvas-container"></div>

    <!-- Floating Orbs for Depth -->
    <div class="fixed inset-0 pointer-events-none z-[1] overflow-hidden">
        <div class="orb w-96 h-96 bg-cyan-600/20 top-[-10%] left-[-10%]" style="animation-delay: 0s;"></div>
        <div class="orb w-80 h-80 bg-purple-600/20 top-[40%] right-[-5%]" style="animation-delay: -5s;"></div>
        <div class="orb w-64 h-64 bg-pink-600/20 bottom-[-5%] left-[30%]" style="animation-delay: -10s;"></div>
    </div>

    <!-- Grid Background -->
    <div class="fixed inset-0 pointer-events-none z-[2] grid-bg"></div>

    <!-- Navigation -->
    <nav class="fixed w-full z-50 top-0 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-6 py-6 flex justify-between items-center">
            <a href="#" class="text-2xl font-display font-bold tracking-tighter hover-trigger z-50 relative group">
                SAVAGE<span class="text-cyan-400">.AI</span>
                <span class="absolute -bottom-2 left-0 w-0 h-0.5 bg-cyan-400 transition-all group-hover:w-full"></span>
            </a>
            
            <div class="hidden md:flex space-x-8 items-center glass-panel px-8 py-3 rounded-full">
                <a href="#services" class="text-sm font-medium text-gray-300 hover:text-white transition-colors hover-trigger">Services</a>
                <a href="#process" class="text-sm font-medium text-gray-300 hover:text-white transition-colors hover-trigger">Process</a>
                <a href="#results" class="text-sm font-medium text-gray-300 hover:text-white transition-colors hover-trigger">Results</a>
                <a href="#contact" class="bg-white text-black px-5 py-2 rounded-full text-sm font-bold hover:bg-cyan-400 transition-colors hover-trigger">Start Project</a>
            </div>

            <!-- Mobile Menu Button -->
            <button class="md:hidden text-white hover-trigger" id="mobile-menu-btn">
                <i data-lucide="menu" class="w-8 h-8"></i>
            </button>
        </div>
    </nav>

    <!-- Mobile Menu Overlay -->
    <div id="mobile-menu" class="fixed inset-0 bg-black/95 z-40 transform translate-x-full transition-transform duration-300 flex flex-col justify-center items-center space-y-8">
        <a href="#services" class="text-2xl font-display font-bold text-white mobile-link">Services</a>
        <a href="#process" class="text-2xl font-display font-bold text-white mobile-link">Process</a>
        <a href="#results" class="text-2xl font-display font-bold text-white mobile-link">Results</a>
        <a href="#contact" class="text-2xl font-display font-bold text-cyan-400 mobile-link">Contact</a>
    </div>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden pt-20 z-10">
        <!-- Gradient Overlay for readability -->
        <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#050507] z-10"></div>

        <div class="relative z-20 max-w-7xl mx-auto px-6 text-center">
            <div class="inline-block mb-4 px-4 py-1 rounded-full border border-cyan-500/30 bg-cyan-500/10 backdrop-blur-sm">
                <span class="text-cyan-400 text-xs font-bold tracking-widest uppercase">Next Gen Automation</span>
            </div>
            
            <h1 class="text-6xl md:text-8xl lg:text-9xl font-display font-bold leading-tight mb-6 tracking-tight">
                <span class="block reveal-text">UNLEASH THE</span>
                <span class="block text-gradient reveal-text">SAVAGE</span>
                <span class="block reveal-text">INTELLIGENCE</span>
            </h1>
            
            <p class="text-gray-400 text-lg md:text-xl max-w-2xl mx-auto mb-10 leading-relaxed reveal-text">
                We engineer autonomous AI systems that dominate workflows, obliterate inefficiency, and scale your business beyond human limits.
            </p>
            
            <div class="flex flex-col md:flex-row gap-4 justify-center reveal-text">
                <a href="#contact" class="group relative px-8 py-4 bg-white text-black font-bold rounded-full overflow-hidden hover-trigger">
                    <div class="absolute inset-0 w-full h-full bg-cyan-400 transform scale-x-0 group-hover:scale-x-100 transition-transform origin-left duration-300"></div>
                    <span class="relative z-10 flex items-center gap-2">
                        Initialize System <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </span>
                </a>
                <a href="#process" class="px-8 py-4 border border-white/20 rounded-full font-bold hover:bg-white/10 transition-colors hover-trigger backdrop-blur-sm">
                    View Architecture
                </a>
            </div>
        </div>

        <!-- Scroll Indicator -->
        <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 z-20 animate-bounce">
            <i data-lucide="chevron-down" class="w-8 h-8 text-gray-500"></i>
        </div>
    </section>

    <!-- Marquee Section -->
    <div class="py-10 border-y border-white/10 bg-black/50 backdrop-blur-sm relative z-20">
        <div class="marquee-container">
            <div class="marquee-content text-4xl md:text-6xl font-display font-bold text-transparent stroke-text opacity-50">
                AUTOMATION • MACHINE LEARNING • NEURAL NETWORKS • EFFICIENCY • SCALABILITY • AI INTEGRATION • AUTOMATION • MACHINE LEARNING • NEURAL NETWORKS • EFFICIENCY • SCALABILITY • AI INTEGRATION •
            </div>
        </div>
    </div>

    <!-- Services Section -->
    <section id="services" class="py-32 relative z-20">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-end mb-20">
                <div>
                    <h2 class="text-cyan-400 font-bold tracking-widest uppercase mb-2">Capabilities</h2>
                    <h3 class="text-4xl md:text-6xl font-display font-bold">Our Arsenal</h3>
                </div>
                <p class="text-gray-400 max-w-md mt-6 md:mt-0 text-right">
                    We don't just write code; we architect digital ecosystems that think, learn, and execute.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Service Card 1 -->
                <div class="glass-card p-8 rounded-2xl hover:border-cyan-500/50 transition-all duration-300 group hover-trigger service-card">
                    <div class="w-14 h-14 bg-cyan-500/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-cyan-500 group-hover:text-black transition-colors">
                        <i data-lucide="bot" class="w-7 h-7 text-cyan-400 group-hover:text-black"></i>
                    </div>
                    <h4 class="text-2xl font-bold mb-4">AI Chatbots</h4>
                    <p class="text-gray-400 leading-relaxed">
                        Custom GPT-4 and LLM integrations trained on your data to handle support, sales, and lead gen 24/7.
                    </p>
                </div>

                <!-- Service Card 2 -->
                <div class="glass-card p-8 rounded-2xl hover:border-purple-500/50 transition-all duration-300 group hover-trigger service-card">
                    <div class="w-14 h-14 bg-purple-500/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-purple-500 group-hover:text-black transition-colors">
                        <i data-lucide="workflow" class="w-7 h-7 text-purple-400 group-hover:text-black"></i>
                    </div>
                    <h4 class="text-2xl font-bold mb-4">Workflow Automation</h4>
                    <p class="text-gray-400 leading-relaxed">
                        Connect your apps and eliminate manual data entry. Zapier, Make.com, and custom API pipelines.
                    </p>
                </div>

                <!-- Service Card 3 -->
                <div class="glass-card p-8 rounded-2xl hover:border-pink-500/50 transition-all duration-300 group hover-trigger service-card">
                    <div class="w-14 h-14 bg-pink-500/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-pink-500 group-hover:text-black transition-colors">
                        <i data-lucide="bar-chart-3" class="w-7 h-7 text-pink-400 group-hover:text-black"></i>
                    </div>
                    <h4 class="text-2xl font-bold mb-4">Predictive Analytics</h4>
                    <p class="text-gray-400 leading-relaxed">
                        Turn raw data into actionable intelligence. Forecast trends and customer behavior with precision.
                    </p>
                </div>

                <!-- Service Card 4 -->
                <div class="glass-card p-8 rounded-2xl hover:border-cyan-500/50 transition-all duration-300 group hover-trigger service-card">
                    <div class="w-14 h-14 bg-cyan-500/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-cyan-500 group-hover:text-black transition-colors">
                        <i data-lucide="scan-face" class="w-7 h-7 text-cyan-400 group-hover:text-black"></i>
                    </div>
                    <h4 class="text-2xl font-bold mb-4">Computer Vision</h4>
                    <p class="text-gray-400 leading-relaxed">
                        Object detection, image recognition, and quality control systems for manufacturing and retail.
                    </p>
                </div>

                <!-- Service Card 5 -->
                <div class="glass-card p-8 rounded-2xl hover:border-purple-500/50 transition-all duration-300 group hover-trigger service-card">
                    <div class="w-14 h-14 bg-purple-500/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-purple-500 group-hover:text-black transition-colors">
                        <i data-lucide="mail" class="w-7 h-7 text-purple-400 group-hover:text-black"></i>
                    </div>
                    <h4 class="text-2xl font-bold mb-4">AI Outreach</h4>
                    <p class="text-gray-400 leading-relaxed">
                        Hyper-personalized email and LinkedIn campaigns that write themselves and book meetings on autopilot.
                    </p>
                </div>

                <!-- Service Card 6 -->
                <div class="glass-card p-8 rounded-2xl hover:border-pink-500/50 transition-all duration-300 group hover-trigger service-card">
                    <div class="w-14 h-14 bg-pink-500/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-pink-500 group-hover:text-black transition-colors">
                        <i data-lucide="code-2" class="w-7 h-7 text-pink-400 group-hover:text-black"></i>
                    </div>
                    <h4 class="text-2xl font-bold mb-4">SaaS Development</h4>
                    <p class="text-gray-400 leading-relaxed">
                        End-to-end development of AI-powered SaaS products from MVP to enterprise scale.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section id="process" class="py-32 bg-white/5 relative overflow-hidden z-20">
        <!-- Background Elements -->
        <div class="absolute top-0 right-0 w-1/2 h-full bg-gradient-to-l from-cyan-900/20 to-transparent"></div>
        
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="text-center mb-20">
                <h2 class="text-cyan-400 font-bold tracking-widest uppercase mb-2">Methodology</h2>
                <h3 class="text-4xl md:text-6xl font-display font-bold">The Execution Protocol</h3>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
                <!-- Step 1 -->
                <div class="relative process-step">
                    <div class="text-8xl font-display font-bold text-white/5 absolute -top-10 -left-4">01</div>
                    <div class="relative z-10">
                        <div class="w-16 h-16 bg-gradient-to-br from-cyan-500 to-blue-600 rounded-2xl flex items-center justify-center mb-6 shadow-lg shadow-cyan-500/20">
                            <i data-lucide="search" class="w-8 h-8 text-white"></i>
                        </div>
                        <h4 class="text-2xl font-bold mb-4">Discovery & Audit</h4>
                        <p class="text-gray-400">
                            We deep dive into your current workflows to identify bottlenecks, inefficiencies, and high-value automation opportunities.
                        </p>
                    </div>
                </div>

                <!-- Step 2 -->
                <div class="relative process-step mt-0 md:mt-16">
                    <div class="text-8xl font-display font-bold text-white/5 absolute -top-10 -left-4">02</div>
                    <div class="relative z-10">
                        <div class="w-16 h-16 bg-gradient-to-br from-purple-500 to-pink-600 rounded-2xl flex items-center justify-center mb-6 shadow-lg shadow-purple-500/20">
                            <i data-lucide="cpu" class="w-8 h-8 text-white"></i>
                        </div>
                        <h4 class="text-2xl font-bold mb-4">Architecture & Build</h4>
                        <p class="text-gray-400">
                            Our engineers build your custom AI stack. We connect APIs, train models, and construct the logic layer.
                        </p>
                    </div>
                </div>

                <!-- Step 3 -->
                <div class="relative process-step mt-0 md:mt-32">
                    <div class="text-8xl font-display font-bold text-white/5 absolute -top-10 -left-4">03</div>
                    <div class="relative z-10">
                        <div class="w-16 h-16 bg-gradient-to-br from-pink-500 to-orange-600 rounded-2xl flex items-center justify-center mb-6 shadow-lg shadow-pink-500/20">
                            <i data-lucide="rocket" class="w-8 h-8 text-white"></i>
                        </div>
                        <h4 class="text-2xl font-bold mb-4">Deploy & Optimize</h4>
                        <p class="text-gray-400">
                            We go live and monitor performance. Continuous learning loops ensure the system gets smarter over time.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section id="results" class="py-24 border-y border-white/10 relative z-20">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="stat-item">
                    <div class="text-5xl md:text-6xl font-display font-bold text-white mb-2 counter" data-target="150">0</div>
                    <div class="text-sm text-gray-400 uppercase tracking-widest">Projects Delivered</div>
                </div>
                <div class="stat-item">
                    <div class="text-5xl md:text-6xl font-display font-bold text-cyan-400 mb-2 counter" data-target="40">0</div>
                    <div class="text-sm text-gray-400 uppercase tracking-widest">Hours Saved / Week</div>
                </div>
                <div class="stat-item">
                    <div class="text-5xl md:text-6xl font-display font-bold text-purple-400 mb-2 counter" data-target="300">0</div>
                    <div class="text-sm text-gray-400 uppercase tracking-widest">% ROI Increase</div>
                </div>
                <div class="stat-item">
                    <div class="text-5xl md:text-6xl font-display font-bold text-pink-400 mb-2 counter" data-target="24">0</div>
                    <div class="text-sm text-gray-400 uppercase tracking-widest">/7 Support</div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA / Contact Section -->
    <section id="contact" class="py-32 relative z-20">
        <div class="absolute inset-0 bg-gradient-to-t from-cyan-900/20 to-transparent"></div>
        <div class="max-w-4xl mx-auto px-6 relative z-10 text-center">
            <h2 class="text-5xl md:text-7xl font-display font-bold mb-8">Ready to Dominate?</h2>
            <p class="text-xl text-gray-300 mb-12">
                Stop doing manual work. Start scaling with intelligence. Book a strategy call with our team today.
            </p>
            
            <form class="glass-card p-8 md:p-12 rounded-3xl text-left max-w-2xl mx-auto" onsubmit="event.preventDefault(); alert('Message sent to Savage Intelligence!');">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                    <div>
                        <label class="block text-sm font-bold text-gray-400 mb-2">Name</label>
                        <input type="text" class="w-full bg-black/50 border border-white/10 rounded-lg p-4 text-white focus:outline-none focus:border-cyan-500 transition-colors" placeholder="John Doe">
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-gray-400 mb-2">Email</label>
                        <input type="email" class="w-full bg-black/50 border border-white/10 rounded-lg p-4 text-white focus:outline-none focus:border-cyan-500 transition-colors" placeholder="john@company.com">
                    </div>
                </div>
                <div class="mb-6">
                    <label class="block text-sm font-bold text-gray-400 mb-2">Project Details</label>
                    <textarea rows="4" class="w-full bg-black/50 border border-white/10 rounded-lg p-4 text-white focus:outline-none focus:border-cyan-500 transition-colors" placeholder="Tell us about your automation needs..."></textarea>
                </div>
                <button type="submit" class="w-full bg-gradient-to-r from-cyan-500 to-blue-600 text-white font-bold py-4 rounded-lg hover:shadow-lg hover:shadow-cyan-500/25 transition-all transform hover:-translate-y-1 hover-trigger">
                    Launch Project
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-white/10 bg-black py-12 relative z-20">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
            <div class="mb-6 md:mb-0">
                <span class="text-2xl font-display font-bold tracking-tighter">SAVAGE<span class="text-cyan-400">.AI</span></span>
                <p class="text-gray-500 text-sm mt-2">Engineering the future of business.</p>
            </div>
            <div class="flex space-x-6">
                <a href="#" class="text-gray-400 hover:text-white transition-colors hover-trigger"><i data-lucide="twitter" class="w-5 h-5"></i></a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors hover-trigger"><i data-lucide="linkedin" class="w-5 h-5"></i></a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors hover-trigger"><i data-lucide="github" class="w-5 h-5"></i></a>
            </div>
        </div>
        <div class="text-center text-gray-700 text-xs mt-12">
             Savage Intelligence. All rights reserved.
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Loader Logic
        window.addEventListener('load', () => {
            const loader = document.getElementById('loader');
            setTimeout(() => {
                loader.style.opacity = '0';
                setTimeout(() => {
                    loader.style.display = 'none';
                    initAnimations();
                }, 800);
            }, 1500);
        });

        // Custom Cursor Logic
        const cursorDot = document.querySelector('.cursor-dot');
        const cursorOutline = document.querySelector('.cursor-outline');
        const hoverTriggers = document.querySelectorAll('.hover-trigger');

        window.addEventListener('mousemove', (e) => {
            const posX = e.clientX;
            const posY = e.clientY;

            cursorDot.style.left = `${posX}px`;
            cursorDot.style.top = `${posY}px`;

            cursorOutline.animate({
                left: `${posX}px`,
                top: `${posY}px`
            }, { duration: 500, fill: "forwards" });
        });

        hoverTriggers.forEach(trigger => {
            trigger.addEventListener('mouseenter', () => {
                cursorOutline.classList.add('hovered');
            });
            trigger.addEventListener('mouseleave', () => {
                cursorOutline.classList.remove('hovered');
            });
        });

        // Mobile Menu Logic
        const mobileBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const mobileLinks = document.querySelectorAll('.mobile-link');
        let isMenuOpen = false;

        mobileBtn.addEventListener('click', () => {
            isMenuOpen = !isMenuOpen;
            if (isMenuOpen) {
                mobileMenu.classList.remove('translate-x-full');
            } else {
                mobileMenu.classList.add('translate-x-full');
            }
        });

        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                isMenuOpen = false;
                mobileMenu.classList.add('translate-x-full');
            });
        });

        // Advanced Three.js Background
        const initThreeJS = () => {
            const container = document.getElementById('canvas-container');
            const scene = new THREE.Scene();
            scene.fog = new THREE.FogExp2(0x050507, 0.0015);

            const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
            camera.position.z = 30;

            const renderer = new THREE.WebGLRenderer({ alpha: true, antialias: true });
            renderer.setSize(window.innerWidth, window.innerHeight);
            renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
            container.appendChild(renderer.domElement);

            // Mouse tracking
            let mouseX = 0;
            let mouseY = 0;
            let targetMouseX = 0;
            let targetMouseY = 0;

            document.addEventListener('mousemove', (event) => {
                targetMouseX = (event.clientX / window.innerWidth) * 2 - 1;
                targetMouseY = -(event.clientY / window.innerHeight) * 2 + 1;
            });

            // Create multiple particle systems for depth
            const createParticleSystem = (count, color, size, spread, speed) => {
                const geometry = new THREE.BufferGeometry();
                const positions = new Float32Array(count * 3);
                const velocities = new Float32Array(count * 3);
                const sizes = new Float32Array(count);

                for (let i = 0; i < count; i++) {
                    positions[i * 3] = (Math.random() - 0.5) * spread;
                    positions[i * 3 + 1] = (Math.random() - 0.5) * spread;
                    positions[i * 3 + 2] = (Math.random() - 0.5) * spread;
                    
                    velocities[i * 3] = (Math.random() - 0.5) * speed;
                    velocities[i * 3 + 1] = (Math.random() - 0.5) * speed;
                    velocities[i * 3 + 2] = (Math.random() - 0.5) * speed;
                    
                    sizes[i] = Math.random() * size;
                }

                geometry.setAttribute('position', new THREE.BufferAttribute(positions, 3));
                geometry.setAttribute('velocity', new THREE.BufferAttribute(velocities, 3));
                geometry.setAttribute('size', new THREE.BufferAttribute(sizes, 1));

                const material = new THREE.PointsMaterial({
                    color: color,
                    size: size,
                    transparent: true,
                    opacity: 0.6,
                    blending: THREE.AdditiveBlending,
                    sizeAttenuation: true
                });

                return new THREE.Points(geometry, material);
            };

            // Create layers
            const particles1 = createParticleSystem(2000, 0x06b6d4, 0.15, 100, 0.02); // Cyan
            const particles2 = createParticleSystem(1000, 0x7c3aed, 0.2, 80, 0.015);  // Purple
            const particles3 = createParticleSystem(500, 0xf472b6, 0.25, 60, 0.01);   // Pink

            scene.add(particles1);
            scene.add(particles2);
            scene.add(particles3);

            // Create connecting lines between nearby particles
            const lineMaterial = new THREE.LineBasicMaterial({
                color: 0x06b6d4,
                transparent: true,
                opacity: 0.1
            });

            const lineGeometry = new THREE.BufferGeometry();
            const linePositions = new Float32Array(2000 * 3); // Max lines
            lineGeometry.setAttribute('position', new THREE.BufferAttribute(linePositions, 3));
            const lines = new THREE.LineSegments(lineGeometry, lineMaterial);
            scene.add(lines);

            // Animation
            const clock = new THREE.Clock();

            const animate = () => {
                const elapsedTime = clock.getElapsedTime();
                const delta = clock.getDelta();

                // Smooth mouse follow
                mouseX += (targetMouseX - mouseX) * 0.05;
                mouseY += (targetMouseY - mouseY) * 0.05;

                // Animate particles
                [particles1, particles2, particles3].forEach((particles, index) => {
                    const positions = particles.geometry.attributes.position.array;
                    const velocities = particles.geometry.attributes.velocity.array;
                    
                    for (let i = 0; i < positions.length; i += 3) {
                        // Update positions
                        positions[i] += velocities[i];
                        positions[i + 1] += velocities[i + 1];
                        positions[i + 2] += velocities[i + 2];

                        // Boundary check - wrap around
                        const spread = index === 0 ? 100 : (index === 1 ? 80 : 60);
                        if (Math.abs(positions[i]) > spread / 2) velocities[i] *= -1;
                        if (Math.abs(positions[i + 1]) > spread / 2) velocities[i + 1] *= -1;
                        if (Math.abs(positions[i + 2]) > spread / 2) velocities[i + 2] *= -1;
                    }
                    
                    particles.geometry.attributes.position.needsUpdate = true;
                    
                    // Rotate based on mouse
                    particles.rotation.y = mouseX * 0.5 + elapsedTime * 0.05 * (index + 1) * 0.3;
                    particles.rotation.x = mouseY * 0.5 + elapsedTime * 0.02 * (index + 1) * 0.3;
                });

                // Update lines between nearby particles (simplified for performance)
                const p1Positions = particles1.geometry.attributes.position.array;
                const linePos = lines.geometry.attributes.position.array;
                let lineIndex = 0;
                const maxDistance = 8;

                for (let i = 0; i < Math.min(100, p1Positions.length / 3); i++) {
                    for (let j = i + 1; j < Math.min(100, p1Positions.length / 3); j++) {
                        const dx = p1Positions[i * 3] - p1Positions[j * 3];
                        const dy = p1Positions[i * 3 + 1] - p1Positions[j * 3 + 1];
                        const dz = p1Positions[i * 3 + 2] - p1Positions[j * 3 + 2];
                        const dist = Math.sqrt(dx * dx + dy * dy + dz * dz);

                        if (dist < maxDistance && lineIndex < linePos.length - 6) {
                            linePos[lineIndex++] = p1Positions[i * 3];
                            linePos[lineIndex++] = p1Positions[i * 3 + 1];
                            linePos[lineIndex++] = p1Positions[i * 3 + 2];
                            linePos[lineIndex++] = p1Positions[j * 3];
                            linePos[lineIndex++] = p1Positions[j * 3 + 1];
                            linePos[lineIndex++] = p1Positions[j * 3 + 2];
                        }
                    }
                }

                // Clear remaining line positions
                for (let i = lineIndex; i < linePos.length; i++) {
                    linePos[i] = 0;
                }
                
                lines.geometry.attributes.position.needsUpdate = true;

                // Camera movement based on mouse
                camera.position.x += (mouseX * 5 - camera.position.x) * 0.02;
                camera.position.y += (mouseY * 5 - camera.position.y) * 0.02;
                camera.lookAt(scene.position);

                renderer.render(scene, camera);
                requestAnimationFrame(animate);
            };

            animate();

            // Resize Handler
            window.addEventListener('resize', () => {
                camera.aspect = window.innerWidth / window.innerHeight;
                camera.updateProjectionMatrix();
                renderer.setSize(window.innerWidth, window.innerHeight);
            });
        };

        initThreeJS();

        // GSAP Animations
        const initAnimations = () => {
            gsap.registerPlugin(ScrollTrigger);

            // Hero Text Reveal
            gsap.from(".reveal-text", {
                y: 100,
                opacity: 0,
                duration: 1.5,
                stagger: 0.2,
                ease: "power4.out"
            });

            // Navbar Scroll Effect
            const navbar = document.getElementById('navbar');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 50) {
                    navbar.classList.add('bg-black/80', 'backdrop-blur-md', 'border-b', 'border-white/10');
                } else {
                    navbar.classList.remove('bg-black/80', 'backdrop-blur-md', 'border-b', 'border-white/10');
                }
            });

            // Service Cards Stagger
            gsap.from(".service-card", {
                scrollTrigger: {
                    trigger: "#services",
                    start: "top 80%",
                },
                y: 50,
                opacity: 0,
                duration: 0.8,
                stagger: 0.1,
                ease: "power2.out"
            });

            // Process Steps
            gsap.from(".process-step", {
                scrollTrigger: {
                    trigger: "#process",
                    start: "top 70%",
                },
                y: 50,
                opacity: 0,
                duration: 1,
                stagger: 0.2,
                ease: "back.out(1.7)"
            });

            // Stats Counter Animation
            const counters = document.querySelectorAll('.counter');
            
            counters.forEach(counter => {
                const target = +counter.getAttribute('data-target');
                
                ScrollTrigger.create({
                    trigger: counter,
                    start: "top 85%",
                    once: true,
                    onEnter: () => {
                        gsap.to(counter, {
                            innerHTML: target,
                            duration: 2,
                            snap: { innerHTML: 1 },
                            ease: "power1.out",
                            onUpdate: function() {
                                counter.innerHTML = Math.ceil(this.targets()[0].innerHTML);
                            }
                        });
                    }
                });
            });
        };

    </script>
</body>
</html>
