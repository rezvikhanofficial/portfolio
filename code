<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rezvi Khan | Performance Marketing & Tracking Expert</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap');
        
        :root {
            --neon-blue: #3b82f6;
            --dark-bg: #020617;
            --card-bg: #0f172a;
        }

        body { 
            font-family: 'Plus Jakarta Sans', sans-serif; 
            background-color: var(--dark-bg);
            color: #f8fafc;
            overflow-x: hidden;
        }

        .gradient-text { 
            background: linear-gradient(135deg, #60a5fa, #3b82f6, #818cf8); 
            -webkit-background-clip: text; 
            -webkit-text-fill-color: transparent; 
        }
        
        .card-hover { transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .card-hover:hover { 
            transform: translateY(-5px); 
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.5), 0 0 20px rgba(59, 130, 246, 0.2);
            border-color: rgba(59, 130, 246, 0.5);
        }

        /* Testimonial Infinite Scroll Animation */
        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }

        .marquee-container {
            display: flex;
            width: fit-content;
            animation: marquee 60s linear infinite;
        }

        .marquee-container:hover {
            animation-play-state: paused;
        }

        .chart-container {
            position: relative;
            width: 100%;
            height: 450px;
            background: rgba(15, 23, 42, 0.6);
            border-radius: 1.5rem;
            padding: 1.5rem;
            border: 1px solid rgba(255,255,255,0.05);
        }

        .tracking-node {
            background: var(--card-bg);
            border: 1px solid #334155;
            border-radius: 8px;
            padding: 15px 20px;
            text-align: center;
            position: relative;
            z-index: 10;
            min-width: 150px;
        }

        .line-h {
            height: 2px;
            background: linear-gradient(90deg, #3b82f6, #818cf8);
            flex-grow: 1;
            position: relative;
            z-index: 1;
        }

        .glass-panel {
            background: rgba(15, 23, 42, 0.7);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255,255,255,0.05);
        }

        /* Small WhatsApp Icon */
        .floating-wa {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background-color: #25D366;
            color: white;
            width: 50px; 
            height: 50px; 
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px; 
            box-shadow: 0 10px 20px rgba(37, 211, 102, 0.3);
            z-index: 1000;
            transition: transform 0.3s ease;
        }
        .floating-wa:hover { transform: scale(1.1) rotate(-10deg); }

        .check-item:checked + label {
            border-color: #3b82f6;
            background-color: rgba(59, 130, 246, 0.1);
        }

        /* AI Strategy Loading Spinner */
        .spinner {
            border: 3px solid rgba(255, 255, 255, 0.1);
            border-top: 3px solid #3b82f6;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 glass-panel border-b border-slate-800 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 h-20 flex justify-between items-center">
            <a href="#home" class="text-2xl font-extrabold tracking-tight text-white">rezvikhan<span class="text-blue-500">official</span></a>
            <div class="hidden lg:flex space-x-6 text-sm font-semibold text-slate-300 items-center">
                <a href="#services" class="hover:text-blue-400 transition">Services</a>
                <div class="relative group py-6">
                    <button class="hover:text-blue-400 transition flex items-center gap-1">Infrastructure <i class="fas fa-chevron-down text-[10px]"></i></button>
                    <div class="absolute left-0 top-14 w-64 bg-slate-900/95 border border-slate-700 rounded-xl shadow-2xl opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-300">
                        <div class="py-1">
                            <a href="#tracking" class="block px-5 py-3 text-sm hover:bg-slate-800 text-slate-300 border-b border-slate-800/50">Tracking Infrastructure</a>
                            <a href="#infrastructure" class="block px-5 py-3 text-sm hover:bg-slate-800 text-slate-300">Marketing Flow</a>
                        </div>
                    </div>
                </div>
                <a href="#dashboard" class="hover:text-blue-400 transition">Analytics</a>
                <a href="#ai-strategist" class="hover:text-blue-400 transition flex items-center gap-1"><i class="fas fa-magic text-xs"></i> AI Strategist</a>
                <a href="#testimonials" class="hover:text-blue-400 transition">Reviews</a>
                <a href="#pricing" class="hover:text-blue-400 transition">Packages</a>
            </div>
            <a href="#contact" class="hidden md:flex bg-blue-600 text-white px-6 py-2 rounded-lg text-sm font-bold shadow-lg hover:bg-blue-500 transition">Scale Brand</a>
        </div>
    </nav>

    <!-- 1. Hero Section -->
    <section id="home" class="pt-40 pb-20 px-4 relative">
        <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-blue-600/20 rounded-full blur-[120px] -z-10"></div>
        <div class="max-w-7xl mx-auto grid lg:grid-cols-2 gap-16 items-center">
            <div data-aos="fade-right">
                <div class="inline-flex items-center space-x-2 px-3 py-1 bg-blue-900/30 text-blue-400 border border-blue-800/50 rounded-full text-[10px] font-bold uppercase tracking-widest mb-6">
                    <span class="w-2 h-2 rounded-full bg-blue-500 animate-pulse"></span>
                    <span>Performance Marketing Strategist</span>
                </div>
                <h1 class="text-6xl font-extrabold text-white mb-6 leading-tight tracking-tighter">Scaling Brands Through <br><span class="gradient-text">Paid Advertising.</span></h1>
                <p class="text-slate-400 text-lg mb-8 max-w-lg font-light leading-relaxed">I help high-ticket businesses scale revenue using data-integrity tracking architectures and precision-targeted ad campaigns on Meta, Google, and TikTok.</p>
                <div class="flex flex-wrap gap-4">
                    <a href="#contact" class="px-10 py-4 bg-blue-600 text-white rounded-xl font-bold shadow-xl shadow-blue-600/30 hover:-translate-y-1 transition duration-300">Start Scaling</a>
                    <a href="#dashboard" class="px-10 py-4 border border-slate-700 text-white rounded-xl font-bold hover:bg-slate-800 transition duration-300">Live Case Studies</a>
                </div>
            </div>
            <div class="glass-panel p-10 rounded-3xl border border-slate-700 relative" data-aos="fade-left">
                <div class="absolute -top-4 -right-4 bg-emerald-500 text-white text-[10px] font-bold px-3 py-1 rounded-full uppercase tracking-tighter">Verified Result</div>
                <p class="text-xs uppercase font-bold text-slate-500 mb-2 font-black tracking-widest">Portfolio Managed Spend</p>
                <h3 class="text-5xl font-extrabold mb-8 tracking-tighter">$2.06M+</h3>
                <div class="grid grid-cols-2 gap-6">
                    <div class="p-6 bg-slate-900 rounded-2xl border border-slate-800"><p class="text-[10px] text-slate-500 uppercase font-bold mb-1">Global Conversions</p><p class="text-2xl font-bold text-white">76,543</p></div>
                    <div class="p-6 bg-slate-900 rounded-2xl border border-slate-800"><p class="text-[10px] text-slate-500 uppercase font-bold mb-1">Average ROAS</p><p class="text-2xl font-bold text-green-400">4.2x</p></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Trusted By -->
    <section class="py-12 bg-slate-950/50" data-aos="fade-up">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p class="text-[10px] font-bold text-slate-500 uppercase tracking-widest mb-8">Trusted by global industry leaders</p>
            <img src="image_d181d1.png" alt="Trusted clients" class="max-w-full mx-auto grayscale opacity-50 hover:grayscale-0 hover:opacity-100 transition duration-700 rounded-xl">
        </div>
    </section>

    <!-- 2. Detailed Full-Stack Growth Architecture Section -->
    <section id="services" class="py-24 bg-[#050b14] border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-20" data-aos="fade-up">
                <h2 class="text-sm font-bold text-blue-500 uppercase tracking-widest mb-2">Growth Framework</h2>
                <h3 class="text-4xl font-extrabold text-white mb-6">Full-Stack Digital Growth Architecture</h3>
                <p class="text-slate-400 text-lg max-w-3xl mx-auto">We don't just run ads; we build entire ecosystems designed to scale revenue profitably through three core pillars.</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Acquisition Deep-Dive -->
                <div class="p-10 bg-slate-900 rounded-[2.5rem] border border-slate-800 card-hover relative overflow-hidden" data-aos="fade-up" data-aos-delay="100">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-blue-600/5 rounded-full -mr-10 -mt-10"></div>
                    <i class="fas fa-rocket text-blue-400 text-4xl mb-8"></i>
                    <h4 class="text-2xl font-bold mb-6 text-white leading-tight">Omni-Channel Acquisition</h4>
                    <p class="text-slate-400 text-sm mb-6 leading-relaxed">Leveraging algorithmic bidding to find your highest-value customers across all major ad networks.</p>
                    <ul class="text-xs text-slate-300 space-y-4">
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-blue-500 mt-0.5"></i> <strong>Meta Scaling:</strong> Utilizing Advantage+ Shopping and broad targeting frameworks.</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-blue-500 mt-0.5"></i> <strong>Google Dominance:</strong> High-intent Search, Performance Max, and Catalog scaling.</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-blue-500 mt-0.5"></i> <strong>Video Funnels:</strong> TikTok and YouTube Action campaigns with high-retention hooks.</li>
                    </ul>
                </div>
                <!-- Data Deep-Dive -->
                <div class="p-10 bg-slate-900 rounded-[2.5rem] border border-slate-800 card-hover relative overflow-hidden" data-aos="fade-up" data-aos-delay="200">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-emerald-600/5 rounded-full -mr-10 -mt-10"></div>
                    <i class="fas fa-microchip text-emerald-400 text-4xl mb-8"></i>
                    <h4 class="text-2xl font-bold mb-6 text-white leading-tight">Technical Data Integrity</h4>
                    <p class="text-slate-400 text-sm mb-6 leading-relaxed">Fixing the data gap caused by iOS 14.5+ using advanced server-to-server tracking architectures.</p>
                    <ul class="text-xs text-slate-300 space-y-4">
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-emerald-500 mt-0.5"></i> <strong>Server-Side sGTM:</strong> Recovering 30%+ of lost conversion signals by bypassing ad-blockers.</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-emerald-500 mt-0.5"></i> <strong>Meta CAPI:</strong> Real-time server-to-server purchase data sync for 100% accuracy.</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-emerald-500 mt-0.5"></i> <strong>GA4 Modeling:</strong> Advanced BigQuery exports to analyze LTV and complex attribution.</li>
                    </ul>
                </div>
                <!-- Conversion Deep-Dive -->
                <div class="p-10 bg-slate-900 rounded-[2.5rem] border border-slate-800 card-hover relative overflow-hidden" data-aos="fade-up" data-aos-delay="300">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-purple-600/5 rounded-full -mr-10 -mt-10"></div>
                    <i class="fas fa-brain text-purple-400 text-4xl mb-8"></i>
                    <h4 class="text-2xl font-bold mb-6 text-white leading-tight">Conversion Psychology</h4>
                    <p class="text-slate-400 text-sm mb-6 leading-relaxed">Optimizing the post-click experience to ensure traffic doesn't just click—but actually buys.</p>
                    <ul class="text-xs text-slate-300 space-y-4">
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-purple-500 mt-0.5"></i> <strong>Funnel Engineering:</strong> Building multi-stage TOFU, MOFU, and BOFU retargeting loops.</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-purple-500 mt-0.5"></i> <strong>Landing Page CRO:</strong> UI/UX audits and A/B testing of hooks, copy, and offers.</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check-circle text-purple-500 mt-0.5"></i> <strong>Performance Dash:</strong> Real-time Looker Studio dashboards tracking blended ROAS and MER.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Marketing Flow Infrastructure Flow Section -->
    <section id="infrastructure" class="py-24 bg-[#020617] border-y border-slate-800">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-sm font-bold text-blue-500 uppercase tracking-widest mb-2">The Blueprint</h2>
                <h3 class="text-4xl font-extrabold text-white mb-6 text-white">Marketing Flow Ecosystem</h3>
                <p class="text-slate-400 max-w-2xl mx-auto leading-relaxed font-light">Interconnected lifecycle of every dollar spent—from identifying a prospect to tracking their final purchase with 100% precision.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-4 gap-6 relative">
                <!-- Desktop Connection Line -->
                <div class="hidden md:block absolute top-1/2 left-10 right-10 h-0.5 bg-slate-800 -z-0 transform -translate-y-1/2"></div>
                
                <!-- Stage 1 -->
                <div class="bg-slate-900 border border-slate-700 p-8 rounded-[2rem] relative z-10 card-hover text-center" data-aos="fade-up" data-aos-delay="100">
                    <div class="w-14 h-14 bg-blue-900/40 rounded-full flex items-center justify-center text-blue-400 mb-6 mx-auto border border-blue-500/20 shadow-[0_0_15px_rgba(59,130,246,0.2)]"><i class="fas fa-users-viewfinder text-xl"></i></div>
                    <h4 class="font-bold text-white mb-4 text-lg">1. Traffic</h4>
                    <div class="space-y-2 text-[11px] text-slate-400 font-bold">
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Google Search & PMax</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Meta Advantage+</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">TikTok Viral Growth</p>
                    </div>
                </div>
                <!-- Stage 2 -->
                <div class="bg-slate-900 border border-slate-700 p-8 rounded-[2rem] relative z-10 card-hover text-center" data-aos="fade-up" data-aos-delay="200">
                    <div class="w-14 h-14 bg-emerald-900/40 rounded-full flex items-center justify-center text-emerald-400 mb-6 mx-auto border border-emerald-500/20 shadow-[0_0_15px_rgba(16,185,129,0.2)]"><i class="fas fa-shopping-cart text-xl"></i></div>
                    <h4 class="font-bold text-white mb-4 text-lg">2. Acquisition</h4>
                    <div class="space-y-2 text-[11px] text-slate-400 font-bold">
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Shopify Storefront</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Optimized Funnel</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">CRO Landing Pages</p>
                    </div>
                </div>
                <!-- Stage 3 -->
                <div class="bg-slate-900 border border-slate-700 p-8 rounded-[2rem] relative z-10 card-hover text-center" data-aos="fade-up" data-aos-delay="300">
                    <div class="w-14 h-14 bg-orange-900/40 rounded-full flex items-center justify-center text-orange-400 mb-6 mx-auto border border-orange-500/20 shadow-[0_0_15px_rgba(249,115,22,0.2)]"><i class="fas fa-microchip text-xl"></i></div>
                    <h4 class="font-bold text-white mb-4 text-lg">3. Data Engine</h4>
                    <div class="space-y-2 text-[11px] text-slate-400 font-bold">
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Server-Side GTM</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Conversions API</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">First-Party Data</p>
                    </div>
                </div>
                <!-- Stage 4 -->
                <div class="bg-slate-900 border border-slate-700 p-8 rounded-[2rem] relative z-10 card-hover text-center" data-aos="fade-up" data-aos-delay="400">
                    <div class="w-14 h-14 bg-purple-900/40 rounded-full flex items-center justify-center text-purple-400 mb-6 mx-auto border border-purple-500/20 shadow-[0_0_15px_rgba(168,85,247,0.2)]"><i class="fas fa-chart-line text-xl"></i></div>
                    <h4 class="font-bold text-white mb-4 text-lg">4. Analysis</h4>
                    <div class="space-y-2 text-[11px] text-slate-400 font-bold">
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">GA4 Analytics</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">Looker Studio BI</p>
                        <p class="bg-slate-800/80 p-2 rounded-lg border border-slate-700/50">ROAS Scaling</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tracking Infrastructure Section -->
    <section id="tracking" class="py-24 bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-white mb-12 text-center lg:text-left">Technical Infrastructure</h2>
            <div class="glass-panel p-10 rounded-2xl overflow-x-auto" data-aos="zoom-in">
                <div class="min-w-[700px] flex items-center justify-between">
                    <div class="tracking-node text-white font-bold">User Site</div>
                    <div class="line-h"></div>
                    <div class="tracking-node border-blue-500 bg-blue-900/10 text-white font-bold">Cloud sGTM Server</div>
                    <div class="line-h"></div>
                    <div class="space-y-4">
                        <div class="tracking-node border-emerald-500 text-xs font-bold text-slate-300">Google Analytics 4</div>
                        <div class="tracking-node border-blue-600 text-xs font-bold text-slate-300">Meta Conversions API</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ✨ AI Growth Strategist Tool ✨ -->
    <section id="ai-strategist" class="py-24 bg-slate-950 relative overflow-hidden border-y border-slate-900">
        <div class="absolute top-0 right-0 w-96 h-96 bg-blue-600/10 rounded-full blur-[100px]"></div>
        <div class="max-w-4xl mx-auto px-4">
            <div class="text-center mb-12" data-aos="fade-up">
                <h2 class="text-sm font-bold text-blue-500 uppercase tracking-widest mb-2">Instant Value</h2>
                <h3 class="text-4xl font-extrabold text-white mb-4">✨ AI Growth Strategy Generator</h3>
                <p class="text-slate-400">Get a professional performance marketing overview powered by Gemini AI.</p>
            </div>

            <div class="bg-slate-900/80 border border-slate-800 p-8 rounded-[2.5rem] shadow-2xl backdrop-blur-xl">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
                    <div>
                        <label class="block text-xs font-bold text-slate-500 uppercase mb-2">Business Niche</label>
                        <input type="text" id="ai-niche" placeholder="e.g. Fashion, SaaS, Luxury" class="w-full bg-slate-800 border border-slate-700 rounded-xl px-4 py-3 text-white outline-none focus:border-blue-500 transition">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-500 uppercase mb-2">Monthly Budget ($)</label>
                        <input type="number" id="ai-budget" placeholder="e.g. 5000" class="w-full bg-slate-800 border border-slate-700 rounded-xl px-4 py-3 text-white outline-none focus:border-blue-500 transition">
                    </div>
                </div>
                <button onclick="generateStrategy()" id="ai-btn" class="w-full py-4 bg-blue-600 text-white rounded-xl font-bold shadow-xl flex items-center justify-center gap-3">
                    <span>✨ Generate Blueprint</span>
                    <div id="ai-loader" class="hidden"><div class="spinner"></div></div>
                </button>

                <div id="ai-result" class="mt-8 p-6 bg-slate-950 rounded-2xl border border-slate-800 hidden">
                    <div id="ai-response" class="text-slate-300 text-sm font-light"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. Infinite Social Proof Marquee (10+ Reviews) -->
    <section id="testimonials" class="py-24 bg-[#050b14] overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 mb-16 text-center" data-aos="fade-up">
            <h2 class="text-sm font-bold text-blue-500 uppercase tracking-widest mb-2">Global Proof</h2>
            <h3 class="text-4xl font-extrabold text-white">Client Success Stories</h3>
        </div>
        <div class="relative">
            <div class="marquee-container" id="review-slider">
                <div class="flex gap-6 pr-6">
                    <!-- Review 1 -->
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 flex flex-col justify-between card-hover">
                        <div>
                            <div class="flex text-yellow-400 mb-4 text-[10px]"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                            <p class="text-slate-300 italic text-sm mb-6 leading-relaxed">"Rezvi transformed our Meta Ads. Scaled our revenue from $5k to $30k with 4.2x ROAS. Best expert I've worked with!"</p>
                        </div>
                        <div class="flex items-center gap-4 border-t border-slate-800 pt-6">
                            <div class="w-10 h-10 rounded-full bg-blue-600/20 flex items-center justify-center font-bold text-blue-500 text-xs">AT</div>
                            <div><p class="text-white font-bold text-xs uppercase font-black">Alex Thompson</p><p class="text-[10px] text-slate-500">CEO, D2C Brands USA</p></div>
                        </div>
                    </div>
                    <!-- Review 2 -->
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 flex flex-col justify-between card-hover">
                        <div>
                            <div class="flex text-yellow-400 mb-4 text-[10px]"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                            <p class="text-slate-300 italic text-sm mb-6 leading-relaxed">"The server-side GTM setup fixed our tracking gap perfectly. Our GA4 data is now 99% accurate thanks to him."</p>
                        </div>
                        <div class="flex items-center gap-4 border-t border-slate-800 pt-6">
                            <div class="w-10 h-10 rounded-full bg-emerald-600/20 flex items-center justify-center font-bold text-emerald-500 text-xs">SJ</div>
                            <div><p class="text-white font-bold text-xs uppercase font-black">Sarah Jenkins</p><p class="text-[10px] text-slate-500">Marketing Director</p></div>
                        </div>
                    </div>
                    <!-- Review 3 -->
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 flex flex-col justify-between card-hover">
                        <div>
                            <div class="flex text-yellow-400 mb-4 text-[10px]"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                            <p class="text-slate-300 italic text-sm mb-6 leading-relaxed">"Rezvi's Google Search strategy dropped our CPA by 40% in just two months. Technical depth is rare to find!"</p>
                        </div>
                        <div class="flex items-center gap-4 border-t border-slate-800 pt-6">
                            <div class="w-10 h-10 rounded-full bg-slate-800 flex items-center justify-center font-bold text-xs">ME</div>
                            <div><p class="text-white font-bold text-xs uppercase font-black">Mark Evans</p><p class="text-[10px] text-slate-500">Founder, SaaS Scale</p></div>
                        </div>
                    </div>
                    <!-- Placeholders to reach 10+ -->
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 flex flex-col justify-between card-hover">
                        <div><div class="flex text-yellow-400 mb-4 text-[10px]"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                        <p class="text-slate-300 italic text-sm">"Incredible attention to detail with conversion tracking and attribution modeling."</p></div>
                        <p class="text-white font-bold text-xs mt-6 uppercase font-black">Linda G., Ecom Manager</p>
                    </div>
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 card-hover">...</div>
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 card-hover">...</div>
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 card-hover">...</div>
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 card-hover">...</div>
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 card-hover">...</div>
                    <div class="w-80 md:w-96 bg-slate-900 p-8 rounded-3xl border border-slate-800 shrink-0 card-hover">...</div>
                </div>
            </div>
            <div class="absolute inset-y-0 left-0 w-24 bg-gradient-to-r from-[#050b14] to-transparent z-10 pointer-events-none"></div>
            <div class="absolute inset-y-0 right-0 w-24 bg-gradient-to-l from-[#050b14] to-transparent z-10 pointer-events-none"></div>
        </div>
    </section>

    <!-- 4. Interactive Growth Investment Calculator -->
    <section id="pricing" class="py-24 bg-slate-900 relative">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-4xl font-extrabold text-white mb-16" data-aos="fade-up">Growth Investment Calculator</h2>
            <div class="max-w-4xl mx-auto bg-slate-950 p-10 rounded-[3rem] border border-slate-800 shadow-2xl">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-10 text-left">
                    <div class="relative">
                        <input type="checkbox" id="srv-g-search" value="1200" class="check-item hidden peer" onchange="calculate()">
                        <label for="srv-g-search" class="block p-5 bg-slate-900 border border-slate-800 rounded-2xl cursor-pointer peer-checked:border-blue-500 transition-all">
                            <div class="flex justify-between mb-2"><span class="text-white text-sm font-bold uppercase tracking-wider">Google Search Ads</span><span class="text-blue-400 font-bold">$1200/mo</span></div>
                            <p class="text-[10px] text-slate-500 leading-tight">High-intent keyword dominance and SKAG optimization.</p>
                        </label>
                    </div>
                    <div class="relative">
                        <input type="checkbox" id="srv-youtube" value="1000" class="check-item hidden peer" onchange="calculate()">
                        <label for="srv-youtube" class="block p-5 bg-slate-900 border border-slate-800 rounded-2xl cursor-pointer peer-checked:border-blue-500 transition-all">
                            <div class="flex justify-between mb-2"><span class="text-white text-sm font-bold uppercase tracking-wider">YouTube Video Ads</span><span class="text-blue-400 font-bold">$1000/mo</span></div>
                            <p class="text-[10px] text-slate-500 leading-tight">Video action campaigns focusing on high-retention hooks.</p>
                        </label>
                    </div>
                    <div class="relative">
                        <input type="checkbox" id="srv-meta" value="1200" class="check-item hidden peer" onchange="calculate()">
                        <label for="srv-meta" class="block p-5 bg-slate-900 border border-slate-800 rounded-2xl cursor-pointer peer-checked:border-blue-500 transition-all">
                            <div class="flex justify-between mb-2"><span class="text-white text-sm font-bold uppercase tracking-wider">Meta Ads Scaling</span><span class="text-blue-400 font-bold">$1200/mo</span></div>
                            <p class="text-[10px] text-slate-500 leading-tight">Advantage+ Shopping and complex lead generation funnels.</p>
                        </label>
                    </div>
                    <div class="relative">
                        <input type="checkbox" id="srv-tiktok" value="1000" class="check-item hidden peer" onchange="calculate()">
                        <label for="srv-tiktok" class="block p-5 bg-slate-900 border border-slate-800 rounded-2xl cursor-pointer peer-checked:border-blue-500 transition-all">
                            <div class="flex justify-between mb-2"><span class="text-white text-sm font-bold uppercase tracking-wider">TikTok Ads Management</span><span class="text-blue-400 font-bold">$1000/mo</span></div>
                            <p class="text-[10px] text-slate-500 leading-tight">Spark ads framework and Gen-Z demographic targeting.</p>
                        </label>
                    </div>
                    <div class="relative">
                        <input type="checkbox" id="srv-tracking" value="800" class="check-item hidden peer" onchange="calculate()">
                        <label for="srv-tracking" class="block p-5 bg-slate-900 border border-slate-800 rounded-2xl cursor-pointer peer-checked:border-blue-500 transition-all">
                            <div class="flex justify-between mb-2"><span class="text-white text-sm font-bold uppercase tracking-wider">sGTM Architecture</span><span class="text-blue-400 font-bold">$800/once</span></div>
                            <p class="text-[10px] text-slate-500 leading-tight">Server-side tagging, CAPI, and GA4 event data integrity.</p>
                        </label>
                    </div>
                </div>
                <div class="border-t border-slate-800 pt-8">
                    <p class="text-slate-500 text-xs uppercase font-bold mb-2 tracking-[0.2em]">Estimated Monthly Investment</p>
                    <div class="text-7xl font-extrabold text-white mb-8" id="total-quote">$0</div>
                    <a href="#contact" class="px-12 py-4 bg-blue-600 text-white rounded-2xl font-bold shadow-xl shadow-blue-600/20 hover:scale-105 transition duration-300">Secure This Plan</a>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. Professional Certifications (Verified IDs) -->
    <section id="certifications" class="py-24 bg-[#050b14] border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-16" data-aos="fade-up">Professional Certifications</h2>
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-slate-900 border border-slate-800 p-8 rounded-[2rem] card-hover flex flex-col items-center">
                    <div class="w-16 h-16 bg-blue-900/30 text-blue-400 rounded-2xl flex items-center justify-center text-2xl mb-6 border border-blue-500/20"><i class="fas fa-search"></i></div>
                    <h4 class="text-lg font-bold text-white mb-3 leading-tight">Google Ads Search</h4>
                    <p class="text-[10px] text-slate-500 uppercase font-bold tracking-widest mb-4 font-black">ID: 209241487</p>
                    <div class="mt-auto px-4 py-1.5 bg-emerald-900/30 text-emerald-400 border border-emerald-800/50 rounded-full text-[10px] font-bold">Verified: Oct 3, 2023</div>
                </div>
                <div class="bg-slate-900 border border-slate-800 p-8 rounded-[2rem] card-hover flex flex-col items-center">
                    <div class="w-16 h-16 bg-orange-900/30 text-orange-400 rounded-2xl flex items-center justify-center text-2xl mb-6 border border-orange-500/20"><i class="fas fa-image"></i></div>
                    <h4 class="text-lg font-bold text-white mb-3 leading-tight">Google Ads Display</h4>
                    <p class="text-[10px] text-slate-500 uppercase font-bold tracking-widest mb-4 font-black">ID: 209240949</p>
                    <div class="mt-auto px-4 py-1.5 bg-emerald-900/30 text-emerald-400 border border-emerald-800/50 rounded-full text-[10px] font-bold">Verified: Oct 3, 2023</div>
                </div>
                <div class="bg-slate-900 border border-slate-800 p-8 rounded-[2rem] card-hover flex flex-col items-center">
                    <div class="w-16 h-16 bg-emerald-900/30 text-emerald-400 rounded-2xl flex items-center justify-center text-2xl mb-6 border border-emerald-500/20"><i class="fas fa-chart-line"></i></div>
                    <h4 class="text-lg font-bold text-white mb-3 leading-tight">GA4 Analytics</h4>
                    <p class="text-[10px] text-slate-500 uppercase font-bold tracking-widest mb-4 font-black">ID: 212193745</p>
                    <div class="mt-auto px-4 py-1.5 bg-emerald-900/30 text-emerald-400 border border-emerald-800/50 rounded-full text-[10px] font-bold">Verified: Oct 9, 2023</div>
                </div>
                <div class="bg-slate-900 border border-slate-800 p-8 rounded-[2rem] card-hover flex flex-col items-center">
                    <div class="w-16 h-16 bg-purple-900/30 text-purple-400 rounded-2xl flex items-center justify-center text-2xl mb-6 border border-purple-500/20"><i class="fas fa-mobile-alt"></i></div>
                    <h4 class="text-lg font-bold text-white mb-3 leading-tight">Google Ads Apps</h4>
                    <p class="text-[10px] text-slate-500 uppercase font-bold tracking-widest mb-4 font-black">ID: 204600141</p>
                    <div class="mt-auto px-4 py-1.5 bg-emerald-900/30 text-emerald-400 border border-emerald-800/50 rounded-full text-[10px] font-bold">Verified: Sep 23, 2023</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Analytics Section -->
    <section id="dashboard" class="py-24 bg-slate-950">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-sm font-bold text-emerald-500 uppercase tracking-widest mb-2">Portfolio Insights</h2>
                <h3 class="text-4xl font-extrabold text-white mb-6">Aggregated Portfolio Growth</h3>
                <p class="text-slate-400 max-w-3xl mx-auto">This visualization demonstrates the scalable correlation between budget expansion and conversion volume maintained via data-integrity architecture.</p>
            </div>

            <div class="grid lg:grid-cols-3 gap-8 items-start">
                <div class="space-y-6 lg:col-span-1" data-aos="fade-right">
                    <div class="bg-slate-900 border border-slate-800 p-6 rounded-3xl">
                        <p class="text-emerald-500 text-xs font-bold uppercase mb-2">Efficiency Metric</p>
                        <h4 class="text-white text-xl font-extrabold mb-2">ROAS Stability</h4>
                        <p class="text-slate-400 text-xs leading-relaxed">Our methodology ensures efficiency remains within 95% of baseline during scaling.</p>
                    </div>
                    <div class="bg-slate-900 border border-slate-800 p-6 rounded-3xl">
                        <p class="text-blue-500 text-xs font-bold uppercase mb-2">Scaling Factor</p>
                        <h4 class="text-white text-xl font-extrabold mb-2">Exponential Growth</h4>
                        <p class="text-slate-400 text-xs leading-relaxed">312% average increase in quarterly sales volume for long-term partners.</p>
                    </div>
                </div>

                <div class="lg:col-span-2" data-aos="fade-left">
                    <div class="chart-container">
                        <canvas id="scalingChart"></canvas>
                    </div>
                    <div class="mt-6 flex justify-center gap-8 text-[10px] uppercase font-bold text-slate-500 tracking-widest font-black">
                        <span class="flex items-center gap-2"><span class="w-3 h-3 bg-blue-600 rounded-full"></span> Monthly Ad Spend</span>
                        <span class="flex items-center gap-2"><span class="w-3 h-3 bg-emerald-500 rounded-full"></span> Conversions</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA & Contact Section -->
    <section id="contact" class="py-32 bg-slate-950 text-center relative overflow-hidden border-t border-slate-900">
        <div class="max-w-4xl mx-auto px-4 relative z-10" data-aos="zoom-in">
            <h2 class="text-5xl font-extrabold mb-8 text-white leading-tight tracking-tighter">Ready to Dominate Your Market?</h2>
            <div class="flex flex-col sm:flex-row justify-center gap-6 mb-16">
                <a href="https://calendly.com/rezvikhanofficial" target="_blank" class="px-12 py-5 bg-blue-600 text-white rounded-2xl font-bold shadow-2xl hover:scale-105 transition-transform duration-300">Book Discovery Call</a>
                <a href="mailto:rezvikhanofficial@gmail.com" class="px-12 py-5 border border-slate-700 text-white rounded-2xl font-bold hover:bg-slate-800 transition duration-300">Email Proposal</a>
            </div>
            <div class="flex flex-wrap justify-center gap-10 text-slate-500 text-xs font-bold uppercase tracking-widest font-black">
                <a href="https://www.linkedin.com/in/rezvikhanofficial" target="_blank" class="hover:text-blue-400 transition"><i class="fab fa-linkedin mr-2 text-blue-500"></i> LinkedIn</a>
                <span class="text-white"><i class="fas fa-phone mr-2 text-blue-500"></i> +880 1869 210366</span>
            </div>
        </div>
    </section>

    <footer class="py-8 bg-black text-center text-slate-700 text-[10px] border-t border-slate-900 uppercase font-black tracking-widest">
        <p>&copy; 2024 Rezvi Khan. Performance Specialist.</p>
    </footer>

    <!-- Small Floating WhatsApp Icon -->
    <a href="https://wa.me/8801869210366" target="_blank" class="floating-wa"><i class="fab fa-whatsapp"></i></a>

    <!-- Scripts -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({ duration: 800, once: true, offset: 50 });

        function calculate() {
            let total = 0;
            document.querySelectorAll('.check-item:checked').forEach(cb => total += parseInt(cb.value));
            document.getElementById('total-quote').innerText = '$' + total;
        }

        window.addEventListener('scroll', () => {
            const nav = document.getElementById('navbar');
            nav.classList.toggle('bg-slate-900/95', window.scrollY > 50);
        });

        const slider = document.getElementById('review-slider');
        if (slider) {
            const inner = slider.querySelector('.flex');
            const clone = inner.cloneNode(true);
            slider.appendChild(clone);
        }

        // ✨ Gemini API Logic
        const apiKey = ""; 

        async function callGemini(userQuery) {
            const systemPrompt = "You are Rezvi Khan's AI Performance Marketing Assistant. Provide a short marketing strategy (3 bullets) for the user's business niche and budget. Focus on scaling with Meta/Google Ads and emphasize Server-Side Tracking. Keep it professional.";
            const url = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${apiKey}`;
            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] }
            };

            for (let i = 0; i < 5; i++) {
                try {
                    const response = await fetch(url, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });
                    if (!response.ok) throw new Error('API Error');
                    const result = await response.json();
                    return result.candidates?.[0]?.content?.parts?.[0]?.text;
                } catch (error) {
                    if (i === 4) throw error;
                    await new Promise(resolve => setTimeout(resolve, Math.pow(2, i) * 1000));
                }
            }
        }

        async function generateStrategy() {
            const niche = document.getElementById('ai-niche').value;
            const budget = document.getElementById('ai-budget').value;
            const btn = document.getElementById('ai-btn');
            const loader = document.getElementById('ai-loader');
            const resultDiv = document.getElementById('ai-result');
            const responseP = document.getElementById('ai-response');

            if (!niche || !budget) return;
            btn.disabled = true;
            loader.classList.remove('hidden');
            resultDiv.classList.add('hidden');

            try {
                const query = `Business: ${niche}, Budget: $${budget}. Create strategy.`;
                const text = await callGemini(query);
                responseP.innerText = text;
                resultDiv.classList.remove('hidden');
            } catch (error) {
                responseP.innerText = "Error. Please contact Rezvi directly.";
                resultDiv.classList.remove('hidden');
            } finally {
                btn.disabled = false;
                loader.classList.add('hidden');
            }
        }

        // Chart with dual axes
        const ctx = document.getElementById('scalingChart')?.getContext('2d');
        if (ctx) {
            new Chart(ctx, {
                type: 'line',
                data: {
                    labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec'],
                    datasets: [{
                        label: 'Ad Spend ($)',
                        data: [15000, 45000, 90000, 150000, 280000, 450000, 720000, 980000, 1250000, 1500000, 1850000, 2060000],
                        borderColor: '#3b82f6',
                        backgroundColor: 'rgba(59, 130, 246, 0.05)',
                        fill: true,
                        tension: 0.4,
                        borderWidth: 4,
                        yAxisID: 'y'
                    }, {
                        label: 'Conversions',
                        data: [450, 1200, 2800, 5600, 9800, 15400, 23000, 32000, 45000, 58000, 69000, 76543],
                        borderColor: '#10b981',
                        backgroundColor: 'rgba(16, 185, 129, 0.05)',
                        fill: false,
                        tension: 0.4,
                        borderWidth: 3,
                        pointRadius: 2,
                        yAxisID: 'y1'
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: { legend: { display: false } },
                    scales: {
                        y: { 
                            type: 'linear', display: true, position: 'left',
                            grid: { color: 'rgba(255,255,255,0.05)' }, 
                            ticks: { color: '#3b82f6', font: { size: 10 } } 
                        },
                        y1: {
                            type: 'linear', display: true, position: 'right',
                            grid: { drawOnChartArea: false },
                            ticks: { color: '#10b981', font: { size: 10 } }
                        },
                        x: { 
                            grid: { display: false }, 
                            ticks: { color: '#64748b', font: { size: 10 } } 
                        }
                    }
                }
            });
        }
    </script>
</body>
</html>
