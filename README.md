<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DevStack Portfolio | Reimagined</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brandDark: '#0B0F19',
                        brandCard: '#151D30',
                        brandPurple: '#8B5CF6',
                        brandNeon: '#10B981',
                        brandTextMut: '#94A3B8'
                    }
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .mono {
            font-family: 'JetBrains Mono', monospace;
        }
    </style>
</head>
<body class="bg-brandDark text-slate-100 min-h-screen selection:bg-brandPurple selection:text-white">

    <header class="fixed top-0 left-0 w-full bg-brandDark/80 backdrop-blur-md border-b border-slate-800/60 z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="mono text-lg font-bold tracking-wider text-transparent bg-clip-text bg-gradient-to-r from-brandPurple to-brandNeon">
                &lt;AAArhamAli /&gt;
            </a>
            
            <nav class="hidden md:flex items-center space-x-8 font-medium text-sm text-brandTextMut">
                <a href="#" class="text-slate-200 hover:text-brandNeon transition-colors">Home</a>
                <a href="#projects" class="hover:text-brandNeon transition-colors">Projects</a>
                <a href="#stack" class="hover:text-brandNeon transition-colors">Stack</a>
                <a href="#about" class="hover:text-brandNeon transition-colors">About</a>
                <a href="#contact" class="hover:text-brandNeon transition-colors">Contact</a>
            </nav>

            <div class="flex items-center space-x-3 bg-brandCard/60 border border-brandNeon/20 px-4 py-1.5 rounded-full text-xs mono">
                <span class="relative flex h-2 w-2">
                    <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-brandNeon opacity-75"></span>
                    <span class="relative inline-flex rounded-full h-2 w-2 bg-brandNeon"></span>
                </span>
                <span class="text-brandNeon">All Systems Operational</span>
            </div>
        </div>
    </header>

    <section class="relative pt-40 pb-24 px-6 overflow-hidden">
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] bg-brandPurple/10 rounded-full blur-[120px] pointer-events-none"></div>
        <div class="absolute top-1/3 left-1/3 w-[300px] h-[300px] bg-brandNeon/5 rounded-full blur-[100px] pointer-events-none"></div>

        <div class="max-w-4xl mx-auto text-center relative z-10">
            <div class="inline-block px-3 py-1 bg-brandPurple/10 border border-brandPurple/30 rounded-full text-xs font-semibold uppercase tracking-wider text-brandPurple mb-6 mono">
                Full-Stack Reliability Engineer
            </div>
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-6 bg-gradient-to-b from-white to-slate-400 bg-clip-text text-transparent leading-none">
                Monitor, Debug & Fix Production <br class="hidden sm:inline"><span class="text-transparent bg-clip-text bg-gradient-to-r from-brandPurple to-brandNeon">at Scale</span>
            </h1>
            <p class="text-lg text-brandTextMut max-w-2xl mx-auto mb-10 leading-relaxed">
                Full-stack developer specializing in observability, infrastructure monitoring, and building high-performance systems. Turning chaos into clarity with modern tooling.
            </p>
            
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
                <a href="#projects" class="w-full sm:w-auto px-8 py-3.5 bg-brandPurple hover:bg-brandPurple/90 text-white font-medium rounded-lg shadow-lg shadow-brandPurple/20 transition-all transform hover:-translate-y-0.5 text-center">
                    View Projects
                </a>
                <a href="#contact" class="w-full sm:w-auto px-8 py-3.5 bg-brandCard hover:bg-slate-800 border border-slate-700 text-slate-200 font-medium rounded-lg transition-all transform hover:-translate-y-0.5 text-center">
                    Get in Touch
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 p-6 bg-brandCard/40 border border-slate-800/80 rounded-2xl backdrop-blur-sm max-w-3xl mx-auto">
                <div class="p-4 border-r border-slate-800/60 last:border-0">
                    <div class="text-2xl sm:text-3xl font-bold text-brandNeon mono mb-1">99.99%</div>
                    <div class="text-xs text-brandTextMut tracking-wide uppercase font-semibold">Uptime</div>
                </div>
                <div class="p-4 md:border-r border-slate-800/60 last:border-0">
                    <div class="text-2xl sm:text-3xl font-bold text-slate-100 mono mb-1">&lt;50ms</div>
                    <div class="text-xs text-brandTextMut tracking-wide uppercase font-semibold">Avg Response</div>
                </div>
                <div class="p-4 border-r border-slate-800/60 last:border-0">
                    <div class="text-2xl sm:text-3xl font-bold text-slate-100 mono mb-1">50+</div>
                    <div class="text-xs text-brandTextMut tracking-wide uppercase font-semibold">Projects Shipped</div>
                </div>
                <div class="p-4 last:border-0">
                    <div class="text-2xl sm:text-3xl font-bold text-brandPurple mono mb-1">200+</div>
                    <div class="text-xs text-brandTextMut tracking-wide uppercase font-semibold">Systems Monitored</div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-24 px-6 border-t border-slate-900 bg-brandDark/50 relative">
        <div class="max-w-7xl mx-auto">
            <div class="max-w-2xl mb-16">
                <h2 class="text-xs uppercase font-bold tracking-widest text-brandNeon mono mb-3">// Capability Catalog</h2>
                <h3 class="text-3xl sm:text-4xl font-bold text-white mb-4">What I Build</h3>
                <p class="text-brandTextMut">
                    From monitoring dashboards to incident management platforms, I specialize in tools that help engineering teams understand and fix production issues faster.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="group p-8 bg-brandCard/60 border border-slate-800/80 rounded-2xl hover:border-brandPurple/40 transition-all duration-300 relative overflow-hidden flex flex-col justify-between">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-brandPurple/5 rounded-full blur-xl group-hover:bg-brandPurple/10 transition-all"></div>
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-brandPurple/10 border border-brandPurple/20 flex items-center justify-center text-brandPurple mb-6 font-bold mono">01</div>
                        <h4 class="text-xl font-bold text-slate-100 mb-3 group-hover:text-brandPurple transition-colors">Uptime Monitoring</h4>
                        <p class="text-sm text-brandTextMut leading-relaxed">Global monitoring for websites, APIs, and servers with instant smart alerts.</p>
                    </div>
                </div>

                <div class="group p-8 bg-brandCard/60 border border-slate-800/80 rounded-2xl hover:border-brandNeon/40 transition-all duration-300 relative overflow-hidden flex flex-col justify-between">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-brandNeon/5 rounded-full blur-xl group-hover:bg-brandNeon/10 transition-all"></div>
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-brandNeon/10 border border-brandNeon/20 flex items-center justify-center text-brandNeon mb-6 font-bold mono">02</div>
                        <h4 class="text-xl font-bold text-slate-100 mb-3 group-hover:text-brandNeon transition-colors">Incident Management</h4>
                        <p class="text-sm text-brandTextMut leading-relaxed">On-call scheduling, automated escalation channels, and post-incident developer workflows.</p>
                    </div>
                </div>

                <div class="group p-8 bg-brandCard/60 border border-slate-800/80 rounded-2xl hover:border-brandPurple/40 transition-all duration-300 relative overflow-hidden flex flex-col justify-between">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-brandPurple/5 rounded-full blur-xl group-hover:bg-brandPurple/10 transition-all"></div>
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-brandPurple/10 border border-brandPurple/20 flex items-center justify-center text-brandPurple mb-6 font-bold mono">03</div>
                        <h4 class="text-xl font-bold text-slate-100 mb-3 group-hover:text-brandPurple transition-colors">Log Management</h4>
                        <p class="text-sm text-brandTextMut leading-relaxed">High-performance structural log collection with blazing-fast SQL-based querying capabilities.</p>
                    </div>
                </div>

                <div class="group p-8 bg-brandCard/60 border border-slate-800/80 rounded-2xl hover:border-brandNeon/40 transition-all duration-300 relative overflow-hidden flex flex-col justify-between">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-brandNeon/5 rounded-full blur-xl group-hover:bg-brandNeon/10 transition-all"></div>
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-brandNeon/10 border border-brandNeon/20 flex items-center justify-center text-brandNeon mb-6 font-bold mono">04</div>
                        <h4 class="text-xl font-bold text-slate-100 mb-3 group-hover:text-brandNeon transition-colors">Error Tracking</h4>
                        <p class="text-sm text-brandTextMut leading-relaxed">AI-native exception isolation, complete with comprehensive session context and trace analysis.</p>
                    </div>
                </div>

                <div class="group p-8 bg-brandCard/60 border border-slate-800/80 rounded-2xl hover:border-brandPurple/40 transition-all duration-300 relative overflow-hidden flex flex-col justify-between">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-brandPurple/5 rounded-full blur-xl group-hover:bg-brandPurple/10 transition-all"></div>
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-brandPurple/10 border border-brandPurple/20 flex items-center justify-center text-brandPurple mb-6 font-bold mono">05</div>
                        <h4 class="text-xl font-bold text-slate-100 mb-3 group-hover:text-brandPurple transition-colors">Distributed Tracing</h4>
                        <p class="text-sm text-brandTextMut leading-relaxed">OpenTelemetry-native distributed request tracing backed by transparent eBPF auto-instrumentation.</p>
                    </div>
                </div>

                <div class="group p-8 bg-brandCard/60 border border-slate-800/80 rounded-2xl hover:border-brandNeon/40 transition-all duration-300 relative overflow-hidden flex flex-col justify-between">
                    <div class="absolute top-0 right-0 w-24 h-24 bg-brandNeon/5 rounded-full blur-xl group-hover:bg-brandNeon/10 transition-all"></div>
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-brandNeon/10 border border-brandNeon/20 flex items-center justify-center text-brandNeon mb-6 font-bold mono">06</div>
                        <h4 class="text-xl font-bold text-slate-100 mb-3 group-hover:text-brandNeon transition-colors">Real User Monitoring</h4>
                        <p class="text-sm text-brandTextMut leading-relaxed">In-depth session replays, Core Web Vitals profiling, and granular frontend performance metric sets.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 px-6 relative overflow-hidden bg-gradient-to-b from-brandDark to-[#070A10]">
        <div class="max-w-4xl mx-auto bg-gradient-to-br from-brandCard to-brandDark border border-slate-800 p-8 sm:p-12 rounded-3xl text-center relative z-10">
            <h3 class="text-3xl sm:text-4xl font-bold text-white mb-4">Ready to collaborate?</h3>
            <p class="text-brandTextMut max-w-xl mx-auto mb-8">
                Whether you need an advanced monitoring dashboard, an observability ecosystem, or a reliable full-stack application—let’s construct something bulletproof together.
            </p>
            <a href="mailto:your-email@domain.com" class="inline-block px-8 py-3.5 bg-brandNeon hover:bg-brandNeon/90 text-brandDark font-bold rounded-lg shadow-lg shadow-brandNeon/10 transition-all transform hover:-translate-y-0.5">
                Contact Me
            </a>
        </div>
    </section>

    <footer class="bg-[#070A10] border-t border-slate-950 text-xs text-brandTextMut py-12 px-6">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
            <div>
                <span class="mono text-base font-bold tracking-wider text-slate-100 block mb-3">&lt;AAArhamAli /&gt;</span>
                <p class="leading-relaxed text-brandTextMut/80">Building reliable, high-performance distributed systems with modern, deep observability infrastructure.</p>
            </div>
            <div>
                <h5 class="text-slate-300 font-semibold mb-3 uppercase tracking-wider mono text-[10px]">Pages</h5>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-brandPurple transition-colors">Home</a></li>
                    <li><a href="#projects" class="hover:text-brandPurple transition-colors">Projects</a></li>
                    <li><a href="#stack" class="hover:text-brandPurple transition-colors">Stack</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-slate-300 font-semibold mb-3 uppercase tracking-wider mono text-[10px]">Resources</h5>
                <ul class="space-y-2">
                    <li><a href="#about" class="hover:text-brandPurple transition-colors">About</a></li>
                    <li><a href="#contact" class="hover:text-brandPurple transition-colors">Contact</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-slate-300 font-semibold mb-3 uppercase tracking-wider mono text-[10px]">Social</h5>
                <ul class="space-y-2">
                    <li><a href="https://github.com/TechWizard-2009" target="_blank" class="hover:text-brandNeon transition-colors">GitHub</a></li>
                    <li><a href="https://www.instagram.com/" target="_blank" class="hover:text-brandNeon transition-colors">Instagram</a></li>
                </ul>
            </div>
        </div>
        <div class="max-w-7xl mx-auto border-t border-slate-900 pt-6 flex flex-col sm:flex-row items-center justify-between gap-4">
            <div>&copy; 2026 DevStack Portfolio. All rights reserved.</div>
            <div class="flex space-x-4">
                <a href="#" class="hover:underline">Privacy Policy</a>
                <a href="#" class="hover:underline">Terms of Service</a>
            </div>
        </div>
    </footer>

</body>
</html>
