## Hi there 👋
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ly Vi Nghiep | Executive Portfolio - Martech & CRM Product Leader</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@200;400;600;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; background-color: #020617; color: #f1f5f9; scroll-behavior: smooth; }
        .glass { background: rgba(15, 23, 42, 0.7); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.05); }
        .gradient-text { background: linear-gradient(135deg, #38bdf8 0%, #818cf8 50%, #c084fc 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .project-card { transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); }
        .project-card:hover { transform: translateY(-12px) scale(1.02); border-color: #38bdf8; box-shadow: 0 25px 50px -12px rgba(56, 189, 248, 0.2); }
        .timeline-dot { width: 12px; height: 12px; background: #38bdf8; border-radius: 50%; position: absolute; left: -6px; top: 12px; box-shadow: 0 0 10px #38bdf8; }
        .vision-bullet::before { content: "→"; color: #38bdf8; font-weight: bold; margin-right: 12px; }
        .skill-badge { background: rgba(56, 189, 248, 0.1); border: 1px solid rgba(56, 189, 248, 0.2); padding: 4px 12px; border-radius: 6px; font-size: 0.7rem; font-weight: 700; color: #7dd3fc; text-transform: uppercase; }
    </style>
</head>
<body>

    <!-- NAVIGATION -->
    <nav class="fixed top-0 w-full z-[100] glass py-4 px-6 md:px-16 flex justify-between items-center border-b border-white/5">
        <div class="flex items-center gap-3">
            <img src="./anh4.jpg" class="w-10 h-10 rounded-full object-cover border border-sky-500 shadow-lg" alt="Ly Vi Nghiep">
            <span class="font-black tracking-tighter text-xl uppercase gradient-text">LY VI NGHIEP</span>
        </div>
        <div class="hidden lg:flex space-x-8 text-[10px] font-bold uppercase tracking-[0.3em] text-slate-400">
            <a href="#summary" class="hover:text-sky-400 transition">Summary</a>
            <a href="#projects" class="hover:text-sky-400 transition">Pillars</a>
            <a href="#experience" class="hover:text-sky-400 transition">Career</a>
            <a href="#skills" class="hover:text-sky-400 transition text-sky-400 font-black">Tech Mastery</a>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section class="min-h-[90vh] flex flex-col lg:flex-row items-center px-6 md:px-20 pt-32 gap-16">
        <div class="lg:w-1/2 space-y-8">
            <div class="inline-flex items-center gap-2 px-4 py-1 rounded-full border border-sky-500/30 bg-sky-500/10 text-sky-400 text-[10px] font-extrabold uppercase tracking-widest">
                Marketing Growth Lead & Product Manager
            </div>
            <h1 class="text-6xl md:text-8xl font-black leading-[0.9] tracking-tighter uppercase italic">
               CRM | CX | CDP 360 <br> <span class="gradient-text">STRATEGIST</span>
            </h1>
            <p class="text-slate-400 text-lg md:text-xl font-light leading-relaxed max-w-xl border-l-2 border-sky-500 pl-6 italic">
                Over 15 years of driving growth through CRM loyalty business model, CRM system platform,  master of customer experience journey map, Marketing lifecycle automation, CDP Architecture, and Data-driven Personalization for Retail & F&B leaders.
            </p>
            <div class="flex gap-4">
                <a href="#experience" class="bg-sky-500 text-white px-8 py-4 rounded-2xl font-bold uppercase text-[10px] tracking-widest hover:bg-sky-600 transition shadow-lg shadow-sky-500/20 text-center">Full Career Timeline</a>
                <a href="#skills" class="glass px-8 py-4 rounded-2xl font-bold uppercase text-[10px] tracking-widest hover:bg-white/5 transition text-center text-white">Skill Matrix</a>
            </div>
        </div>
        <div class="lg:w-1/2 relative">
            <div class="absolute inset-0 bg-sky-500/20 blur-[120px] rounded-full animate-pulse"></div>
            <img src="./anh1.jpg" alt="Ly Vi Nghiep Hero" class="relative z-10 w-full max-w-md mx-auto rounded-[4rem] shadow-2xl grayscale hover:grayscale-0 transition duration-1000 border border-white/5">
        </div>
    </section>

    <!-- PROFESSIONAL CORE (BULLET POINTS) -->
    <section id="summary" class="py-32 px-6 md:px-20 bg-slate-900/30">
        <div class="max-w-7xl mx-auto flex flex-col lg:flex-row gap-20 items-center">
            <div class="lg:w-1/3">
                <img src="./anh2.jpg" alt="Ly Vi Nghiep Professional" class="rounded-[3rem] border border-sky-500/30 shadow-2xl">
            </div>
            <div class="lg:w-2/3 space-y-8">
                <h2 class="text-4xl font-black uppercase tracking-tighter italic italic italic italic underline decoration-sky-500 underline-offset-8">Professional <span class="text-sky-400">Core</span></h2>
                <div class="glass p-10 rounded-[3rem] space-y-6 shadow-xl border-r-4 border-sky-500">
                    <ul class="space-y-4 text-slate-200 text-lg">
                        <li class="vision-bullet"><b>15+ Years Track Record:</b> Proven leadership in CRM, Loyalty Programs, and Data Strategy across Retail, F&B, Fashion, and Agencies.</li>
                        <li class="vision-bullet"><b>Multinational Portfolio:</b> Direct impact on leaders such as <b>Circle K, GS25, Hakuhodo, Golden Gate, ACFC, Auchan, and Metro Cash & Carry.</b></li>
                        <li class="vision-bullet"><b>CDP Architect:</b> Specialized in building end-to-end Customer Data Platforms (CDP) that unify multi-channel data into a single <b>User 360 view.</b></li>
                        <li class="vision-bullet"><b>Martech Ecosystems:</b> Expert in architecting Loyalty Mobile Apps, CRM backend systems, and O2O (Online-to-Offline) commercial integration.</li>
                        <li class="vision-bullet"><b>Growth & AI:</b> Leveraging Machine Learning models to optimize Marketing Automation, driving significant revenue growth and high-value retention.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- IMPACTFUL PROJECT PILLARS (KEPT 100%) -->
    <section id="projects" class="py-32 px-6 md:px-20">
        <div class="text-center mb-24 space-y-4">
            <h2 class="text-5xl font-black uppercase tracking-tighter italic text-white italic text-white text-white">Impactful <span class="text-sky-500">Project Pillars</span></h2>
            <p class="text-slate-500 uppercase tracking-[0.5em] text-[10px] font-black italic">The Foundation of Success</p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-10 max-w-7xl mx-auto">
            
            <!-- Pillar 1: Loyalty Apps -->
            <div class="project-card glass p-10 rounded-[3rem] space-y-6 relative overflow-hidden group">
                <div class="w-16 h-16 bg-sky-500/20 rounded-2xl flex items-center justify-center text-sky-400 mb-4">
                    <i data-lucide="smartphone"></i>
                </div>
                <h3 class="text-2xl font-black text-white uppercase italic tracking-tighter">Loyalty App Ecosystems</h3>
                <div class="space-y-4">
                    <div class="border-l-2 border-sky-500 pl-4">
                        <p class="text-xs font-bold text-sky-400 uppercase">GS25 Vietnam</p>
                        <p class="text-sm text-slate-300">Lead development of <b>"Digital Fridge"</b>, Lucky Wheel, and Buy & Earn features to maximize DAU.</p>
                    </div>
                    <div class="border-l-2 border-rose-500 pl-4">
                        <p class="text-xs font-bold text-rose-500 uppercase">Circle K VN</p>
                        <p class="text-sm text-slate-300">Built <b>CK Club App</b> from scratch for 520+ stores, achieving 62% retention rate.</p>
                    </div>
                    <div class="border-l-2 border-indigo-500 pl-4">
                        <p class="text-xs font-bold text-indigo-500 uppercase">Golden Gate</p>
                        <p class="text-sm text-slate-300">Architected <b>The Golden Spoon App</b> with E-wallet & Reward Policy integration.</p>
                    </div>
                </div>
            </div>

            <!-- Pillar 2: Loyalty Model Concepts -->
            <div class="project-card glass p-10 rounded-[3rem] space-y-6 relative overflow-hidden group">
                <div class="w-16 h-16 bg-purple-500/20 rounded-2xl flex items-center justify-center text-purple-400 mb-4">
                    <i data-lucide="award"></i>
                </div>
                <h3 class="text-2xl font-black text-white uppercase italic tracking-tighter">Loyalty Model Architecture</h3>
                <div class="space-y-4">
                    <div class="glass p-4 rounded-2xl border border-white/5 italic italic italic underline decoration-sky-500/20 decoration-sky-500/20">
                        <p class="text-xs font-bold text-purple-400 uppercase mb-1">Coupon & Stamp Card</p>
                        <p class="text-sm text-slate-300">Developed "Continuity Concepts" for retail, driving transaction growth from 8% to 15%.</p>
                    </div>
                    <div class="glass p-4 rounded-2xl border border-white/5 italic underline decoration-sky-500/20 decoration-sky-500/20">
                        <p class="text-xs font-bold text-purple-400 uppercase mb-1">Earn & Burn Strategy</p>
                        <p class="text-sm text-slate-300">Designed Sapporo VN 2024 Loyalty model with cross-channel point exchange alliances.</p>
                    </div>
                    <div class="glass p-4 rounded-2xl border border-white/5 italic underline decoration-sky-500/20 decoration-sky-500/20">
                        <p class="text-xs font-bold text-purple-400 uppercase mb-1">Retention Lifecycle</p>
                        <p class="text-sm text-slate-300">8% steady user return lift through Coupon Automation at Golden Gate South regional.</p>
                    </div>
                </div>
            </div>

            <!-- Pillar 3: CDP & Data Unification -->
            <div class="project-card glass p-10 rounded-[3rem] space-y-6 relative overflow-hidden group">
                <div class="w-16 h-16 bg-emerald-500/20 rounded-2xl flex items-center justify-center text-emerald-400 mb-4">
                    <i data-lucide="database"></i>
                </div>
                <h3 class="text-2xl font-black text-white uppercase italic tracking-tighter italic tracking-tighter">CDP & User 360 Portals</h3>
                <div class="space-y-4">
                    <div class="border-b border-white/5 pb-4">
                        <p class="text-xs font-bold text-emerald-400 uppercase font-black uppercase">CDP Implementation</p>
                        <p class="text-sm text-slate-300 italic">"Unified profile integration for Ajinomoto, Muji, and GS25."</p>
                    </div>
                    <ul class="text-sm space-y-2 text-slate-300 font-medium">
                        <li class="flex gap-2"><i data-lucide="check" class="text-emerald-400 w-4"></i> BigQuery ETL Architecture (Circle K)</li>
                        <li class="flex gap-2"><i data-lucide="check" class="text-emerald-400 w-4"></i> Real-time behavioral segmentation</li>
                        <li class="flex gap-2"><i data-lucide="check" class="text-emerald-400 w-4"></i> Marketing Automation flows (Zalo/SMS/App)</li>
                    </ul>
                </div>
            </div>

        </div>
    </section>

    <!-- CAREER TIMELINE (FULL 100% CONTENT - PARAPHRASED) -->
    <section id="experience" class="py-32 px-6 md:px-20 bg-slate-950">
        <h2 class="text-5xl font-black mb-24 text-center italic uppercase tracking-tighter">Professional <span class="text-sky-500">Timeline</span></h2>
        
        <div class="max-w-5xl mx-auto border-l-2 border-slate-800 relative space-y-20 ml-4 md:ml-auto">
            
            <!-- GS25 -->
            <div class="relative pl-12 group">
                <div class="timeline-dot"></div>
                <div class="grid lg:grid-cols-3 gap-8">
                    <div class="lg:col-span-1">
                        <span class="text-sky-500 font-black text-xl italic italic">03/2025 - Present</span>
                        <h3 class="text-3xl font-black text-white uppercase mt-2">GS25 Vietnam</h3>
                        <p class="text-slate-500 font-bold uppercase text-[10px] tracking-widest underline italic">Martech CRM Loyalty Product Manager</p>
                    </div>
                    <div class="lg:col-span-2 glass p-8 rounded-[2.5rem] space-y-4 text-sm text-slate-300 leading-relaxed italic">
                        <ul class="space-y-3">
                            <li>• <b class="text-white uppercase italic uppercase">Strategic Architect:</b> Engineered the "CRM Loyalty Model Business Plan 2025-2027" to maximize CLV and repeat purchase frequency.</li>
                            <li>• <b class="text-white uppercase italic uppercase">Product Leadership:</b> Leading the end-to-end GS25 Loyalty App lifecycle, from technical requirements to high-engagement features like **Lucky Wheel, Spin Stamp, and Digital Fridge.**</li>
                            <li>• <b class="text-white uppercase italic uppercase">Martech Integration:</b> Spearheading multi-channel data integration (POS, App, Social) into a CDP for a unified **User 360** profile.</li>
                            <li>• <b class="text-white uppercase italic uppercase">Growth Automation:</b> Designing rule-based lifecycle marketing flows for App Push, SMS, and Zalo ZNS targeting Welcome, Birthday, and Win-back sequences.</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- HAKUHODO -->
            <div class="relative pl-12 group">
                <div class="timeline-dot"></div>
                <div class="grid lg:grid-cols-3 gap-8">
                    <div class="lg:col-span-1">
                        <span class="text-indigo-400 font-black text-xl italic italic italic">2023 - 2025</span>
                        <h3 class="text-3xl font-black text-white uppercase mt-2 italic text-white uppercase mt-2 italic text-white uppercase mt-2 italic">Hakuhodo VN</h3>
                        <p class="text-slate-500 font-bold uppercase text-[10px] tracking-widest underline italic italic tracking-widest underline italic italic tracking-widest underline italic">Senior Digital Transformation Manager</p>
                    </div>
                    <div class="lg:col-span-2 glass p-8 rounded-[2.5rem] space-y-4 text-sm text-slate-300 leading-relaxed leading-relaxed leading-relaxed leading-relaxed leading-relaxed leading-relaxed italic">
                        <ul class="space-y-3">
                            <li>• <b class="text-indigo-400 italic">Consultancy Lead:</b> Delivered end-to-end DX services including CRM platform strategy, Data Strategy, and Mobile/Web ecosystem design for major Japanese clients.</li>
                            <li>• <b class="text-indigo-400 italic">CDP Specialist:</b> Designed hierarchical customer data trees for **Ajinomoto VN** to enable behavioral and preference-based segmentation.</li>
                            <li>• <b class="text-indigo-400 italic">Loyalty Strategy:</b> Developed "Earn & Burn" models for **Sapporo VN** and integrated automated multi-channel marketing campaigns.</li>
                            <li>• <b class="text-indigo-400 italic">Omnichannel O2O:</b> Aligned offline store data with e-commerce platforms for **Muji VN** to create a unified customer experience.</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- CIRCLE K -->
            <div class="relative pl-12 group">
                <div class="timeline-dot shadow-rose-500"></div>
                <div class="grid lg:grid-cols-3 gap-8">
                    <div class="lg:col-span-1">
                        <span class="text-rose-500 font-black text-xl italic tracking-tighter tracking-tighter">05/2019 - 09/2023</span>
                        <h3 class="text-3xl font-black text-white uppercase mt-2 leading-none uppercase mt-2 leading-none text-white uppercase mt-2 leading-none uppercase mt-2 leading-none text-white uppercase mt-2 leading-none uppercase mt-2 leading-none italic italic">Circle K VN</h3>
                        <p class="text-slate-500 font-bold uppercase text-[10px] tracking-widest underline italic">Senior CRM Loyalty & Data Manager</p>
                    </div>
                    <div class="lg:col-span-2 glass p-8 rounded-[2.5rem] space-y-4 text-sm text-slate-300 leading-relaxed">
                        <ul class="space-y-3">
                            <li>• <b class="text-rose-400 italic">App Ownership:</b> Built the **CK Club App** and CRM platform from scratch for 520+ stores, focusing on Stamp Card and Coupon continuity.</li>
                            <li>• <b class="text-rose-400 italic">Retention Growth:</b> Achieved a **62% retention rate** via Walt Disney Continuity and Red Season gamification campaigns.</li>
                            <li>• <b class="text-rose-400 italic">Data Science:</b> Established ETL architecture on **Google BigQuery**, unifying offline POS and online delivery (CK Go) data.</li>
                            <li>• <b class="text-rose-400 italic">Sales Optimization:</b> Applied **Apriori Algorithm (Basket Analysis)** and RFM models, increasing sales transactions from 8% to 15% in Q4/2020.</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- ACFC -->
            <div class="relative pl-12">
                <div class="timeline-dot shadow-sky-500"></div>
                <div class="grid lg:grid-cols-3 gap-8">
                    <div class="lg:col-span-1">
                        <span class="text-sky-500 font-black text-xl italic italic">2018 - 2019</span>
                        <h3 class="text-3xl font-black text-white uppercase mt-2 italic italic uppercase mt-2 italic italic">ACFC (IPPG)</h3>
                        <p class="text-slate-500 font-bold uppercase text-[10px] tracking-widest underline italic italic tracking-widest underline italic italic tracking-widest underline italic">CRM Manager</p>
                    </div>
                    <div class="lg:col-span-2 glass p-8 rounded-[2.5rem] space-y-4 text-sm text-slate-300 leading-relaxed">
                        <p>Strategized Loyalty for 14 brands (**Nike, GAP, Levi's, Calvin Klein...**). Built **HubSpot Marketing Automation** saving 60% manual time. Developed multi-channel data reports tracking Member behavior in both Online and Offline environments.</p>
                    </div>
                </div>
            </div>

            <!-- GOLDEN GATE -->
            <div class="relative pl-12">
                <div class="timeline-dot shadow-orange-500 shadow-orange-500"></div>
                <div class="grid lg:grid-cols-3 gap-8">
                    <div class="lg:col-span-1 text-orange-400 font-black text-xl italic italic">2015 - 2017</span>
                        <h3 class="text-3xl font-black text-white uppercase mt-2 italic italic italic">Golden Gate</h3>
                        <p class="text-slate-500 font-bold uppercase text-[10px] tracking-widest underline italic italic italic">CRM Leader (South Regional)</p>
                    </div>
                    <div class="lg:col-span-2 glass p-8 rounded-[2.5rem] space-y-4 text-sm text-slate-300 leading-relaxed text-slate-300 leading-relaxed text-slate-300 leading-relaxed">
                        <p>Managed member loyalty for all 14 Brands (**Gogi, Kichi-Kichi, Sumo BBQ...**). Led HCM CRM team in implementing E-wallet accumulation and reward mechanics. Launched <b>The Golden Spoon App</b> and established partner co-operation branding policies.</p>
                    </div>
                </div>
            </div>

            <!-- AUCHAN & METRO -->
            <div class="grid md:grid-cols-2 gap-8 lg:ml-4">
                <div class="glass p-8 rounded-[2.5rem] border-t-2 border-slate-700">
                    <span class="text-slate-500 font-black text-[10px] uppercase">2013 - 2015 Milestone</span>
                    <h3 class="text-xl font-bold text-white uppercase mt-2 italic underline underline-offset-4 decoration-sky-500 font-bold text-white uppercase mt-2 italic underline underline-offset-4 decoration-sky-500">Auchan Vietnam</h3>
                    <p class="text-[11px] text-slate-400 mt-4 leading-relaxed font-medium">CRM & Promotion Specialist. Developed long-term integrated CRM tactics for loyalty cards and seasonal repurchase strategies across multiple sale channels.</p>
                </div>
                <div class="glass p-8 rounded-[2.5rem] border-t-2 border-slate-700 font-medium">
                    <span class="text-slate-500 font-black text-[10px] uppercase uppercase uppercase">2010 - 2013 Milestone</span>
                    <h3 class="text-xl font-bold text-white uppercase mt-2 italic underline underline-offset-4 decoration-sky-500">Metro Cash & Carry</h3>
                    <p class="text-[11px] text-slate-400 mt-4 leading-relaxed font-medium">Trader Development Executive. Assisting Head of Trade in managing Retail Buyers/Wholesalers and General/Modern Trade segments (Mom & Pop, Minimarts, Convenience Stores).</p>
                </div>
            </div>

        </div>
    </section>

    <!-- TECHNICAL MASTERY (FULL 100% SKILL SET) -->
    <section id="skills" class="py-32 px-6 md:px-20 relative overflow-hidden italic italic italic italic">
        <img src="./anh3.jpg" class="absolute right-[-10%] top-20 w-1/3 opacity-10 grayscale rounded-full blur-[2px] pointer-events-none">
        
        <div class="max-w-7xl mx-auto space-y-20">
            <h2 class="text-5xl font-black text-center uppercase tracking-tighter italic">Technical <span class="text-sky-500 italic uppercase">Mastery</span></h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
                <!-- Group 1: Strategic Martech -->
                <div class="space-y-8">
                    <div class="w-14 h-14 bg-sky-500/20 rounded-2xl flex items-center justify-center text-sky-400"><i data-lucide="layers"></i></div>
                    <h3 class="text-2xl font-black uppercase text-sky-400 italic">Strategy & Frameworks</h3>
                    <ul class="text-xs space-y-4 text-slate-400 font-extrabold uppercase tracking-[0.1em] italic">
                        <li>• CRM Strategy & Loyalty Model Business Canvas</li>
                        <li>• Lifecycle Marketing (User Data Strategy)</li>
                        <li>• Customer Journey Touchpoint Optimization</li>
                        <li>• O2O Strategy & Mobile App Ecosystems</li>
                        <li>• CDP Planning & User 360 Architecture</li>
                        <li>• SDK Tracking Setup (Insider, CleverTap, GA360)</li>
                    </ul>
                </div>

                <!-- Group 2: Data Science & ML -->
                <div class="space-y-8 italic italic">
                    <div class="w-14 h-14 bg-purple-500/20 rounded-2xl flex items-center justify-center text-purple-400"><i data-lucide="cpu"></i></div>
                    <h3 class="text-2xl font-black uppercase text-purple-400">Data Science Models</h3>
                    <div class="space-y-3">
                        <div class="glass p-4 rounded-xl border-l-2 border-purple-500 shadow-xl shadow-purple-500/5">
                            <h4 class="text-white text-[10px] font-black uppercase tracking-widest">RFM & K-Means Clustering</h4>
                            <p class="text-[9px] text-slate-500 mt-1 uppercase italic underline decoration-sky-500/30 font-bold tracking-widest font-black uppercase tracking-widest">Advanced Behavioral Segmentation</p>
                        </div>
                        <div class="glass p-4 rounded-xl border-l-2 border-purple-500 shadow-xl shadow-purple-500/5">
                            <h4 class="text-white text-[10px] font-black uppercase tracking-widest">Logistic Regression</h4>
                            <p class="text-[9px] text-slate-500 mt-1 uppercase italic underline decoration-sky-500/30 font-bold tracking-widest font-black uppercase tracking-widest">Customer Churn & Retention Prediction</p>
                        </div>
                        <div class="glass p-4 rounded-xl border-l-2 border-purple-500 shadow-xl shadow-purple-500/5">
                            <h4 class="text-white text-[10px] font-black uppercase tracking-widest">Apriori Algorithm</h4>
                            <p class="text-[9px] text-slate-500 mt-1 uppercase italic underline decoration-sky-500/30 font-bold tracking-widest font-black uppercase tracking-widest">Market Basket Affinities & Combo Selection</p>
                        </div>
                        <div class="glass p-4 rounded-xl border-l-2 border-purple-500 shadow-xl shadow-purple-500/5">
                            <h4 class="text-white text-[10px] font-black uppercase tracking-widest font-black uppercase tracking-widest">Collaborative Filtering</h4>
                            <p class="text-[9px] text-slate-500 mt-1 uppercase italic underline decoration-sky-500/30 font-bold tracking-widest">1:1 User-based Recommendation System</p>
                        </div>
                    </div>
                </div>

                <!-- Group 3: Technical BI -->
                <div class="space-y-8">
                    <div class="w-14 h-14 bg-emerald-500/20 rounded-2xl flex items-center justify-center text-emerald-400"><i data-lucide="database"></i></div>
                    <h3 class="text-2xl font-black uppercase text-emerald-400 italic">BI & Technical Stack</h3>
                    <div class="space-y-6 pr-6">
                        <div>
                            <div class="flex justify-between text-[10px] font-bold uppercase mb-2 text-white"><span>SQL (BigQuery, PostgreSQL)</span><span>98%</span></div>
                            <div class="w-full bg-white/5 h-1 rounded-full"><div class="bg-emerald-500 h-full w-[98%] shadow-[0_0_10px_#10b981]"></div></div>
                        </div>
                        <div>
                            <div class="flex justify-between text-[10px] font-bold uppercase mb-2 text-white italic italic italic underline decoration-sky-500/30 underline-offset-4 decoration-sky-500/20"><span>Python (Jupyter, VS Code, Colab)</span><span>92%</span></div>
                            <div class="w-full bg-white/5 h-1 rounded-full text-white"><div class="bg-emerald-500 h-full w-[92%] shadow-[0_0_10px_#10b981]"></div></div>
                        </div>
                        <div>
                            <div class="flex justify-between text-[10px] font-bold uppercase mb-2 text-white italic underline underline-offset-4 decoration-sky-500/20"><span>Power BI / Tableau / Data Studio</span><span>95%</span></div>
                            <div class="w-full bg-white/5 h-1 rounded-full italic"><div class="bg-emerald-500 h-full w-[95%] shadow-[0_0_10px_#10b981]"></div></div>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-2 pt-4 pr-10">
                        <span class="skill-badge">HUBSPOT</span> <span class="skill-badge">SALESFORCE</span> <span class="skill-badge">ZALO ZNS</span> <span class="skill-badge">FIREBASE</span> <span class="skill-badge">ADVANCED EXCEL</span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer id="contact" class="py-32 px-6 md:px-20 border-t border-white/5 text-center flex flex-col items-center">
        <div class="relative mb-16">
            <div class="absolute inset-0 bg-sky-500/20 blur-[80px] rounded-full animate-pulse"></div>
            <img src="./anh5.jpg" class="w-64 h-64 rounded-full object-cover relative z-10 border-8 border-slate-900 shadow-2xl grayscale hover:grayscale-0 transition duration-700 italic">
        </div>
        <h2 class="text-6xl font-black mb-12 italic uppercase tracking-tighter leading-none text-white italic uppercase tracking-tighter leading-none text-white">Let's Connect for <br><span class="gradient-text uppercase tracking-tighter italic underline italic underline decoration-sky-500 underline-offset-8">Scalable Growth</span></h2>
        
        <div class="flex flex-col md:flex-row gap-12 items-center justify-center p-10 glass rounded-[3rem] w-full max-w-4xl">
            <div class="space-y-1">
                <i data-lucide="phone" class="mx-auto text-sky-500 w-5 h-5 mb-2"></i>
                <p class="font-black text-2xl text-white tracking-widest italic tracking-widest italic tracking-widest italic tracking-widest italic italic">(+84) 946 93 81 83</p>
            </div>
            <div class="h-10 w-px bg-white/10 hidden md:block italic italic"></div>
            <div class="space-y-1">
                <i data-lucide="mail" class="mx-auto text-sky-500 w-5 h-5 mb-2 italic italic italic underline decoration-sky-500 underline-offset-8"></i>
                <p class="font-black text-xl text-white lowercase">vinghiep.ly@gmail.com</p>
            </div>
        </div>
        
        <p class="text-slate-700 text-[10px] font-bold uppercase tracking-[0.8em] mt-24 italic tracking-[0.8em] mt-24 italic tracking-[0.8em] mt-24 italic tracking-[0.8em] mt-24 italic underline decoration-sky-500/10">Ly Vi Nghiep Portfolio © 2024</p>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
<!--
**NghiepLy/NghiepLy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
