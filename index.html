<!DOCTYPE html>
<html lang="hi" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnePlus OxygenOS Smartphone Simulator</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        oneplus: {
                            red: '#eb0029',
                            darkRed: '#a8001d',
                            bg: '#000000',
                            card: '#141416',
                            cardHover: '#1f1f23',
                            border: '#27272a',
                            subtext: '#9ca3af'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        ::-webkit-scrollbar {
            width: 4px;
        }
        ::-webkit-scrollbar-thumb {
            background: #27272a;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #eb0029;
        }
        .glass-card {
            background: rgba(20, 20, 22, 0.85);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .red-glow {
            box-shadow: 0 0 20px rgba(235, 0, 41, 0.25);
        }
        .oneplus-1-digit {
            color: #eb0029;
            font-weight: 700;
        }
    </style>
</head>
<body class="bg-zinc-950 text-gray-100 font-sans antialiased min-h-screen flex items-center justify-center p-0 md:p-4 selection:bg-oneplus-red selection:text-white">

    <div class="relative w-full max-w-[420px] h-[100vh] md:h-[860px] md:rounded-[48px] overflow-hidden border-0 md:border-[10px] border-zinc-800 shadow-2xl flex flex-col bg-black">
        
        <!-- Status Bar -->
        <div id="status-bar" class="w-full h-9 px-6 pt-2 flex justify-between items-center text-xs font-semibold z-50 select-none text-white bg-transparent">
            <span id="status-time" class="tracking-wide cursor-pointer" onclick="openStealthModal()" title="Tap to Edit Specs">12:00</span>
            <div class="flex items-center space-x-2 text-[11px]">
                <!-- Discreet Edit Trigger in Status Bar -->
                <button onclick="openStealthModal()" class="text-[10px] text-zinc-500 hover:text-oneplus-red transition p-0.5" title="Open Spec Editor">
                    <i class="fa-solid fa-key"></i>
                </button>
                <span class="text-[10px] font-bold text-oneplus-red tracking-wider">5G</span>
                <i class="fa-solid fa-wifi"></i>
                <i class="fa-solid fa-signal"></i>
                <div class="flex items-center space-x-1">
                    <span id="status-battery-text">88%</span>
                    <i class="fa-solid fa-battery-three-quarters text-sm"></i>
                </div>
            </div>
        </div>

        <div id="screen-container" class="relative flex-1 w-full overflow-hidden bg-black">

            <!-- 1. HOME SCREEN -->
            <div id="page-home" class="absolute inset-0 flex flex-col justify-between p-5 pb-6 transition-transform duration-300 ease-out z-10 bg-cover bg-center" style="background-image: radial-gradient(circle at 50% 20%, rgba(235, 0, 41, 0.18), transparent 75%), linear-gradient(to bottom, rgba(0,0,0,0.3), rgba(0,0,0,0.85));">
                
                <!-- TOP: Clock & Weather Widget -->
                <div class="pt-6 flex flex-col items-center cursor-pointer select-none" onclick="openApp('Clock')">
                    <div id="oneplus-clock" class="text-6xl font-light tracking-tight flex items-center drop-shadow-lg">
                        <!-- Populated by JS -->
                    </div>
                    <div class="mt-2.5 flex items-center space-x-2 text-xs text-zinc-300 font-medium bg-black/40 backdrop-blur-md px-3.5 py-1.5 rounded-full border border-white/10 shadow-sm">
                        <i class="fa-solid fa-cloud-sun text-amber-400"></i>
                        <span id="weather-text">28°C • Sunny • New Delhi</span>
                    </div>
                </div>

                <!-- MIDDLE: Shelf/Never Settle Widget -->
                <div class="my-auto px-1">
                    <div class="glass-card rounded-2xl p-4 flex items-center justify-between border border-white/10 shadow-xl hover:border-oneplus-red/40 transition">
                        <div class="flex items-center space-x-3.5">
                            <div class="w-11 h-11 rounded-2xl bg-oneplus-red/20 border border-oneplus-red/40 text-oneplus-red flex items-center justify-center text-xl font-black shadow-inner">
                                1+
                            </div>
                            <div>
                                <h4 class="text-sm font-bold text-white tracking-wide">NEVER SETTLE</h4>
                                <p class="text-xs text-zinc-400" id="home-device-sub">OnePlus 12 • 16 GB RAM</p>
                            </div>
                        </div>
                        <button onclick="navigateTo('page-about')" class="text-xs bg-oneplus-red hover:bg-red-700 text-white font-semibold px-3.5 py-1.5 rounded-xl transition shadow-md">
                            About
                        </button>
                    </div>
                </div>

                <!-- BOTTOM: Grid of Icons -->
                <div class="space-y-6">
                    <div class="grid grid-cols-4 gap-4 px-1">
                        <!-- Phone App -->
                        <div class="flex flex-col items-center space-y-1.5 cursor-pointer group" onclick="openApp('Phone')">
                            <div class="w-14 h-14 bg-gradient-to-tr from-emerald-600 to-green-500 rounded-2xl flex items-center justify-center text-white text-xl shadow-lg group-hover:scale-105 transition">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <span class="text-[11px] text-zinc-300 font-medium">Phone</span>
                        </div>

                        <!-- Messages App -->
                        <div class="flex flex-col items-center space-y-1.5 cursor-pointer group" onclick="openApp('Messages')">
                            <div class="w-14 h-14 bg-gradient-to-tr from-blue-600 to-cyan-500 rounded-2xl flex items-center justify-center text-white text-xl shadow-lg group-hover:scale-105 transition">
                                <i class="fa-solid fa-comment-dots"></i>
                            </div>
                            <span class="text-[11px] text-zinc-300 font-medium">Messages</span>
                        </div>

                        <!-- Chrome App -->
                        <div class="flex flex-col items-center space-y-1.5 cursor-pointer group" onclick="openApp('Chrome')">
                            <div class="w-14 h-14 bg-gradient-to-tr from-red-500 via-amber-500 to-green-500 rounded-2xl flex items-center justify-center text-white text-xl shadow-lg group-hover:scale-105 transition">
                                <i class="fa-brands fa-chrome"></i>
                            </div>
                            <span class="text-[11px] text-zinc-300 font-medium">Chrome</span>
                        </div>

                        <!-- Settings App -->
                        <div class="flex flex-col items-center space-y-1.5 cursor-pointer group" onclick="navigateTo('page-settings')">
                            <div class="w-14 h-14 bg-gradient-to-tr from-zinc-700 to-zinc-800 rounded-2xl border border-zinc-600/50 flex items-center justify-center text-white text-2xl shadow-lg group-hover:scale-105 transition relative">
                                <i class="fa-solid fa-gear"></i>
                                <span class="absolute top-1 right-1 w-2.5 h-2.5 bg-oneplus-red rounded-full"></span>
                            </div>
                            <span class="text-[11px] text-white font-semibold">Settings</span>
                        </div>
                    </div>

                    <!-- Swipe Up Hint -->
                    <div class="flex flex-col items-center space-y-1 cursor-pointer opacity-70 hover:opacity-100 transition" onclick="toggleAppDrawer(true)">
                        <i class="fa-solid fa-chevron-up text-xs text-zinc-400 animate-bounce"></i>
                        <span class="text-[10px] tracking-widest uppercase text-zinc-400 font-semibold">Swipe Up for All Apps</span>
                    </div>
                </div>
            </div>

            <!-- APP DRAWER -->
            <div id="app-drawer" class="absolute inset-0 bg-black/95 backdrop-blur-2xl z-20 translate-y-full transition-transform duration-300 ease-out flex flex-col p-5">
                <div class="relative mb-5">
                    <i class="fa-solid fa-magnifying-glass absolute left-4 top-3.5 text-zinc-500 text-sm"></i>
                    <input type="text" id="app-search" onkeyup="filterApps()" placeholder="Search Apps..." class="w-full bg-zinc-900 border border-zinc-800 rounded-xl py-2.5 pl-11 pr-4 text-sm text-white placeholder-zinc-500 focus:outline-none focus:border-oneplus-red">
                    <button onclick="toggleAppDrawer(false)" class="absolute right-3 top-2.5 text-zinc-400 hover:text-white p-1">
                        <i class="fa-solid fa-xmark text-lg"></i>
                    </button>
                </div>
                <div class="flex-1 overflow-y-auto pr-1">
                    <div id="drawer-apps-list" class="grid grid-cols-4 gap-y-6 gap-x-3 text-center">
                        <div class="app-item flex flex-col items-center space-y-1.5 cursor-pointer" onclick="navigateTo('page-settings')">
                            <div class="w-14 h-14 bg-gradient-to-tr from-zinc-700 to-zinc-800 rounded-2xl border border-zinc-600 flex items-center justify-center text-white text-2xl">
                                <i class="fa-solid fa-gear"></i>
                            </div>
                            <span class="text-[11px] text-white font-medium">Settings</span>
                        </div>
                        <div class="app-item flex flex-col items-center space-y-1.5 cursor-pointer" onclick="navigateTo('page-about')">
                            <div class="w-14 h-14 bg-oneplus-red rounded-2xl flex items-center justify-center text-white text-2xl red-glow">
                                <i class="fa-solid fa-mobile-screen-button"></i>
                            </div>
                            <span class="text-[11px] text-white font-medium">About Device</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 2. FULL OXYGENOS SETTINGS SCREEN -->
            <div id="page-settings" class="absolute inset-0 bg-black z-30 translate-x-full transition-transform duration-300 ease-out flex flex-col overflow-hidden">
                <!-- Settings Header -->
                <div class="p-4 border-b border-zinc-800/80 flex items-center justify-between bg-zinc-950/90 backdrop-blur-lg sticky top-0 z-10">
                    <div class="flex items-center space-x-3">
                        <button onclick="navigateTo('page-home')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center hover:bg-zinc-700">
                            <i class="fa-solid fa-arrow-left text-sm"></i>
                        </button>
                        <h2 class="text-lg font-bold text-white tracking-wide">Settings</h2>
                    </div>
                    <span class="text-[11px] px-2.5 py-1 bg-oneplus-red/20 text-oneplus-red font-bold rounded-full border border-oneplus-red/30">OxygenOS</span>
                </div>

                <!-- Settings Scrollable Body -->
                <div class="flex-1 overflow-y-auto p-4 space-y-4 text-left">

                    <!-- Search Bar in Settings -->
                    <div class="relative">
                        <i class="fa-solid fa-magnifying-glass absolute left-3.5 top-3 text-zinc-500 text-sm"></i>
                        <input type="text" id="settings-search" onkeyup="filterSettings()" placeholder="Search settings..." class="w-full bg-zinc-900 border border-zinc-800 rounded-xl py-2 pl-10 pr-4 text-sm text-white placeholder-zinc-500 focus:outline-none focus:border-oneplus-red">
                    </div>

                    <!-- User Account Banner -->
                    <div class="bg-gradient-to-r from-zinc-900 to-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 flex items-center space-x-3.5 cursor-pointer hover:border-zinc-700 transition" onclick="showToast('OnePlus Account Active')">
                        <div class="w-12 h-12 rounded-full bg-oneplus-red/20 text-oneplus-red flex items-center justify-center text-xl font-bold border border-oneplus-red/30">
                            <i class="fa-solid fa-user"></i>
                        </div>
                        <div class="flex-1">
                            <h4 class="text-sm font-semibold text-white">OnePlus Account</h4>
                            <p class="text-xs text-zinc-400">Cloud Sync & Red Cable Club Active</p>
                        </div>
                        <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                    </div>

                    <!-- NETWORK & CONNECTIVITY SECTION -->
                    <div class="settings-group space-y-1">
                        <span class="text-[11px] font-bold text-zinc-500 uppercase tracking-wider px-1">Network & Connectivity</span>
                        
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl overflow-hidden divide-y divide-zinc-800/50">
                            <div class="setting-item p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-wifi')">
                                <div class="flex items-center space-x-3.5">
                                    <div class="w-8 h-8 rounded-xl bg-blue-500/20 text-blue-400 flex items-center justify-center text-sm">
                                        <i class="fa-solid fa-wifi"></i>
                                    </div>
                                    <div>
                                        <p class="text-sm font-medium text-white">Wi-Fi</p>
                                        <p class="text-xs text-zinc-400">Connected to OnePlus_5G</p>
                                    </div>
                                </div>
                                <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                            </div>

                            <div class="setting-item p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-bluetooth')">
                                <div class="flex items-center space-x-3.5">
                                    <div class="w-8 h-8 rounded-xl bg-indigo-500/20 text-indigo-400 flex items-center justify-center text-sm">
                                        <i class="fa-brands fa-bluetooth-b"></i>
                                    </div>
                                    <div>
                                        <p class="text-sm font-medium text-white">Bluetooth</p>
                                        <p class="text-xs text-zinc-400">On • OnePlus Buds Pro 2</p>
                                    </div>
                                </div>
                                <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                            </div>

                            <div class="setting-item p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="showToast('Mobile Network: 5G Dual SIM Active')">
                                <div class="flex items-center space-x-3.5">
                                    <div class="w-8 h-8 rounded-xl bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-sm">
                                        <i class="fa-solid fa-signal"></i>
                                    </div>
                                    <div>
                                        <p class="text-sm font-medium text-white">Mobile Network</p>
                                        <p class="text-xs text-zinc-400">Jio 5G / Airtel 5G</p>
                                    </div>
                                </div>
                                <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                            </div>
                        </div>
                    </div>

                    <!-- DISPLAY & SOUND SECTION -->
                    <div class="settings-group space-y-1">
                        <span class="text-[11px] font-bold text-zinc-500 uppercase tracking-wider px-1">Display & Sound</span>
                        
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl overflow-hidden divide-y divide-zinc-800/50">
                            <div class="setting-item p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-display')">
                                <div class="flex items-center space-x-3.5">
                                    <div class="w-8 h-8 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-sm">
                                        <i class="fa-solid fa-sun"></i>
                                    </div>
                                    <div>
                                        <p class="text-sm font-medium text-white">Display & Brightness</p>
                                        <p class="text-xs text-zinc-400">120Hz ProXDR • Dark Mode</p>
                                    </div>
                                </div>
                                <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                            </div>

                            <div class="setting-item p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-battery')">
                                <div class="flex items-center space-x-3.5">
                                    <div class="w-8 h-8 rounded-xl bg-green-500/20 text-green-400 flex items-center justify-center text-sm">
                                        <i class="fa-solid fa-battery-three-quarters"></i>
                                    </div>
                                    <div>
                                        <p class="text-sm font-medium text-white">Battery</p>
                                        <p class="text-xs text-zinc-400">88% • Smart Charging Active</p>
                                    </div>
                                </div>
                                <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                            </div>
                        </div>
                    </div>

                    <!-- SYSTEM & ABOUT SECTION -->
                    <div class="settings-group space-y-1">
                        <span class="text-[11px] font-bold text-zinc-500 uppercase tracking-wider px-1">System & Device Info</span>
                        
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl overflow-hidden divide-y divide-zinc-800/50">
                            <!-- MAIN HIGHLIGHTED ABOUT DEVICE BUTTON -->
                            <div class="setting-item p-4 flex items-center justify-between cursor-pointer bg-gradient-to-r from-oneplus-red/10 via-zinc-900 to-zinc-900 hover:from-oneplus-red/20 transition border-l-4 border-oneplus-red" onclick="navigateTo('page-about')">
                                <div class="flex items-center space-x-3.5">
                                    <div class="w-10 h-10 rounded-2xl bg-oneplus-red text-white flex items-center justify-center text-lg font-bold shadow-md red-glow">
                                        <i class="fa-solid fa-mobile-screen-button"></i>
                                    </div>
                                    <div>
                                        <p class="text-sm font-bold text-white">About Device</p>
                                        <p class="text-xs text-zinc-300" id="settings-about-subtitle">OnePlus 12 • 16 GB RAM • 512 GB</p>
                                    </div>
                                </div>
                                <i class="fa-solid fa-chevron-right text-sm text-oneplus-red font-bold"></i>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <!-- 3. REALISTIC AUTHENTIC ABOUT DEVICE PAGE -->
            <div id="page-about" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col overflow-hidden">
                <!-- Header -->
                <div class="p-4 border-b border-zinc-800/80 flex items-center justify-between bg-zinc-950/90 backdrop-blur-lg sticky top-0 z-10">
                    <div class="flex items-center space-x-3">
                        <button onclick="navigateTo('page-settings')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center hover:bg-zinc-700">
                            <i class="fa-solid fa-arrow-left text-sm"></i>
                        </button>
                        <h2 class="text-base font-bold text-white">About Device</h2>
                    </div>
                    <div class="flex items-center space-x-2">
                        <!-- Secret Edit Button -->
                        <button onclick="openStealthModal()" class="w-7 h-7 rounded-full bg-zinc-800/80 text-zinc-400 hover:text-oneplus-red hover:bg-zinc-700 flex items-center justify-center transition" title="Edit Specs">
                            <i class="fa-solid fa-pen-to-square text-xs"></i>
                        </button>
                        <span class="text-xs px-2.5 py-1 bg-oneplus-red text-white font-bold rounded-full shadow-md">Official</span>
                    </div>
                </div>

                <!-- Scrollable Official Specs List -->
                <div class="flex-1 overflow-y-auto p-4 space-y-4 text-left">

                    <!-- OxygenOS Official Banner (Triple tap to open stealth editor) -->
                    <div class="bg-gradient-to-r from-zinc-900 via-zinc-900 to-zinc-800 border border-zinc-800 rounded-2xl p-4 relative overflow-hidden cursor-pointer select-none group" onclick="handleSecretTap()">
                        <div class="flex items-center space-x-4">
                            <div class="w-16 h-16 bg-oneplus-red text-white flex flex-col items-center justify-center font-black text-2xl rounded-2xl shadow-xl red-glow">
                                <span>1+</span>
                            </div>
                            <div class="flex-1">
                                <div class="flex items-center justify-between">
                                    <h3 id="about-oxygen-ver" class="text-lg font-bold text-white">OxygenOS 14.0</h3>
                                    <span class="text-[9px] text-zinc-500 border border-zinc-700 px-1.5 py-0.5 rounded opacity-60 group-hover:opacity-100">3x Tap to Edit</span>
                                </div>
                                <p id="about-android-ver" class="text-xs text-zinc-400">Official Version | Android 14</p>
                                <div class="mt-1.5 flex items-center space-x-1.5 text-xs text-emerald-400 font-semibold">
                                    <i class="fa-solid fa-circle-check"></i>
                                    <span>System is up to date</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Device Name Card -->
                    <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-4 flex items-center justify-between">
                        <div>
                            <span class="text-[11px] font-bold text-zinc-500 uppercase tracking-wider block mb-0.5">Device Name</span>
                            <h3 id="about-device-name" class="text-base font-bold text-white">OnePlus 12</h3>
                        </div>
                        <div class="text-right">
                            <span class="text-[11px] font-bold text-zinc-500 uppercase tracking-wider block mb-0.5">Model</span>
                            <span id="about-model-name" class="text-xs text-zinc-300 font-semibold">CPH2581</span>
                        </div>
                    </div>

                    <!-- Specs 2x3 Grid -->
                    <div class="grid grid-cols-2 gap-3">
                        <!-- Processor -->
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 space-y-1">
                            <i class="fa-solid fa-microchip text-oneplus-red text-base"></i>
                            <span class="text-[10px] font-bold text-zinc-500 uppercase block">Processor</span>
                            <p id="about-processor" class="text-xs font-semibold text-white leading-tight">Snapdragon® 8 Gen 3</p>
                        </div>

                        <!-- RAM -->
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 space-y-1">
                            <i class="fa-solid fa-memory text-oneplus-red text-base"></i>
                            <span class="text-[10px] font-bold text-zinc-500 uppercase block">RAM</span>
                            <p id="about-ram" class="text-xs font-semibold text-white leading-tight">16 GB (+12 GB RAM Expansion)</p>
                        </div>

                        <!-- Storage -->
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 space-y-1">
                            <i class="fa-solid fa-hard-drive text-oneplus-red text-base"></i>
                            <span class="text-[10px] font-bold text-zinc-500 uppercase block">Storage</span>
                            <p id="about-storage" class="text-xs font-semibold text-white leading-tight">512 GB UFS 4.0</p>
                        </div>

                        <!-- Battery -->
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 space-y-1">
                            <i class="fa-solid fa-battery-full text-oneplus-red text-base"></i>
                            <span class="text-[10px] font-bold text-zinc-500 uppercase block">Battery</span>
                            <p id="about-battery" class="text-xs font-semibold text-white leading-tight">5400 mAh (100W SUPERVOOC)</p>
                        </div>

                        <!-- Screen -->
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 space-y-1">
                            <i class="fa-solid fa-mobile-screen text-oneplus-red text-base"></i>
                            <span class="text-[10px] font-bold text-zinc-500 uppercase block">Screen Size</span>
                            <p id="about-display" class="text-xs font-semibold text-white leading-tight">6.82" 120Hz ProXDR AMOLED</p>
                        </div>

                        <!-- Camera -->
                        <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl p-3.5 space-y-1">
                            <i class="fa-solid fa-camera text-oneplus-red text-base"></i>
                            <span class="text-[10px] font-bold text-zinc-500 uppercase block">Camera System</span>
                            <p id="about-camera" class="text-xs font-semibold text-white leading-tight">50MP Hasselblad Triple Camera</p>
                        </div>
                    </div>

                    <!-- Warranty Status Card -->
                    <div class="bg-gradient-to-r from-zinc-900 via-zinc-900 to-zinc-900 border border-emerald-500/30 rounded-2xl p-4 space-y-3 cursor-pointer select-none" onclick="handleSecretTap()">
                        <div class="flex items-center justify-between border-b border-zinc-800/80 pb-2.5">
                            <div class="flex items-center space-x-2">
                                <i class="fa-solid fa-shield-halved text-emerald-400 text-sm"></i>
                                <span class="text-xs font-bold text-white">Warranty & Protection</span>
                            </div>
                            <span id="about-warranty-badge" class="text-[10px] font-bold bg-emerald-500/20 text-emerald-400 px-2 py-0.5 rounded-full border border-emerald-500/30">Active</span>
                        </div>
                        <div class="grid grid-cols-2 gap-2 text-xs">
                            <div>
                                <span class="text-[10px] font-medium text-zinc-500 block">Coverage Expire Date</span>
                                <span id="about-warranty-date" class="font-semibold text-zinc-200">Dec 28, 2026</span>
                            </div>
                            <div>
                                <span class="text-[10px] font-medium text-zinc-500 block">Coverage Type</span>
                                <span id="about-warranty-type" class="font-semibold text-zinc-200">Official Brand Warranty</span>
                            </div>
                            <div class="col-span-2 pt-1 border-t border-zinc-800/50 flex justify-between text-[11px]">
                                <span class="text-zinc-500">Serial Number (S/N):</span>
                                <span id="about-serial-no" class="font-mono text-zinc-300">OP12984X7721</span>
                            </div>
                        </div>
                    </div>

                    <!-- Sub-pages Links: Version, Legal Info, Regulatory -->
                    <div class="bg-zinc-900 border border-zinc-800/80 rounded-2xl overflow-hidden divide-y divide-zinc-800/50">
                        <!-- Version Details -->
                        <div class="p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-version')">
                            <span class="text-xs font-semibold text-white">Version Details (Build & Kernel)</span>
                            <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                        </div>

                        <!-- Legal Info -->
                        <div class="p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-legal')">
                            <span class="text-xs font-semibold text-white">Legal Information & Licenses</span>
                            <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                        </div>

                        <!-- Regulatory & Markings -->
                        <div class="p-3.5 flex items-center justify-between cursor-pointer hover:bg-zinc-800/50 transition" onclick="navigateTo('page-regulatory')">
                            <span class="text-xs font-semibold text-white">Regulatory & Certification Markings</span>
                            <i class="fa-solid fa-chevron-right text-xs text-zinc-500"></i>
                        </div>
                    </div>

                </div>
            </div>

            <!-- 4. LEGAL INFORMATION SUB-PAGE -->
            <div id="page-legal" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-about')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Legal Information</h2>
                </div>
                <div class="p-4 space-y-3 overflow-y-auto flex-1 text-xs">
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800 space-y-1 cursor-pointer" onclick="showToast('User Agreement Document')">
                        <p class="font-semibold text-white">OnePlus User Agreement</p>
                        <p class="text-zinc-400 text-[11px]">Terms and conditions governing device software and services.</p>
                    </div>
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800 space-y-1 cursor-pointer" onclick="showToast('Privacy Policy')">
                        <p class="font-semibold text-white">Privacy Policy</p>
                        <p class="text-zinc-400 text-[11px]">How OxygenOS handles user data and privacy protections.</p>
                    </div>
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800 space-y-1 cursor-pointer" onclick="showToast('Open Source Licenses')">
                        <p class="font-semibold text-white">Open Source Licenses</p>
                        <p class="text-zinc-400 text-[11px]">Third-party open-source libraries and Linux kernel licenses.</p>
                    </div>
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800 space-y-1 cursor-pointer" onclick="showToast('Safety Guidelines')">
                        <p class="font-semibold text-white">Safety Information</p>
                        <p class="text-zinc-400 text-[11px]">Battery safety, RF exposure limits (SAR), and operating environment guidelines.</p>
                    </div>
                </div>
            </div>

            <!-- 5. VERSION DETAILS SUB-PAGE -->
            <div id="page-version" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-about')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Version Details</h2>
                </div>
                <div class="p-4 space-y-3 overflow-y-auto flex-1 text-xs">
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800">
                        <span class="text-zinc-500 font-medium block">Build Number</span>
                        <p id="version-build-no" class="font-mono font-semibold text-white text-xs mt-0.5">CPH2581_14.0.0.604(EX01)</p>
                    </div>
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800">
                        <span class="text-zinc-500 font-medium block">Baseband Version</span>
                        <p class="font-mono text-zinc-300 text-xs mt-0.5">Q_V1_P14,Q_V1_P14</p>
                    </div>
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800">
                        <span class="text-zinc-500 font-medium block">Kernel Version</span>
                        <p class="font-mono text-zinc-300 text-xs mt-0.5">6.1.25-android14-11-g9845f012</p>
                    </div>
                    <div class="bg-zinc-900 p-3.5 rounded-2xl border border-zinc-800">
                        <span class="text-zinc-500 font-medium block">Android Security Patch Level</span>
                        <p class="font-semibold text-emerald-400 text-xs mt-0.5">September 5, 2026</p>
                    </div>
                </div>
            </div>

            <!-- 6. REGULATORY & CERTIFICATION SUB-PAGE -->
            <div id="page-regulatory" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-about')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Regulatory Info</h2>
                </div>
                <div class="p-4 space-y-4 overflow-y-auto flex-1 text-xs">
                    <div class="bg-zinc-900 p-4 rounded-2xl border border-zinc-800 space-y-2 text-center">
                        <span class="text-zinc-400 font-semibold block">Regulatory Certification Marks</span>
                        <div class="flex items-center justify-center space-x-4 text-2xl text-zinc-300 py-2">
                            <span class="font-bold border border-zinc-600 px-2 rounded">CE</span>
                            <i class="fa-solid fa-recycle"></i>
                            <span class="font-bold border border-zinc-600 px-2 rounded">BIS</span>
                        </div>
                        <p class="text-[11px] text-zinc-500">Designed by OnePlus • Assembled in India / China</p>
                    </div>
                    <div class="bg-zinc-900 p-4 rounded-2xl border border-zinc-800 space-y-2">
                        <span class="text-zinc-400 font-semibold block">Device Identification</span>
                        <div class="flex justify-between border-b border-zinc-800 pb-1.5">
                            <span class="text-zinc-500">IMEI 1:</span>
                            <span id="regulatory-imei1" class="font-mono text-zinc-200">864902061234567</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-zinc-500">IMEI 2:</span>
                            <span id="regulatory-imei2" class="font-mono text-zinc-200">864902061234568</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 7. WI-FI SUB-PAGE -->
            <div id="page-wifi" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-settings')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Wi-Fi Settings</h2>
                </div>
                <div class="p-4 space-y-4">
                    <div class="bg-zinc-900 p-4 rounded-2xl flex items-center justify-between border border-zinc-800">
                        <div>
                            <p class="text-sm font-semibold text-white">Wi-Fi Toggle</p>
                            <p class="text-xs text-zinc-400">Wi-Fi is currently enabled</p>
                        </div>
                        <input type="checkbox" checked class="w-5 h-5 accent-oneplus-red rounded cursor-pointer">
                    </div>
                </div>
            </div>

            <!-- 8. BLUETOOTH SUB-PAGE -->
            <div id="page-bluetooth" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-settings')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Bluetooth</h2>
                </div>
                <div class="p-4 space-y-4">
                    <div class="bg-zinc-900 p-4 rounded-2xl flex items-center justify-between border border-zinc-800">
                        <div>
                            <p class="text-sm font-semibold text-white">Bluetooth</p>
                            <p class="text-xs text-zinc-400">Discoverable as "OnePlus Smartphone"</p>
                        </div>
                        <input type="checkbox" checked class="w-5 h-5 accent-oneplus-red rounded cursor-pointer">
                    </div>
                </div>
            </div>

            <!-- 9. DISPLAY SUB-PAGE -->
            <div id="page-display" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-settings')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Display & Brightness</h2>
                </div>
                <div class="p-4 space-y-4">
                    <div class="bg-zinc-900 p-4 rounded-2xl border border-zinc-800 space-y-3">
                        <p class="text-sm font-semibold text-white">Brightness Level</p>
                        <input type="range" min="10" max="100" value="80" class="w-full accent-oneplus-red">
                    </div>
                </div>
            </div>

            <!-- 10. BATTERY SUB-PAGE -->
            <div id="page-battery" class="absolute inset-0 bg-black z-40 translate-x-full transition-transform duration-300 ease-out flex flex-col">
                <div class="p-4 border-b border-zinc-800 flex items-center space-x-3 bg-zinc-950">
                    <button onclick="navigateTo('page-settings')" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-arrow-left text-sm"></i>
                    </button>
                    <h2 class="text-base font-bold text-white">Battery Health</h2>
                </div>
                <div class="p-4 space-y-4">
                    <div class="bg-zinc-900 p-5 rounded-2xl border border-zinc-800 text-center space-y-2">
                        <span class="text-4xl font-extrabold text-emerald-400">88%</span>
                        <p class="text-xs text-zinc-400">Smart Charging Enabled</p>
                    </div>
                </div>
            </div>

            <!-- SECRET STEALTH EDIT MODAL POPUP (Triggered by 3 fast taps on logo) -->
            <div id="stealth-editor-modal" class="absolute inset-0 bg-black/95 backdrop-blur-2xl z-50 hidden flex-col p-5 overflow-y-auto">
                <div class="flex items-center justify-between border-b border-zinc-800 pb-3 mb-4">
                    <div class="flex items-center space-x-2">
                        <i class="fa-solid fa-user-gear text-oneplus-red text-base"></i>
                        <h3 class="text-sm font-bold text-white uppercase tracking-wider">Stealth Spec Editor</h3>
                    </div>
                    <button onclick="closeStealthModal()" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center hover:bg-zinc-700">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>

                <div class="space-y-4 text-left">
                    <!-- Preset Selector Dropdown -->
                    <div class="bg-zinc-900 border border-zinc-800 rounded-2xl p-3.5">
                        <label class="block text-xs font-bold text-oneplus-red uppercase tracking-wider mb-2">
                            Quick Select OnePlus Model:
                        </label>
                        <select id="modal-model-presets" onchange="loadPresetModel(this.value)" class="w-full bg-zinc-800 border border-zinc-700 text-white text-xs font-medium rounded-xl px-3 py-2.5 appearance-none focus:outline-none focus:border-oneplus-red">
                            <option value="op12">OnePlus 12 5G (Flagship)</option>
                            <option value="op12r">OnePlus 12R</option>
                            <option value="opopen">OnePlus Open (Foldable)</option>
                            <option value="opnord4">OnePlus Nord 4 5G</option>
                            <option value="op11">OnePlus 11 5G</option>
                            <option value="op10pro">OnePlus 10 Pro 5G</option>
                            <option value="op9pro">OnePlus 9 Pro 5G</option>
                            <option value="opnord3">OnePlus Nord 3 5G</option>
                            <option value="op7pro">OnePlus 7 Pro</option>
                        </select>
                    </div>

                    <!-- Input Fields -->
                    <div class="bg-zinc-900 border border-zinc-800 rounded-2xl p-3.5 space-y-3">
                        <div>
                            <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Device Name</label>
                            <input type="text" id="edit-device-name" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                        </div>

                        <div>
                            <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Model Code</label>
                            <input type="text" id="edit-model-name" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                        </div>

                        <div>
                            <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Processor / Chipset</label>
                            <input type="text" id="edit-processor" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                        </div>

                        <div class="grid grid-cols-2 gap-2.5">
                            <div>
                                <label class="block text-[11px] font-semibold text-zinc-400 mb-1">RAM</label>
                                <input type="text" id="edit-ram" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                            </div>
                            <div>
                                <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Storage</label>
                                <input type="text" id="edit-storage" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-2.5">
                            <div>
                                <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Battery</label>
                                <input type="text" id="edit-battery" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                            </div>
                            <div>
                                <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Display</label>
                                <input type="text" id="edit-display" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                            </div>
                        </div>

                        <!-- Warranty Fields -->
                        <div class="border-t border-zinc-800 pt-2 grid grid-cols-2 gap-2.5">
                            <div>
                                <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Warranty Expiration</label>
                                <input type="text" id="edit-warranty-date" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                            </div>
                            <div>
                                <label class="block text-[11px] font-semibold text-zinc-400 mb-1">Serial Number (S/N)</label>
                                <input type="text" id="edit-serial-no" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                            </div>
                        </div>

                        <div>
                            <label class="block text-[11px] font-semibold text-zinc-400 mb-1">IMEI 1</label>
                            <input type="text" id="edit-imei1" class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-oneplus-red">
                        </div>
                    </div>

                    <!-- Action Buttons -->
                    <div class="flex items-center space-x-3 pt-2">
                        <button onclick="saveStealthSpecs()" class="flex-1 bg-oneplus-red hover:bg-red-700 text-white font-semibold py-2.5 rounded-xl text-xs transition shadow-lg red-glow flex items-center justify-center space-x-2">
                            <i class="fa-solid fa-floppy-disk"></i>
                            <span>Save Changes</span>
                        </button>
                        <button onclick="resetSpecifications()" class="bg-zinc-800 hover:bg-zinc-700 text-zinc-300 font-medium px-4 py-2.5 rounded-xl text-xs transition border border-zinc-700">
                            Reset
                        </button>
                    </div>
                </div>
            </div>

            <!-- GENERIC APP POPUP -->
            <div id="app-modal" class="absolute inset-0 bg-black/95 backdrop-blur-xl z-50 hidden flex-col justify-between p-6">
                <div class="flex items-center justify-between border-b border-zinc-800 pb-4">
                    <h3 id="modal-app-title" class="text-lg font-bold text-white">App</h3>
                    <button onclick="closeAppModal()" class="w-8 h-8 rounded-full bg-zinc-800 text-zinc-300 flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>
                <div class="flex-1 flex flex-col items-center justify-center text-center space-y-3">
                    <i id="modal-big-icon" class="fa-solid fa-mobile-screen text-4xl text-oneplus-red"></i>
                    <h4 id="modal-inner-title" class="text-xl font-bold text-white">App Launch</h4>
                    <p id="modal-inner-desc" class="text-xs text-zinc-400">OxygenOS Native Experience Simulator.</p>
                </div>
                <button onclick="closeAppModal()" class="w-full bg-zinc-800 text-white font-medium py-2.5 rounded-xl border border-zinc-700">
                    Close
                </button>
            </div>

        </div>

        <!-- BOTTOM NAVIGATION BAR (BACK, HOME, RECENTS) -->
        <div class="w-full h-11 bg-black border-t border-zinc-900 flex items-center justify-around text-zinc-400 relative z-50 select-none">
            <!-- Back Button -->
            <button onclick="goBack()" class="p-2 hover:text-white transition active:scale-90" title="Back">
                <i class="fa-solid fa-chevron-left text-sm"></i>
            </button>
            <!-- Home Pill Gesture -->
            <button onclick="navigateTo('page-home')" class="w-28 h-1.5 bg-zinc-500 hover:bg-white rounded-full transition active:scale-95 duration-150 cursor-pointer" title="Home"></button>
            <!-- Recents Button -->
            <button onclick="showToast('OxygenOS Task Switcher')" class="p-2 hover:text-white transition active:scale-90" title="Recents">
                <i class="fa-regular fa-square text-sm"></i>
            </button>
        </div>

    </div>

    <script>
        // Official Preset Models Data
        const ONEPLUS_PRESETS = {
            op12: {
                deviceName: "OnePlus 12",
                modelName: "CPH2581",
                processor: "Snapdragon® 8 Gen 3 Mobile Platform",
                ram: "16 GB (+12 GB RAM Expansion)",
                storage: "512 GB UFS 4.0",
                battery: "5400 mAh (100W SUPERVOOC)",
                display: "6.82\" 120Hz ProXDR AMOLED",
                camera: "50MP Hasselblad Triple Camera",
                oxygenVer: "OxygenOS 14.0",
                androidVer: "Android 14",
                warrantyDate: "Dec 28, 2026",
                serialNo: "OP12984X7721",
                imei1: "864902061234567",
                imei2: "864902061234568"
            },
            op12r: {
                deviceName: "OnePlus 12R",
                modelName: "CPH2585",
                processor: "Snapdragon® 8 Gen 2 Mobile Platform",
                ram: "16 GB LPDDR5X",
                storage: "256 GB UFS 3.1",
                battery: "5500 mAh (100W SUPERVOOC)",
                display: "6.78\" 120Hz LTPO4 AMOLED",
                camera: "50MP Sony IMX890 Camera",
                oxygenVer: "OxygenOS 14.0",
                androidVer: "Android 14",
                warrantyDate: "Nov 15, 2026",
                serialNo: "OP12R8812A90",
                imei1: "864902062234561",
                imei2: "864902062234562"
            },
            opopen: {
                deviceName: "OnePlus Open",
                modelName: "CPH2551",
                processor: "Snapdragon® 8 Gen 2 Mobile Platform",
                ram: "16 GB LPDDR5X",
                storage: "512 GB",
                battery: "4805 mAh (67W SUPERVOOC)",
                display: "7.82\" Flexi-fluid AMOLED 120Hz",
                camera: "48MP Dual Sony Hasselblad",
                oxygenVer: "OxygenOS 13.2 Fold",
                androidVer: "Android 13",
                warrantyDate: "Jan 10, 2027",
                serialNo: "OPOPEN9932L1",
                imei1: "864902063234563",
                imei2: "864902063234564"
            },
            opnord4: {
                deviceName: "OnePlus Nord 4 5G",
                modelName: "CPH2621",
                processor: "Snapdragon® 7+ Gen 3",
                ram: "12 GB (+8 GB Expansion)",
                storage: "256 GB UFS 4.0",
                battery: "5500 mAh (100W SUPERVOOC)",
                display: "6.74\" 120Hz Ultra Fluid AMOLED",
                camera: "50MP Sony LYT-600 OIS",
                oxygenVer: "OxygenOS 14.1",
                androidVer: "Android 14",
                warrantyDate: "Oct 20, 2026",
                serialNo: "OPNORD411029",
                imei1: "864902064234565",
                imei2: "864902064234566"
            },
            op11: {
                deviceName: "OnePlus 11 5G",
                modelName: "CPH2449",
                processor: "Snapdragon® 8 Gen 2",
                ram: "16 GB LPDDR5X",
                storage: "256 GB UFS 4.0",
                battery: "5000 mAh",
                display: "6.7\" 2K 120Hz Fluid AMOLED",
                camera: "50MP Hasselblad Camera",
                oxygenVer: "OxygenOS 13.0",
                androidVer: "Android 13",
                warrantyDate: "Aug 12, 2025",
                serialNo: "OP1188334199",
                imei1: "864902065234567",
                imei2: "864902065234568"
            },
            op10pro: {
                deviceName: "OnePlus 10 Pro 5G",
                modelName: "NE2210",
                processor: "Snapdragon® 8 Gen 1",
                ram: "12 GB",
                storage: "256 GB",
                battery: "5000 mAh (80W SUPERVOOC)",
                display: "6.7\" QHD+ 120Hz Fluid AMOLED",
                camera: "48MP Hasselblad Triple Camera",
                oxygenVer: "OxygenOS 12.1",
                androidVer: "Android 12",
                warrantyDate: "May 04, 2025",
                serialNo: "OP10P5511200",
                imei1: "864902066234569",
                imei2: "864902066234570"
            },
            op9pro: {
                deviceName: "OnePlus 9 Pro 5G",
                modelName: "LE2121",
                processor: "Snapdragon® 888",
                ram: "12 GB",
                storage: "256 GB",
                battery: "4500 mAh",
                display: "6.67\" 120Hz Fluid AMOLED",
                camera: "48MP Hasselblad Camera System",
                oxygenVer: "OxygenOS 11.0",
                androidVer: "Android 11",
                warrantyDate: "Expired",
                serialNo: "OP9P11223344",
                imei1: "864902067234571",
                imei2: "864902067234572"
            },
            opnord3: {
                deviceName: "OnePlus Nord 3 5G",
                modelName: "CPH2493",
                processor: "MediaTek Dimensity 9000",
                ram: "16 GB LPDDR5X",
                storage: "256 GB",
                battery: "5000 mAh",
                display: "6.74\" 120Hz Super Fluid AMOLED",
                camera: "50MP Sony IMX890 OIS",
                oxygenVer: "OxygenOS 13.1",
                androidVer: "Android 13",
                warrantyDate: "Jul 18, 2025",
                serialNo: "OPN377112001",
                imei1: "864902068234573",
                imei2: "864902068234574"
            },
            op7pro: {
                deviceName: "OnePlus 7 Pro",
                modelName: "GM1911",
                processor: "Snapdragon® 855",
                ram: "8 GB",
                storage: "256 GB",
                battery: "4000 mAh",
                display: "6.67\" 90Hz QHD+ Fluid AMOLED",
                camera: "48MP Triple Camera System",
                oxygenVer: "OxygenOS 11.0",
                androidVer: "Android 11",
                warrantyDate: "Expired",
                serialNo: "OP7P90112233",
                imei1: "864902069234575",
                imei2: "864902069234576"
            }
        };

        // Navigation History Stack
        let navigationHistory = ['page-home'];
        let currentSpecs = { ...ONEPLUS_PRESETS.op12 };
        let tapCount = 0;
        let tapTimer = null;

        window.onload = function() {
            updateClock();
            setInterval(updateClock, 1000);
            loadSavedSpecs();

            // Display introductory hint toast so user knows how to edit specs
            setTimeout(() => {
                showToast("💡 Hint: Triple-tap OxygenOS logo or tap 🔑 / ✏️ icon to edit specs!");
            }, 800);
        };

        // Red "1" OnePlus Clock Renderer
        function updateClock() {
            const now = new Date();
            let hours = now.getHours();
            let minutes = now.getMinutes();
            hours = hours < 10 ? '0' + hours : '' + hours;
            minutes = minutes < 10 ? '0' + minutes : '' + minutes;

            document.getElementById('status-time').innerText = `${hours}:${minutes}`;

            const timeString = `${hours}:${minutes}`;
            let clockHtml = '';

            for (let char of timeString) {
                if (char === '1') {
                    clockHtml += `<span class="oneplus-1-digit">1</span>`;
                } else {
                    clockHtml += `<span>${char}</span>`;
                }
            }

            document.getElementById('oneplus-clock').innerHTML = clockHtml;
        }

        // Screen Navigation Controller
        function navigateTo(pageId) {
            toggleAppDrawer(false);
            closeAppModal();

            const pages = ['page-home', 'page-settings', 'page-about', 'page-legal', 'page-version', 'page-regulatory', 'page-wifi', 'page-bluetooth', 'page-display', 'page-battery'];
            
            pages.forEach(id => {
                const el = document.getElementById(id);
                if (id === pageId) {
                    el.classList.remove('translate-x-full');
                } else if (id !== 'page-home' && pages.indexOf(id) > pages.indexOf(pageId)) {
                    el.classList.add('translate-x-full');
                }
            });

            if (navigationHistory[navigationHistory.length - 1] !== pageId) {
                navigationHistory.push(pageId);
            }
        }

        function goBack() {
            if (navigationHistory.length > 1) {
                navigationHistory.pop();
                const previousPage = navigationHistory[navigationHistory.length - 1];
                navigateTo(previousPage);
            } else {
                navigateTo('page-home');
            }
        }

        // App Drawer Toggle
        function toggleAppDrawer(open) {
            const drawer = document.getElementById('app-drawer');
            if (open) {
                drawer.classList.remove('translate-y-full');
            } else {
                drawer.classList.add('translate-y-full');
            }
        }

        // Search Filter Logic
        function filterSettings() {
            const query = document.getElementById('settings-search').value.toLowerCase();
            const items = document.querySelectorAll('.setting-item');
            
            items.forEach(item => {
                const text = item.innerText.toLowerCase();
                item.style.display = text.includes(query) ? 'flex' : 'none';
            });
        }

        function filterApps() {
            const query = document.getElementById('app-search').value.toLowerCase();
            const items = document.querySelectorAll('.app-item');
            
            items.forEach(item => {
                const text = item.innerText.toLowerCase();
                item.style.display = text.includes(query) ? 'flex' : 'none';
            });
        }

        // App Launch Simulation
        function openApp(appName) {
            const modal = document.getElementById('app-modal');
            document.getElementById('modal-app-title').innerText = appName;
            document.getElementById('modal-inner-title').innerText = `${appName} Active`;
            document.getElementById('modal-inner-desc').innerText = `Running smoothly on ${currentSpecs.deviceName}.`;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeAppModal() {
            const modal = document.getElementById('app-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Secret Triple Tap to Open Stealth Editor Modal
        function handleSecretTap() {
            tapCount++;
            clearTimeout(tapTimer);
            if (tapCount >= 3) {
                tapCount = 0;
                openStealthModal();
            } else {
                tapTimer = setTimeout(() => { tapCount = 0; }, 800);
            }
        }

        function openStealthModal() {
            populateSpecsToModalInputs();
            const modal = document.getElementById('stealth-editor-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            showToast("Stealth Editor Opened!");
        }

        function closeStealthModal() {
            const modal = document.getElementById('stealth-editor-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Load & Render Specifications
        function loadSavedSpecs() {
            const saved = localStorage.getItem('op_custom_specs');
            if (saved) {
                try {
                    currentSpecs = JSON.parse(saved);
                } catch(e) {
                    console.error("Failed to parse saved specs", e);
                }
            }
            renderSpecsToUI();
        }

        function renderSpecsToUI() {
            // About Device Main Texts
            document.getElementById('about-device-name').innerText = currentSpecs.deviceName;
            document.getElementById('about-model-name').innerText = currentSpecs.modelName;
            document.getElementById('about-processor').innerText = currentSpecs.processor;
            document.getElementById('about-ram').innerText = currentSpecs.ram;
            document.getElementById('about-storage').innerText = currentSpecs.storage;
            document.getElementById('about-battery').innerText = currentSpecs.battery;
            document.getElementById('about-display').innerText = currentSpecs.display;
            document.getElementById('about-camera').innerText = currentSpecs.camera || "50MP Hasselblad Triple Camera";

            document.getElementById('about-oxygen-ver').innerText = currentSpecs.oxygenVer || "OxygenOS 14.0";
            document.getElementById('about-android-ver').innerText = `Official Version | ${currentSpecs.androidVer || "Android 14"}`;

            // Warranty Card
            document.getElementById('about-warranty-date').innerText = currentSpecs.warrantyDate || "Dec 28, 2026";
            document.getElementById('about-serial-no').innerText = currentSpecs.serialNo || "OP12984X7721";

            // Regulatory Sub-page
            document.getElementById('regulatory-imei1').innerText = currentSpecs.imei1 || "864902061234567";
            document.getElementById('regulatory-imei2').innerText = currentSpecs.imei2 || "864902061234568";

            // Version details build no
            document.getElementById('version-build-no').innerText = `${currentSpecs.modelName || 'CPH2581'}_14.0.0.604(EX01)`;

            // Home & Settings Subtitles
            document.getElementById('home-device-sub').innerText = `${currentSpecs.deviceName} • ${currentSpecs.ram}`;
            document.getElementById('settings-about-subtitle').innerText = `${currentSpecs.deviceName} • ${currentSpecs.ram} • ${currentSpecs.storage}`;
        }

        function populateSpecsToModalInputs() {
            document.getElementById('edit-device-name').value = currentSpecs.deviceName;
            document.getElementById('edit-model-name').value = currentSpecs.modelName;
            document.getElementById('edit-processor').value = currentSpecs.processor;
            document.getElementById('edit-ram').value = currentSpecs.ram;
            document.getElementById('edit-storage').value = currentSpecs.storage;
            document.getElementById('edit-battery').value = currentSpecs.battery;
            document.getElementById('edit-display').value = currentSpecs.display;
            document.getElementById('edit-warranty-date').value = currentSpecs.warrantyDate || "Dec 28, 2026";
            document.getElementById('edit-serial-no').value = currentSpecs.serialNo || "OP12984X7721";
            document.getElementById('edit-imei1').value = currentSpecs.imei1 || "864902061234567";
        }

        function loadPresetModel(key) {
            if (ONEPLUS_PRESETS[key]) {
                currentSpecs = { ...ONEPLUS_PRESETS[key] };
                populateSpecsToModalInputs();
                showToast(`Loaded ${currentSpecs.deviceName} Preset`);
            }
        }

        function saveStealthSpecs() {
            currentSpecs.deviceName = document.getElementById('edit-device-name').value;
            currentSpecs.modelName = document.getElementById('edit-model-name').value;
            currentSpecs.processor = document.getElementById('edit-processor').value;
            currentSpecs.ram = document.getElementById('edit-ram').value;
            currentSpecs.storage = document.getElementById('edit-storage').value;
            currentSpecs.battery = document.getElementById('edit-battery').value;
            currentSpecs.display = document.getElementById('edit-display').value;
            currentSpecs.warrantyDate = document.getElementById('edit-warranty-date').value;
            currentSpecs.serialNo = document.getElementById('edit-serial-no').value;
            currentSpecs.imei1 = document.getElementById('edit-imei1').value;

            localStorage.setItem('op_custom_specs', JSON.stringify(currentSpecs));
            renderSpecsToUI();
            closeStealthModal();
            showToast("Specifications Saved!");
        }

        function resetSpecifications() {
            localStorage.removeItem('op_custom_specs');
            currentSpecs = { ...ONEPLUS_PRESETS.op12 };
            document.getElementById('modal-model-presets').value = 'op12';
            populateSpecsToModalInputs();
            renderSpecsToUI();
            closeStealthModal();
            showToast("Reset to OnePlus 12 Defaults!");
        }

        // Toast Feedback Popup
        function showToast(msg) {
            const toast = document.createElement('div');
            toast.className = 'fixed bottom-14 left-1/2 -translate-x-1/2 bg-oneplus-red text-white text-xs font-bold px-4 py-2 rounded-full shadow-2xl z-50 transition transform duration-300 border border-white/20';
            toast.innerText = msg;
            document.body.appendChild(toast);
            setTimeout(() => {
                toast.remove();
            }, 2500);
        }
    </script>
</body>
</html>
