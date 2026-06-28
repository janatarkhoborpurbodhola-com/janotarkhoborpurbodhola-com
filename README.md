# janotarkhoborpurbodhola-com


<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>দৈনিক জনতার খবর | সত্যের সন্ধানে প্রতিনিয়ত</title>
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Galada&family=Hind+Siliguri:wght@400;600;700&display=swap');
        body {
            font-family: 'Hind Siliguri', sans-serif;
        }
        .logo-font {
            font-family: 'Galada', cursive;
        }
        /* Custom dark mode override */
        .dark-mode {
            background-color: #121212;
            color: #e0e0e0;
        }
        .dark-mode .bg-white {
            background-color: #1e1e1e !important;
            color: #ffffff;
        }
        .dark-mode .text-gray-700 {
            color: #cbd5e1 !important;
        }
        .dark-mode .text-gray-600 {
            color: #94a3b8 !important;
        }
        .dark-mode .border-b {
            border-color: #334155 !important;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 transition-colors duration-300" id="body">

    <!-- Top Utility Bar -->
    <div class="bg-slate-900 text-gray-300 text-xs py-2 px-4 flex justify-between items-center">
        <div>
            <i class="far fa-calendar-alt mr-1"></i> রবিবার, ২৮ জুন, ২০২৬
        </div>
        <div class="flex items-center space-x-4">
            <button onclick="toggleDarkMode()" class="hover:text-amber-400 text-sm focus:outline-none" title="ডার্ক মোড">
                <i class="fas fa-moon" id="theme-icon"></i> ডার্ক মোড
            </button>
            <span class="hidden md:inline">|</span>
            <div class="hidden md:flex space-x-3">
                <a href="#" class="hover:text-white">EN</a>
                <a href="https://www.facebook.com/share/1F6GYCfHFy/" target="_blank" class="hover:text-blue-400"><i class="fab fa-facebook-f"></i></a>
                <a href="#" class="hover:text-green-400"><i class="fab fa-whatsapp"></i></a>
            </div>
        </div>
    </div>

    <!-- Main Header & Logo -->
    <header class="bg-white border-b py-4 px-4 shadow-sm">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4">
            <!-- Website Logo -->
            <div class="flex items-center">
                <a href="#">
                    <img src="36901.png" alt="দৈনিক জনতার খবর" class="h-16 md:h-20 object-contain mx-auto">
                </a>
            </div>
            <!-- Header Ad Banner (Placeholder) -->
            <div class="w-full md:w-auto bg-gray-100 dark:bg-zinc-800 border border-dashed border-gray-300 p-4 text-center text-xs text-gray-400 rounded">
                <span class="block text-[10px] uppercase tracking-wider text-gray-400">বিজ্ঞাপন স্থান</span>
                Google AdSense / ব্যানার বিজ্ঞাপন (728x90)
            </div>
        </div>
    </header>

    <!-- Navigation Bar -->
    <nav class="bg-red-700 text-white sticky top-0 z-50 shadow-md">
        <div class="max-w-7xl mx-auto flex justify-between items-center px-4">
            <div class="flex items-center space-x-1 overflow-x-auto whitespace-nowrap scrollbar-none py-1">
                <a href="#" class="px-3 py-2 bg-red-800 font-bold rounded"><i class="fas fa-home"></i> হোম</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">জাতীয়</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">রাজনীতি</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">আন্তর্জাতিক</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">খেলাধুলা</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">বিনোদন</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">তথ্যপ্রযুক্তি</a>
                <a href="#" class="px-3 py-2 hover:bg-red-600 transition">চাকরির খবর</a>
            </div>
            <div class="p-2">
                <button class="hover:text-gray-200 p-1"><i class="fas fa-search"></i></button>
            </div>
        </div>
    </nav>

    <!-- Breaking News Ticker -->
    <div class="bg-amber-100 dark:bg-amber-950 border-b border-amber-200 py-2 px-4">
        <div class="max-w-7xl mx-auto flex items-center">
            <span class="bg-red-600 text-white px-2 py-0.5 text-xs font-bold rounded-sm mr-3 animate-pulse whitespace-nowrap">ব্রেকিং নিউজ</span>
            <marquee class="text-sm text-amber-900 dark:text-amber-100" behavior="scroll" direction="left" scrollamount="6">
                সারাদেশে আবহাওয়ার বড় পরিবর্তন, ভারী বর্ষণের পূর্বাভাস... | দৈনিক জনতার খবর-এর নতুন ডিজিটাল সংস্করণ চালু... | পূর্বধলায় নতুন আইটি সেন্টারের শুভ উদ্বোধন...
            </marquee>
        </div>
    </div>

    <!-- Main Content Grid -->
    <main class="max-w-7xl mx-auto px-4 py-6 grid grid-cols-1 lg:grid-cols-3 gap-6">
        
        <!-- Left & Center: News Sections (2 Columns on large screens) -->
        <div class="lg:col-span-2 space-y-6">
            
            <!-- Featured News Area -->
            <div class="bg-white p-4 rounded-lg shadow-sm border">
                <span class="text-xs font-bold text-red-600 uppercase border-b-2 border-red-600 pb-1 mb-3 inline-block">শীর্ষ সংবাদ</span>
                <div class="space-y-3">
                    <div class="w-full h-64 md:h-96 bg-gray-200 rounded overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1504711434969-e33886168f5c?auto=format&fit=crop&w=800&q=80" alt="News" class="w-full h-full object-cover">
                    </div>
                    <h1 class="text-2xl md:text-3xl font-bold hover:text-red-600 cursor-pointer transition">ডিজিটাল প্রযুক্তির ছোঁয়ায় বদলে যাচ্ছে গ্রামীণ অর্থনীতি: নেত্রকোনায় নতুন সম্ভাবনা</h1>
                    <p class="text-gray-600 text-sm line-clamp-3">
                        বর্তমান সময়ে প্রযুক্তির প্রসার গ্রাম ছাড়িয়ে মফস্বল শহরগুলোতেও বিপুল সাড়া জাগিয়েছে। বিশেষ করে তরুণ উদ্যোক্তারা এখন ঘরে বসেই বিভিন্ন তথ্য ও সেবামূলক প্ল্যাটফর্ম তৈরি করছেন, যা স্থানীয় মানুষের জীবনযাত্রাকে সহজ করে তুলছে...
                    </p>
                    <div class="text-xs text-gray-400 flex items-center space-x-2">
                        <span><i class="far fa-user"></i> বিশেষ প্রতিবেদক</span>
                        <span>•</span>
                        <span><i class="far fa-clock"></i> ৫ মিনিট আগে</span>
                    </div>
                </div>
            </div>

            <!-- Category Based Grid -->
            <div>
                <h3 class="text-lg font-bold border-b-2 border-red-600 pb-1 mb-4 flex justify-between items-center">
                    <span><i class="fas fa-th-large text-red-600 mr-1"></i> সর্বশেষ সংবাদ</span>
                    <a href="#" class="text-xs text-red-600 hover:underline">সব দেখুন</a>
                </h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <!-- News Card 1 -->
                    <div class="bg-white p-3 rounded border flex space-x-3">
                        <div class="w-1/3 h-24 bg-gray-200 rounded overflow-hidden flex-shrink-0">
                            <img src="https://images.unsplash.com/photo-1526470608268-f674ce90ebd4?auto=format&fit=crop&w=300&q=80" class="w-full h-full object-cover">
                        </div>
                        <div class="w-2/3 flex flex-col justify-between">
                            <h4 class="font-bold text-sm hover:text-red-600 line-clamp-2 cursor-pointer">পূর্বধলা হসপিটাল গেইট এলাকায় নতুন আধুনিক তথ্য সেবাকেন্দ্র চালু</h4>
                            <span class="text-[11px] text-gray-400">১০ মিনিট আগে</span>
                        </div>
                    </div>
                    <!-- News Card 2 -->
                    <div class="bg-white p-3 rounded border flex space-x-3">
                        <div class="w-1/3 h-24 bg-gray-200 rounded overflow-hidden flex-shrink-0">
                            <img src="https://images.unsplash.com/photo-1470229722913-7c0e2dbbafd3?auto=format&fit=crop&w=300&q=80" class="w-full h-full object-cover">
                        </div>
                        <div class="w-2/3 flex flex-col justify-between">
                            <h4 class="font-bold text-sm hover:text-red-600 line-clamp-2 cursor-pointer">ঐতিহ্যবাহী লোকসংগীত উৎসবের আয়োজন: অংশ নেবেন দেশসেরা শিল্পীবৃন্দ</h4>
                            <span class="text-[11px] text-gray-400">১ ঘণ্টা আগে</span>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- Right: Sidebar (1 Column) -->
        <div class="space-y-6">
            
            <!-- Social Share / Wallet Promo Widgets -->
            <div class="bg-white p-4 rounded-lg shadow-sm border text-center">
                <h3 class="font-bold text-gray-800 mb-3 text-sm">আমাদের সোশ্যাল মিডিয়ায় ফলো করুন</h3>
                <div class="flex justify-center space-x-3">
                    <a href="https://www.facebook.com/share/1F6GYCfHFy/" target="_blank" class="w-10 h-10 rounded-full bg-blue-600 text-white flex items-center justify-center hover:bg-blue-700 transition">
                        <i class="fab fa-facebook-f"></i>
                    </a>
                    <a href="#" class="w-10 h-10 rounded-full bg-green-500 text-white flex items-center justify-center hover:bg-green-600 transition">
                        <i class="fab fa-whatsapp"></i>
                    </a>
                    <a href="#" class="w-10 h-10 rounded-full bg-sky-400 text-white flex items-center justify-center hover:bg-sky-500 transition">
                        <i class="fab fa-twitter"></i>
                    </a>
                </div>
            </div>

            <!-- Popular / Most Read News -->
            <div class="bg-white p-4 rounded-lg shadow-sm border">
                <h3 class="font-bold text-base border-b pb-2 mb-3 text-red-600"><i class="fas fa-fire mr-1"></i> সর্বাধিক পঠিত</h3>
                <ul class="space-y-3 text-sm divide-y divide-gray-100">
                    <li class="pt-2 first:pt-0">
                        <a href="#" class="hover:text-red-600 font-medium line-clamp-2">১. নেত্রকোনার বিভিন্ন উপজেলার আজকের আবহাওয়ার খবর ও তাপমাত্রা</a>
                    </li>
                    <li class="pt-2">
                        <a href="#" class="hover:text-red-600 font-medium line-clamp-2">২. ফ্রিল্যান্সিং শুরু করার সহজ গাইডলাইন ও দরকারি টিপস</a>
                    </li>
                    <li class="pt-2">
                        <a href="#" class="hover:text-red-600 font-medium line-clamp-2">৩. বাজারে সোনার দাম আবারো রেকর্ড পরিবর্তন, জেনে নিন আজকের রেট</a>
                    </li>
                </ul>
            </div>

            <!-- Sidebar Ad Box -->
            <div class="bg-gray-100 dark:bg-zinc-800 border border-dashed border-gray-300 p-6 text-center text-xs text-gray-400 rounded h-64 flex flex-col justify-center items-center">
                <span class="block text-[10px] uppercase tracking-wider text-gray-400 mb-2">বিজ্ঞাপন স্থান</span>
                300x250 Banner Ad
            </div>

        </div>

    </main>

    <!-- Footer Area -->
    <footer class="bg-slate-900 text-gray-400 pt-10 pb-6 px-4 mt-12 border-t-4 border-red-600">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 text-sm">
            
            <!-- About Section -->
            <div>
                <!-- Brand logo inversion for dark footer -->
                <img src="36901.png" alt="দৈনিক জনতার খবর" class="h-14 object-contain mb-4 bg-white p-1 rounded">
                <p class="leading-relaxed">
                    দৈনিক জনতার খবর একটি সত্যনিষ্ঠ ও নিরপেক্ষ অনলাইন সংবাদ মাধ্যম। আমরা প্রতিনিয়ত বস্তুনিষ্ঠ সংবাদ প্রকাশে অঙ্গীকারাবদ্ধ।
                </p>
            </div>

            <!-- Quick Links -->
            <div>
                <h4 class="text-white font-bold text-base mb-4 border-l-4 border-red-600 pl-2">প্রয়োজনীয় লিংক</h4>
                <ul class="space-y-2 grid grid-cols-2">
                    <li><a href="#" class="hover:text-white transition">আমাদের সম্পর্কে</a></li>
                    <li><a href="#" class="hover:text-white transition">যোগাযোগ পৃষ্ঠা</a></li>
                    <li><a href="#" class="hover:text-white transition">গোপনীয়তা নীতি</a></li>
                    <li><a href="#" class="hover:text-white transition">ব্যবহারের শর্তাবলী</a></li>
                </ul>
            </div>

            <!-- Contact Information -->
            <div>
                <h4 class="text-white font-bold text-base mb-4 border-l-4 border-red-600 pl-2">যোগাযোগ</h4>
                <ul class="space-y-3">
                    <li class="flex items-start">
                        <i class="fas fa-map-marker-alt text-red-500 mt-1 mr-2 w-4 text-center"></i>
                        <span>পূর্বধলা হসপিটাল গেইট, পূর্বধলা, নেত্রকোনা।</span>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-phone-alt text-red-500 mr-2 w-4 text-center"></i>
                        <a href="tel:01930242007" class="hover:text-white">01930242007</a>
                    </li>
                    <li class="flex items-center">
                        <i class="fas fa-envelope text-red-500 mr-2 w-4 text-center"></i>
                        <a href="mailto:seyam2858@gmail.com" class="hover:text-white">seyam2858@gmail.com</a>
                    </li>
                </ul>
            </div>

        </div>

        <hr class="border-gray-800 my-6">

        <!-- Copyright Info -->
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center text-xs gap-2">
            <p>&copy; ২০২৬ দৈনিক জনতার খবর। সর্বস্বত্ব সংরক্ষিত।</p>
            <p>কারিগরি সহায়তায়: <a href="#" class="text-red-500 font-bold">Seyam</a></p>
        </div>
    </footer>

    <!-- Toggle Dark Mode Script -->
    <script>
        function toggleDarkMode() {
            const body = document.getElementById('body');
            const icon = document.getElementById('theme-icon');
            body.classList.toggle('dark-mode');
            
            if(body.classList.contains('dark-mode')) {
                icon.classList.replace('fa-moon', 'fa-sun');
            } else {
                icon.classList.replace('fa-sun', 'fa-moon');
            }
        }
    </script>
</body>
</html> 