<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Our Water, Our Future</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Lexend:wght@100..900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
<script>
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#137fec",
            "background-light": "#f6f7f8",
            "background-dark": "#101922",
          },
          fontFamily: {
            "display": ["Lexend", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          },
        },
      },
    }
  </script>
<style>
    .material-symbols-outlined {
      font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24
    }
  </style>
</head>
<body class="font-display bg-background-light dark:bg-background-dark">
<div class="relative flex min-h-screen w-full flex-col group/design-root overflow-x-hidden">
<div class="layout-container flex h-full grow flex-col">
<!-- TopNavBar -->
<header class="sticky top-0 z-50 flex items-center justify-between whitespace-nowrap border-b border-solid border-gray-200/80 dark:border-gray-800/80 bg-background-light/80 dark:bg-background-dark/80 backdrop-blur-sm px-4 sm:px-8 lg:px-16 py-3">
<div class="flex items-center gap-4 text-gray-900 dark:text-white">
<div class="size-6 text-primary">
<svg fill="currentColor" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
<path d="M13.8261 17.4264C16.7203 18.1174 20.2244 18.5217 24 18.5217C27.7756 18.5217 31.2797 18.1174 34.1739 17.4264C36.9144 16.7722 39.9967 15.2331 41.3563 14.1648L24.8486 40.6391C24.4571 41.267 23.5429 41.267 23.1514 40.6391L6.64374 14.1648C8.00331 15.2331 11.0856 16.7722 13.8261 17.4264Z"></path>
<path clip-rule="evenodd" d="M39.998 12.236C39.9944 12.2537 39.9875 12.2845 39.9748 12.3294C39.9436 12.4399 39.8949 12.5741 39.8346 12.7175C39.8168 12.7597 39.7989 12.8007 39.7813 12.8398C38.5103 13.7113 35.9788 14.9393 33.7095 15.4811C30.9875 16.131 27.6413 16.5217 24 16.5217C20.3587 16.5217 17.0125 16.131 14.2905 15.4811C12.0012 14.9346 9.44505 13.6897 8.18538 12.8168C8.17384 12.7925 8.16216 12.767 8.15052 12.7408C8.09919 12.6249 8.05721 12.5114 8.02977 12.411C8.00356 12.3152 8.00039 12.2667 8.00004 12.2612C8.00004 12.261 8 12.2607 8.00004 12.2612C8.00004 12.2359 8.0104 11.9233 8.68485 11.3686C9.34546 10.8254 10.4222 10.2469 11.9291 9.72276C14.9242 8.68098 19.1919 8 24 8C28.8081 8 33.0758 8.68098 36.0709 9.72276C37.5778 10.2469 38.6545 10.8254 39.3151 11.3686C39.9006 11.8501 39.9857 12.1489 39.998 12.236ZM4.95178 15.2312L21.4543 41.6973C22.6288 43.5809 25.3712 43.5809 26.5457 41.6973L43.0534 15.223C43.0709 15.1948 43.0878 15.1662 43.104 15.1371L41.3563 14.1648C43.104 15.1371 43.1038 15.1374 43.104 15.1371L43.1051 15.135L43.1065 15.1325L43.1101 15.1261L43.1199 15.1082C43.1276 15.094 43.1377 15.0754 43.1497 15.0527C43.1738 15.0075 43.2062 14.9455 43.244 14.8701C43.319 14.7208 43.4196 14.511 43.5217 14.2683C43.6901 13.8679 44 13.0689 44 12.2609C44 10.5573 43.003 9.22254 41.8558 8.2791C40.6947 7.32427 39.1354 6.55361 37.385 5.94477C33.8654 4.72057 29.133 4 24 4C18.867 4 14.1346 4.72057 10.615 5.94478C8.86463 6.55361 7.30529 7.32428 6.14419 8.27911C4.99695 9.22255 3.99999 10.5573 3.99999 12.2609C3.99999 13.1275 4.29264 13.9078 4.49321 14.3607C4.60375 14.6102 4.71348 14.8196 4.79687 14.9689C4.83898 15.0444 4.87547 15.1065 4.9035 15.1529C4.91754 15.1762 4.92954 15.1957 4.93916 15.2111L4.94662 15.223L4.95178 15.2312ZM35.9868 18.996L24 38.22L12.0131 18.996C12.4661 19.1391 12.9179 19.2658 13.3617 19.3718C16.4281 20.1039 20.0901 20.5217 24 20.5217C27.9099 20.5217 31.5719 20.1039 34.6383 19.3718C35.082 19.2658 35.5339 19.1391 35.9868 18.996Z" fill="currentColor" fill-rule="evenodd"></path>
</svg>
</div>
<h1 class="text-lg font-bold tracking-tight">Our Water, Our Future</h1>
</div>
<div class="flex flex-1 justify-end gap-8">
<nav class="hidden items-center gap-9 md:flex">
<a class="text-sm font-medium text-gray-700 hover:text-primary dark:text-gray-300 dark:hover:text-primary" href="#causes">Causes</a>
<a class="text-sm font-medium text-gray-700 hover:text-primary dark:text-gray-300 dark:hover:text-primary" href="#consequences">Consequences</a>
<a class="text-sm font-medium text-gray-700 hover:text-primary dark:text-gray-300 dark:hover:text-primary" href="#solutions">Solutions</a>
</nav>
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 bg-primary text-white text-sm font-bold tracking-wide shadow-sm hover:bg-primary/90">
<span class="truncate">Get Involved</span>
</button>
</div>
</header>
<main class="flex flex-1 flex-col">
<!-- HeroSection -->
<section class="@container">
<div class="flex min-h-[calc(100vh-68px)] flex-col items-center justify-center gap-6 bg-cover bg-center bg-no-repeat p-4 text-center md:gap-8" data-alt="Calm, clear water reflecting a blue sky" style='background-image: linear-gradient(rgba(0, 0, 0, 0.2) 0%, rgba(0, 0, 0, 0.5) 100%), url("https://lh3.googleusercontent.com/aida-public/AB6AXuCsYJUXXVeV4v9m7XSwre0kE1O8KHaud_wXaV4q0fJ-cbzXVKy1BnA3JUTp5Gt40j_zLbNRqSDc7kFbkATg_CepW4WnIVqkuUqQH4BIoi9SRrzgVhez7ZScHY_rTyy-ZIuXyahAQu-Wc-fOGPb7R3_X_0Mu6cDOHjWVkDz_SOdCKD5fpDUKpawRxh92woJ-1m6ChtEbGGvysEadVk77SUc93-xA4j2eXItR18RTer6JUtgMJ0uslyYF975racbmt2K6U5gzF1WTuM0T");'>
<h1 class="text-white text-4xl font-black leading-tight tracking-tighter md:text-6xl">Our Water, Our Future</h1>
<p class="max-w-2xl text-white/90 text-sm font-normal leading-normal md:text-base">Every drop counts. Discover the story of our planet's most precious resource and how we can protect it together.</p>
<a class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 md:h-12 md:px-5 bg-primary text-white text-sm font-bold tracking-wide md:text-base hover:bg-primary/90" href="#intro">
<span class="truncate">Learn More</span>
</a>
</div>
</section>
<div class="mx-auto w-full max-w-4xl px-4 py-16 sm:px-6 lg:px-8 lg:py-24">
<!-- Introduction -->
<section class="mb-16 scroll-mt-20" id="intro">
<p class="text-gray-800 dark:text-gray-200 text-lg font-normal leading-relaxed text-center">Water is the lifeblood of our planet, a finite resource essential for all known forms of life. Yet, it is increasingly under threat from pollution. This article explores the primary causes of water contamination, its far-reaching consequences, and the actionable solutions we can all embrace to safeguard our water for generations to come.</p>
</section>
<!-- Causes Section -->
<section class="mb-20 scroll-mt-20" id="causes">
<h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white text-center">The Unseen Currents: Understanding Water Pollution</h2>
<p class="mt-4 text-center text-gray-600 dark:text-gray-400">Pollution begins from many sources, often hidden from plain sight but with devastating effects.</p>
<div class="mt-12 grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
<div class="flex flex-col items-center text-center p-6 bg-white dark:bg-background-dark/50 rounded-xl shadow-sm border border-gray-200 dark:border-gray-800">
<div class="mb-4 flex h-14 w-14 items-center justify-center rounded-full bg-primary/20 text-primary">
<span class="material-symbols-outlined !text-3xl" data-icon="delete">delete</span>
</div>
<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Incorrect Waste Disposal</h3>
<p class="mt-2 text-sm text-gray-600 dark:text-gray-400">Chemicals, oils, and litter from households and industries are often dumped directly into rivers and lakes, contaminating the water supply.</p>
</div>
<div class="flex flex-col items-center text-center p-6 bg-white dark:bg-background-dark/50 rounded-xl shadow-sm border border-gray-200 dark:border-gray-800">
<div class="mb-4 flex h-14 w-14 items-center justify-center rounded-full bg-primary/20 text-primary">
<span class="material-symbols-outlined !text-3xl" data-icon="water_drop">water_drop</span>
</div>
<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Untreated Sewage</h3>
<p class="mt-2 text-sm text-gray-600 dark:text-gray-400">In many parts of the world, raw sewage is discharged into water bodies, introducing harmful bacteria and pathogens.</p>
</div>
<div class="flex flex-col items-center text-center p-6 bg-white dark:bg-background-dark/50 rounded-xl shadow-sm border border-gray-200 dark:border-gray-800">
<div class="mb-4 flex h-14 w-14 items-center justify-center rounded-full bg-primary/20 text-primary">
<span class="material-symbols-outlined !text-3xl" data-icon="inventory">inventory</span>
</div>
<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Excessive Plastic Use</h3>
<p class="mt-2 text-sm text-gray-600 dark:text-gray-400">Single-use plastics break down into microplastics, which infiltrate our waterways, harming wildlife and entering the food chain.</p>
</div>
</div>
</section>
<!-- Consequences Section -->
<section class="mb-20 scroll-mt-20" id="consequences">
<h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white text-center">The Ripple Effect: Consequences of Contamination</h2>
<p class="mt-4 text-center text-gray-600 dark:text-gray-400">The impact of polluted water extends far beyond dirty rivers, affecting every living being on Earth.</p>
<div class="mt-12 grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
<div class="h-64 md:h-full w-full overflow-hidden rounded-xl">
<img class="h-full w-full object-cover" data-alt="A sea turtle swimming among plastic bags in the ocean" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCx1_opf1mXujLtx1RGuaXmBAHpm82NYzPDZBvm8-4mHj4BQyBbUlebK_XF9I0WVeQrVWe6hpTDyzuEMYQT29oF2J5zGOwFXGCRJ5LP-i-lip4cPMWt6dCmqj7pvdVsP0aWGh9vgrmlgw2bmgq32SAKIllXos3LFAeB4jcDbK8uGESlOguzy7NyPON6ub4yZF2D_ZfwtRGg_FFnDlV11dfEAmDrVhXFxL3hlM7qzmOOFTydxjrH_ES4LxzprGKs8-FX51IYx-3QVls9"/>
</div>
<div class="space-y-6">
<div class="flex items-start gap-4">
<span class="material-symbols-outlined text-2xl text-primary mt-1">eco</span>
<div>
<h4 class="font-semibold text-gray-800 dark:text-gray-200">Environmental Degradation</h4>
<p class="text-sm text-gray-600 dark:text-gray-400">Pollutants create toxic environments, leading to 'dead zones' where aquatic life cannot survive.</p>
</div>
</div>
<div class="flex items-start gap-4">
<span class="material-symbols-outlined text-2xl text-primary mt-1">set_meal</span>
<div>
<h4 class="font-semibold text-gray-800 dark:text-gray-200">Harm to Aquatic Animals</h4>
<p class="text-sm text-gray-600 dark:text-gray-400">Wildlife can mistake plastic for food or become entangled, while chemical pollutants poison them.</p>
</div>
</div>
<div class="flex items-start gap-4">
<span class="material-symbols-outlined text-2xl text-primary mt-1">health_and_safety</span>
<div>
<h4 class="font-semibold text-gray-800 dark:text-gray-200">Threats to Human Health</h4>
<p class="text-sm text-gray-600 dark:text-gray-400">Contaminated drinking water is a leading cause of diseases like cholera, typhoid, and dysentery worldwide.</p>
</div>
</div>
</div>
</div>
<div class="mt-8 p-6 bg-primary/10 dark:bg-primary/20 rounded-xl border border-primary/20">
<blockquote class="text-center text-primary dark:text-blue-300">
<p class="text-lg italic">"Over 80% of the world's wastewater is released into the environment without treatment. This not only pollutes our rivers and lakes but also contaminates the oceans."</p>
<cite class="mt-4 block text-sm font-medium not-italic">- UN-Water Report</cite>
</blockquote>
</div>
</section>
<!-- Solutions Section -->
<section class="scroll-mt-20" id="solutions">
<h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white text-center">Turning the Tide: Pathways to Clean Water</h2>
<p class="mt-4 text-center text-gray-600 dark:text-gray-400">The challenge is immense, but together, through conscious actions, we can create a sustainable future for our water.</p>
<div class="mt-12 grid grid-cols-1 gap-6 md:grid-cols-2 lg:grid-cols-3">
<div class="overflow-hidden rounded-xl bg-white dark:bg-background-dark/50 shadow-sm border border-gray-200 dark:border-gray-800">
<img class="h-40 w-full object-cover" data-alt="Hands sorting plastic bottles into a recycling bin" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC8O3aYOrnEEqQCzya-1K_tBOwSNKsIm7dBFwwm5JvTiS1HPr9BH8MP8F45lO9WhDlUdcvyljRENF2mJ1qQPhzHdR-0M17Md4NbTzvXCVLf4mF5x_d-b08ul3RsOLWvHNQ1pYY9m7NCFEkQIGDcGmVzvrJZPCRBkBAyX8aRWurUAm-6OliIEf3bDHNtHOeNFf1M2p4OE0iE5Xx4iBmpuyDV2RTrJwIfRZAeYG6VixxliOZpT3ICVJBBUNiuh2c8ashIvIc9jShJ8nHl"/>
<div class="p-6">
<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Individual Action</h3>
<ul class="mt-4 space-y-2 text-sm text-gray-600 dark:text-gray-400 list-disc list-inside">
<li>Reduce plastic consumption.</li>
<li>Properly dispose of chemical waste.</li>
<li>Conserve water at home.</li>
<li>Participate in local clean-ups.</li>
</ul>
</div>
</div>
<div class="overflow-hidden rounded-xl bg-white dark:bg-background-dark/50 shadow-sm border border-gray-200 dark:border-gray-800">
<img class="h-40 w-full object-cover" data-alt="A person teaching a group of children about the environment" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC7-lpJQLvJ6p6MeT7WFG17wmrcxHxkLiajtYR0dsFaIT6ZleUr2Khu51BWXwHiOy_G2zpvbn_GcSFRZa9M3tbGZq5Bj7JU7S3ohjg1OlyOAMzNqAhAw6n5liwPGmhCF02_xGCDbjdQ6raoqEfGDX_it_fUzrpH5HUj5TgpsxsHg9NB_2V01hBlPv83Fn3FaX2bJMqdXnm0NULJp8Nx_Ce0URmM0dch1NuHF1n9za6pfsf1P3Sh95LgOhtr606_xOcf-uP2CoYjidSO"/>
<div class="p-6">
<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Community &amp; Education</h3>
<ul class="mt-4 space-y-2 text-sm text-gray-600 dark:text-gray-400 list-disc list-inside">
<li>Promote environmental education.</li>
<li>Support businesses with sustainable practices.</li>
<li>Advocate for better sanitation infrastructure.</li>
<li>Organize awareness campaigns.</li>
</ul>
</div>
</div>
<div class="overflow-hidden rounded-xl bg-white dark:bg-background-dark/50 shadow-sm border border-gray-200 dark:border-gray-800">
<img class="h-40 w-full object-cover" data-alt="Two professionals in a modern building looking over documents" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCFWnj0Itd4-KqPVx7jcvNOuRTlzHhwRTwRtx-4PZMkom9L-pf3quLXppqgbxloc_fJh0qpQGPRCxZ3eouAfx-DAJ8TNdVSR4RE9DwOR9om7H9MLIXnlK2lxxpBVT0ejxd4oZYwy1pOj3tq9TwH5KnC5-45E856BUGB8AktF-KYr9FZkbeYgR9yjIlKI2QJf06OUx1PQzZiXJxVHrOGgg6yq7Mjwngmu0TqM1-lest4uy8JQTkZ6x2F01qPjC7GK-7ua2_Z3o1kBwWW"/>
<div class="p-6">
<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Government &amp; Policy</h3>
<ul class="mt-4 space-y-2 text-sm text-gray-600 dark:text-gray-400 list-disc list-inside">
<li>Enforce stricter anti-pollution laws.</li>
<li>Invest in wastewater treatment facilities.</li>
<li>Ban single-use plastics.</li>
<li>Protect vital water ecosystems.</li>
</ul>
</div>
</div>
</div>
</section>
</div>
<!-- CTA Section -->
<section class="bg-gray-100 dark:bg-background-dark/50 mt-16">
<div class="mx-auto max-w-4xl px-4 py-16 text-center sm:px-6 lg:px-8 lg:py-20">
<h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white">Be the Change for Clean Water</h2>
<p class="mt-4 max-w-2xl mx-auto text-gray-600 dark:text-gray-400">The power to protect our planet's most vital resource is in our collective hands. Every small action contributes to a larger wave of change. Start today.</p>
<button class="mt-8 flex min-w-[84px] max-w-sm cursor-pointer items-center justify-center overflow-hidden rounded-lg h-12 px-8 bg-primary text-white text-base font-bold tracking-wide shadow-lg hover:bg-primary/90 mx-auto">
<span class="truncate">Pledge to Protect Our Water</span>
</button>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-gray-800 dark:bg-black/50 text-white">
<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-8">
<div class="flex flex-col items-center justify-between gap-4 sm:flex-row">
<div class="flex items-center gap-3">
<div class="size-5 text-primary">
<svg fill="currentColor" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
<path d="M13.8261 17.4264C16.7203 18.1174 20.2244 18.5217 24 18.5217C27.7756 18.5217 31.2797 18.1174 34.1739 17.4264C36.9144 16.7722 39.9967 15.2331 41.3563 14.1648L24.8486 40.6391C24.4571 41.267 23.5429 41.267 23.1514 40.6391L6.64374 14.1648C8.00331 15.2331 11.0856 16.7722 13.8261 17.4264Z"></path>
<path clip-rule="evenodd" d="M39.998 12.236C39.9944 12.2537 39.9875 12.2845 39.9748 12.3294C39.9436 12.4399 39.8949 12.5741 39.8346 12.7175C39.8168 12.7597 39.7989 12.8007 39.7813 12.8398C38.5103 13.7113 35.9788 14.9393 33.7095 15.4811C30.9875 16.131 27.6413 16.5217 24 16.5217C20.3587 16.5217 17.0125 16.131 14.2905 15.4811C12.0012 14.9346 9.44505 13.6897 8.18538 12.8168C8.17384 12.7925 8.16216 12.767 8.15052 12.7408C8.09919 12.6249 8.05721 12.5114 8.02977 12.411C8.00356 12.3152 8.00039 12.2667 8.00004 12.2612C8.00004 12.261 8 12.2607 8.00004 12.2612C8.00004 12.2359 8.0104 11.9233 8.68485 11.3686C9.34546 10.8254 10.4222 10.2469 11.9291 9.72276C14.9242 8.68098 19.1919 8 24 8C28.8081 8 33.0758 8.68098 36.0709 9.72276C37.5778 10.2469 38.6545 10.8254 39.3151 11.3686C39.9006 11.8501 39.9857 12.1489 39.998 12.236ZM4.95178 15.2312L21.4543 41.6973C22.6288 43.5809 25.3712 43.5809 26.5457 41.6973L43.0534 15.223C43.0709 15.1948 43.0878 15.1662 43.104 15.1371L41.3563 14.1648C43.104 15.1371 43.1038 15.1374 43.104 15.1371L43.1051 15.135L43.1065 15.1325L43.1101 15.1261L43.1199 15.1082C43.1276 15.094 43.1377 15.0754 43.1497 15.0527C43.1738 15.0075 43.2062 14.9455 43.244 14.8701C43.319 14.7208 43.4196 14.511 43.5217 14.2683C43.6901 13.8679 44 13.0689 44 12.2609C44 10.5573 43.003 9.22254 41.8558 8.2791C40.6947 7.32427 39.1354 6.55361 37.385 5.94477C33.8654 4.72057 29.133 4 24 4C18.867 4 14.1346 4.72057 10.615 5.94478C8.86463 6.55361 7.30529 7.32428 6.14419 8.27911C4.99695 9.22255 3.99999 10.5573 3.99999 12.2609C3.99999 13.1275 4.29264 13.9078 4.49321 14.3607C4.60375 14.6102 4.71348 14.8196 4.79687 14.9689C4.83898 15.0444 4.87547 15.1065 4.9035 15.1529C4.91754 15.1762 4.92954 15.1957 4.93916 15.2111L4.94662 15.223L4.95178 15.2312ZM35.9868 18.996L24 38.22L12.0131 18.996C12.4661 19.1391 12.9179 19.2658 13.3617 19.3718C16.4281 20.1039 20.0901 20.5217 24 20.5217C27.9099 20.5217 31.5719 20.1039 34.6383 19.3718C35.082 19.2658 35.5339 19.1391 35.9868 18.996Z" fill="currentColor" fill-rule="evenodd"></path>
</svg>
</div>
<p class="text-sm text-gray-400">© 2024 Our Water, Our Future. All Rights Reserved.</p>
</div>
<div class="flex items-center gap-4 text-gray-400">
<a class="hover:text-primary" href="#">Privacy Policy</a>
<a class="hover:text-primary" href="#">Terms of Service</a>
</div>
</div>
</div>
</footer>
</div>
</div>
</body></html>
