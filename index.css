<!-- Main Map Dashboard -->
<!DOCTYPE html>

<html lang="ko"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#400200",
              "tertiary-fixed-dim": "#ffb4a6",
              "secondary-fixed": "#6ffe93",
              "tertiary-fixed": "#ffdad4",
              "on-tertiary-container": "#fffbff",
              "surface-variant": "#e0e3e6",
              "surface-container-low": "#f2f4f7",
              "error": "#ba1a1a",
              "on-secondary-container": "#007433",
              "surface": "#f7f9fc",
              "tertiary-container": "#d2412b",
              "outline-variant": "#c1c6d7",
              "background": "#f7f9fc",
              "on-secondary-fixed-variant": "#005322",
              "inverse-primary": "#afc6ff",
              "surface-container": "#eceef1",
              "surface-bright": "#f7f9fc",
              "surface-tint": "#0059c7",
              "on-tertiary-fixed-variant": "#900f01",
              "primary-fixed": "#d9e2ff",
              "surface-dim": "#d8dadd",
              "primary": "#0057c2",
              "on-error-container": "#93000a",
              "primary-container": "#006ef2",
              "secondary-fixed-dim": "#4fe17a",
              "secondary": "#006d30",
              "on-secondary": "#ffffff",
              "on-surface": "#191c1e",
              "on-primary-fixed": "#001a43",
              "on-primary-container": "#fefcff",
              "inverse-on-surface": "#eff1f4",
              "surface-container-lowest": "#ffffff",
              "secondary-container": "#6ffe93",
              "on-surface-variant": "#414755",
              "error-container": "#ffdad6",
              "on-primary-fixed-variant": "#004398",
              "on-secondary-fixed": "#00210a",
              "inverse-surface": "#2d3133",
              "surface-container-high": "#e6e8eb",
              "on-error": "#ffffff",
              "on-background": "#191c1e",
              "tertiary": "#af2815",
              "surface-container-highest": "#e0e3e6",
              "on-primary": "#ffffff",
              "primary-fixed-dim": "#afc6ff",
              "outline": "#727786",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Inter", "Pretendard", "sans-serif"],
              "body": ["Inter", "Pretendard", "sans-serif"],
              "label": ["Inter", "Pretendard", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Inter', 'Pretendard', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface overflow-hidden">
<!-- Top Navigation Bar -->
<header class="fixed top-0 w-full flex justify-between items-center px-6 py-3 h-16 bg-white/80 dark:bg-slate-900/80 backdrop-blur-xl z-50 shadow-sm">
<div class="flex items-center gap-8">
<span class="text-xl font-bold bg-gradient-to-r from-[#0057c2] to-[#006ef2] bg-clip-text text-transparent">Digital Cartographer</span>
<nav class="hidden md:flex items-center gap-6 font-['Pretendard'] text-sm font-medium tracking-tight">
<a class="text-[#0057c2] dark:text-blue-400 font-bold border-b-2 border-[#0057c2] pb-1" href="#">Map</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">Favorites</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">My Listings</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">Support</a>
</nav>
</div>
<div class="flex items-center gap-4">
<button class="p-2 text-on-surface-variant hover:bg-slate-50 rounded-full transition-all">
<span class="material-symbols-outlined" data-icon="notifications">notifications</span>
</button>
<button class="p-2 text-on-surface-variant hover:bg-slate-50 rounded-full transition-all">
<span class="material-symbols-outlined" data-icon="settings">settings</span>
</button>
<div class="w-8 h-8 rounded-full overflow-hidden border border-outline-variant/30">
<img alt="User avatar" data-alt="professional headshot of a smiling male real estate agent with a clean blurred background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC5uvyEZBgN7RRb7Iou9Co9B5h_pNoWtWhak97IrazFiA6S2sLeq95IxrT2kc1WGOgvWK8s8A2f_NAm4K33HFMXCw1tYN5Th8ou925dUUthZfa7TEX5hmVD_qNcY9A657OJKPZ1dcjQ2RhJwOp8dFP1vI3BQn1AuF15nvy7VnHtvyEYVMUmhUFokF2bY5yEmjCn2uVf0xToHBqUEmkifeNVbXFpN-DF_arFdGyf0difYTv7fLn8Q5pM350VISKtVo9Cy70TYjcYyEir"/>
</div>
</div>
</header>
<main class="flex h-screen pt-16">
<!-- Sidebar: Property Listings -->
<aside class="w-96 bg-surface-container-low flex flex-col z-40 shadow-xl overflow-hidden">
<!-- Search & Filters -->
<div class="p-5 bg-surface-container-lowest flex flex-col gap-4 shadow-sm">
<div class="relative group">
<span class="material-symbols-outlined absolute left-4 top-1/2 -translate-y-1/2 text-on-surface-variant">search</span>
<input class="w-full pl-12 pr-4 py-3 bg-surface-container-high border-none rounded-xl text-on-surface placeholder:text-on-surface-variant focus:ring-2 focus:ring-primary transition-all" placeholder="Search by location, apartment name..." type="text"/>
</div>
<div class="flex gap-2 overflow-x-auto pb-1 no-scrollbar">
<button class="px-4 py-1.5 bg-primary text-on-primary rounded-full text-sm font-semibold whitespace-nowrap">Sale</button>
<button class="px-4 py-1.5 bg-surface-container-highest text-on-surface-variant rounded-full text-sm font-medium whitespace-nowrap hover:bg-primary-fixed/30 transition-colors">Jeonse</button>
<button class="px-4 py-1.5 bg-surface-container-highest text-on-surface-variant rounded-full text-sm font-medium whitespace-nowrap hover:bg-primary-fixed/30 transition-colors">Rent</button>
<button class="px-4 py-1.5 bg-surface-container-highest text-on-surface-variant rounded-full text-sm font-medium whitespace-nowrap hover:bg-primary-fixed/30 transition-colors">Price</button>
</div>
</div>
<!-- List Area -->
<div class="flex-1 overflow-y-auto p-4 space-y-4">
<p class="text-xs font-bold text-on-surface-variant uppercase tracking-widest px-1">Nearby Listings (124)</p>
<!-- Selected Listing Card -->
<div class="bg-surface-container-lowest rounded-xl p-3 shadow-md ring-2 ring-primary relative group cursor-pointer">
<div class="flex gap-4">
<div class="w-24 h-24 rounded-lg overflow-hidden flex-shrink-0">
<img class="w-full h-full object-cover" data-alt="modern minimalist apartment interior with floor to ceiling windows and warm wooden floors" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDpRVGDFX78u8CRRb11Ud62yNN5wfJf1WihT-sdcf_cITsoHxRaMPtOLe8v21eCtNHLnfQbyjYjxxVX_lM1D0hcdnL8OxaYhyWVijU9wHyZEXwvE0vwtMV6yQ5jFdI_fPZkx8Oxvrbfi5BVx6ibvDaaPzaLEhRNXKgvLmy_yGJZSjqXMSrVz8tqWyKF-Z1DofRPnc3CZ_gHWTzLJiqeCo-MIQailKRctZSdrPr48bja1qHkj9t4gL67ZLjpCmQfsaBZYjeGoJGTqHc3"/>
</div>
<div class="flex-1">
<div class="flex justify-between items-start">
<span class="text-primary font-bold text-lg">₩ 1.25B</span>
<span class="material-symbols-outlined text-primary" style="font-variation-settings: 'FILL' 1;">bookmark</span>
</div>
<h3 class="font-semibold text-on-surface leading-tight mt-1">Acme Heights Apt. 104</h3>
<div class="text-xs text-on-surface-variant mt-1">24F · 84m² · Gangnam-gu</div>
<div class="mt-2 flex gap-2">
<span class="text-[10px] bg-secondary-container text-on-secondary-container px-2 py-0.5 rounded font-bold">AVAILABLE</span>
<span class="text-[10px] bg-tertiary-container text-on-tertiary-container px-2 py-0.5 rounded font-bold">ENDING SOON</span>
</div>
</div>
</div>
</div>
<!-- Standard Card 1 -->
<div class="bg-surface-container-lowest rounded-xl p-3 hover:shadow-lg transition-all cursor-pointer group">
<div class="flex gap-4">
<div class="w-24 h-24 rounded-lg overflow-hidden flex-shrink-0 grayscale group-hover:grayscale-0 transition-all">
<img class="w-full h-full object-cover" data-alt="contemporary living room with designer furniture and neutral color palette soft natural lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDjqvWENOmM0YX_J_Ue46KVkwTRjOExiWPAwQsjebBPEzY58WX3mBA_kUvbLjFrf8g34lAOQN6uf9DHz7Y-8LrE2eSusHi3FedlKWI888WJhAf33c4LyE4REjZrc3u9cpC0jINY8syfyn5ZVpV_odrdIgZ-fssc704C13YbGDD-_c4zdcwspzqr6cQ9t9KjWQcymZopzb76mQUDgjxb87MwwsZ2dXN9MqRX2FHrnTcTKQK8ydBtdfDoikk5v27LslTWm_Mqc9T-EWQH"/>
</div>
<div class="flex-1">
<div class="flex justify-between items-start">
<span class="text-on-surface font-bold text-lg">₩ 840M</span>
<span class="material-symbols-outlined text-outline">bookmark</span>
</div>
<h3 class="font-semibold text-on-surface leading-tight mt-1">Silver Tower 1201</h3>
<div class="text-xs text-on-surface-variant mt-1">12F · 59m² · Seocho-gu</div>
</div>
</div>
</div>
<!-- Standard Card 2 -->
<div class="bg-surface-container-lowest rounded-xl p-3 hover:shadow-lg transition-all cursor-pointer group">
<div class="flex gap-4">
<div class="w-24 h-24 rounded-lg overflow-hidden flex-shrink-0 grayscale group-hover:grayscale-0 transition-all">
<img class="w-full h-full object-cover" data-alt="clean bright kitchen in a modern high-rise apartment with white cabinets and marble counters" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBaXZ-GR3DTgsGEOcnJOLx8ibGG2N_yp9tLNZep8mEkshsq7dS3EyKwlAWtT-J0Sy7kxeBKJTxitdcY1Ft4l2LQUzCkd7dBhWBSC1pu1OlIFwsKeN1u1Pw-uAs3xZpVVVSOAVwA9lvz0FBT9ZzEMZOZaYHIVk94uGeoONBtXlmc45jyI_QDEvPthirN23tQbSSml-w0s9R6OdD99NJOYbwq3YEAKQ-3uLoSISpcFsEuS7-_x6iAz072WAWGFJDyR24C5OZ6MJMkKxS7"/>
</div>
<div class="flex-1">
<div class="flex justify-between items-start">
<span class="text-on-surface font-bold text-lg">₩ 1.12B</span>
<span class="material-symbols-outlined text-outline">bookmark</span>
</div>
<h3 class="font-semibold text-on-surface leading-tight mt-1">Parkside Residence</h3>
<div class="text-xs text-on-surface-variant mt-1">8F · 102m² · Songpa-gu</div>
</div>
</div>
</div>
<!-- Standard Card 3 -->
<div class="bg-surface-container-lowest rounded-xl p-3 hover:shadow-lg transition-all cursor-pointer group">
<div class="flex gap-4">
<div class="w-24 h-24 rounded-lg overflow-hidden flex-shrink-0 grayscale group-hover:grayscale-0 transition-all">
<img class="w-full h-full object-cover" data-alt="warm cozy studio apartment interior with plants and artistic decor elements" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDAaxbQHapC7mMypeRlVi7vpYn2Is3EY_5KS1al4-S8yxWxhCdwGxu9ocMMdfm6c7NK0R-PSc9PI16ZZbFq2NnHh_UMXROcUK_PYyrSWtfR8QermaPYOPdEZDjM1PuG5FscGodBlgWrVBdwir-dFv3iE5oOz_4zLRC96BuwVyzycxnYXJQDj3NKxluDEBgy0odDOkkx7SvEGH6hn7fKmlc1Cx0eWZogtUOaXwno_SLzLDouzuIX5qMUG9RBAzmAveQWp-_nXnP836bo"/>
</div>
<div class="flex-1">
<div class="flex justify-between items-start">
<span class="text-on-surface font-bold text-lg">₩ 650M</span>
<span class="material-symbols-outlined text-outline">bookmark</span>
</div>
<h3 class="font-semibold text-on-surface leading-tight mt-1">The Oasis Studio</h3>
<div class="text-xs text-on-surface-variant mt-1">3F · 42m² · Mapo-gu</div>
</div>
</div>
</div>
</div>
</aside>
<!-- Map Area -->
<section class="flex-1 relative bg-slate-200 overflow-hidden">
<!-- Simulated Map Image -->
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover opacity-60 mix-blend-multiply" data-alt="top down satellite map view of a dense urban area with streets and buildings in cool tones" data-location="Seoul" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBn3ISmk6MWEFoEy7JmlMfO9pjkK476-8iCRqfWland8aNf2SzTGntNy7oiWT9NPgJX-0BJow5pv2NL57XYbEm7ul4cC-O4_ijhEZ0fv4-DogNMDbmRSHOfHdbABd0A4gYbwgjjJda8IqI8BjkAc83ldvHQXgC5BKVaZuQbG8_6gj2dV6iO36A9P_OqHMhNG_wpsaw94jwQ_-m6Ugnv1UDBoB8OLRrtZe6Ec9lIxzy11aJbCn11f6cxaA4XcK8mhzgtu6bP36GRaqBw"/>
<div class="absolute inset-0 bg-primary/5"></div>
</div>
<!-- Map Markers -->
<!-- Highlighted Marker -->
<div class="absolute top-[40%] left-[45%] z-20 group">
<div class="relative flex flex-col items-center">
<div class="bg-primary text-on-primary px-3 py-1.5 rounded-full font-bold text-sm shadow-xl scale-125 transition-transform origin-bottom">
                        1.25B
                    </div>
<div class="w-3 h-3 bg-primary rounded-full mt-1 border-2 border-white animate-pulse"></div>
<div class="absolute -inset-4 bg-primary/20 rounded-full -z-10 blur-md"></div>
</div>
</div>
<!-- Normal Marker 1 -->
<div class="absolute top-[30%] left-[60%] z-10">
<div class="flex flex-col items-center cursor-pointer">
<div class="bg-white text-on-surface px-3 py-1.5 rounded-full font-bold text-sm shadow-lg hover:bg-primary-fixed transition-colors">
                        840M
                    </div>
<div class="w-2.5 h-2.5 bg-white rounded-full mt-1 border border-primary/20"></div>
</div>
</div>
<!-- Normal Marker 2 -->
<div class="absolute top-[55%] left-[30%] z-10">
<div class="flex flex-col items-center cursor-pointer">
<div class="bg-white text-on-surface px-3 py-1.5 rounded-full font-bold text-sm shadow-lg hover:bg-primary-fixed transition-colors">
                        1.12B
                    </div>
<div class="w-2.5 h-2.5 bg-white rounded-full mt-1 border border-primary/20"></div>
</div>
</div>
<!-- Normal Marker 3 -->
<div class="absolute top-[20%] left-[25%] z-10">
<div class="flex flex-col items-center cursor-pointer">
<div class="bg-white text-on-surface px-3 py-1.5 rounded-full font-bold text-sm shadow-lg hover:bg-primary-fixed transition-colors">
                        650M
                    </div>
<div class="w-2.5 h-2.5 bg-white rounded-full mt-1 border border-primary/20"></div>
</div>
</div>
<!-- Map Tools Floating Controls -->
<div class="absolute bottom-8 right-8 flex flex-col gap-3 z-30">
<div class="bg-white/80 backdrop-blur-xl rounded-2xl shadow-2xl p-1 flex flex-col">
<button class="p-3 text-on-surface hover:bg-primary-fixed/30 rounded-xl transition-colors">
<span class="material-symbols-outlined" data-icon="add">add</span>
</button>
<div class="h-px bg-outline-variant/30 mx-2"></div>
<button class="p-3 text-on-surface hover:bg-primary-fixed/30 rounded-xl transition-colors">
<span class="material-symbols-outlined" data-icon="remove">remove</span>
</button>
</div>
<button class="bg-white/80 backdrop-blur-xl p-4 rounded-2xl shadow-2xl text-primary hover:bg-primary hover:text-white transition-all group">
<span class="material-symbols-outlined" data-icon="my_location">my_location</span>
</button>
<button class="bg-white/80 backdrop-blur-xl px-4 py-3 rounded-2xl shadow-2xl flex items-center gap-2 text-on-surface font-semibold text-sm hover:bg-slate-50 transition-all">
<span class="material-symbols-outlined" data-icon="layers">layers</span>
<span>Satellite</span>
</button>
</div>
<!-- Current Map Location Tooltip -->
<div class="absolute top-6 left-6 z-30">
<div class="bg-white/90 backdrop-blur-md px-4 py-2 rounded-full shadow-lg border border-white flex items-center gap-2">
<div class="w-2 h-2 rounded-full bg-secondary"></div>
<span class="text-sm font-semibold">Showing results in Gangnam-gu, Seoul</span>
</div>
</div>
</section>
</main>
<!-- Side Navigation for Task-specific Management (Hidden by default but provided for JSON compliance) -->
<nav class="hidden fixed left-0 top-16 h-[calc(100vh-64px)] p-4 z-40 bg-[#f7f9fc] dark:bg-slate-950 w-72 flex-col border-r-0">
<div class="mb-8 px-4">
<h2 class="text-lg font-black text-[#191c1e] dark:text-white">Property Manager</h2>
<p class="text-xs text-on-surface-variant">Verified Partner</p>
</div>
<div class="space-y-2 flex-1">
<a class="flex items-center gap-3 bg-[#0057c2] text-white rounded-xl px-4 py-3 shadow-lg shadow-blue-500/20 font-semibold" href="#">
<span class="material-symbols-outlined" data-icon="map">map</span>
                Map Explorer
            </a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 transition-colors font-semibold" href="#">
<span class="material-symbols-outlined" data-icon="bookmark">bookmark</span>
                Saved Homes
            </a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 transition-colors font-semibold" href="#">
<span class="material-symbols-outlined" data-icon="dashboard_customize">dashboard_customize</span>
                Management
            </a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 transition-colors font-semibold" href="#">
<span class="material-symbols-outlined" data-icon="help">help</span>
                Help Center
            </a>
</div>
<button class="mt-auto bg-[#0057c2] text-white py-4 rounded-xl font-bold text-center shadow-lg hover:translate-x-1 duration-200">
            Add New Listing
        </button>
</nav>
</body></html>

<!-- Admin Dashboard -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Digital Cartographer | Property Manager Dashboard</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#400200",
              "tertiary-fixed-dim": "#ffb4a6",
              "secondary-fixed": "#6ffe93",
              "tertiary-fixed": "#ffdad4",
              "on-tertiary-container": "#fffbff",
              "surface-variant": "#e0e3e6",
              "surface-container-low": "#f2f4f7",
              "error": "#ba1a1a",
              "on-secondary-container": "#007433",
              "surface": "#f7f9fc",
              "tertiary-container": "#d2412b",
              "outline-variant": "#c1c6d7",
              "background": "#f7f9fc",
              "on-secondary-fixed-variant": "#005322",
              "inverse-primary": "#afc6ff",
              "surface-container": "#eceef1",
              "surface-bright": "#f7f9fc",
              "surface-tint": "#0059c7",
              "on-tertiary-fixed-variant": "#900f01",
              "primary-fixed": "#d9e2ff",
              "surface-dim": "#d8dadd",
              "primary": "#0057c2",
              "on-error-container": "#93000a",
              "primary-container": "#006ef2",
              "secondary-fixed-dim": "#4fe17a",
              "secondary": "#006d30",
              "on-secondary": "#ffffff",
              "on-surface": "#191c1e",
              "on-primary-fixed": "#001a43",
              "on-primary-container": "#fefcff",
              "inverse-on-surface": "#eff1f4",
              "surface-container-lowest": "#ffffff",
              "secondary-container": "#6ffe93",
              "on-surface-variant": "#414755",
              "error-container": "#ffdad6",
              "on-primary-fixed-variant": "#004398",
              "on-secondary-fixed": "#00210a",
              "inverse-surface": "#2d3133",
              "surface-container-high": "#e6e8eb",
              "on-error": "#ffffff",
              "on-background": "#191c1e",
              "tertiary": "#af2815",
              "surface-container-highest": "#e0e3e6",
              "on-primary": "#ffffff",
              "primary-fixed-dim": "#afc6ff",
              "outline": "#727786",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Inter", "sans-serif"],
              "body": ["Inter", "sans-serif"],
              "label": ["Inter", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface selection:bg-primary-fixed selection:text-on-primary-fixed">
<!-- Top Navigation Bar -->
<header class="fixed top-0 w-full flex justify-between items-center px-6 py-3 h-16 bg-white/80 dark:bg-slate-900/80 backdrop-blur-xl z-50 shadow-sm">
<div class="flex items-center gap-8">
<span class="text-xl font-bold bg-gradient-to-r from-[#0057c2] to-[#006ef2] bg-clip-text text-transparent font-['Pretendard']">Digital Cartographer</span>
<nav class="hidden md:flex gap-6 items-center">
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors font-['Pretendard'] text-sm font-medium tracking-tight" href="#">Map</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors font-['Pretendard'] text-sm font-medium tracking-tight" href="#">Favorites</a>
<a class="text-[#0057c2] dark:text-blue-400 font-bold border-b-2 border-[#0057c2] pb-1 font-['Pretendard'] text-sm tracking-tight" href="#">My Listings</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors font-['Pretendard'] text-sm font-medium tracking-tight" href="#">Support</a>
</nav>
</div>
<div class="flex items-center gap-4">
<button class="p-2 rounded-full hover:bg-slate-50 dark:hover:bg-slate-800/50 transition-all duration-200">
<span class="material-symbols-outlined text-on-surface-variant">notifications</span>
</button>
<button class="p-2 rounded-full hover:bg-slate-50 dark:hover:bg-slate-800/50 transition-all duration-200">
<span class="material-symbols-outlined text-on-surface-variant">settings</span>
</button>
<div class="h-8 w-8 rounded-full overflow-hidden border border-outline-variant/30">
<img alt="User avatar" data-alt="professional portrait of a male real estate agent in a blue suit with a friendly smile, clean studio background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAzO8YRATwiLDTGfgUqgnUUE-JsTJE7LZbtbLsqNlrKNy6ApL5iwC0hrAGvGZ31w0Sru72IaKTsHymb4QhYbGpowWVeQVsem_wKxL9r4Mewg8-DAJBmbGJ7AbqghzC8bhLUcB44jT7TBx1Ci1QB-F0vzUe26ss3BHgtLM03_I6XZbJUqWnrE6uQBLp5nSFma92ylqXTttWwTNbrKIT8nk-DIwqqPFBE9zmGr6x4KgQShNmV0RFQTcwKg5hJ52Ruzg2vpCF7D4rnk6IN"/>
</div>
</div>
</header>
<!-- Side Navigation Bar -->
<aside class="fixed left-0 top-16 h-[calc(100vh-64px)] w-72 flex flex-col p-4 z-40 bg-[#f7f9fc] dark:bg-slate-950">
<div class="mb-8 px-4 py-2">
<h2 class="text-lg font-black text-[#191c1e] dark:text-white font-['Pretendard']">Property Manager</h2>
<p class="text-on-surface-variant text-sm font-medium">Verified Partner</p>
</div>
<nav class="flex-1 space-y-2">
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors font-['Pretendard'] text-base font-semibold" href="#">
<span class="material-symbols-outlined">dashboard</span>
<span>Dashboard</span>
</a>
<a class="flex items-center gap-3 bg-[#0057c2] text-white rounded-xl px-4 py-3 shadow-lg shadow-blue-500/20 font-['Pretendard'] text-base font-semibold" href="#">
<span class="material-symbols-outlined">dashboard_customize</span>
<span>My Listings</span>
</a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors font-['Pretendard'] text-base font-semibold" href="#">
<span class="material-symbols-outlined">mail</span>
<span>Inquiries</span>
</a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors font-['Pretendard'] text-base font-semibold" href="#">
<span class="material-symbols-outlined">person</span>
<span>Account Settings</span>
</a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors font-['Pretendard'] text-base font-semibold" href="#">
<span class="material-symbols-outlined">help</span>
<span>Help Center</span>
</a>
</nav>
<div class="mt-auto p-2">
<button class="w-full flex items-center justify-center gap-2 py-4 bg-gradient-to-r from-[#0057c2] to-[#006ef2] text-white rounded-full font-bold shadow-lg shadow-primary/20 hover:scale-[1.02] active:scale-95 transition-all">
<span class="material-symbols-outlined">add</span>
<span>Add New Listing</span>
</button>
</div>
</aside>
<!-- Main Content Canvas -->
<main class="ml-72 mt-16 p-8 min-h-screen">
<div class="max-w-6xl mx-auto">
<!-- Page Header & Actions -->
<div class="flex flex-col md:flex-row md:items-end justify-between mb-8 gap-6">
<div>
<h1 class="text-3xl font-bold text-on-surface font-headline tracking-tight mb-2">My Listings</h1>
<p class="text-on-surface-variant text-lg">Manage and track your property portfolio performance.</p>
</div>
<div class="flex items-center gap-3">
<div class="relative group">
<span class="material-symbols-outlined absolute left-4 top-1/2 -translate-y-1/2 text-on-surface-variant group-focus-within:text-primary transition-colors">search</span>
<input class="pl-12 pr-6 py-3 bg-surface-container-lowest border-none rounded-full w-72 focus:ring-2 focus:ring-primary shadow-sm text-sm font-medium" placeholder="Search properties..." type="text"/>
</div>
<button class="flex items-center gap-2 px-5 py-3 bg-surface-container-highest rounded-full text-on-surface font-semibold hover:bg-surface-container-high transition-colors">
<span class="material-symbols-outlined">tune</span>
<span>Filter</span>
</button>
</div>
</div>
<!-- Dashboard Quick Stats -->
<div class="grid grid-cols-1 md:grid-cols-4 gap-6 mb-10">
<div class="bg-surface-container-lowest p-6 rounded-xl shadow-sm hover:shadow-md transition-shadow">
<p class="text-on-surface-variant text-sm font-bold uppercase tracking-wider mb-2">Total Listings</p>
<p class="text-3xl font-black text-on-surface">24</p>
</div>
<div class="bg-surface-container-lowest p-6 rounded-xl shadow-sm hover:shadow-md transition-shadow">
<p class="text-on-surface-variant text-sm font-bold uppercase tracking-wider mb-2">Total Views</p>
<p class="text-3xl font-black text-on-surface">12.8k</p>
</div>
<div class="bg-surface-container-lowest p-6 rounded-xl shadow-sm hover:shadow-md transition-shadow border-l-4 border-secondary">
<p class="text-on-surface-variant text-sm font-bold uppercase tracking-wider mb-2">Active</p>
<p class="text-3xl font-black text-secondary">18</p>
</div>
<div class="bg-surface-container-lowest p-6 rounded-xl shadow-sm hover:shadow-md transition-shadow border-l-4 border-primary">
<p class="text-on-surface-variant text-sm font-bold uppercase tracking-wider mb-2">In Review</p>
<p class="text-3xl font-black text-primary">4</p>
</div>
</div>
<!-- Listings Data Table/List -->
<div class="bg-surface-container-lowest rounded-xl shadow-sm overflow-hidden">
<table class="w-full border-collapse">
<thead>
<tr class="bg-surface-container-low/50">
<th class="px-6 py-4 text-left text-xs font-bold text-on-surface-variant uppercase tracking-widest">Property Details</th>
<th class="px-6 py-4 text-left text-xs font-bold text-on-surface-variant uppercase tracking-widest">Price</th>
<th class="px-6 py-4 text-left text-xs font-bold text-on-surface-variant uppercase tracking-widest">Status</th>
<th class="px-6 py-4 text-left text-xs font-bold text-on-surface-variant uppercase tracking-widest">Performance</th>
<th class="px-6 py-4 text-left text-xs font-bold text-on-surface-variant uppercase tracking-widest">Date Added</th>
<th class="px-6 py-4 text-right text-xs font-bold text-on-surface-variant uppercase tracking-widest">Actions</th>
</tr>
</thead>
<tbody class="divide-y divide-surface-container">
<!-- Row 1: Active -->
<tr class="hover:bg-surface-container-low/30 transition-colors group">
<td class="px-6 py-5">
<div class="flex items-center gap-4">
<div class="w-20 h-14 rounded-lg overflow-hidden flex-shrink-0 shadow-sm">
<img alt="Property thumbnail" data-alt="modern luxury villa exterior with swimming pool at sunset, soft warm architectural lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDX450RW8XGp7HtWEUe0EX5TK4j9wRkUI6-bIi4ImCknF0C9EzstoJJ9FyyNuXDPeaDC7JzsjuoAP3EI87ZJh43DakP71OrTcy3H7zUqSPH7d3wlgrPmnQnjylCIjuLikhQJmbQXfZKGaU1D3s7y1U42Uwe3CI0XkauaaF74DjGpu-S9iqvABEMNsowPi6a6ED7JMeQzhX6TQOHgUfTM4Yt0Qv-rveSox0UcqiD2HFb3tztLsq3gXPdzikoPxEPMA1ZyUzEC67O8NUD"/>
</div>
<div>
<p class="font-bold text-on-surface group-hover:text-primary transition-colors">The Serenity Penthouse</p>
<p class="text-xs text-on-surface-variant">Gangnam-gu, Seoul</p>
</div>
</div>
</td>
<td class="px-6 py-5">
<span class="font-semibold text-on-surface">₩2,450M</span>
</td>
<td class="px-6 py-5">
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-bold bg-secondary-container text-on-secondary-container">
<span class="w-1.5 h-1.5 rounded-full bg-secondary mr-2"></span>
                                    Active
                                </span>
</td>
<td class="px-6 py-5">
<div class="flex flex-col">
<span class="text-sm font-bold text-on-surface">4,281 views</span>
<span class="text-xs text-secondary font-medium">↑ 12% this week</span>
</div>
</td>
<td class="px-6 py-5 text-sm text-on-surface-variant">Oct 12, 2023</td>
<td class="px-6 py-5 text-right">
<button class="p-2 hover:bg-surface-container-high rounded-lg transition-colors">
<span class="material-symbols-outlined text-on-surface-variant">more_vert</span>
</button>
</td>
</tr>
<!-- Row 2: In Review -->
<tr class="hover:bg-surface-container-low/30 transition-colors group">
<td class="px-6 py-5">
<div class="flex items-center gap-4">
<div class="w-20 h-14 rounded-lg overflow-hidden flex-shrink-0 shadow-sm">
<img alt="Property thumbnail" data-alt="contemporary beachfront house with large glass windows and minimalist design, bright daylight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB0wXyVUnBTG2m_Kbaq9f45GnygkSP7g36oGsh6p0K6Y8hTVBYPyq4A0DlzXqHHd3YSmlAe4PGOqafqQKuaZ1Cl1tKPK9E-UFzi2KYbfBaR013Cq1WCPsPMZmuPhxB8JX3LarkCpux7QUGVJObh5n8ybj3y3ZEfHOKEeORVRDYvVMZl2U-XDzI0suCOiUm6RWFPtAh04a09rL_gz3pUB-V07_ocAuybCQV_Wck7xWsuuKiW0NZMYJIvTUdchPX_-SLiicY8cHGf7-d-"/>
</div>
<div>
<p class="font-bold text-on-surface group-hover:text-primary transition-colors">Azure Bay Residence</p>
<p class="text-xs text-on-surface-variant">Haeundae, Busan</p>
</div>
</div>
</td>
<td class="px-6 py-5">
<span class="font-semibold text-on-surface">₩1,820M</span>
</td>
<td class="px-6 py-5">
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-bold bg-primary-fixed text-on-primary-fixed-variant">
<span class="w-1.5 h-1.5 rounded-full bg-primary mr-2"></span>
                                    In Review
                                </span>
</td>
<td class="px-6 py-5">
<div class="flex flex-col">
<span class="text-sm font-bold text-on-surface-variant">--</span>
<span class="text-xs text-on-surface-variant">Pending approval</span>
</div>
</td>
<td class="px-6 py-5 text-sm text-on-surface-variant">Nov 04, 2023</td>
<td class="px-6 py-5 text-right">
<button class="p-2 hover:bg-surface-container-high rounded-lg transition-colors">
<span class="material-symbols-outlined text-on-surface-variant">more_vert</span>
</button>
</td>
</tr>
<!-- Row 3: Sold -->
<tr class="hover:bg-surface-container-low/30 transition-colors group opacity-80">
<td class="px-6 py-5">
<div class="flex items-center gap-4">
<div class="w-20 h-14 rounded-lg overflow-hidden flex-shrink-0 grayscale">
<img alt="Property thumbnail" data-alt="cozy suburban family home with a green lawn and white picket fence, bright afternoon sun" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXP0MLgKEGVUar_iey3RoaNe_7EVmj54HHx3vChHOiUCa0Dacv4vbJLXISni5dffWYBuvtgnp7CkhXIkNia6OdNkM_27wqwosulB3x4aycynJ1TECpUeYwSlonpvBx8yXeOREevdttFC2EQMWy7c_TGi0e9S-LJfYudRCPnVL6GHJE5FMatqH7BHcyLqJ5Fymhkv5gj83rA4hidf3m2C_Hnh00a2pX2_LZUe6AXtGGMOtyUrisIDHr_e-SWTWTMzLznXN6ajK_3jLa"/>
</div>
<div>
<p class="font-bold text-on-surface-variant">Maple Wood Estates</p>
<p class="text-xs text-on-surface-variant">Bundang-gu, Seongnam</p>
</div>
</div>
</td>
<td class="px-6 py-5">
<span class="font-semibold text-on-surface-variant">₩950M</span>
</td>
<td class="px-6 py-5">
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-bold bg-surface-container-highest text-on-surface-variant">
<span class="w-1.5 h-1.5 rounded-full bg-outline mr-2"></span>
                                    Sold
                                </span>
</td>
<td class="px-6 py-5">
<div class="flex flex-col">
<span class="text-sm font-bold text-on-surface-variant">14,200 views</span>
<span class="text-xs text-on-surface-variant italic">Finalized</span>
</div>
</td>
<td class="px-6 py-5 text-sm text-on-surface-variant">Aug 22, 2023</td>
<td class="px-6 py-5 text-right">
<button class="p-2 hover:bg-surface-container-high rounded-lg transition-colors">
<span class="material-symbols-outlined text-on-surface-variant">more_vert</span>
</button>
</td>
</tr>
<!-- Row 4: Active -->
<tr class="hover:bg-surface-container-low/30 transition-colors group">
<td class="px-6 py-5">
<div class="flex items-center gap-4">
<div class="w-20 h-14 rounded-lg overflow-hidden flex-shrink-0 shadow-sm">
<img alt="Property thumbnail" data-alt="scandinavian style apartment interior with minimalist furniture and large windows, soft diffused light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDFvNsE2U61lUBwVza_2chavylwoFMKxjLkKkSsyKHdGcQPF-_bhH82lwvbhnVdgZfNmmXq_bFuhqsJTmE6MTMNwpdTb67JDg3vQ-b1S_jwVJq1T8MjTbk-aq4A0IH03fXJEpWY-J3rkDWL6CwBcU5L-ptYWNDF03qNT1aGaSrI-PLKAK6I35nDGtibN-ajxmk2ZoSyJu3jag1LEsVfiOY61_gT7_9g5pjG8qe2O7CSTemS-79vS_0zFKXtJa41_XDbzIbnV2HBxIRP"/>
</div>
<div>
<p class="font-bold text-on-surface group-hover:text-primary transition-colors">Nordic Loft 402</p>
<p class="text-xs text-on-surface-variant">Yeonhui-dong, Seoul</p>
</div>
</div>
</td>
<td class="px-6 py-5">
<span class="font-semibold text-on-surface">₩640M</span>
</td>
<td class="px-6 py-5">
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-bold bg-secondary-container text-on-secondary-container">
<span class="w-1.5 h-1.5 rounded-full bg-secondary mr-2"></span>
                                    Active
                                </span>
</td>
<td class="px-6 py-5">
<div class="flex flex-col">
<span class="text-sm font-bold text-on-surface">842 views</span>
<span class="text-xs text-tertiary font-medium">↓ 5% this week</span>
</div>
</td>
<td class="px-6 py-5 text-sm text-on-surface-variant">Oct 29, 2023</td>
<td class="px-6 py-5 text-right">
<button class="p-2 hover:bg-surface-container-high rounded-lg transition-colors">
<span class="material-symbols-outlined text-on-surface-variant">more_vert</span>
</button>
</td>
</tr>
</tbody>
</table>
<!-- Pagination Footer -->
<div class="px-6 py-4 flex items-center justify-between bg-surface-container-low/30">
<p class="text-sm text-on-surface-variant font-medium">Showing 1 to 4 of 24 listings</p>
<div class="flex items-center gap-1">
<button class="w-8 h-8 flex items-center justify-center rounded-lg hover:bg-surface-container-highest transition-colors disabled:opacity-30" disabled="">
<span class="material-symbols-outlined text-sm">chevron_left</span>
</button>
<button class="w-8 h-8 flex items-center justify-center rounded-lg bg-primary text-on-primary font-bold text-sm">1</button>
<button class="w-8 h-8 flex items-center justify-center rounded-lg hover:bg-surface-container-highest transition-colors font-bold text-sm">2</button>
<button class="w-8 h-8 flex items-center justify-center rounded-lg hover:bg-surface-container-highest transition-colors font-bold text-sm">3</button>
<button class="w-8 h-8 flex items-center justify-center rounded-lg hover:bg-surface-container-highest transition-colors">
<span class="material-symbols-outlined text-sm">chevron_right</span>
</button>
</div>
</div>
</div>
</div>
</main>
<!-- Floating Action Button (Optional Contextual Rendering) -->
<div class="fixed bottom-8 right-8 z-50">
<button class="w-14 h-14 rounded-full bg-primary text-on-primary shadow-xl shadow-primary/40 flex items-center justify-center hover:scale-110 active:scale-90 transition-transform">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">add</span>
</button>
</div>
</body></html>

<!-- My Favorites -->
<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>My Favorites | Digital Cartographer</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#400200",
              "tertiary-fixed-dim": "#ffb4a6",
              "secondary-fixed": "#6ffe93",
              "tertiary-fixed": "#ffdad4",
              "on-tertiary-container": "#fffbff",
              "surface-variant": "#e0e3e6",
              "surface-container-low": "#f2f4f7",
              "error": "#ba1a1a",
              "on-secondary-container": "#007433",
              "surface": "#f7f9fc",
              "tertiary-container": "#d2412b",
              "outline-variant": "#c1c6d7",
              "background": "#f7f9fc",
              "on-secondary-fixed-variant": "#005322",
              "inverse-primary": "#afc6ff",
              "surface-container": "#eceef1",
              "surface-bright": "#f7f9fc",
              "surface-tint": "#0059c7",
              "on-tertiary-fixed-variant": "#900f01",
              "primary-fixed": "#d9e2ff",
              "surface-dim": "#d8dadd",
              "primary": "#0057c2",
              "on-error-container": "#93000a",
              "primary-container": "#006ef2",
              "secondary-fixed-dim": "#4fe17a",
              "secondary": "#006d30",
              "on-secondary": "#ffffff",
              "on-surface": "#191c1e",
              "on-primary-fixed": "#001a43",
              "on-primary-container": "#fefcff",
              "inverse-on-surface": "#eff1f4",
              "surface-container-lowest": "#ffffff",
              "secondary-container": "#6ffe93",
              "on-surface-variant": "#414755",
              "error-container": "#ffdad6",
              "on-primary-fixed-variant": "#004398",
              "on-secondary-fixed": "#00210a",
              "inverse-surface": "#2d3133",
              "surface-container-high": "#e6e8eb",
              "on-error": "#ffffff",
              "on-background": "#191c1e",
              "tertiary": "#af2815",
              "surface-container-highest": "#e0e3e6",
              "on-primary": "#ffffff",
              "primary-fixed-dim": "#afc6ff",
              "outline": "#727786",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Inter"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface">
<!-- Top Navigation Bar -->
<header class="fixed top-0 w-full flex justify-between items-center px-6 py-3 h-16 bg-white/80 dark:bg-slate-900/80 backdrop-blur-xl z-50 shadow-sm">
<div class="flex items-center gap-8">
<span class="text-xl font-bold bg-gradient-to-r from-[#0057c2] to-[#006ef2] bg-clip-text text-transparent">Digital Cartographer</span>
<nav class="hidden md:flex gap-6 font-['Pretendard'] text-sm font-medium tracking-tight">
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">Map</a>
<a class="text-[#0057c2] dark:text-blue-400 font-bold border-b-2 border-[#0057c2] pb-1" href="#">Favorites</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">My Listings</a>
<a class="text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">Support</a>
</nav>
</div>
<div class="flex items-center gap-4">
<button class="p-2 hover:bg-slate-50 dark:hover:bg-slate-800/50 transition-all duration-200 rounded-full">
<span class="material-symbols-outlined text-on-surface-variant">notifications</span>
</button>
<button class="p-2 hover:bg-slate-50 dark:hover:bg-slate-800/50 transition-all duration-200 rounded-full">
<span class="material-symbols-outlined text-on-surface-variant">settings</span>
</button>
<div class="h-8 w-8 rounded-full bg-slate-200 overflow-hidden ml-2">
<img alt="User avatar" data-alt="close-up portrait of a professional male architect in his 30s with short hair and glasses wearing a navy blue polo shirt" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBC05DM6BknKLYnuYd9_Xir3zg9692dgWyNvqM6ffl10Ido09qzjZFE8fNoKyWcy6jHI6ohVSDbtzZO7Lledgo-dKJ9-1lnoXTOT0Z0qC01ymDKsoBtZYuN7M4qjUR5aadceRTs53dRR8V2doL617RQIflH-uHEZMcUGqi9RWHJy5GTWbME-L8GescEJpmSRWeAo8q7qCyZp9wNxwkjQbzPZTTttpqH8ffwbfycloCa3KArWqq26JqqNbXpdA9kioslvHACJfp5Nbwp"/>
</div>
</div>
</header>
<!-- Side Navigation Bar (Hidden on mobile) -->
<aside class="fixed left-0 top-16 h-[calc(100vh-64px)] w-72 p-4 z-40 bg-[#f7f9fc] dark:bg-slate-950 hidden md:flex flex-col border-r-0">
<div class="mb-8 px-4">
<h2 class="text-lg font-black text-[#191c1e] dark:text-white">Property Manager</h2>
<p class="text-xs text-on-surface-variant font-medium">Verified Partner</p>
</div>
<nav class="flex flex-col gap-1 flex-1 font-['Pretendard'] text-base font-semibold">
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors hover:translate-x-1 duration-200" href="#">
<span class="material-symbols-outlined">map</span>
                Map Explorer
            </a>
<a class="flex items-center gap-3 bg-[#0057c2] text-white rounded-xl px-4 py-3 shadow-lg shadow-blue-500/20" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">bookmark</span>
                Saved Homes
            </a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors hover:translate-x-1 duration-200" href="#">
<span class="material-symbols-outlined">dashboard_customize</span>
                Management
            </a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors hover:translate-x-1 duration-200" href="#">
<span class="material-symbols-outlined">help</span>
                Help Center
            </a>
</nav>
<button class="mt-auto mb-4 mx-2 bg-gradient-to-r from-[#0057c2] to-[#006ef2] text-white py-4 rounded-full font-bold shadow-md active:scale-95 transition-all">
            Add New Listing
        </button>
</aside>
<!-- Main Content Canvas -->
<main class="md:ml-72 pt-24 pb-12 px-6 md:px-12">
<!-- Header & Filters Area -->
<section class="mb-10 flex flex-col md:flex-row md:items-end justify-between gap-6">
<div>
<span class="text-primary font-semibold text-sm tracking-widest uppercase mb-2 block">Curated Collection</span>
<h1 class="text-4xl font-extrabold text-on-surface tracking-tight">My Favorites</h1>
<p class="text-on-surface-variant mt-2 max-w-lg">Keep track of the properties that match your lifestyle. You have <span class="text-primary font-bold">12 saved listings</span>.</p>
</div>
<div class="flex items-center gap-3">
<div class="relative">
<select class="appearance-none bg-surface-container-lowest border-none rounded-xl px-4 py-3 pr-10 text-sm font-medium text-on-surface-variant shadow-sm focus:ring-2 focus:ring-primary transition-all">
<option>Date Added (Newest)</option>
<option>Price (Low to High)</option>
<option>Price (High to Low)</option>
</select>
<span class="material-symbols-outlined absolute right-3 top-1/2 -translate-y-1/2 text-on-surface-variant pointer-events-none">expand_more</span>
</div>
<button class="bg-surface-container-lowest p-3 rounded-xl shadow-sm hover:bg-surface-container transition-colors">
<span class="material-symbols-outlined text-on-surface-variant">grid_view</span>
</button>
</div>
</section>
<!-- Grid of Saved Property Cards -->
<div class="grid grid-cols-1 lg:grid-cols-2 xl:grid-cols-3 gap-8">
<!-- Property Card 1 -->
<div class="group bg-surface-container-lowest rounded-2xl overflow-hidden shadow-sm hover:shadow-xl hover:-translate-y-1 transition-all duration-300">
<div class="relative h-64">
<img class="w-full h-full object-cover" data-alt="ultra-modern luxury villa with glass walls and a large swimming pool in front, set in a lush tropical garden at twilight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCACshJFB6IM6BmNxQ87VT5gx13El8gOEQcOivY7z6VG7gqqTUcG_Os0hx9ud9OUnSCthJjPn33ijslHV4s0eTUeX5bWBteaK7OtmRgNgES6TcKg1LLbrQEJ2x7NSq0USD0s803DbOQCL4Zf-MV3DVIa38oMRNKesutHFzlGxwqyHs6oUJ1VbPsZd0LJN6wpCtm0mFqrvW_ATRoSksOs-zYdK-vqyLdDLObJpHVcpwEsTUQl5_IXdPoUNxjkOAlnQh7ninUXMCzsvWa"/>
<button class="absolute top-4 right-4 bg-white/90 backdrop-blur-md p-2 rounded-full text-tertiary transition-transform group-hover:scale-110">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">favorite</span>
</button>
<div class="absolute bottom-4 left-4 flex gap-2">
<span class="bg-secondary/90 backdrop-blur-md text-white px-3 py-1 rounded-full text-xs font-bold">Available</span>
<span class="bg-primary/90 backdrop-blur-md text-white px-3 py-1 rounded-full text-xs font-bold">New Construction</span>
</div>
</div>
<div class="p-6">
<div class="flex justify-between items-start mb-2">
<h3 class="text-xl font-bold text-on-surface">The Zenith Penthouse</h3>
<span class="text-2xl font-black text-primary">$4,250,000</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant mb-4">
<span class="material-symbols-outlined text-sm">location_on</span>
<span class="text-sm">Gangnam-gu, Seoul, KR</span>
</div>
<div class="flex items-center justify-between border-t border-slate-50 pt-4">
<div class="flex gap-4">
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">bed</span>
<span class="text-xs font-semibold">4 Beds</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">bathtub</span>
<span class="text-xs font-semibold">3 Baths</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">square_foot</span>
<span class="text-xs font-semibold">320 m²</span>
</div>
</div>
</div>
</div>
</div>
<!-- Property Card 2 -->
<div class="group bg-surface-container-lowest rounded-2xl overflow-hidden shadow-sm hover:shadow-xl hover:-translate-y-1 transition-all duration-300">
<div class="relative h-64">
<img class="w-full h-full object-cover" data-alt="architectural shot of a contemporary minimalist home with clean lines, white concrete, and large oak wood accents in a serene forest setting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA98PDZqz1TeuI-YQ7OxyZO1m-NvqExFffpIXssq_S7Gm6r3W8GXwhxumQGFYw8cVd5dgKVQOALdI3HS-mZDGKGGcoBZdRMcn__2ahKP_63baLn8Dsp-P84Huz7v8Il_xaH6Jdjr18Cv3K5eIcLRv0QdbPmdB2PiJCvF2AZBoHgBGsdDmX9hRN0Pna4lJiQ-_TQe5yzkTN73Amxcoioqn0LUsx6_KlZH6Or95mDAQj_4Np98uqFY2ycgQ-NZDBOGX9MyzyM9_74Qk8e"/>
<button class="absolute top-4 right-4 bg-white/90 backdrop-blur-md p-2 rounded-full text-tertiary transition-transform group-hover:scale-110">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">favorite</span>
</button>
<div class="absolute bottom-4 left-4 flex gap-2">
<span class="bg-tertiary/90 backdrop-blur-md text-white px-3 py-1 rounded-full text-xs font-bold">Ending Soon</span>
</div>
</div>
<div class="p-6">
<div class="flex justify-between items-start mb-2">
<h3 class="text-xl font-bold text-on-surface">Forest Edge Retreat</h3>
<span class="text-2xl font-black text-primary">$1,890,000</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant mb-4">
<span class="material-symbols-outlined text-sm">location_on</span>
<span class="text-sm">Gapyeong-gun, Gyeonggi-do</span>
</div>
<div class="flex items-center justify-between border-t border-slate-50 pt-4">
<div class="flex gap-4">
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">bed</span>
<span class="text-xs font-semibold">3 Beds</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">bathtub</span>
<span class="text-xs font-semibold">2 Baths</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">square_foot</span>
<span class="text-xs font-semibold">185 m²</span>
</div>
</div>
</div>
</div>
</div>
<!-- Property Card 3 -->
<div class="group bg-surface-container-lowest rounded-2xl overflow-hidden shadow-sm hover:shadow-xl hover:-translate-y-1 transition-all duration-300">
<div class="relative h-64">
<img class="w-full h-full object-cover" data-alt="stunning coastal mansion overlooking the sea with Mediterranean architecture, terracotta roof tiles, and vibrant bougainvillea flowers in the foreground" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCThD7imWP69zES05Hois0jDUWNGGvuKmrykoaXe7T4gtt5drnSeJFtFBapPVbWmCuOJQtsdrH1GlxqA4ExD5WnvG1zlwkBB0CRDsbLbP8zxtyJwqpDPnypdrafJYjD0mkhOj-TTz_z_tfu8XkJ6Z4sM3qRqZoUxYuWpIadpO-MnRT81tE_w8pfgPvxUbcimy5GHxSrLIu4SQPka5ytQhk2LwkcaQiOd5Z2ktGXRaevJHdsRlEftayoWdL06azgBEmolwbJfFM8e_oy"/>
<button class="absolute top-4 right-4 bg-white/90 backdrop-blur-md p-2 rounded-full text-tertiary transition-transform group-hover:scale-110">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">favorite</span>
</button>
<div class="absolute bottom-4 left-4 flex gap-2">
<span class="bg-secondary/90 backdrop-blur-md text-white px-3 py-1 rounded-full text-xs font-bold">Available</span>
</div>
</div>
<div class="p-6">
<div class="flex justify-between items-start mb-2">
<h3 class="text-xl font-bold text-on-surface">Azure Bay Estate</h3>
<span class="text-2xl font-black text-primary">$2,400,000</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant mb-4">
<span class="material-symbols-outlined text-sm">location_on</span>
<span class="text-sm">Haeundae-gu, Busan</span>
</div>
<div class="flex items-center justify-between border-t border-slate-50 pt-4">
<div class="flex gap-4">
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">bed</span>
<span class="text-xs font-semibold">5 Beds</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">bathtub</span>
<span class="text-xs font-semibold">4 Baths</span>
</div>
<div class="flex items-center gap-1 text-on-surface-variant">
<span class="material-symbols-outlined text-sm">square_foot</span>
<span class="text-xs font-semibold">410 m²</span>
</div>
</div>
</div>
</div>
</div>
</div>
<!-- Empty State (Conditional Mockup) -->
<div class="hidden mt-20 flex-col items-center text-center max-w-md mx-auto">
<div class="w-48 h-48 mb-8 relative">
<div class="absolute inset-0 bg-primary-container/20 rounded-full animate-pulse"></div>
<div class="absolute inset-4 bg-primary-container/40 rounded-full"></div>
<div class="absolute inset-0 flex items-center justify-center">
<span class="material-symbols-outlined text-6xl text-primary" style="font-variation-settings: 'wght' 200;">heart_plus</span>
</div>
</div>
<h2 class="text-2xl font-bold text-on-surface mb-3">No Saved Properties Yet</h2>
<p class="text-on-surface-variant mb-8">Start your journey by exploring the interactive map and hearting properties that catch your eye.</p>
<button class="bg-gradient-to-r from-[#0057c2] to-[#006ef2] text-white px-8 py-4 rounded-full font-bold shadow-lg hover:shadow-blue-500/30 transition-all active:scale-95 flex items-center gap-2">
<span class="material-symbols-outlined">map</span>
                Explore Map
            </button>
</div>
</main>
<!-- Mobile Bottom Navigation -->
<nav class="md:hidden fixed bottom-0 w-full bg-white/90 backdrop-blur-xl border-t border-slate-100 flex justify-around items-center h-20 px-4 z-50">
<a class="flex flex-col items-center gap-1 text-slate-400" href="#">
<span class="material-symbols-outlined">map</span>
<span class="text-[10px] font-bold">Map</span>
</a>
<a class="flex flex-col items-center gap-1 text-primary" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">bookmark</span>
<span class="text-[10px] font-bold">Saved</span>
</a>
<button class="bg-primary text-white p-4 rounded-full -mt-10 shadow-lg shadow-blue-500/40">
<span class="material-symbols-outlined">add</span>
</button>
<a class="flex flex-col items-center gap-1 text-slate-400" href="#">
<span class="material-symbols-outlined">dashboard_customize</span>
<span class="text-[10px] font-bold">Manage</span>
</a>
<a class="flex flex-col items-center gap-1 text-slate-400" href="#">
<span class="material-symbols-outlined">person</span>
<span class="text-[10px] font-bold">Profile</span>
</a>
</nav>
</body></html>

<!-- Property Detail Page -->
<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<style>
        body { font-family: 'Inter', sans-serif; }
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#400200",
              "tertiary-fixed-dim": "#ffb4a6",
              "secondary-fixed": "#6ffe93",
              "tertiary-fixed": "#ffdad4",
              "on-tertiary-container": "#fffbff",
              "surface-variant": "#e0e3e6",
              "surface-container-low": "#f2f4f7",
              "error": "#ba1a1a",
              "on-secondary-container": "#007433",
              "surface": "#f7f9fc",
              "tertiary-container": "#d2412b",
              "outline-variant": "#c1c6d7",
              "background": "#f7f9fc",
              "on-secondary-fixed-variant": "#005322",
              "inverse-primary": "#afc6ff",
              "surface-container": "#eceef1",
              "surface-bright": "#f7f9fc",
              "surface-tint": "#0059c7",
              "on-tertiary-fixed-variant": "#900f01",
              "primary-fixed": "#d9e2ff",
              "surface-dim": "#d8dadd",
              "primary": "#0057c2",
              "on-error-container": "#93000a",
              "primary-container": "#006ef2",
              "secondary-fixed-dim": "#4fe17a",
              "secondary": "#006d30",
              "on-secondary": "#ffffff",
              "on-surface": "#191c1e",
              "on-primary-fixed": "#001a43",
              "on-primary-container": "#fefcff",
              "inverse-on-surface": "#eff1f4",
              "surface-container-lowest": "#ffffff",
              "secondary-container": "#6ffe93",
              "on-surface-variant": "#414755",
              "error-container": "#ffdad6",
              "on-primary-fixed-variant": "#004398",
              "on-secondary-fixed": "#00210a",
              "inverse-surface": "#2d3133",
              "surface-container-high": "#e6e8eb",
              "on-error": "#ffffff",
              "on-background": "#191c1e",
              "tertiary": "#af2815",
              "surface-container-highest": "#e0e3e6",
              "on-primary": "#ffffff",
              "primary-fixed-dim": "#afc6ff",
              "outline": "#727786",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Inter"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
</head>
<body class="bg-surface text-on-surface">
<!-- TopNavBar -->
<header class="fixed top-0 w-full flex justify-between items-center px-6 py-3 h-16 bg-white/80 dark:bg-slate-900/80 backdrop-blur-xl shadow-sm z-50">
<div class="flex items-center gap-8">
<span class="text-xl font-bold bg-gradient-to-r from-[#0057c2] to-[#006ef2] bg-clip-text text-transparent">Digital Cartographer</span>
<nav class="hidden md:flex items-center gap-6">
<a class="font-['Pretendard'] text-sm font-medium tracking-tight text-[#0057c2] dark:text-blue-400 font-bold border-b-2 border-[#0057c2] pb-1" href="#">Map</a>
<a class="font-['Pretendard'] text-sm font-medium tracking-tight text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">Favorites</a>
<a class="font-['Pretendard'] text-sm font-medium tracking-tight text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">My Listings</a>
<a class="font-['Pretendard'] text-sm font-medium tracking-tight text-slate-500 dark:text-slate-400 hover:text-slate-900 dark:hover:text-white transition-colors" href="#">Support</a>
</nav>
</div>
<div class="flex items-center gap-4">
<button class="p-2 rounded-full hover:bg-slate-50 dark:hover:bg-slate-800/50 transition-all duration-200">
<span class="material-symbols-outlined text-on-surface-variant">notifications</span>
</button>
<button class="p-2 rounded-full hover:bg-slate-50 dark:hover:bg-slate-800/50 transition-all duration-200">
<span class="material-symbols-outlined text-on-surface-variant">settings</span>
</button>
<div class="w-8 h-8 rounded-full bg-slate-200 overflow-hidden">
<img alt="User avatar" data-alt="professional headshot of a smiling man in a business casual blue shirt with soft studio lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBfO1GiJ1qG3C2wgEBkRMZ-vYyM8rgSfzWQEdmUPan5xJCOM-55nXWYQGMR83KG1C6hWIqFDQ-IPplqlkI2eTe6ALSxXpR2qxcBXinoZrYPh1f-7LcaeHlLLQtHa6p165yt56FUkaPG4kl2C13yjt0LycVgkWz3IW_Rs54T1-dusu4JvS_a8endgM6GRFR9V9HqXVjQIQvrVp8qqfrZ3MFMzcxyLj8jpoifjeiAuGTCa8RS2Vz0jdgfH5AU5pAEiiAFcRES-V3DSfHu"/>
</div>
</div>
</header>
<main class="pt-20 pb-12 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
<!-- Breadcrumb / Back Navigation -->
<div class="mb-6 flex items-center justify-between">
<a class="flex items-center gap-2 text-primary font-medium hover:underline" href="#">
<span class="material-symbols-outlined text-sm">arrow_back</span>
                Back to List
            </a>
<div class="flex items-center gap-3">
<button class="flex items-center gap-2 px-4 py-2 bg-surface-container-lowest rounded-full shadow-sm hover:shadow-md transition-shadow text-on-surface-variant text-sm font-medium">
<span class="material-symbols-outlined text-lg">share</span>
                    Share
                </button>
<button class="flex items-center gap-2 px-4 py-2 bg-surface-container-lowest rounded-full shadow-sm hover:shadow-md transition-shadow text-on-surface-variant text-sm font-medium">
<span class="material-symbols-outlined text-lg">bookmark</span>
                    Save to Favorites
                </button>
</div>
</div>
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
<!-- Left/Center Area -->
<div class="lg:col-span-8 space-y-8">
<!-- Image Gallery -->
<section class="relative group">
<div class="grid grid-cols-4 grid-rows-2 gap-3 h-[500px] rounded-3xl overflow-hidden shadow-xl">
<div class="col-span-3 row-span-2 relative overflow-hidden">
<img class="w-full h-full object-cover transform hover:scale-105 transition-transform duration-700" data-alt="ultra-modern luxury apartment interior with floor-to-ceiling windows overlooking a city skyline at dusk with warm ambient lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCTiHNp1RMtS0tfdF6RRSm4Gx6wAAU0d0KQhz7NyG9y6WKpjG4rv7erYVwT0X-zdceFjy_dDXAG2cdJupStsdOSXDhYgPPHIYD1I-g-3lIdnGEYVLCh1MvLbIxJk3_OIA-BCxXJaw9eTczIc1_bisztM3XGX08QNaKCh_u95u_mgATNUZK3ty-xYEAcBbGtdqRMvkyJQK2WZiCC0t6FBnXMaF478JAE3jpJ9lMsTGmQs3S-WCu2_dfAioP5Ir9FCaxN_-R62HKiLbwU"/>
</div>
<div class="col-span-1 row-span-1 overflow-hidden">
<img class="w-full h-full object-cover transform hover:scale-105 transition-transform duration-500" data-alt="minimalist modern kitchen with marble island and high-end stainless steel appliances in bright daylight" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCGj74KgJY0gWQoquLRLEN5g-Hxgcfn_wvKqr4hn6TJXlFmcRqxv7lZxs83nBC1Y8-UrakZGHrDjnrpeikMyXaMyFvU5ICqBZQ5Atw2a9XMaVaxICbuf04bkH_ud6Fuajh5hoCiEPQLHCEQnxuiJge60YJLYI5Qb_9ZC8X1gypjYwTT_nOMZoaFw_9eI9JbkezFIR_bDsofd0iJyFEscsSJ4PQzrQJ5NrkvAcaxYL99_3zooZKOZJUyAK0EzEXnrNTCypFVighVbvo3"/>
</div>
<div class="col-span-1 row-span-1 relative overflow-hidden">
<img class="w-full h-full object-cover transform hover:scale-105 transition-transform duration-500" data-alt="cozy contemporary bedroom with neutral tones and large windows allowing soft morning light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAsWZ9ogYIIOimz17jjwgHZQLzqfQmVmSX5_ys0HA017mF8E4GeVOvd7O_GvY27H1zJe7pmdBe_BnUWkaDXGnVE7QoxHtJmpHXzQYhcaA718pT0j_OSQ7pXpHJtn0ZKjbLI096iL0wuNiQE73ZOV5G_sqE3bM8CB23wcxrMQU6cAq0sRQ_rMWpsNs9hyRqsl690MvW3-PrjzBVC9P2WWbTHCqoMyg05LX9_SZ_FalgyvFH8kUIdaaO626EvRrrQHS3v32aCkbUhVaK2"/>
<div class="absolute inset-0 bg-black/40 flex items-center justify-center cursor-pointer">
<span class="text-white font-bold text-lg">+12 Photos</span>
</div>
</div>
</div>
</section>
<!-- Header Details -->
<section class="bg-surface-container-lowest p-8 rounded-3xl shadow-sm space-y-4">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
<div>
<span class="inline-block px-3 py-1 bg-primary/10 text-primary text-xs font-bold rounded-full mb-3 tracking-wider uppercase">Exclusive Listing</span>
<h1 class="text-3xl font-bold text-on-surface tracking-tight">Skyline Vista Penthouse</h1>
<p class="text-on-surface-variant flex items-center gap-1 mt-1">
<span class="material-symbols-outlined text-sm">location_on</span>
                                128 Mapo-daero, Mapo-gu, Seoul, Republic of Korea
                            </p>
</div>
<div class="text-right">
<p class="text-primary font-black text-4xl leading-none">Jeonse 4억 5,000만</p>
<p class="text-on-surface-variant text-sm mt-1 font-medium">Monthly Management: 250,000 KRW</p>
</div>
</div>
<!-- Quick Stats Grid -->
<div class="grid grid-cols-2 md:grid-cols-5 gap-4 pt-6 mt-6 border-t border-outline-variant/20">
<div class="flex items-center gap-3 p-3 rounded-2xl bg-surface-container-low">
<div class="w-10 h-10 rounded-xl bg-white flex items-center justify-center text-primary shadow-sm">
<span class="material-symbols-outlined">layers</span>
</div>
<div>
<p class="text-[10px] uppercase tracking-wider text-on-surface-variant font-bold">Floor</p>
<p class="text-sm font-semibold">18th / 22F</p>
</div>
</div>
<div class="flex items-center gap-3 p-3 rounded-2xl bg-surface-container-low">
<div class="w-10 h-10 rounded-xl bg-white flex items-center justify-center text-primary shadow-sm">
<span class="material-symbols-outlined">bed</span>
</div>
<div>
<p class="text-[10px] uppercase tracking-wider text-on-surface-variant font-bold">Rooms</p>
<p class="text-sm font-semibold">3 Bed</p>
</div>
</div>
<div class="flex items-center gap-3 p-3 rounded-2xl bg-surface-container-low">
<div class="w-10 h-10 rounded-xl bg-white flex items-center justify-center text-primary shadow-sm">
<span class="material-symbols-outlined">bathtub</span>
</div>
<div>
<p class="text-[10px] uppercase tracking-wider text-on-surface-variant font-bold">Baths</p>
<p class="text-sm font-semibold">2 Bath</p>
</div>
</div>
<div class="flex items-center gap-3 p-3 rounded-2xl bg-surface-container-low">
<div class="w-10 h-10 rounded-xl bg-white flex items-center justify-center text-primary shadow-sm">
<span class="material-symbols-outlined">explore</span>
</div>
<div>
<p class="text-[10px] uppercase tracking-wider text-on-surface-variant font-bold">Orientation</p>
<p class="text-sm font-semibold">South-West</p>
</div>
</div>
<div class="flex items-center gap-3 p-3 rounded-2xl bg-surface-container-low">
<div class="w-10 h-10 rounded-xl bg-white flex items-center justify-center text-primary shadow-sm">
<span class="material-symbols-outlined">thermostat</span>
</div>
<div>
<p class="text-[10px] uppercase tracking-wider text-on-surface-variant font-bold">Heating</p>
<p class="text-sm font-semibold">Individual</p>
</div>
</div>
</div>
</section>
<!-- Description Block -->
<section class="bg-surface-container-lowest p-8 rounded-3xl shadow-sm">
<h3 class="text-xl font-bold mb-6 flex items-center gap-2">
<span class="w-2 h-6 bg-primary rounded-full"></span>
                        Property Description
                    </h3>
<div class="space-y-4 text-on-surface-variant leading-relaxed">
<p>This premium penthouse offers an unparalleled living experience in the heart of Mapo-gu. Featuring a spacious open-concept layout with architectural lighting and imported Italian marble finishes.</p>
<p>The unit was recently renovated in 2023 with smart home integration, including automated blinds, climate control, and a state-of-the-art security system. Residents enjoy exclusive access to the building's rooftop garden and private fitness center.</p>
<ul class="grid grid-cols-2 gap-y-2 gap-x-8 pt-4">
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">check_circle</span> Built-in Wardrobes</li>
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">check_circle</span> Induction Cooktop</li>
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">check_circle</span> Dishwasher</li>
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-secondary text-lg">check_circle</span> System AC</li>
</ul>
</div>
</section>
<!-- Broker Info -->
<section class="bg-surface-container-lowest p-8 rounded-3xl shadow-sm">
<h3 class="text-xl font-bold mb-6">Listing Agent</h3>
<div class="flex flex-col sm:flex-row items-center justify-between p-6 rounded-2xl border border-outline-variant/30 bg-surface">
<div class="flex items-center gap-6 mb-4 sm:mb-0">
<div class="w-20 h-20 rounded-full border-4 border-white shadow-lg overflow-hidden">
<img alt="Agent Profile" data-alt="confident professional real estate agent in a tailored charcoal suit with a friendly and trustworthy expression" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBLFHwEfNOezHfhOF0QfrDjHv9aNLPnOO4lxiL7V_CFoFKuRs6rEei77WNI43Pw7PIIMOA_sVP1fp6j_VnVuAPv10aE_DvHEdGOW9ixP9Yt_Q1m1CdG_gS03tIz1qkeYRTzPO5NVBvPa0V26i6_zPVeS34vRyRBI0smC1K9z4UcMJ9rCP2XHxyk69CSs5xOIEWKaCp2IDyQg8rtRvoQg566hBj8S4iFLUErUm2_SbHGuNcUuPQOjqr-kU36bs0c2FMCisB6l3mb6wq_"/>
</div>
<div>
<h4 class="text-lg font-bold">Ji-hun Park</h4>
<p class="text-on-surface-variant text-sm">Gold Key Realty • Senior Manager</p>
<div class="flex items-center gap-1 mt-1 text-secondary font-bold text-sm">
<span class="material-symbols-outlined text-sm">verified</span>
                                    Verified Partner
                                </div>
</div>
</div>
<div class="flex gap-3 w-full sm:w-auto">
<button class="flex-1 sm:flex-none px-6 py-3 bg-primary text-white font-bold rounded-xl flex items-center justify-center gap-2 hover:scale-105 transition-transform active:scale-95 shadow-lg shadow-primary/20">
<span class="material-symbols-outlined">call</span>
                                Call
                            </button>
<button class="flex-1 sm:flex-none px-6 py-3 bg-white border-2 border-primary text-primary font-bold rounded-xl flex items-center justify-center gap-2 hover:bg-primary/5 transition-colors">
<span class="material-symbols-outlined">chat_bubble</span>
                                Message
                            </button>
</div>
</div>
</section>
</div>
<!-- Right Sidebar (Sticky) -->
<aside class="lg:col-span-4 lg:sticky lg:top-24 h-fit space-y-6">
<!-- Map Card -->
<div class="bg-surface-container-lowest rounded-3xl shadow-sm overflow-hidden">
<div class="p-5 flex items-center justify-between border-b border-outline-variant/10">
<h4 class="font-bold flex items-center gap-2">
<span class="material-symbols-outlined text-primary">map</span>
                            Location
                        </h4>
<button class="text-xs text-primary font-bold hover:underline">Full View</button>
</div>
<div class="h-64 w-full bg-slate-200 relative group">
<img class="w-full h-full object-cover" data-alt="detailed city map of Seoul Mapo-gu district showing street networks and green spaces in high resolution" data-location="Seoul" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB0ZezqLbrvPC7_yhsdr57_344ndouOf4tEMaKqXGPpmmcv_5u9n2e3jJpm47089XRcgIJmplgzyAcPry-oihIedbldGUh2lw5Zav8ECExuAhnjnmkvZX3nCGuW7zpms0Y861okRoLqKHAt7Bp61g0Vql0TlHpwIM5Hgfk3a-EPJGS-p-huadBwnANjCtC71k6Z6fFr2sdZEsk1bbqovFTuv7ctoZ1GeqM4poVLo7Bgwm1aK5M90yB2m3Oj6_dbA8gLDlIEQ0i5oF8R"/>
<div class="absolute inset-0 flex items-center justify-center">
<div class="relative">
<div class="w-12 h-12 bg-primary/20 rounded-full absolute -top-4 -left-4 animate-ping"></div>
<span class="material-symbols-outlined text-4xl text-primary relative z-10" style="font-variation-settings: 'FILL' 1;">location_on</span>
</div>
</div>
</div>
<div class="p-5">
<p class="text-sm text-on-surface-variant leading-relaxed">
                            Conveniently located within a 5-minute walk from Mapo Station (Line 5). Adjacent to central business districts and Han River parks.
                        </p>
</div>
</div>
<!-- Action Sticky Box -->
<div class="bg-primary p-6 rounded-3xl shadow-xl shadow-primary/30 text-white space-y-6">
<div>
<p class="text-white/80 text-sm font-medium">Ready to see it?</p>
<h4 class="text-2xl font-bold">Schedule a Tour</h4>
</div>
<div class="space-y-3">
<div class="flex items-center gap-3 bg-white/10 p-4 rounded-2xl">
<span class="material-symbols-outlined">calendar_today</span>
<div class="text-sm">
<p class="opacity-70 font-medium">Next available</p>
<p class="font-bold">Tomorrow, 10:00 AM</p>
</div>
</div>
</div>
<button class="w-full py-4 bg-white text-primary font-black rounded-2xl shadow-lg hover:scale-[1.02] active:scale-95 transition-all">
                        Request Viewing
                    </button>
<p class="text-center text-[10px] uppercase tracking-widest opacity-60">Avg. response time: 15 mins</p>
</div>
<!-- Help Center Quick Link -->
<div class="bg-surface-container p-6 rounded-3xl flex items-center justify-between group cursor-pointer">
<div class="flex items-center gap-4">
<div class="w-10 h-10 rounded-full bg-white flex items-center justify-center text-primary group-hover:rotate-12 transition-transform">
<span class="material-symbols-outlined">help_center</span>
</div>
<div class="text-sm">
<p class="font-bold">Have questions?</p>
<p class="text-on-surface-variant">Check our Buyer Guide</p>
</div>
</div>
<span class="material-symbols-outlined text-on-surface-variant group-hover:translate-x-1 transition-transform">chevron_right</span>
</div>
</aside>
</div>
</main>
<!-- SideNavBar (Triggered for Management/Exploration) -->
<!-- Hidden on Mobile, Fixed for Web Context if user needs to navigate out -->
<div class="hidden md:flex fixed left-0 top-16 h-[calc(100vh-64px)] p-4 z-40 w-16 hover:w-72 group bg-[#f7f9fc] dark:bg-slate-950 border-r-0 transition-all duration-300 ease-in-out overflow-hidden">
<div class="flex flex-col h-full w-64">
<div class="space-y-2">
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors" href="#">
<span class="material-symbols-outlined">map</span>
<span class="opacity-0 group-hover:opacity-100 whitespace-nowrap font-['Pretendard'] text-base font-semibold">Map Explorer</span>
</a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors" href="#">
<span class="material-symbols-outlined">bookmark</span>
<span class="opacity-0 group-hover:opacity-100 whitespace-nowrap font-['Pretendard'] text-base font-semibold">Saved Homes</span>
</a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors" href="#">
<span class="material-symbols-outlined">dashboard_customize</span>
<span class="opacity-0 group-hover:opacity-100 whitespace-nowrap font-['Pretendard'] text-base font-semibold">Management</span>
</a>
<a class="flex items-center gap-3 text-slate-600 dark:text-slate-400 px-4 py-3 rounded-xl hover:bg-slate-200/50 dark:hover:bg-slate-800/50 transition-colors" href="#">
<span class="material-symbols-outlined">help</span>
<span class="opacity-0 group-hover:opacity-100 whitespace-nowrap font-['Pretendard'] text-base font-semibold">Help Center</span>
</a>
</div>
<div class="mt-auto opacity-0 group-hover:opacity-100 transition-opacity">
<button class="w-full py-4 bg-[#0057c2] text-white font-bold rounded-xl shadow-lg shadow-blue-500/20 flex items-center justify-center gap-2">
<span class="material-symbols-outlined">add</span>
                    Add Listing
                </button>
</div>
</div>
</div>
</body></html>
