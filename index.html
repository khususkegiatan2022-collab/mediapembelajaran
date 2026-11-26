<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MPI: Peta dan Komponen-Komponennya - Kelas V SD</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0284c7',
                            600: '#0369a1',
                            700: '#035485',
                            800: '#075985',
                            900: '#0c4a6e',
                        },
                        mapGreen: '#10b981',
                        mapYellow: '#f59e0b',
                        mapLand: '#dcfce7',
                        mapWater: '#bae6fd',
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #f8fafc;
            user-select: none;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #f1f5f9;
            border-radius: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
        .pulsing-spot {
            animation: pulse-ring 2s infinite;
        }
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(2, 132, 199, 0.7); }
            70% { transform: scale(1.05); box-shadow: 0 0 0 10px rgba(2, 132, 199, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(2, 132, 199, 0); }
        }
        .card-hover {
            transition: all 0.25s ease-in-out;
        }
        .card-hover:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px -10px rgba(15, 23, 42, 0.15);
        }
    </style>
</head>
<body class="text-slate-800 bg-slate-50 min-h-screen flex flex-col justify-between">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Logo & Title -->
                <div class="flex items-center gap-3 cursor-pointer" onclick="navigateTo('beranda')">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-teal-500 flex items-center justify-center text-white shadow-md">
                        <i class="fa-solid me-0 fa-map-location-dot text-lg"></i>
                    </div>
                    <div>
                        <h1 class="text-lg font-bold text-slate-800 leading-tight">PETA & KOMPONENNYA</h1>
                        <p class="text-xs font-semibold text-brand-600">MPI Kelas V Sekolah Dasar</p>
                    </div>
                </div>

                <!-- Desktop Navigation Buttons -->
                <nav class="hidden lg:flex items-center gap-1 bg-slate-100 p-1.5 rounded-2xl border border-slate-200/80">
                    <button onclick="navigateTo('beranda')" id="nav-beranda" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-brand-700 bg-white shadow-xs font-semibold">
                        <i class="fa-solid fa-house text-xs"></i> Beranda
                    </button>
                    <button onclick="navigateTo('materi')" id="nav-materi" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-slate-600 hover:text-slate-900 hover:bg-slate-200/50">
                        <i class="fa-solid fa-book-open text-xs"></i> Materi
                    </button>
                    <button onclick="navigateTo('eksplorasi')" id="nav-eksplorasi" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-slate-600 hover:text-slate-900 hover:bg-slate-200/50">
                        <i class="fa-solid fa-compass text-xs"></i> Eksplorasi Peta
                    </button>
                    <button onclick="navigateTo('tantangan')" id="nav-tantangan" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-slate-600 hover:text-slate-900 hover:bg-slate-200/50">
                        <i class="fa-solid fa-gamepad text-xs"></i> Mini Games
                    </button>
                    <button onclick="navigateTo('latihan')" id="nav-latihan" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-slate-600 hover:text-slate-900 hover:bg-slate-200/50">
                        <i class="fa-solid fa-pen-to-square text-xs"></i> Latihan Soal
                    </button>
                    <button onclick="navigateTo('pembahasan')" id="nav-pembahasan" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-slate-600 hover:text-slate-900 hover:bg-slate-200/50">
                        <i class="fa-solid fa-lightbulb text-xs"></i> Pembahasan
                    </button>
                    <button onclick="navigateTo('hasil')" id="nav-hasil" class="nav-btn px-3.5 py-1.5 rounded-xl font-medium text-sm flex items-center gap-2 transition text-slate-600 hover:text-slate-900 hover:bg-slate-200/50">
                        <i class="fa-solid fa-star text-xs"></i> Hasil Belajar
                    </button>
                </nav>

                <!-- Audio Toggle & Mobile Menu Trigger -->
                <div class="flex items-center gap-2">
                    <button onclick="toggleSound()" id="sound-btn" title="Suara Efek" class="w-10 h-10 rounded-xl bg-slate-100 hover:bg-slate-200 border border-slate-200 text-slate-700 flex items-center justify-center transition">
                        <i class="fa-solid fa-volume-high text-sm"></i>
                    </button>
                    <button onclick="toggleMobileNav()" class="lg:hidden w-10 h-10 rounded-xl bg-slate-100 hover:bg-slate-200 border border-slate-200 text-slate-700 flex items-center justify-center">
                        <i class="fa-solid fa-bars text-base"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden lg:hidden border-t border-slate-200 bg-white px-4 pt-2 pb-4 space-y-1">
            <button onclick="navigateTo('beranda')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-house text-brand-600 w-5"></i> 🏠 BERANDA
            </button>
            <button onclick="navigateTo('materi')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-book-open text-brand-600 w-5"></i> 📚 MATERI
            </button>
            <button onclick="navigateTo('eksplorasi')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-compass text-brand-600 w-5"></i> 🗺️️ EKSPLORASI PETA
            </button>
            <button onclick="navigateTo('tantangan')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-gamepad text-brand-600 w-5"></i> 🎮 MINI GAMES & TANTANGAN
            </button>
            <button onclick="navigateTo('latihan')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-pen-to-square text-brand-600 w-5"></i> ✏️ LATIHAN SOAL
            </button>
            <button onclick="navigateTo('pembahasan')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-lightbulb text-brand-600 w-5"></i> 💡 PEMBAHASAN
            </button>
            <button onclick="navigateTo('hasil')" class="w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-slate-100 font-medium text-sm flex items-center gap-3">
                <i class="fa-solid fa-star text-brand-600 w-5"></i> ⭐ HASIL BELAJAR
            </button>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex-grow w-full">

        <!-- ================= PAGE 1: BERANDA ================= -->
        <section id="page-beranda" class="page-section space-y-8 animate-fadeIn">
            <!-- Hero Banner -->
            <div class="relative overflow-hidden rounded-3xl bg-gradient-to-br from-brand-900 via-brand-800 to-teal-800 text-white p-8 sm:p-12 shadow-xl border border-brand-700/50">
                <!-- Background Map Grid Pattern Decorative -->
                <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:20px_20px] pointer-events-none"></div>
                <div class="absolute -right-12 -bottom-12 w-96 h-96 bg-teal-400/20 rounded-full blur-3xl pointer-events-none"></div>

                <div class="relative z-10 grid md:grid-cols-12 gap-8 items-center">
                    <div class="md:col-span-7 space-y-5">
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md px-3.5 py-1.5 rounded-full text-xs font-semibold text-teal-200 border border-white/20">
                            <i class="fa-solid fa-graduation-cap"></i> Media Pembelajaran Interaktif IPS
                        </div>
                        <h2 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight text-white">
                            PETA DAN KOMPONEN-KOMPONENNYA
                        </h2>
                        <p class="text-base sm:text-lg text-slate-200 max-w-xl leading-relaxed">
                            Yuk, kenali peta dan cara membacanya! Pelajari fungsi peta, jelajahi setiap komponennya secara interaktif, dan uji pemahamanmu dengan latihan yang seru!
                        </p>
                        
                        <div class="pt-2 flex flex-wrap gap-3">
                            <button onclick="navigateTo('materi')" class="px-6 py-3.5 rounded-xl bg-gradient-to-r from-teal-400 to-emerald-400 text-slate-900 font-bold hover:brightness-110 active:scale-95 transition shadow-lg shadow-teal-500/20 flex items-center gap-2 text-base">
                                <i class="fa-solid fa-circle-play"></i> MULAI BELAJAR
                            </button>
                            <button onclick="openModal('modal-petunjuk')" class="px-6 py-3.5 rounded-xl bg-white/15 hover:bg-white/20 text-white border border-white/25 font-semibold transition active:scale-95 flex items-center gap-2 text-base">
                                <i class="fa-solid fa-circle-info"></i> PETUNJUK
                            </button>
                        </div>
                    </div>

                    <!-- SVG Hero Illustration -->
                    <div class="md:col-span-5 flex justify-center">
                        <div class="relative w-full max-w-xs sm:max-w-sm bg-white/10 backdrop-blur-md p-4 rounded-2xl border border-white/20 shadow-2xl transform rotate-1 hover:rotate-0 transition duration-300">
                            <!-- SVG Map Display -->
                            <svg viewBox="0 0 400 280" class="w-full h-auto rounded-xl shadow-inner bg-sky-100">
                                <!-- Ocean Background -->
                                <rect width="400" height="280" fill="#bae6fd"/>
                                <!-- Grid Lines -->
                                <path d="M 0,70 L 400,70 M 0,140 L 400,140 M 0,210 L 400,210" stroke="#0284c7" stroke-dasharray="3,3" stroke-width="0.7" opacity="0.4"/>
                                <path d="M 100,0 L 100,280 M 200,0 L 200,280 M 300,0 L 300,280" stroke="#0284c7" stroke-dasharray="3,3" stroke-width="0.7" opacity="0.4"/>
                                <!-- Island Shapes -->
                                <path d="M 40,80 Q 80,40 140,70 T 220,110 T 160,180 T 60,150 Z" fill="#4ade80" stroke="#16a34a" stroke-width="2"/>
                                <path d="M 250,130 Q 310,100 360,140 T 320,230 T 230,200 Z" fill="#86efac" stroke="#16a34a" stroke-width="2"/>
                                <!-- Mountain Icons -->
                                <polygon points="100,110 110,90 120,110" fill="#b45309"/>
                                <polygon points="105,98 110,90 115,98" fill="#f8fafc"/>
                                <polygon points="290,160 300,140 310,160" fill="#b45309"/>
                                <!-- City Dot & Capital Star -->
                                <circle cx="80" cy="130" r="5" fill="#dc2626"/>
                                <polygon points="160,120 163,127 170,127 164,131 166,138 160,133 154,138 156,131 150,127 157,127" fill="#f59e0b"/>
                                <!-- Compass Rose in SVG -->
                                <g transform="translate(350, 45)">
                                    <circle cx="0" cy="0" r="22" fill="#ffffff" opacity="0.9" stroke="#0369a1" stroke-width="1.5"/>
                                    <path d="M 0,-18 L 4,0 L 0,4 L -4,0 Z" fill="#dc2626"/>
                                    <path d="M 0,18 L 4,0 L 0,-4 L -4,0 Z" fill="#64748b"/>
                                    <text x="0" y="-20" text-anchor="middle" font-size="10" font-weight="bold" fill="#0f172a">U</text>
                                </g>
                                <!-- Title Banner -->
                                <rect x="20" y="15" width="200" height="28" rx="6" fill="#ffffff" opacity="0.95"/>
                                <text x="120" y="34" text-anchor="middle" font-size="11" font-weight="bold" fill="#0f172a">PETA PULAU NUSANTARA</text>
                            </svg>
                            <div class="mt-3 text-center">
                                <span class="text-xs font-medium text-teal-100 bg-white/10 px-3 py-1 rounded-full">Peta Digital Interaktif SD Kelas 5</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Learning Objectives & Features Cards -->
            <div class="grid md:grid-cols-3 gap-6">
                <!-- Tujuan Pembelajaran -->
                <div class="md:col-span-2 bg-white rounded-3xl p-6 sm:p-8 border border-slate-200 shadow-sm space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-xl bg-amber-100 text-amber-700 flex items-center justify-center font-bold text-lg">
                            <i class="fa-solid fa-bullseye"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-slate-800">Tujuan Pembelajaran</h3>
                            <p class="text-xs text-slate-500">Capaian pembelajaran yang ingin diraih siswa</p>
                        </div>
                    </div>

                    <ul class="grid sm:grid-cols-2 gap-3 text-sm text-slate-700 pt-2">
                        <li class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-xl border border-slate-100">
                            <i class="fa-solid fa-circle-check text-emerald-500 text-base mt-0.5"></i>
                            <span>Menjelaskan <strong>pengertian peta</strong> dengan benar.</span>
                        </li>
                        <li class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-xl border border-slate-100">
                            <i class="fa-solid fa-circle-check text-emerald-500 text-base mt-0.5"></i>
                            <span>Mengidentifikasi <strong>fungsi peta</strong> dalam kehidupan sehari-hari.</span>
                        </li>
                        <li class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-xl border border-slate-100">
                            <i class="fa-solid fa-circle-check text-emerald-500 text-base mt-0.5"></i>
                            <span>Menyebutkan <strong>komponen-komponen peta</strong> lengkap.</span>
                        </li>
                        <li class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-xl border border-slate-100">
                            <i class="fa-solid fa-circle-check text-emerald-500 text-base mt-0.5"></i>
                            <span>Menjelaskan <strong>fungsi tiap komponen</strong> peta secara rinci.</span>
                        </li>
                        <li class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-xl border border-slate-100">
                            <i class="fa-solid fa-circle-check text-emerald-500 text-base mt-0.5"></i>
                            <span>Mengidentifikasi komponen melalui <strong>gambar interaktif</strong>.</span>
                        </li>
                        <li class="flex items-start gap-2.5 bg-slate-50 p-3 rounded-xl border border-slate-100">
                            <i class="fa-solid fa-circle-check text-emerald-500 text-base mt-0.5"></i>
                            <span>Menerapkan pemahaman lewat <strong>latihan & tantangan soal</strong>.</span>
                        </li>
                    </ul>
                </div>

                <!-- Quick Menu Shortcut -->
                <div class="bg-gradient-to-br from-slate-900 to-brand-950 rounded-3xl p-6 text-white flex flex-col justify-between shadow-md">
                    <div>
                        <div class="flex items-center gap-3 mb-4">
                            <div class="w-10 h-10 rounded-xl bg-white/10 flex items-center justify-center text-teal-300">
                                <i class="fa-solid fa-rocket text-lg"></i>
                            </div>
                            <h3 class="text-xl font-bold">Akses Cepat</h3>
                        </div>
                        <p class="text-xs text-slate-300 mb-6">Pilih menu pembelajaran yang ingin kamu akses sekarang:</p>
                        
                        <div class="space-y-2.5">
                            <button onclick="navigateTo('eksplorasi')" class="w-full p-3 rounded-xl bg-white/10 hover:bg-white/20 border border-white/10 text-left font-medium text-sm flex items-center justify-between transition">
                                <span class="flex items-center gap-2.5"><i class="fa-solid fa-map text-teal-400"></i> Eksplorasi Peta Klik</span>
                                <i class="fa-solid fa-arrow-right text-xs text-slate-400"></i>
                            </button>
                            <button onclick="navigateTo('tantangan')" class="w-full p-3 rounded-xl bg-white/10 hover:bg-white/20 border border-white/10 text-left font-medium text-sm flex items-center justify-between transition">
                                <span class="flex items-center gap-2.5"><i class="fa-solid fa-gamepad text-amber-400"></i> Mini Games Komponen</span>
                                <i class="fa-solid fa-arrow-right text-xs text-slate-400"></i>
                            </button>
                            <button onclick="navigateTo('latihan')" class="w-full p-3 rounded-xl bg-white/10 hover:bg-white/20 border border-white/10 text-left font-medium text-sm flex items-center justify-between transition">
                                <span class="flex items-center gap-2.5"><i class="fa-solid fa-pen text-sky-400"></i> Latihan 15 Soal</span>
                                <i class="fa-solid fa-arrow-right text-xs text-slate-400"></i>
                            </button>
                        </div>
                    </div>

                    <div class="mt-6 pt-4 border-t border-white/10 text-center text-xs text-slate-400">
                        Kurikulum Merdeka • IPS Kelas 5 SD
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= PAGE 2: MATERI ================= -->
        <section id="page-materi" class="page-section hidden space-y-8 animate-fadeIn">
            <!-- Header Banner -->
            <div class="bg-gradient-to-r from-brand-700 to-teal-700 text-white p-6 sm:p-8 rounded-3xl shadow-sm flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                <div>
                    <span class="bg-white/20 text-white text-xs px-3 py-1 rounded-full font-semibold">BAB 1: MATERI PEMBELAJARAN</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold mt-1">Peta dan Komponen-Komponennya</h2>
                    <p class="text-sm text-teal-100 mt-1">Pelajari pengertian peta, fungsi peta, dan 10 komponen penyusunnya.</p>
                </div>
                <!-- Navigation Tab Switcher -->
                <div class="flex bg-brand-900/40 p-1 rounded-xl border border-white/20">
                    <button onclick="switchMateriTab('pengertian')" id="tab-pengertian" class="materi-tab-btn px-4 py-2 rounded-lg text-xs font-bold transition bg-white text-brand-900 shadow-sm">
                        1. Pengertian & Fungsi
                    </button>
                    <button onclick="switchMateriTab('komponen')" id="tab-komponen" class="materi-tab-btn px-4 py-2 rounded-lg text-xs font-bold transition text-white hover:bg-white/10">
                        2. 10 Komponen Peta
                    </button>
                </div>
            </div>

            <!-- Tab 1: Pengertian & Fungsi Peta -->
            <div id="materi-sub-pengertian" class="space-y-6">
                <div class="grid md:grid-cols-12 gap-6 items-stretch">
                    <!-- Concept Card -->
                    <div class="md:col-span-7 bg-white p-6 sm:p-8 rounded-3xl border border-slate-200 shadow-sm space-y-4 flex flex-col justify-between">
                        <div class="space-y-4">
                            <div class="inline-flex items-center gap-2 text-brand-700 font-bold text-sm bg-brand-50 px-3 py-1.5 rounded-lg border border-brand-100">
                                <i class="fa-solid fa-lightbulb"></i> Apa itu Peta?
                            </div>
                            <h3 class="text-2xl font-bold text-slate-800 leading-snug">
                                Pengertian Peta
                            </h3>
                            <div class="p-4 rounded-2xl bg-amber-50/80 border border-amber-200/80 text-slate-800 text-base leading-relaxed font-medium">
                                "<strong>Peta</strong> adalah gambaran permukaan bumi pada bidang datar yang dibuat dengan menggunakan skala tertentu dan dilengkapi simbol-simbol untuk memberikan informasi mengenai suatu wilayah."
                            </div>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Peta membantu manusia melihat bentuk wilayah yang sangat luas dalam wujud yang diperkecil pada kertas atau layar digital.
                            </p>
                        </div>

                        <!-- Fun Quote -->
                        <div class="pt-4 border-t border-slate-100 flex items-center gap-3 text-xs text-slate-500">
                            <i class="fa-solid fa-quote-left text-2xl text-brand-400"></i>
                            <span>Dengan membaca peta, kita bisa 'keliling dunia' tanpa harus tersesat!</span>
                        </div>
                    </div>

                    <!-- SVG Illustration Card -->
                    <div class="md:col-span-5 bg-gradient-to-br from-sky-50 to-teal-50 p-6 rounded-3xl border border-sky-100 flex flex-col items-center justify-center text-center">
                        <svg viewBox="0 0 240 180" class="w-full max-w-xs drop-shadow-md">
                            <!-- Globe & Flat Paper Illustration -->
                            <circle cx="120" cy="80" r="50" fill="#38bdf8" stroke="#0284c7" stroke-width="2"/>
                            <path d="M 80,70 C 90,50 110,60 120,50 C 130,40 150,60 160,70 C 150,100 130,110 110,120 C 90,110 80,90 80,70 Z" fill="#4ade80" stroke="#16a34a" stroke-width="1.5"/>
                            <path d="M 40,150 L 200,150 L 180,110 L 60,110 Z" fill="#ffffff" stroke="#94a3b8" stroke-width="2"/>
                            <path d="M 70,120 L 170,120 M 80,135 L 160,135" stroke="#38bdf8" stroke-width="2" stroke-linecap="round"/>
                            <path d="M 120,80 L 120,110" stroke="#f59e0b" stroke-width="2" stroke-dasharray="2,2"/>
                        </svg>
                        <p class="text-xs font-semibold text-slate-600 mt-2">Transformasi Permukaan Bumi Bulat ke Bidang Datar</p>
                    </div>
                </div>

                <!-- Fungsi Peta -->
                <div class="bg-white p-6 sm:p-8 rounded-3xl border border-slate-200 shadow-sm space-y-4">
                    <h3 class="text-xl font-bold text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-compass text-brand-600"></i> Contoh Fungsi Peta Dalam Kehidupan Sehari-hari:
                    </h3>
                    
                    <div class="grid sm:grid-cols-2 lg:grid-cols-5 gap-4 pt-2">
                        <!-- Card 1 -->
                        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200/80 card-hover flex flex-col justify-between">
                            <div class="w-10 h-10 rounded-xl bg-sky-100 text-sky-700 flex items-center justify-center font-bold text-lg mb-3">
                                📍
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-slate-800 mb-1">Mencari Lokasi</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Menemukan tempat tertentu seperti sekolah, rumah sakit, atau tempat wisata.</p>
                            </div>
                        </div>
                        <!-- Card 2 -->
                        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200/80 card-hover flex flex-col justify-between">
                            <div class="w-10 h-10 rounded-xl bg-emerald-100 text-emerald-700 flex items-center justify-center font-bold text-lg mb-3">
                                🧭
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-slate-800 mb-1">Mengetahui Arah</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Menentukan arah perjalanan agar tidak tersesat saat berpergian.</p>
                            </div>
                        </div>
                        <!-- Card 3 -->
                        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200/80 card-hover flex flex-col justify-between">
                            <div class="w-10 h-10 rounded-xl bg-purple-100 text-purple-700 flex items-center justify-center font-bold text-lg mb-3">
                                🗺️
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-slate-800 mb-1">Letak Wilayah</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Mengetahui posisi relatif suatu desa, kota, provinsi, atau negara.</p>
                            </div>
                        </div>
                        <!-- Card 4 -->
                        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200/80 card-hover flex flex-col justify-between">
                            <div class="w-10 h-10 rounded-xl bg-amber-100 text-amber-700 flex items-center justify-center font-bold text-lg mb-3">
                                📏
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-slate-800 mb-1">Jarak Antartempat</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Menghitung perkiraan jarak dari satu lokasi ke lokasi lainnya.</p>
                            </div>
                        </div>
                        <!-- Card 5 -->
                        <div class="bg-slate-50 p-4 rounded-2xl border border-slate-200/80 card-hover flex flex-col justify-between">
                            <div class="w-10 h-10 rounded-xl bg-teal-100 text-teal-700 flex items-center justify-center font-bold text-lg mb-3">
                                ⛰️
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-slate-800 mb-1">Kenampakan Alam</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Mengetahui gunung, sungai, danau, laut, dan bentuk permukaan bumi.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Tab 2: 10 Komponen Peta -->
            <div id="materi-sub-komponen" class="hidden space-y-6">
                <div class="bg-amber-50 border border-amber-200 text-amber-900 p-4 rounded-2xl flex items-center gap-3 text-sm">
                    <i class="fa-solid fa-circle-info text-amber-600 text-lg"></i>
                    <span>Klik atau baca setiap komponen peta di bawah ini untuk memahami fungsi dan contohnya secara lengkap.</span>
                </div>

                <div class="grid md:grid-cols-2 gap-6">
                    <!-- A. Judul Peta -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-brand-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">A. Judul Peta</h4>
                            <span class="text-xs bg-brand-100 text-brand-800 font-bold px-2.5 py-1 rounded-full">Komponen 1</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Judul peta menunjukkan <strong>isi atau wilayah</strong> yang digambarkan dalam peta. Terletak di bagian atas agar mudah dibaca pertama kali.
                        </p>
                        <div class="bg-slate-50 p-3 rounded-xl text-xs font-semibold text-slate-700 border border-slate-200 flex items-center gap-2">
                            <i class="fa-solid fa-heading text-brand-600"></i> Contoh: <span class="text-brand-700 font-bold">"Peta Provinsi Jawa Tengah"</span>
                        </div>
                    </div>

                    <!-- B. Skala -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-teal-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">B. Skala Peta</h4>
                            <span class="text-xs bg-teal-100 text-teal-800 font-bold px-2.5 py-1 rounded-full">Komponen 2</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Skala menunjukkan <strong>perbandingan jarak pada peta</strong> dengan jarak sebenarnya di permukaan bumi.
                        </p>
                        <div class="bg-slate-50 p-3 rounded-xl text-xs font-semibold text-slate-700 border border-slate-200 space-y-1">
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-ruler-horizontal text-teal-600"></i> Contoh: <span class="text-teal-700 font-bold">Skala 1 : 100.000</span>
                            </div>
                            <p class="text-slate-500 font-normal">Artinya: 1 cm pada peta mewakili 100.000 cm (1 km) jarak sebenarnya.</p>
                        </div>
                    </div>

                    <!-- C. Legenda -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-amber-500">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">C. Legenda</h4>
                            <span class="text-xs bg-amber-100 text-amber-800 font-bold px-2.5 py-1 rounded-full">Komponen 3</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Legenda berisi <strong>keterangan mengenai arti dari simbol-simbol</strong> yang digunakan di dalam peta.
                        </p>
                        <div class="bg-slate-50 p-3 rounded-xl text-xs font-medium text-slate-700 border border-slate-200 grid grid-cols-2 gap-2">
                            <div><span class="font-bold text-red-600">●</span> = Kota/Ibukota</div>
                            <div><span class="font-bold text-slate-800">━</span> = Jalan Raya</div>
                            <div><span class="font-bold text-slate-900">■</span> = Bangunan</div>
                            <div><span class="font-bold text-sky-500">🌊</span> = Perairan / Laut</div>
                        </div>
                    </div>

                    <!-- D. Simbol -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-emerald-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">D. Simbol Peta</h4>
                            <span class="text-xs bg-emerald-100 text-emerald-800 font-bold px-2.5 py-1 rounded-full">Komponen 4</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Tanda atau gambar sederhana yang digunakan untuk <strong>mewakili objek/kenampakan sesungguhnya</strong> di lapangan (seperti gunung, sungai, kota).
                        </p>
                        <div class="bg-emerald-50/60 p-3 rounded-xl text-xs text-slate-700 border border-emerald-100 flex items-center justify-between">
                            <span>Tebak Simbol: ▲</span>
                            <span class="font-bold text-emerald-800">Jawaban: Gunung</span>
                        </div>
                    </div>

                    <!-- E. Arah Mata Angin -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-purple-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">E. Arah Mata Angin (Orientasi)</h4>
                            <span class="text-xs bg-purple-100 text-purple-800 font-bold px-2.5 py-1 rounded-full">Komponen 5</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Petunjuk arah untuk mengetahui arah posisi suatu lokasi pada peta. Terdiri dari 8 arah utama.
                        </p>
                        <div class="bg-slate-50 p-3 rounded-xl text-xs text-slate-700 border border-slate-200">
                            <strong>Utara, Timur, Selatan, Barat</strong> serta arah perantara (Timur Laut, Tenggara, Barat Daya, Barat Laut).
                        </div>
                    </div>

                    <!-- F. Garis Koordinat -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-indigo-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">F. Garis Koordinat (Astronomis)</h4>
                            <span class="text-xs bg-indigo-100 text-indigo-800 font-bold px-2.5 py-1 rounded-full">Komponen 6</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Garis khayal berupa <strong>garis lintang dan garis bujur</strong> yang membantu menentukan letak astronomis dan posisi tepat suatu wilayah.
                        </p>
                        <div class="bg-slate-50 p-3 rounded-xl text-xs font-semibold text-slate-700 border border-slate-200">
                            Contoh: Indonesia terletak di antara 6° LU - 11° LS dan 95° BT - 141° BT.
                        </div>
                    </div>

                    <!-- G. Garis Tepi -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-rose-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">G. Garis Tepi (Border)</h4>
                            <span class="text-xs bg-rose-100 text-rose-800 font-bold px-2.5 py-1 rounded-full">Komponen 7</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Garis yang <strong>membatasi area gambar peta</strong> agar rapi dan berada tepat di dalam bingkai gambar.
                        </p>
                    </div>

                    <!-- H. Inset -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-sky-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">H. Inset Peta</h4>
                            <span class="text-xs bg-sky-100 text-sky-800 font-bold px-2.5 py-1 rounded-full">Komponen 8</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            <strong>Peta kecil tambahan</strong> yang digunakan untuk memperjelas letak suatu wilayah dalam lingkup wilayah yang lebih luas.
                        </p>
                    </div>

                    <!-- I. Warna Peta -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-lime-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">I. Warna Peta</h4>
                            <span class="text-xs bg-lime-100 text-lime-800 font-bold px-2.5 py-1 rounded-full">Komponen 9</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Warna membedakan kenampakan alam:
                        </p>
                        <div class="grid grid-cols-2 gap-2 text-xs font-medium">
                            <div class="flex items-center gap-1.5"><span class="w-3 h-3 rounded bg-blue-500 inline-block"></span> Biru: Perairan</div>
                            <div class="flex items-center gap-1.5"><span class="w-3 h-3 rounded bg-emerald-500 inline-block"></span> Hijau: Dataran Rendah</div>
                            <div class="flex items-center gap-1.5"><span class="w-3 h-3 rounded bg-amber-400 inline-block"></span> Kuning: Dataran Tinggi</div>
                            <div class="flex items-center gap-1.5"><span class="w-3 h-3 rounded bg-amber-800 inline-block"></span> Cokelat: Pegunungan</div>
                        </div>
                    </div>

                    <!-- J. Sumber & Tahun Pembuatan -->
                    <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-3 border-l-4 border-l-cyan-600">
                        <div class="flex justify-between items-center">
                            <h4 class="font-extrabold text-lg text-slate-800">J. Sumber & Tahun Pembuatan</h4>
                            <span class="text-xs bg-cyan-100 text-cyan-800 font-bold px-2.5 py-1 rounded-full">Komponen 10</span>
                        </div>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            <strong>Sumber</strong> menunjukkan kelembagaan pembuat peta (misal: Badan Informasi Geospasial). <strong>Tahun pembuatan</strong> memastikan apakah peta masih akurat/baru.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= PAGE 3: EKSPLORASI PETA ================= -->
        <section id="page-eksplorasi" class="page-section hidden space-y-6 animate-fadeIn">
            <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                <div>
                    <span class="bg-brand-100 text-brand-800 text-xs px-3 py-1 rounded-full font-bold">FITUR INTERAKTIF</span>
                    <h2 class="text-2xl font-extrabold text-slate-800 mt-1">🗺️ Eksplorasi Peta: Klik & Temukan!</h2>
                    <p class="text-sm text-slate-600">Klik tombol bernomor pada gambar peta di bawah ini untuk mempelajari pengertian & fungsinya.</p>
                </div>
                <div class="text-xs bg-slate-100 text-slate-700 px-3 py-2 rounded-xl border border-slate-200">
                    <i class="fa-solid fa-hand-pointer text-brand-600 mr-1"></i> Sentuh / Klik titik berpijar pada peta
                </div>
            </div>

            <div class="grid lg:grid-cols-12 gap-6 items-start">
                <!-- Interactive SVG Map Canvas -->
                <div class="lg:col-span-8 bg-white p-4 sm:p-6 rounded-3xl border border-slate-200 shadow-sm relative overflow-hidden">
                    <div class="relative w-full bg-sky-100 rounded-2xl border-4 border-slate-800 overflow-hidden shadow-inner">
                        
                        <!-- SVG Peta Interaktif -->
                        <svg viewBox="0 0 700 480" class="w-full h-auto select-none">
                            <!-- Garis Tepi (Border) -->
                            <rect x="2" y="2" width="696" height="476" fill="none" stroke="#1e293b" stroke-width="4"/>
                            <rect x="8" y="8" width="684" height="464" fill="#bae6fd" stroke="#0284c7" stroke-width="1"/>

                            <!-- Garis Koordinat Grid -->
                            <g stroke="#0284c7" stroke-dasharray="4,4" stroke-width="0.8" opacity="0.4">
                                <line x1="0" y1="120" x2="700" y2="120"/>
                                <line x1="0" y1="240" x2="700" y2="240"/>
                                <line x1="0" y1="360" x2="700" y2="360"/>
                                <line x1="175" y1="0" x2="175" y2="480"/>
                                <line x1="350" y1="0" x2="350" y2="480"/>
                                <line x1="525" y1="0" x2="525" y2="480"/>
                            </g>

                            <!-- Map Features: Islands (Warna Peta) -->
                            <!-- Island 1: Dataran Rendah & Tinggi -->
                            <path d="M 50,140 Q 120,80 280,130 T 420,200 T 300,320 T 100,280 Z" fill="#86efac" stroke="#15803d" stroke-width="2"/>
                            <!-- Island 2 -->
                            <path d="M 450,220 Q 560,180 640,250 T 580,380 T 420,330 Z" fill="#fef08a" stroke="#ca8a04" stroke-width="2"/>

                            <!-- Mountains (Simbol) -->
                            <polygon points="180,180 195,150 210,180" fill="#b45309" stroke="#78350f" stroke-width="1"/>
                            <polygon points="188,162 195,150 202,162" fill="#ffffff"/>

                            <polygon points="230,210 242,185 254,210" fill="#b45309" stroke="#78350f" stroke-width="1"/>
                            
                            <!-- Rivers (Simbol Line) -->
                            <path d="M 195,180 Q 220,220 260,230 T 320,250" fill="none" stroke="#0284c7" stroke-width="3.5" stroke-linecap="round"/>

                            <!-- Cities (Simbol Point) -->
                            <circle cx="280" cy="180" r="6" fill="#dc2626" stroke="#ffffff" stroke-width="1.5"/>
                            <circle cx="500" cy="280" r="5" fill="#0f172a" stroke="#ffffff" stroke-width="1"/>

                            <!-- Title Box -->
                            <g transform="translate(180, 20)">
                                <rect x="0" y="0" width="340" height="42" rx="8" fill="#ffffff" stroke="#0f172a" stroke-width="2" opacity="0.95"/>
                                <text x="170" y="26" text-anchor="middle" font-size="16" font-weight="800" fill="#0f172a">PETA PROVINSI NUSANTARA HIJAU</text>
                            </g>

                            <!-- Inset Box -->
                            <g transform="translate(20, 340)">
                                <rect x="0" y="0" width="130" height="95" rx="6" fill="#ffffff" stroke="#0f172a" stroke-width="1.5"/>
                                <rect x="5" y="5" width="120" height="85" fill="#e0f2fe"/>
                                <path d="M 15,40 Q 40,20 70,35 T 110,60" fill="none" stroke="#22c55e" stroke-width="4" opacity="0.8"/>
                                <rect x="35" y="25" width="30" height="25" fill="none" stroke="#dc2626" stroke-width="1.5" stroke-dasharray="2,2"/>
                                <text x="65" y="82" text-anchor="middle" font-size="9" font-weight="bold" fill="#0f172a">INSET PETA</text>
                            </g>

                            <!-- Compass Rose Box -->
                            <g transform="translate(580, 30)">
                                <circle cx="45" cy="45" r="35" fill="#ffffff" stroke="#0f172a" stroke-width="1.5" opacity="0.95"/>
                                <path d="M 45,15 L 52,45 L 45,40 L 38,45 Z" fill="#dc2626"/>
                                <path d="M 45,75 L 52,45 L 45,50 L 38,45 Z" fill="#64748b"/>
                                <text x="45" y="12" text-anchor="middle" font-size="11" font-weight="bold" fill="#0f172a">U</text>
                                <text x="82" y="49" text-anchor="middle" font-size="9" font-weight="bold" fill="#0f172a">T</text>
                                <text x="45" y="87" text-anchor="middle" font-size="9" font-weight="bold" fill="#0f172a">S</text>
                                <text x="9" y="49" text-anchor="middle" font-size="9" font-weight="bold" fill="#0f172a">B</text>
                            </g>

                            <!-- Legend Box -->
                            <g transform="translate(520, 330)">
                                <rect x="0" y="0" width="155" height="110" rx="6" fill="#ffffff" stroke="#0f172a" stroke-width="1.5"/>
                                <text x="12" y="18" font-size="11" font-weight="bold" fill="#0f172a">LEGENDA:</text>
                                <polygon points="20,32 26,22 32,32" fill="#b45309"/>
                                <text x="40" y="30" font-size="10" fill="#334155">Gunung</text>
                                <circle cx="26" cy="45" r="4" fill="#dc2626"/>
                                <text x="40" y="48" font-size="10" fill="#334155">Ibukota</text>
                                <line x1="18" y1="62" x2="34" y2="62" stroke="#0284c7" stroke-width="3"/>
                                <text x="40" y="65" font-size="10" fill="#334155">Sungai</text>
                                <rect x="20" y="76" width="12" height="12" fill="#86efac" stroke="#15803d"/>
                                <text x="40" y="86" font-size="10" fill="#334155">Dataran Rendah</text>
                            </g>

                            <!-- Scale Text -->
                            <g transform="translate(200, 425)">
                                <rect x="0" y="0" width="180" height="26" rx="4" fill="#ffffff" stroke="#0f172a" stroke-width="1"/>
                                <text x="90" y="17" text-anchor="middle" font-size="10" font-weight="bold" fill="#0f172a">Skala 1 : 1.000.000</text>
                            </g>

                            <!-- Source Text -->
                            <text x="200" y="462" font-size="9" font-weight="semibold" fill="#334155">Sumber: BIG (Badan Informasi Geospasial) - 2024</text>
                        </svg>

                        <!-- CLICKABLE HOTSPOTS OVERLAY -->
                        <!-- 1. Judul Hotspot -->
                        <button onclick="showComponentDetail('judul')" class="absolute top-[5%] left-[28%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            1
                        </button>

                        <!-- 2. Skala Hotspot -->
                        <button onclick="showComponentDetail('skala')" class="absolute bottom-[9%] left-[30%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            2
                        </button>

                        <!-- 3. Legenda Hotspot -->
                        <button onclick="showComponentDetail('legenda')" class="absolute bottom-[18%] right-[8%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            3
                        </button>

                        <!-- 4. Simbol Hotspot -->
                        <button onclick="showComponentDetail('simbol')" class="absolute top-[35%] left-[27%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            4
                        </button>

                        <!-- 5. Arah Mata Angin Hotspot -->
                        <button onclick="showComponentDetail('orientasi')" class="absolute top-[8%] right-[8%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            5
                        </button>

                        <!-- 6. Inset Hotspot -->
                        <button onclick="showComponentDetail('inset')" class="absolute bottom-[10%] left-[6%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            6
                        </button>

                        <!-- 7. Garis Tepi Hotspot -->
                        <button onclick="showComponentDetail('garis-tepi')" class="absolute top-[2%] left-[2%] w-10 h-10 rounded-full bg-red-500 text-white font-black text-sm border-2 border-white shadow-lg pulsing-spot flex items-center justify-center hover:scale-110 transition">
                            7
                        </button>
                    </div>
                </div>

                <!-- Info Panel Card -->
                <div class="lg:col-span-4 bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-4 sticky top-20" id="eksplorasi-info-card">
                    <div class="flex items-center gap-3 border-b border-slate-100 pb-4">
                        <div class="w-10 h-10 rounded-2xl bg-brand-600 text-white flex items-center justify-center font-extrabold text-lg" id="info-number">
                            ?
                        </div>
                        <div>
                            <h3 class="font-bold text-lg text-slate-800" id="info-title">Pilih Komponen Peta</h3>
                            <p class="text-xs text-slate-500">Klik tombol nomor pada gambar peta</p>
                        </div>
                    </div>

                    <div class="space-y-3 text-sm text-slate-600 leading-relaxed" id="info-body">
                        <p class="text-slate-500 italic">
                            Sentuh atau klik angka berpijar (1-7) pada bidang peta di samping untuk memunculkan penjelasan lengkap mengenai komponen tersebut!
                        </p>
                    </div>

                    <div id="info-example" class="hidden p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-xs font-medium text-slate-700">
                        <!-- Dynamic example will appear here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= PAGE 4: MINI GAMES / TANTANGAN ================= -->
        <section id="page-tantangan" class="page-section hidden space-y-6 animate-fadeIn">
            <div class="bg-gradient-to-r from-amber-500 to-orange-600 text-white p-6 sm:p-8 rounded-3xl shadow-sm flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4">
                <div>
                    <span class="bg-white/20 text-white text-xs px-3 py-1 rounded-full font-bold">MODE MAIN SAMBIL BELAJAR</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold mt-1">🎮 Tantangan & Mini Games Peta</h2>
                    <p class="text-sm text-amber-100 mt-1">Asah pemahamanmu lewat permainan seru sebelum masuk ke Latihan Soal!</p>
                </div>
            </div>

            <!-- Mini Game Selection Tabs -->
            <div class="grid md:grid-cols-3 gap-6">
                <!-- Game 1: Tebak Simbol -->
                <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-4 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-sky-100 text-sky-700 flex items-center justify-center text-2xl mb-3">
                            🧩
                        </div>
                        <h3 class="font-extrabold text-lg text-slate-800">Tebak Komponen Peta</h3>
                        <p class="text-xs text-slate-600 mt-1">Lihat potongan gambar/simbol dan tebak nama komponen yang tepat!</p>
                    </div>
                    <button onclick="startMiniGame('tebak')" class="w-full py-3 rounded-xl bg-sky-600 hover:bg-sky-700 text-white font-bold text-sm transition">
                        Mainkan Sekarang
                    </button>
                </div>

                <!-- Game 2: Benar atau Salah -->
                <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-4 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-emerald-100 text-emerald-700 flex items-center justify-center text-2xl mb-3">
                            ⚡
                        </div>
                        <h3 class="font-extrabold text-lg text-slate-800">Benar atau Salah?</h3>
                        <p class="text-xs text-slate-600 mt-1">Uji kecepatan pemahaman pernyataan seputar peta secara instan.</p>
                    </div>
                    <button onclick="startMiniGame('tf')" class="w-full py-3 rounded-xl bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-sm transition">
                        Mainkan Sekarang
                    </button>
                </div>

                <!-- Game 3: Tantangan Situasi -->
                <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm space-y-4 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-purple-100 text-purple-700 flex items-center justify-center text-2xl mb-3">
                            🧭
                        </div>
                        <h3 class="font-extrabold text-lg text-slate-800">Tantangan Situasi</h3>
                        <p class="text-xs text-slate-600 mt-1">Bantu karakter menyelesaikan masalah kehidupan nyata dengan peta!</p>
                    </div>
                    <button onclick="startMiniGame('situasi')" class="w-full py-3 rounded-xl bg-purple-600 hover:bg-purple-700 text-white font-bold text-sm transition">
                        Mainkan Sekarang
                    </button>
                </div>
            </div>

            <!-- Mini Game Container Window -->
            <div id="minigame-container" class="hidden bg-white p-6 sm:p-8 rounded-3xl border border-slate-200 shadow-md space-y-6">
                <!-- Mini Game Content inserted dynamically via JS -->
            </div>
        </section>

        <!-- ================= PAGE 5: LATIHAN SOAL ================= -->
        <section id="page-latihan" class="page-section hidden space-y-6 animate-fadeIn">
            <!-- Quiz Header Bar -->
            <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                <div>
                    <span class="bg-brand-100 text-brand-800 text-xs px-3 py-1 rounded-full font-bold">EVALUASI INTERAKTIF</span>
                    <h2 class="text-2xl font-extrabold text-slate-800 mt-1">✏️ Latihan Soal (15 Soal)</h2>
                    <p class="text-sm text-slate-600">Jawab pertanyaan berikut untuk mengukur pemahamanmu.</p>
                </div>

                <!-- Progress Bar & Indicator -->
                <div class="w-full md:w-64 space-y-1.5">
                    <div class="flex justify-between text-xs font-bold text-slate-700">
                        <span>Kemajuan Soal</span>
                        <span id="quiz-progress-text">Soal 1 dari 15</span>
                    </div>
                    <div class="w-full h-3 bg-slate-100 rounded-full overflow-hidden border border-slate-200">
                        <div id="quiz-progress-bar" class="h-full bg-gradient-to-r from-brand-500 to-teal-400 transition-all duration-300 w-[6.66%]"></div>
                    </div>
                </div>
            </div>

            <!-- Main Question Card Container -->
            <div class="bg-white p-6 sm:p-8 rounded-3xl border border-slate-200 shadow-sm space-y-6 max-w-4xl mx-auto">
                <!-- Question Badge & Difficulty -->
                <div class="flex justify-between items-center border-b border-slate-100 pb-4">
                    <div class="flex items-center gap-2">
                        <span id="question-number-badge" class="w-8 h-8 rounded-xl bg-brand-600 text-white font-extrabold text-sm flex items-center justify-center">1</span>
                        <span id="question-difficulty" class="text-xs px-3 py-1 rounded-full font-bold bg-emerald-100 text-emerald-800">
                            Tingkat: Mudah
                        </span>
                    </div>
                    <span id="question-type-badge" class="text-xs text-slate-500 font-semibold bg-slate-100 px-3 py-1 rounded-full">
                        Pilihan Ganda
                    </span>
                </div>

                <!-- Question Text -->
                <div id="question-text" class="text-lg sm:text-xl font-bold text-slate-800 leading-snug">
                    Bagian peta yang menunjukkan nama atau isi wilayah yang digambarkan disebut ....
                </div>

                <!-- Optional Question Visual / SVG / Box -->
                <div id="question-visual" class="hidden p-4 bg-slate-50 rounded-2xl border border-slate-200 text-center">
                    <!-- Visual contents loaded dynamically -->
                </div>

                <!-- Options List -->
                <div id="quiz-options-container" class="space-y-3 pt-2">
                    <!-- Dynamic option buttons inserted via JavaScript -->
                </div>

                <!-- Feedback Banner Box -->
                <div id="quiz-feedback-box" class="hidden p-4 rounded-2xl border transition-all animate-fadeIn">
                    <!-- Feedback contents inserted via JavaScript -->
                </div>

                <!-- Footer Navigation Buttons -->
                <div class="flex justify-between items-center pt-4 border-t border-slate-100">
                    <button onclick="prevQuestion()" id="quiz-prev-btn" class="px-5 py-2.5 rounded-xl border border-slate-300 text-slate-600 hover:bg-slate-100 font-bold text-sm transition disabled:opacity-40 disabled:cursor-not-allowed">
                        <i class="fa-solid fa-arrow-left mr-1"></i> Sebelum
                    </button>

                    <button onclick="nextQuestion()" id="quiz-next-btn" class="px-6 py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold text-sm transition shadow-md flex items-center gap-2">
                        <span>Selanjutnya</span> <i class="fa-solid fa-arrow-right"></i>
                    </button>
                </div>
            </div>
        </section>

        <!-- ================= PAGE 6: PEMBAHASAN ================= -->
        <section id="page-pembahasan" class="page-section hidden space-y-6 animate-fadeIn">
            <div class="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                <div>
                    <span class="bg-amber-100 text-amber-800 text-xs px-3 py-1 rounded-full font-bold">KUNCI & PENJELASAN</span>
                    <h2 class="text-2xl font-extrabold text-slate-800 mt-1">💡 Pembahasan Lengkap 15 Soal</h2>
                    <p class="text-sm text-slate-600">Pelajari pembahasan ilmiah dengan bahasa sederhana untuk memahami seluruh materi.</p>
                </div>
                <button onclick="navigateTo('latihan')" class="px-4 py-2 rounded-xl bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold text-xs transition flex items-center gap-2">
                    <i class="fa-solid fa-rotate-left"></i> Coba Latihan Lagi
                </button>
            </div>

            <!-- Explanations Accordion / List -->
            <div id="pembahasan-list" class="space-y-4 max-w-4xl mx-auto">
                <!-- Dynamically populated 15 discussions -->
            </div>
        </section>

        <!-- ================= PAGE 7: HASIL BELAJAR ================= -->
        <section id="page-hasil" class="page-section hidden space-y-8 animate-fadeIn max-w-4xl mx-auto">
            <!-- Results Card -->
            <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-lg text-center space-y-6 relative overflow-hidden">
                <div class="absolute -top-24 -right-24 w-64 h-64 bg-teal-100 rounded-full blur-3xl pointer-events-none"></div>
                <div class="absolute -bottom-24 -left-24 w-64 h-64 bg-sky-100 rounded-full blur-3xl pointer-events-none"></div>

                <div class="relative z-10 space-y-2">
                    <span class="text-xs font-bold text-brand-600 bg-brand-50 px-3 py-1.5 rounded-full border border-brand-100">
                        RAPORT HASIL BELAJAR MPI
                    </span>
                    <h2 class="text-3xl font-extrabold text-slate-800">⭐ HASIL EVALUASI PEMBELAJARAN</h2>
                    <p class="text-sm text-slate-500">Materi: Peta dan Komponen-Komponennya (Kelas V SD)</p>
                </div>

                <!-- Big Score Circle -->
                <div class="relative z-10 flex flex-col items-center justify-center my-4">
                    <div class="w-40 h-40 rounded-full bg-gradient-to-tr from-brand-600 to-teal-500 p-2 shadow-xl flex items-center justify-center">
                        <div class="w-full h-full rounded-full bg-white flex flex-col items-center justify-center">
                            <span id="result-score-number" class="text-5xl font-black text-brand-700">0</span>
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-widest mt-1">NILAI AKHIR</span>
                        </div>
                    </div>
                    
                    <div id="result-category-badge" class="mt-4 px-4 py-1.5 rounded-full text-sm font-extrabold bg-emerald-100 text-emerald-800 shadow-sm">
                        Kategori: Sangat Baik
                    </div>
                </div>

                <!-- Stats Breakdown Grid -->
                <div class="relative z-10 grid grid-cols-3 gap-4 max-w-lg mx-auto bg-slate-50 p-4 rounded-2xl border border-slate-200">
                    <div class="p-2">
                        <div class="text-xs text-slate-500 font-semibold">Total Soal</div>
                        <div class="text-xl font-bold text-slate-800" id="result-total-questions">15</div>
                    </div>
                    <div class="p-2 border-x border-slate-200">
                        <div class="text-xs text-slate-500 font-semibold">Jawaban Benar</div>
                        <div class="text-xl font-bold text-emerald-600" id="result-correct-count">0</div>
                    </div>
                    <div class="p-2">
                        <div class="text-xs text-slate-500 font-semibold">Jawaban Salah</div>
                        <div class="text-xl font-bold text-rose-600" id="result-wrong-count">0</div>
                    </div>
                </div>

                <!-- Feedback Message Box -->
                <div id="result-feedback-msg" class="relative z-10 p-5 rounded-2xl bg-sky-50 border border-sky-200 text-slate-800 text-sm font-medium leading-relaxed max-w-xl mx-auto">
                    Pesan evaluasi otomatis akan muncul di sini sesuai dengan perolehan nilai siswa.
                </div>

                <!-- Action Buttons -->
                <div class="relative z-10 flex flex-wrap justify-center gap-3 pt-4">
                    <button onclick="resetAndRepeatQuiz()" class="px-6 py-3 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold text-sm transition shadow-md flex items-center gap-2">
                        <i class="fa-solid fa-rotate-right"></i> 🔄 ULANGI LATIHAN
                    </button>
                    <button onclick="navigateTo('materi')" class="px-6 py-3 rounded-xl bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold text-sm transition flex items-center gap-2">
                        <i class="fa-solid fa-book-open"></i> 📚 KEMBALI KE MATERI
                    </button>
                    <button onclick="navigateTo('beranda')" class="px-6 py-3 rounded-xl bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold text-sm transition flex items-center gap-2">
                        <i class="fa-solid fa-house"></i> 🏠 BERANDA
                    </button>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-white border-t border-slate-200 py-6 mt-12 text-center text-xs text-slate-500">
        <div class="max-w-7xl mx-auto px-4">
            <p class="font-semibold text-slate-700">Media Pembelajaran Interaktif (MPI) - Peta dan Komponen-Komponennya</p>
            <p class="mt-1 text-slate-400">Dirancang khusus untuk Pembelajaran IPS Kelas V Sekolah Dasar • Berbasis Kurikulum Merdeka</p>
        </div>
    </footer>

    <!-- MODAL: PETUNJUK PENGGUNAAN -->
    <div id="modal-petunjuk" class="fixed inset-0 z-50 bg-slate-900/60 backdrop-blur-sm flex items-center justify-center p-4 hidden animate-fadeIn">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 space-y-5 shadow-2xl relative">
            <button onclick="closeModal('modal-petunjuk')" class="absolute top-4 right-4 w-9 h-9 rounded-full bg-slate-100 text-slate-500 hover:text-slate-800 flex items-center justify-center transition">
                <i class="fa-solid fa-xmark"></i>
            </button>

            <div class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-2xl bg-brand-100 text-brand-700 flex items-center justify-center text-xl font-bold">
                    💡
                </div>
                <div>
                    <h3 class="text-xl font-extrabold text-slate-800">Petunjuk Penggunaan MPI</h3>
                    <p class="text-xs text-slate-500">Panduan mudah belajar untuk siswa Kelas V</p>
                </div>
            </div>

            <ol class="space-y-3 text-sm text-slate-700 list-decimal list-inside leading-relaxed">
                <li class="p-2.5 rounded-xl bg-slate-50 border border-slate-100">
                    <strong>Membaca Materi:</strong> Pilih menu 📚 <strong>MATERI</strong> untuk mempelajari pengertian peta, fungsi, dan 10 komponen dasarnya.
                </li>
                <li class="p-2.5 rounded-xl bg-slate-50 border border-slate-100">
                    <strong>Eksplorasi Interaktif:</strong> Buka menu 🗺️ <strong>EKSPLORASI PETA</strong> dan klik tombol angka di peta untuk menemukan lokasi tiap komponen.
                </li>
                <li class="p-2.5 rounded-xl bg-slate-50 border border-slate-100">
                    <strong>Mengerjakan Latihan:</strong> Klik ✏️️ <strong>LATIHAN SOAL</strong> untuk menjawab 15 pertanyaan interaktif. Jawaban akan langsung diperiksa secara otomatis!
                </li>
                <li class="p-2.5 rounded-xl bg-slate-50 border border-slate-100">
                    <strong>Lihat Pembahasan & Nilai:</strong> Buka 💡 <strong>PEMBAHASAN</strong> untuk mempelajari kunci jawaban dan cek skor akhirmu di ⭐ <strong>HASIL BELAJAR</strong>.
                </li>
            </ol>

            <button onclick="closeModal('modal-petunjuk')" class="w-full py-3 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold text-sm transition shadow-md">
                Saya Mengerti, Ayo Mulai!
            </button>
        </div>
    </div>

    <script>
        /* ==========================================================================
           STATE & DATA STORAGE
           ========================================================================== */
        let soundEnabled = true;
        let currentQuestionIndex = 0;
        let userAnswers = new Array(15).fill(null);

        // Web Audio Synthesizer for Interactive Sound Effects
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        
        function playSound(type) {
            if (!soundEnabled) return;
            try {
                if (audioCtx.state === 'suspended') {
                    audioCtx.resume();
                }
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.connect(gain);
                gain.connect(audioCtx.destination);

                if (type === 'click') {
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(600, audioCtx.currentTime);
                    osc.frequency.exponentialRampToValueAtTime(800, audioCtx.currentTime + 0.08);
                    gain.gain.setValueAtTime(0.15, audioCtx.currentTime);
                    gain.gain.linearRampToValueAtTime(0.01, audioCtx.currentTime + 0.08);
                    osc.start();
                    osc.stop(audioCtx.currentTime + 0.08);
                } else if (type === 'correct') {
                    osc.type = 'triangle';
                    osc.frequency.setValueAtTime(523.25, audioCtx.currentTime); // C5
                    osc.frequency.setValueAtTime(659.25, audioCtx.currentTime + 0.1); // E5
                    osc.frequency.setValueAtTime(783.99, audioCtx.currentTime + 0.2); // G5
                    gain.gain.setValueAtTime(0.2, audioCtx.currentTime);
                    gain.gain.linearRampToValueAtTime(0.01, audioCtx.currentTime + 0.35);
                    osc.start();
                    osc.stop(audioCtx.currentTime + 0.35);
                } else if (type === 'wrong') {
                    osc.type = 'sawtooth';
                    osc.frequency.setValueAtTime(250, audioCtx.currentTime);
                    osc.frequency.setValueAtTime(180, audioCtx.currentTime + 0.15);
                    gain.gain.setValueAtTime(0.2, audioCtx.currentTime);
                    gain.gain.linearRampToValueAtTime(0.01, audioCtx.currentTime + 0.3);
                    osc.start();
                    osc.stop(audioCtx.currentTime + 0.3);
                }
            } catch(e) {
                console.log("Audio play error:", e);
            }
        }

        function toggleSound() {
            soundEnabled = !soundEnabled;
            const btn = document.getElementById('sound-btn');
            if (soundEnabled) {
                btn.innerHTML = `<i class="fa-solid fa-volume-high text-sm"></i>`;
                btn.classList.remove('text-rose-500');
                playSound('click');
            } else {
                btn.innerHTML = `<i class="fa-solid fa-volume-xmark text-sm"></i>`;
                btn.classList.add('text-rose-500');
            }
        }

        /* ==========================================================================
           NAVIGATION CONTROL
           ========================================================================== */
        function navigateTo(pageId) {
            playSound('click');
            // Hide all pages
            document.querySelectorAll('.page-section').forEach(sec => sec.classList.add('hidden'));
            
            // Show selected page
            const target = document.getElementById('page-' + pageId);
            if (target) {
                target.classList.remove('hidden');
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }

            // Update nav button highlights
            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.classList.remove('text-brand-700', 'bg-white', 'shadow-xs', 'font-semibold');
                btn.classList.add('text-slate-600');
            });
            const activeNavBtn = document.getElementById('nav-' + pageId);
            if (activeNavBtn) {
                activeNavBtn.classList.remove('text-slate-600');
                activeNavBtn.classList.add('text-brand-700', 'bg-white', 'shadow-xs', 'font-semibold');
            }

            // Close mobile nav if open
            document.getElementById('mobile-menu').classList.add('hidden');

            // Render page specific data
            if (pageId === 'latihan') {
                renderQuestion();
            } else if (pageId === 'pembahasan') {
                renderPembahasanList();
            } else if (pageId === 'hasil') {
                calculateAndRenderResults();
            }
        }

        function toggleMobileNav() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        function openModal(id) {
            playSound('click');
            document.getElementById(id).classList.remove('hidden');
        }

        function closeModal(id) {
            playSound('click');
            document.getElementById(id).classList.add('hidden');
        }

        function switchMateriTab(tab) {
            playSound('click');
            if (tab === 'pengertian') {
                document.getElementById('materi-sub-pengertian').classList.remove('hidden');
                document.getElementById('materi-sub-komponen').classList.add('hidden');
                document.getElementById('tab-pengertian').className = "materi-tab-btn px-4 py-2 rounded-lg text-xs font-bold transition bg-white text-brand-900 shadow-sm";
                document.getElementById('tab-komponen').className = "materi-tab-btn px-4 py-2 rounded-lg text-xs font-bold transition text-white hover:bg-white/10";
            } else {
                document.getElementById('materi-sub-pengertian').classList.add('hidden');
                document.getElementById('materi-sub-komponen').classList.remove('hidden');
                document.getElementById('tab-komponen').className = "materi-tab-btn px-4 py-2 rounded-lg text-xs font-bold transition bg-white text-brand-900 shadow-sm";
                document.getElementById('tab-pengertian').className = "materi-tab-btn px-4 py-2 rounded-lg text-xs font-bold transition text-white hover:bg-white/10";
            }
        }

        /* ==========================================================================
           EKSPLORASI PETA INTERACTIVE DATA
           ========================================================================== */
        const mapComponentsData = {
            'judul': {
                number: 1,
                title: "Judul Peta",
                desc: "Judul peta menunjukkan isi atau wilayah yang digambarkan di dalam peta. Judul diletakkan di bagian atas agar pembaca langsung tahu wilayah mana yang dipelajari.",
                function: "Memberikan informasi awal mengenai isi dan nama daerah pada peta.",
                example: "📌 Contoh: 'PETA PROVINSI JAWA TENGAH' atau 'PETA PULAU NUSANTARA HIJAU'."
            },
            'skala': {
                number: 2,
                title: "Skala Peta",
                desc: "Skala menunjukkan perbandingan antara jarak pada bidang peta dengan jarak yang sebenarnya di permukaan bumi.",
                function: "Membantu memperkirakan jarak sungguhan antarlokasi di lapangan.",
                example: "📏 Contoh: Skala 1 : 1.000.000 (artinya 1 cm pada peta sama dengan 1.000.000 cm / 10 km jarak asli)."
            },
            'legenda': {
                number: 3,
                title: "Legenda Peta",
                desc: "Legenda adalah kotak keterangan yang memuat penjelasan mengenai arti dari semua simbol yang tercantum dalam peta.",
                function: "Memudahkan pembaca memahami arti gambar atau simbol khusus di peta.",
                example: "📑 Contoh: Penjelasan bahwa garis biru adalah sungai, dan segitiga cokelat adalah gunung."
            },
            'simbol': {
                number: 4,
                title: "Simbol Peta",
                desc: "Simbol adalah gambar sederhana atau tanda khusus untuk mewakili kenampakan sesungguhnya di permukaan bumi.",
                function: "Mewakili objek alam maupun buatan manusia agar peta tidak terlalu penuh teks.",
                example: "▲ = Gunung, ● = Kota/Ibukota, 〰️ = Sungai."
            },
            'orientasi': {
                number: 5,
                title: "Arah Mata Angin (Orientasi)",
                desc: "Simbol petunjuk arah yang menunjukkan posisi Utara, Timur, Selatan, dan Barat.",
                function: "Menentukan arah dan navigasi suatu tempat agar pembaca tidak salah arah.",
                example: "🧭 Contoh: Panah menunjuk ke arah atas mewakili arah Utara (U)."
            },
            'inset': {
                number: 6,
                title: "Inset Peta",
                desc: "Inset adalah peta kecil tambahan yang disisipkan untuk memperjelas posisi suatu wilayah terhadap daerah sekitarnya yang lebih luas.",
                function: "Menjelaskan kedudukan wilayah peta utama dalam cakupan yang lebih besar.",
                example: "🗺️ Contoh: Peta kecil Indonesia di sudut peta Provinsi Jawa Tengah."
            },
            'garis-tepi': {
                number: 7,
                title: "Garis Tepi (Border)",
                desc: "Garis yang mengelilingi dan membatasi seluruh bidang gambar peta.",
                function: "Merapikan tampilan peta dan memastikan gambar peta berada tepat di dalam bingkai.",
                example: "🖼️ Contoh: Garis kotak ganda di sekeliling pinggir peta."
            }
        };

        function showComponentDetail(key) {
            playSound('click');
            const item = mapComponentsData[key];
            if (!item) return;

            document.getElementById('info-number').innerText = item.number;
            document.getElementById('info-title').innerText = item.title;
            document.getElementById('info-body').innerHTML = `
                <p><strong>Pengertian:</strong> ${item.desc}</p>
                <p class="mt-2"><strong>Fungsi Utama:</strong> ${item.function}</p>
            `;
            
            const exBox = document.getElementById('info-example');
            exBox.classList.remove('hidden');
            exBox.innerHTML = item.example;
        }

        /* ==========================================================================
           MINI GAMES LOGIC
           ========================================================================== */
        function startMiniGame(type) {
            playSound('click');
            const box = document.getElementById('minigame-container');
            box.classList.remove('hidden');

            if (type === 'tebak') {
                box.innerHTML = `
                    <div class="space-y-4">
                        <div class="flex justify-between items-center border-b pb-3">
                            <h3 class="font-bold text-lg text-sky-800">🧩 Tebak Komponen Peta</h3>
                            <span class="text-xs font-semibold bg-sky-100 text-sky-800 px-3 py-1 rounded-full">Mini Game 1</span>
                        </div>
                        <p class="text-sm text-slate-600">Perhatikan simbol berikut: <span class="text-3xl font-bold text-amber-700 mx-2">▲</span></p>
                        <p class="text-sm font-semibold text-slate-800">Apakah arti dari simbol segitiga tersebut dalam peta?</p>
                        <div class="grid sm:grid-cols-2 gap-3 pt-2">
                            <button onclick="checkMiniGameAnswer(this, true, 'Hebat! Segitiga melambangkan Gunung.')" class="p-3 rounded-xl border border-slate-200 hover:bg-sky-50 text-left text-sm font-semibold transition">A. Gunung</button>
                            <button onclick="checkMiniGameAnswer(this, false, 'Kurang tepat. Coba lagi!')" class="p-3 rounded-xl border border-slate-200 hover:bg-sky-50 text-left text-sm font-semibold transition">B. Danau</button>
                            <button onclick="checkMiniGameAnswer(this, false, 'Kurang tepat. Coba lagi!')" class="p-3 rounded-xl border border-slate-200 hover:bg-sky-50 text-left text-sm font-semibold transition">C. Jalan Raya</button>
                            <button onclick="checkMiniGameAnswer(this, false, 'Kurang tepat. Coba lagi!')" class="p-3 rounded-xl border border-slate-200 hover:bg-sky-50 text-left text-sm font-semibold transition">D. Bandar Udara</button>
                        </div>
                        <div id="minigame-feedback" class="hidden p-3 rounded-xl text-xs font-bold"></div>
                    </div>
                `;
            } else if (type === 'tf') {
                box.innerHTML = `
                    <div class="space-y-4">
                        <div class="flex justify-between items-center border-b pb-3">
                            <h3 class="font-bold text-lg text-emerald-800">⚡ Benar atau Salah?</h3>
                            <span class="text-xs font-semibold bg-emerald-100 text-emerald-800 px-3 py-1 rounded-full">Mini Game 2</span>
                        </div>
                        <p class="text-base font-bold text-slate-800">"Legenda digunakan untuk menjelaskan arti dari simbol-simbol yang ada pada peta."</p>
                        <div class="flex gap-4 pt-2">
                            <button onclick="checkMiniGameAnswer(this, true, 'Tepat Sekali! Legenda adalah kunci penjelas simbol.')" class="flex-1 py-3 rounded-xl bg-emerald-600 text-white font-bold text-sm hover:bg-emerald-700 transition">BENAR</button>
                            <button onclick="checkMiniGameAnswer(this, false, 'Salah. Pernyataan di atas sebenarnya BENAR!')" class="flex-1 py-3 rounded-xl bg-rose-600 text-white font-bold text-sm hover:bg-rose-700 transition">SALAH</button>
                        </div>
                        <div id="minigame-feedback" class="hidden p-3 rounded-xl text-xs font-bold"></div>
                    </div>
                `;
            } else if (type === 'situasi') {
                box.innerHTML = `
                    <div class="space-y-4">
                        <div class="flex justify-between items-center border-b pb-3">
                            <h3 class="font-bold text-lg text-purple-800">🧭 Tantangan Peta Situasional</h3>
                            <span class="text-xs font-semibold bg-purple-100 text-purple-800 px-3 py-1 rounded-full">Mini Game 3</span>
                        </div>
                        <div class="p-4 rounded-2xl bg-purple-50 text-slate-800 text-sm leading-relaxed border border-purple-100">
                            "Rina dan kelompoknya ingin pergi berkemah dari sekolah menuju bukit. Supaya tidak tersesat di perjalanan, Rina ingin memastikan arah mata angin yang benar."
                        </div>
                        <p class="text-sm font-bold text-slate-800">Komponen peta apa yang paling dibutuhkan Rina?</p>
                        <div class="grid sm:grid-cols-2 gap-3">
                            <button onclick="checkMiniGameAnswer(this, false, 'Kurang tepat! Skala untuk menghitung jarak.')" class="p-3 rounded-xl border border-slate-200 hover:bg-purple-50 text-left text-sm font-semibold transition">Skala Peta</button>
                            <button onclick="checkMiniGameAnswer(this, true, 'Jawaban Benar! Orientasi / Arah mata angin membantu menentukan arah lokasi.')" class="p-3 rounded-xl border border-slate-200 hover:bg-purple-50 text-left text-sm font-semibold transition">Arah Mata Angin (Orientasi)</button>
                        </div>
                        <div id="minigame-feedback" class="hidden p-3 rounded-xl text-xs font-bold"></div>
                    </div>
                `;
            }
        }

        function checkMiniGameAnswer(btn, isCorrect, message) {
            const fb = document.getElementById('minigame-feedback');
            fb.classList.remove('hidden', 'bg-emerald-100', 'text-emerald-800', 'bg-rose-100', 'text-rose-800');
            if (isCorrect) {
                playSound('correct');
                fb.classList.add('bg-emerald-100', 'text-emerald-800');
                fb.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i> 🎉 ${message}`;
            } else {
                playSound('wrong');
                fb.classList.add('bg-rose-100', 'text-rose-800');
                fb.innerHTML = `<i class="fa-solid fa-circle-xmark mr-1"></i> 💡 ${message}`;
            }
        }

        /* ==========================================================================
           15 INTERACTIVE QUIZ QUESTIONS DATABASE
           ========================================================================== */
        const questionsDB = [
            {
                id: 1,
                type: "Pilihan Ganda",
                difficulty: "Easy",
                difficultyLabel: "Mudah",
                question: "Bagian peta yang menunjukkan nama atau isi wilayah yang digambarkan disebut ....",
                options: ["A. Legenda", "B. Judul peta", "C. Skala", "D. Inset"],
                correctIndex: 1,
                explanation: "Judul peta menunjukkan isi atau wilayah yang digambarkan pada peta. Oleh karena itu, bagian yang menunjukkan nama wilayah disebut judul peta."
            },
            {
                id: 2,
                type: "Pilihan Ganda",
                difficulty: "Easy",
                difficultyLabel: "Mudah",
                question: "Jika pada peta terdapat simbol garis yang mewakili jalan, keterangan mengenai arti dari simbol tersebut dapat ditemukan pada ....",
                options: ["A. Judul", "B. Legenda", "C. Skala", "D. Garis tepi"],
                correctIndex: 1,
                explanation: "Legenda adalah tempat atau kotak keterangan yang memuat arti seluruh simbol yang ada pada peta."
            },
            {
                id: 3,
                type: "Pilihan Ganda",
                difficulty: "Easy",
                difficultyLabel: "Mudah",
                question: "Skala pada peta berfungsi untuk ....",
                options: [
                    "A. menunjukkan arah",
                    "B. menjelaskan simbol",
                    "C. menunjukkan perbandingan jarak pada peta dengan jarak sebenarnya",
                    "D. menunjukkan nama wilayah"
                ],
                correctIndex: 2,
                explanation: "Skala adalah angka perbandingan antara jarak di dalam bidang peta dengan jarak asli sesungguhnya di lapangan."
            },
            {
                id: 4,
                type: "Pilihan Ganda",
                difficulty: "Easy",
                difficultyLabel: "Mudah",
                question: "Simbol berwarna biru pada peta biasanya menggambarkan kenampakan alam berupa ....",
                options: ["A. Dataran tinggi", "B. Hutan lebat", "C. Perairan (Sungai, Danau, Laut)", "D. Jalan raya"],
                correctIndex: 2,
                explanation: "Warna biru secara umum pada peta digunakan khusus untuk melambangkan wilayah perairan seperti sungai, danau, dan laut."
            },
            {
                id: 5,
                type: "Pilihan Ganda",
                difficulty: "Easy",
                difficultyLabel: "Mudah",
                question: "Komponen peta yang berguna untuk petunjuk arah posisi lokasi (Utara, Timur, Selatan, Barat) dinamakan ....",
                options: ["A. Orientasi / Arah mata angin", "B. Inset", "C. Skala", "D. Garis koordinat"],
                correctIndex: 0,
                explanation: "Orientasi atau panah arah mata angin berfungsi membantu pengguna mengetahui petunjuk arah suatu tempat pada peta."
            },
            {
                id: 6,
                type: "Benar / Salah",
                difficulty: "Medium",
                difficultyLabel: "Sedang",
                question: "[Benar / Salah] Legenda adalah peta kecil yang digunakan untuk menunjukkan lokasi suatu wilayah dalam wilayah yang lebih luas.",
                options: ["A. BENAR", "B. SALAH"],
                correctIndex: 1,
                explanation: "SALAH. Peta kecil yang menunjukkan lokasi wilayah dalam lingkup yang lebih luas disebut INSET, sedangkan legenda adalah kotak keterangan simbol."
            },
            {
                id: 7,
                type: "Penerapan",
                difficulty: "Medium",
                difficultyLabel: "Sedang",
                question: "Sebuah peta memiliki Skala 1 : 100.000. Jika jarak Kota A ke Kota B pada peta adalah 2 cm, berapakah jarak sebenarnya di lapangan?",
                options: ["A. 200 meter", "B. 2 kilometer", "C. 20 kilometer", "D. 200 kilometer"],
                correctIndex: 1,
                explanation: "Skala 1 : 100.000 artinya 1 cm = 100.000 cm (1 km). Jika jarak peta 2 cm, maka jarak sebenarnya = 2 × 1 km = 2 km."
            },
            {
                id: 8,
                type: "Pilihan Ganda",
                difficulty: "Medium",
                difficultyLabel: "Sedang",
                question: "Peta kecil di sudut peta yang berfungsi memperjelas letak suatu wilayah terhadap daerah sekitarnya dinamakan ....",
                options: ["A. Inset", "B. Garis Astronomis", "C. Legenda", "D. Simbol"],
                correctIndex: 0,
                explanation: "Inset adalah peta kecil tambahan yang diletakkan di sudut peta utama untuk memperjelas konteks lokasi."
            },
            {
                id: 9,
                type: "Pilihan Ganda",
                difficulty: "Medium",
                difficultyLabel: "Sedang",
                question: "Garis khayal pada peta yang terdiri dari garis lintang dan garis bujur disebut ....",
                options: ["A. Garis tepi", "B. Garis skala", "C. Garis koordinat (astronomis)", "D. Garis legenda"],
                correctIndex: 2,
                explanation: "Garis koordinat terdiri dari garis horizontal (lintang) dan vertikal (bujur) untuk menentukan posisi pasti suatu lokasi di bumi."
            },
            {
                id: 10,
                type: "Identifikasi Gambar",
                difficulty: "Medium",
                difficultyLabel: "Sedang",
                question: "Garis ganda yang mengelilingi dan membatasi seluruh bidang gambar peta agar rapi disebut ....",
                options: ["A. Garis Tepi (Border)", "B. Garis Koordinat", "C. Garis Katulistiwa", "D. Garis Skala"],
                correctIndex: 0,
                explanation: "Garis tepi merupakan bingkai pembatas wilayah peta."
            },
            {
                id: 11,
                type: "Tantangan Situasi",
                difficulty: "Hard",
                difficultyLabel: "Menantang",
                question: "Rina ingin mencari letak Kota Bandung pada peta Provinsi Jawa Barat. Komponen peta apa yang pertama kali ia periksa untuk memastikan peta tersebut benar-benar peta Jawa Barat?",
                options: ["A. Legenda", "B. Judul Peta", "C. Sumber Peta", "D. Inset"],
                correctIndex: 1,
                explanation: "Judul peta memberikan informasi awal mengenai isi wilayah. Rina harus melihat Judul Peta terlebih dahulu."
            },
            {
                id: 12,
                type: "Benar / Salah",
                difficulty: "Hard",
                difficultyLabel: "Menantang",
                question: "[Benar / Salah] Garis Koordinat pada peta berguna untuk menentukan letak astronomis dan pembagian zona waktu suatu wilayah.",
                options: ["A. BENAR", "B. SALAH"],
                correctIndex: 0,
                explanation: "BENAR. Garis bujur menentukan pembagian waktu, dan gabungan garis lintang-bujur menentukan letak astronomis."
            },
            {
                id: 13,
                type: "Tantangan Situasi",
                difficulty: "Hard",
                difficultyLabel: "Menantang",
                question: "Pak Budi hendak merencanakan perjalanan jalan darat dari Jakarta ke Surabaya. Ia ingin tahu arah perjalanan dan estimasi jarak lintasannya. Dua komponen utama yang paling dibutuhkan Pak Budi adalah ....",
                options: [
                    "A. Garis tepi dan Warna peta",
                    "B. Arah mata angin dan Skala peta",
                    "C. Inset dan Tahun pembuatan",
                    "D. Legenda dan Sumber peta"
                ],
                correctIndex: 1,
                explanation: "Arah mata angin memberikan petunjuk navigasi arah, sedangkan Skala peta digunakan untuk menghitung estimasi jarak sebenarnya."
            },
            {
                id: 14,
                type: "Pilihan Ganda",
                difficulty: "Hard",
                difficultyLabel: "Menantang",
                question: "Mengapa pada sebuah peta wajib dicantumkan Sumber dan Tahun Pembuatan?",
                options: [
                    "A. Supaya peta terlihat lebih berwarna",
                    "B. Untuk memberikan kepastian keakuratan serta keaktualan data peta",
                    "C. Untuk menggantikan fungsi legenda",
                    "D. Agar peta dapat diperbesar"
                ],
                correctIndex: 1,
                explanation: "Tahun pembuatan dan sumber penting untuk memastikan informasi peta masih baru, akurat, dan dapat dipercaya."
            },
            {
                id: 15,
                type: "Pilihan Ganda",
                difficulty: "Hard",
                difficultyLabel: "Menantang",
                question: "Perhatikan simbol warna pada peta: Wilayah yang diberi warna HIJAU pada peta menggambarkan daerah ....",
                options: ["A. Lautan dalam", "B. Pegunungan tinggi", "C. Dataran rendah", "D. Puncak gunung berapi"],
                correctIndex: 2,
                explanation: "Pada peta umum, warna hijau digunakan untuk melambangkan daerah dataran rendah (ketinggian 0–200 meter dpl)."
            }
        ];

        /* ==========================================================================
           QUIZ ENGINE LOGIC
           ========================================================================== */
        function renderQuestion() {
            const q = questionsDB[currentQuestionIndex];
            
            // Progress Bar
            const percent = ((currentQuestionIndex + 1) / questionsDB.length) * 100;
            document.getElementById('quiz-progress-bar').style.width = percent + '%';
            document.getElementById('quiz-progress-text').innerText = `Soal ${currentQuestionIndex + 1} dari ${questionsDB.length}`;

            // Badges & Details
            document.getElementById('question-number-badge').innerText = q.id;
            document.getElementById('question-type-badge').innerText = q.type;
            
            const diffEl = document.getElementById('question-difficulty');
            diffEl.innerText = 'Tingkat: ' + q.difficultyLabel;
            if (q.difficulty === 'Easy') {
                diffEl.className = 'text-xs px-3 py-1 rounded-full font-bold bg-emerald-100 text-emerald-800';
            } else if (q.difficulty === 'Medium') {
                diffEl.className = 'text-xs px-3 py-1 rounded-full font-bold bg-amber-100 text-amber-800';
            } else {
                diffEl.className = 'text-xs px-3 py-1 rounded-full font-bold bg-purple-100 text-purple-800';
            }

            // Question Text
            document.getElementById('question-text').innerText = q.question;

            // Render Options
            const container = document.getElementById('quiz-options-container');
            container.innerHTML = '';

            const selectedAns = userAnswers[currentQuestionIndex];

            q.options.forEach((opt, idx) => {
                const btn = document.createElement('button');
                btn.className = `w-full text-left p-4 rounded-2xl border font-semibold text-sm transition-all flex items-center justify-between `;
                
                if (selectedAns === idx) {
                    btn.classList.add('border-brand-600', 'bg-brand-50', 'text-brand-900', 'shadow-xs');
                } else {
                    btn.classList.add('border-slate-200', 'bg-white', 'hover:bg-slate-50', 'text-slate-700');
                }

                btn.innerHTML = `
                    <span>${opt}</span>
                    <span class="w-6 h-6 rounded-full border flex items-center justify-center text-xs ${selectedAns === idx ? 'border-brand-600 bg-brand-600 text-white' : 'border-slate-300'}">
                        ${selectedAns === idx ? '<i class="fa-solid fa-check"></i>' : ''}
                    </span>
                `;

                btn.onclick = () => selectOption(idx);
                container.appendChild(btn);
            });

            // Update Feedback Box
            const fbBox = document.getElementById('quiz-feedback-box');
            if (selectedAns !== null) {
                fbBox.classList.remove('hidden');
                if (selectedAns === q.correctIndex) {
                    fbBox.className = "p-4 rounded-2xl border bg-emerald-50 border-emerald-200 text-emerald-900 animate-fadeIn";
                    fbBox.innerHTML = `
                        <div class="font-extrabold text-sm flex items-center gap-2">
                            <span>🎉 BENAR!</span>
                        </div>
                        <p class="text-xs mt-1 text-emerald-800 font-medium">"Hebat! Jawabanmu tepat."</p>
                    `;
                } else {
                    fbBox.className = "p-4 rounded-2xl border bg-amber-50 border-amber-200 text-amber-900 animate-fadeIn";
                    fbBox.innerHTML = `
                        <div class="font-extrabold text-sm flex items-center gap-2">
                            <span>💡 BELUM TEPAT</span>
                        </div>
                        <p class="text-xs mt-1 text-amber-800 font-medium">"Coba perhatikan kembali fungsi komponen peta tersebut."</p>
                    `;
                }
            } else {
                fbBox.classList.add('hidden');
            }

            // Buttons State
            document.getElementById('quiz-prev-btn').disabled = (currentQuestionIndex === 0);
            
            const nextBtn = document.getElementById('quiz-next-btn');
            if (currentQuestionIndex === questionsDB.length - 1) {
                nextBtn.innerHTML = `<span>Lihat Hasil</span> <i class="fa-solid fa-trophy"></i>`;
                nextBtn.className = "px-6 py-2.5 rounded-xl bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-sm transition shadow-md flex items-center gap-2";
            } else {
                nextBtn.innerHTML = `<span>Selanjutnya</span> <i class="fa-solid fa-arrow-right"></i>`;
                nextBtn.className = "px-6 py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold text-sm transition shadow-md flex items-center gap-2";
            }
        }

        function selectOption(idx) {
            const q = questionsDB[currentQuestionIndex];
            userAnswers[currentQuestionIndex] = idx;
            
            if (idx === q.correctIndex) {
                playSound('correct');
            } else {
                playSound('wrong');
            }

            renderQuestion();
        }

        function nextQuestion() {
            playSound('click');
            if (currentQuestionIndex < questionsDB.length - 1) {
                currentQuestionIndex++;
                renderQuestion();
            } else {
                navigateTo('hasil');
            }
        }

        function prevQuestion() {
            playSound('click');
            if (currentQuestionIndex > 0) {
                currentQuestionIndex--;
                renderQuestion();
            }
        }

        /* ==========================================================================
           PEMBAHASAN & HASIL BELAJAR RENDERERS
           ========================================================================== */
        function renderPembahasanList() {
            const listContainer = document.getElementById('pembahasan-list');
            listContainer.innerHTML = '';

            questionsDB.forEach((q, idx) => {
                const isCorrect = (userAnswers[idx] === q.correctIndex);
                const userAnsText = userAnswers[idx] !== null ? q.options[userAnswers[idx]] : "Belum Dijawab";
                const correctOptText = q.options[q.correctIndex];

                const card = document.createElement('div');
                card.className = "bg-white p-5 rounded-2xl border border-slate-200 shadow-xs space-y-2";
                
                card.innerHTML = `
                    <div class="flex justify-between items-center border-b border-slate-100 pb-2">
                        <span class="font-extrabold text-sm text-slate-800">Nomor ${q.id}</span>
                        <span class="text-xs font-bold px-2.5 py-0.5 rounded-full ${userAnswers[idx] === null ? 'bg-slate-100 text-slate-600' : isCorrect ? 'bg-emerald-100 text-emerald-800' : 'bg-rose-100 text-rose-800'}">
                            ${userAnswers[idx] === null ? 'Belum Dijawab' : isCorrect ? 'Benar' : 'Salah'}
                        </span>
                    </div>
                    <p class="text-sm font-bold text-slate-800">${q.question}</p>
                    <div class="text-xs space-y-1 font-medium text-slate-700">
                        <p>Jawabanmu: <span class="${isCorrect ? 'text-emerald-700 font-bold' : 'text-rose-600 font-bold'}">${userAnsText}</span></p>
                        <p>Kunci Jawaban: <span class="text-brand-700 font-bold">${correctOptText}</span></p>
                    </div>
                    <div class="p-3 bg-slate-50 rounded-xl border border-slate-100 text-xs text-slate-600 leading-relaxed mt-2">
                        <strong>Pembahasan:</strong> ${q.explanation}
                    </div>
                `;

                listContainer.appendChild(card);
            });
        }

        function calculateAndRenderResults() {
            let correctCount = 0;
            let wrongCount = 0;

            userAnswers.forEach((ans, idx) => {
                if (ans === questionsDB[idx].correctIndex) {
                    correctCount++;
                } else {
                    wrongCount++;
                }
            });

            const score = Math.round((correctCount / questionsDB.length) * 100);

            document.getElementById('result-score-number').innerText = score;
            document.getElementById('result-total-questions').innerText = questionsDB.length;
            document.getElementById('result-correct-count').innerText = correctCount;
            document.getElementById('result-wrong-count').innerText = wrongCount;

            const categoryBadge = document.getElementById('result-category-badge');
            const msgBox = document.getElementById('result-feedback-msg');

            if (score >= 90) {
                categoryBadge.className = "mt-4 px-4 py-1.5 rounded-full text-sm font-extrabold bg-emerald-100 text-emerald-800 shadow-sm";
                categoryBadge.innerText = "Kategori: Sangat Baik (90 - 100)";
                msgBox.innerText = "🎉 Hebat! Kamu sudah memahami peta dan komponen-komponennya dengan sangat baik. Pertahankan prestasimu!";
            } else if (score >= 80) {
                categoryBadge.className = "mt-4 px-4 py-1.5 rounded-full text-sm font-extrabold bg-sky-100 text-sky-800 shadow-sm";
                categoryBadge.innerText = "Kategori: Baik (80 - 89)";
                msgBox.innerText = "👍 Bagus sekali! Pemahamanmu mengenai komponen peta sudah baik. Kamu bisa membaca pembahasan untuk menyempurnakannya!";
            } else if (score >= 70) {
                categoryBadge.className = "mt-4 px-4 py-1.5 rounded-full text-sm font-extrabold bg-amber-100 text-amber-800 shadow-sm";
                categoryBadge.innerText = "Kategori: Cukup (70 - 79)";
                msgBox.innerText = "😊 Cukup bagus! Kamu sudah memahami sebagian besar materi peta. Pelajari kembali poin komponen yang belum tepat!";
            } else {
                categoryBadge.className = "mt-4 px-4 py-1.5 rounded-full text-sm font-extrabold bg-rose-100 text-rose-800 shadow-sm";
                categoryBadge.innerText = "Kategori: Perlu Belajar Lagi (< 70)";
                msgBox.innerText = "💪 Tetap semangat! Yuk, pelajari kembali materi dan pembahasan sebelum mencoba latihan lagi!";
            }
        }

        function resetAndRepeatQuiz() {
            playSound('click');
            currentQuestionIndex = 0;
            userAnswers = new Array(15).fill(null);
            navigateTo('latihan');
        }

        // Initialize default view on load
        window.onload = function() {
            navigateTo('beranda');
        };
    </script>
</body>
</html>
