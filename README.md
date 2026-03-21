<iframe src="https://debeatzgh1.github.io/The-Ultimate-Guide-to-Side-Hustle/" width="100%" height="400" frameborder="0" allowfullscreen></iframe>






<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DeBeatzGH | Side Hustle Framework</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&family=JetBrains+Mono&display=swap');

        :root {
            --accent: #00f2ff;
            --bg: #0a0a0c;
            --glass: rgba(255, 255, 255, 0.03);
            --border: rgba(255, 255, 255, 0.08);
        }

        body {
            background-color: var(--bg);
            color: #e2e8f0;
            font-family: 'Plus Jakarta Sans', sans-serif;
            line-height: 1.6;
        }

        /* --- PROFESSIONAL LAZY LOAD --- */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* --- PREMIUM FAQ ACCORDION --- */
        .faq-card {
            background: var(--glass);
            border: 1px solid var(--border);
            border-radius: 20px;
            margin-bottom: 1rem;
            overflow: hidden;
            transition: 0.3s;
        }
        .faq-card:hover { border-color: var(--accent); background: rgba(255,255,255,0.05); }

        .faq-header {
            padding: 20px 25px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 800;
            letter-spacing: -0.5px;
        }

        .faq-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease-out;
            background: rgba(0,0,0,0.2);
        }

        .faq-card.open .faq-content { max-height: 2000px; padding: 25px; border-top: 1px solid var(--border); }
        .faq-card.open i { transform: rotate(180deg); color: var(--accent); }

        /* --- TABLE & CODE STYLING --- */
        table { width: 100%; border-collapse: collapse; margin: 15px 0; font-size: 13px; }
        th { text-align: left; color: var(--accent); padding: 12px; border-bottom: 2px solid var(--border); text-transform: uppercase; font-size: 10px; }
        td { padding: 12px; border-bottom: 1px solid var(--border); }
        code { font-family: 'JetBrains Mono'; color: var(--accent); background: rgba(0,242,255,0.1); padding: 2px 6px; border-radius: 4px; }
        
        pre {
            background: #000;
            padding: 20px;
            border-radius: 12px;
            border: 1px solid var(--border);
            font-size: 12px;
            overflow-x: auto;
        }

        .badge-grid span {
            font-family: 'JetBrains Mono';
            font-size: 10px;
            padding: 4px 10px;
            border-radius: 6px;
            background: #1e293b;
            margin-right: 5px;
        }
    </style>
</head>
<body class="p-6 md:p-20">

    <header class="max-w-4xl mx-auto mb-16 text-center reveal">
        <h1 class="text-4xl md:text-6xl font-black tracking-tighter mb-4 text-white">THE SIDE HUSTLE <span class="text-cyan-400">FRAMEWORK</span></h1>
        <p class="text-gray-400 max-w-2xl mx-auto">This repository is not just a list of links. It is a <b class="text-white">mechanical system</b> for building profitable digital assets in 2026.</p>
        
        <div class="flex flex-wrap justify-center gap-4 mt-8">
            <div class="bg-white/5 px-6 py-3 rounded-2xl border border-white/10 text-xs font-bold uppercase tracking-widest"><i class="fas fa-bolt text-cyan-400 mr-2"></i> Speed Over Perfection</div>
            <div class="bg-white/5 px-6 py-3 rounded-2xl border border-white/10 text-xs font-bold uppercase tracking-widest"><i class="fas fa-check-circle text-green-400 mr-2"></i> Profit Over Revenue</div>
        </div>
    </header>

    <main class="max-w-4xl mx-auto">

        <div class="faq-card reveal">
            <div class="faq-header" onclick="toggleFaq(this)">
                <span>PHASE 1: IDEA VALIDATION & THE PAINKILLER MATRIX</span>
                <i class="fas fa-chevron-down transition-transform"></i>
            </div>
            <div class="faq-content">
                <p class="mb-4 text-gray-400">Before you buy a domain, score your idea using the <b>Pain Killer Matrix</b>. If the score is below 20, pivot.</p>
                <table>
                    <thead>
                        <tr><th>Criteria</th><th>Question</th><th>Score (1-10)</th></tr>
                    </thead>
                    <tbody>
                        <tr><td><b>Pain Level</b></td><td>Is this a "hair on fire" problem?</td><td><code>[ ]</code></td></tr>
                        <tr><td><b>Purchasing Power</b></td><td>Does this audience have money?</td><td><code>[ ]</code></td></tr>
                        <tr><td><b>Accessibility</b></td><td>Can you find 100 people today?</td><td><code>[ ]</code></td></tr>
                    </tbody>
                </table>
                <h4 class="mt-6 font-bold text-white mb-2">The "Smoke Test" Protocol:</h4>
                <ul class="list-disc ml-6 space-y-2 text-sm text-gray-400">
                    <li><b>Build:</b> A one-page site on GitHub Pages.</li>
                    <li><b>The Offer:</b> "Join waitlist for 50% off."</li>
                    <li><b>The KPI:</b> Get 10 emails from 100 clicks or the idea is dead.</li>
                </ul>
            </div>
        </div>

        <div class="faq-card reveal">
            <div class="faq-header" onclick="toggleFaq(this)">
                <span>PHASE 2: THE "NO-BUDGET" TECH STACK (2026)</span>
                <i class="fas fa-chevron-down transition-transform"></i>
            </div>
            <div class="faq-content">
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <h4 class="text-cyan-400 font-bold mb-3 text-sm">DESIGN & UI</h4>
                        <ul class="space-y-2 text-sm">
                            <li><b>Canva:</b> Branding & Social</li>
                            <li><b>UnDraw:</b> Open Source SVGs</li>
                            <li><b>Phosphor:</b> Premium Icons</li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-cyan-400 font-bold mb-3 text-sm">BUILD & HOST</h4>
                        <ul class="space-y-2 text-sm">
                            <li><b>GitHub Pages:</b> Free Static Hosting</li>
                            <li><b>Tally Forms:</b> Unlimited Free Forms</li>
                            <li><b>Stripe:</b> No-Code Payment Links</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="faq-card reveal">
            <div class="faq-header" onclick="toggleFaq(this)">
                <span>PHASE 3: MARKETING & COLD OUTREACH SCRIPTS</span>
                <i class="fas fa-chevron-down transition-transform"></i>
            </div>
            <div class="faq-content">
                <p class="text-xs uppercase text-gray-500 font-bold mb-4">Copy-Paste Validation Script:</p>
                <div class="bg-black/50 p-6 rounded-xl border-l-4 border-cyan-400 italic text-sm">
                    "Hi [Name], I saw your post about [Problem]. I built a very ugly but functional tool to fix that. I’m looking for 5 people to tear it apart for free. Interested in a link?"
                </div>
                <div class="mt-6">
                    <h4 class="font-bold mb-2">First 100 Users Checklist:</h4>
                    <div class="space-y-2">
                        <label class="flex items-center gap-3 text-sm"><input type="checkbox" class="accent-cyan-400"> Cold DM Strategy (10/day)</label>
                        <label class="flex items-center gap-3 text-sm"><input type="checkbox" class="accent-cyan-400"> Reddit/Subreddit Helpful Comments</label>
                        <label class="flex items-center gap-3 text-sm"><input type="checkbox" class="accent-cyan-400"> Directory Submissions</label>
                    </div>
                </div>
            </div>
        </div>

        <div class="faq-card reveal">
            <div class="faq-header" onclick="toggleFaq(this)">
                <span>PHASE 4: PRICING PSYCHOLOGY & LEGAL</span>
                <i class="fas fa-chevron-down transition-transform"></i>
            </div>
            <div class="faq-content">
                <div class="space-y-4">
                    <div>
                        <h4 class="font-bold text-white">The "Anchor" Price:</h4>
                        <p class="text-sm text-gray-400">Offer Option A ($29) and Option B ($99). Option B makes A look like a bargain.</p>
                    </div>
                    <div class="p-4 bg-red-500/10 border border-red-500/20 rounded-xl">
                        <h4 class="text-red-400 font-bold text-xs uppercase">The "Tax Man" Rule:</h4>
                        <p class="text-[11px] text-gray-400 mt-1">Save 30% of every dollar you make. Put it in a separate account and do not touch it.</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="mt-20 p-8 border border-dashed border-white/20 rounded-3xl text-center reveal">
            <h3 class="text-xs font-black uppercase tracking-widest text-gray-500 mb-6">Project Status Badges</h3>
            <div class="badge-grid flex flex-wrap justify-center gap-2">
                <span class="border border-yellow-500/50 text-yellow-500">⬛️ IDEA</span>
                <span class="border border-cyan-500/50 text-cyan-500">🟨 BUILDING</span>
                <span class="border border-green-500/50 text-green-400">🟩 LAUNCHED</span>
                <span class="border border-white/20">REVENUE: $0</span>
            </div>
        </div>

    </main>

    <footer class="mt-20 py-10 border-t border-white/5 text-center reveal">
        <p class="text-[10px] text-gray-600 font-bold uppercase tracking-widest">DeBeatzGH © 2026 // Dkonsult Ecosystem</p>
    </footer>

    <script>
        // --- FAQ TOGGLE LOGIC ---
        function toggleFaq(header) {
            const card = header.parentElement;
            card.classList.toggle('open');
        }

        // --- LAZY LOAD OBSERVER ---
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
    </script>
</body>
</html>
