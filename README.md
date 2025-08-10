
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Haute Estate</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <meta name="description" content="Haute Estate — Curated luxury homes & lifestyle. Follow @HauteEstate on Instagram.">
  <!-- Tailwind via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root{--accent:#b8860b; --bg:#0b0b0b}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial}
    h1,h2,h3{font-family:'Playfair Display', serif}
  </style>
</head>
<body class="bg-white text-gray-900">
  <!-- NAV -->
  <header class="border-b">
    <div class="max-w-6xl mx-auto flex items-center justify-between p-6">
      <a href="#" class="flex items-center gap-3">
        <div class="w-10 h-10 rounded-full bg-black text-white flex items-center justify-center font-semibold">HE</div>
        <div>
          <div class="text-sm font-semibold">Haute Estate</div>
          <div class="text-xs text-gray-500">Curated Luxury Living</div>
        </div>
      </a>
      <nav class="hidden md:flex gap-6 items-center text-sm">
        <a href="#listings" class="hover:text-gray-700">Listings</a>
        <a href="#about" class="hover:text-gray-700">About</a>
        <a href="#contact" class="hover:text-gray-700">Contact</a>
        <a href="https://instagram.com/HauteEstate" target="_blank" class="inline-block px-4 py-2 border rounded-md text-sm font-medium" style="border-color:var(--accent); color:var(--accent)">Follow @HauteEstate</a>
      </nav>
      <button id="menuBtn" class="md:hidden">☰</button>
    </div>
    <div id="mobileMenu" class="hidden border-t md:hidden">
      <div class="p-4 flex flex-col gap-3">
        <a href="#listings">Listings</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a href="https://instagram.com/HauteEstate" target="_blank">Instagram</a>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <section class="bg-[url('https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?q=80&w=1600&auto=format&fit=crop&ixlib=rb-4.0.3&s=0a2f7d0f1a2cbb4a4b0b6b5ea4fb6d5b')] bg-cover bg-center">
    <div class="backdrop-brightness-75">
      <div class="max-w-6xl mx-auto p-12 text-white flex flex-col md:flex-row items-center gap-8">
        <div class="md:w-1/2">
          <h1 class="text-4xl md:text-5xl font-bold leading-tight">Haute Estate</h1>
          <p class="mt-4 text-lg max-w-lg">Exclusive luxury homes, curated with taste. Follow our Instagram for daily reveals and design inspiration.</p>
          <div class="mt-6 flex gap-3">
            <a href="#listings" class="px-6 py-3 bg-white text-black rounded-md font-medium">View Listings</a>
            <a href="https://instagram.com/HauteEstate" target="_blank" class="px-6 py-3 border rounded-md" style="border-color:var(--accent); color:var(--accent)">Follow on Instagram</a>
          </div>
        </div>
        <div class="md:w-1/2 grid grid-cols-2 gap-3">
          <!-- small preview images -->
          <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=8c3c1b2e4f1a3bdc" alt="property" class="w-full h-40 object-cover rounded-lg">
          <img src="https://images.unsplash.com/photo-1554995207-c18c203602cb?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=7d6e0c7f5f6b8d9a" alt="interior" class="w-full h-40 object-cover rounded-lg">
          <img src="https://images.unsplash.com/photo-1533777324565-a040eb52fac2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=2b5f6f7a1a" alt="kitchen" class="w-full h-40 object-cover rounded-lg">
          <img src="https://images.unsplash.com/photo-1505691723518-36a8b6f9a5d6?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=4e6b3f7b" alt="exterior" class="w-full h-40 object-cover rounded-lg">
        </div>
      </div>
    </div>
  </section>

  <!-- FEATURED LISTINGS -->
  <section id="listings" class="max-w-6xl mx-auto p-8">
    <div class="flex items-center justify-between">
      <h2 class="text-2xl font-semibold">Featured Listings</h2>
      <a href="#" class="text-sm underline">See all</a>
    </div>
    <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- card -->
      <article class="group border rounded-lg overflow-hidden">
        <div class="relative">
          <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?q=80&w=1400&auto=format&fit=crop&ixlib=rb-4.0.3&s=8c3c1b2e4f1a3bdc" alt="listing" class="w-full h-56 object-cover transition-transform group-hover:scale-105">
          <div class="absolute left-4 top-4 bg-black/60 text-white px-3 py-1 rounded">Just Listed</div>
        </div>
        <div class="p-4">
          <div class="text-sm text-gray-500">Beverly Hills • 5 Beds · 6 Baths · 6,200 sqft</div>
          <h3 class="mt-2 font-semibold">Modern Mediterranean Villa</h3>
          <p class="mt-2 text-gray-600 text-sm">Exquisite finishes, private gardens, and panoramic views. Designed for refined living.</p>
          <div class="mt-4 flex items-center justify-between">
            <div class="text-lg font-bold">$8,500,000</div>
            <a href="#contact" class="text-sm underline">Request Showing</a>
          </div>
        </div>
      </article>

      <!-- card 2 -->
      <article class="group border rounded-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1549187774-b4e9f0441d3f?q=80&w=1400&auto=format&fit=crop&ixlib=rb-4.0.3&s=7b4c3d7e" alt="listing" class="w-full h-56 object-cover transition-transform group-hover:scale-105">
        <div class="p-4">
          <div class="text-sm text-gray-500">Malibu • 4 Beds · 4 Baths · 3,400 sqft</div>
          <h3 class="mt-2 font-semibold">Cliffside Contemporary</h3>
          <p class="mt-2 text-gray-600 text-sm">Floor-to-ceiling glass and private beach access make this a coastal sanctuary.</p>
          <div class="mt-4 flex items-center justify-between">
            <div class="text-lg font-bold">$5,200,000</div>
            <a href="#contact" class="text-sm underline">Request Showing</a>
          </div>
        </div>
      </article>

      <!-- card 3 -->
      <article class="group border rounded-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1507089947368-19c1da9775ae?q=80&w=1400&auto=format&fit=crop&ixlib=rb-4.0.3&s=2f1c9b2a" alt="listing" class="w-full h-56 object-cover transition-transform group-hover:scale-105">
        <div class="p-4">
          <div class="text-sm text-gray-500">Los Angeles • 6 Beds · 7 Baths · 8,000 sqft</div>
          <h3 class="mt-2 font-semibold">Hollywood Hills Estate</h3>
          <p class="mt-2 text-gray-600 text-sm">A cinematic property with infinity pool, home cinema, and expansive outdoor entertaining.</p>
          <div class="mt-4 flex items-center justify-between">
            <div class="text-lg font-bold">$12,900,000</div>
            <a href="#contact" class="text-sm underline">Request Showing</a>
          </div>
        </div>
      </article>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="bg-gray-50 py-12">
    <div class="max-w-4xl mx-auto p-6 text-center">
      <h2 class="text-2xl font-semibold">About Haute Estate</h2>
      <p class="mt-4 text-gray-700">Haute Estate curates a selective portfolio of luxury residences and lifestyle experiences. We share exclusive previews and intimate design stories on our Instagram — a living lookbook for buyers who appreciate craft and discretion.</p>
    </div>
  </section>

  <!-- INSTAGRAM / SOCIAL EMBED -->
  <section class="max-w-6xl mx-auto p-8">
    <h2 class="text-2xl font-semibold">From Instagram</h2>
    <p class="text-sm text-gray-500 mt-1">Latest posts from @HauteEstate</p>
    <div class="mt-6 grid grid-cols-2 md:grid-cols-4 gap-3">
      <!-- Replace these image blocks with an Instagram embed or use a plugin to show your real feed -->
      <img src="https://images.unsplash.com/photo-1523217582562-09d0def993a6?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=3b2d" alt="ig1" class="w-full h-40 object-cover rounded-md">
      <img src="https://images.unsplash.com/photo-1505691723518-36a8b6f9a5d6?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=4e6b3f7b" alt="ig2" class="w-full h-40 object-cover rounded-md">
      <img src="https://images.unsplash.com/photo-1560347876-aeef00ee58a1?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=9a8b" alt="ig3" class="w-full h-40 object-cover rounded-md">
      <img src="https://images.unsplash.com/photo-1499951360447-b19be8fe80f5?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=6c7d" alt="ig4" class="w-full h-40 object-cover rounded-md">
    </div>
    <div class="mt-4 text-center">
      <a href="https://instagram.com/HauteEstate" target="_blank" class="inline-block px-6 py-3 border rounded-md" style="border-color:var(--accent); color:var(--accent)">Visit @HauteEstate</a>
    </div>
  </section>

  <!-- CONTACT -->
  <footer id="contact" class="bg-black text-white py-12">
    <div class="max-w-6xl mx-auto p-6 grid grid-cols-1 md:grid-cols-3 gap-6">
      <div>
        <h3 class="text-lg font-semibold">Get in touch</h3>
        <p class="mt-2 text-gray-300">For inquiries, showings, or collaborations — reach out.</p>
        <p class="mt-4 text-sm">Email: <a href="mailto:hello@hauteestate.com" class="underline">hello@hauteestate.com</a></p>
      </div>
      <div>
        <h3 class="text-lg font-semibold">Sign up</h3>
        <p class="mt-2 text-gray-300 text-sm">Join our VIP list for early access to new listings.</p>
        <form action="mailto:hello@hauteestate.com" method="post" enctype="text/plain" class="mt-3 flex flex-col gap-2">
          <input name="name" placeholder="Name" class="p-2 rounded text-black" />
          <input name="email" placeholder="Email" class="p-2 rounded text-black" />
          <button type="submit" class="mt-2 px-4 py-2 bg-white text-black rounded">Join VIP List</button>
        </form>
      </div>
    </div>
    <div class="border-t border-gray-800 mt-6 pt-6 text-center text-sm text-gray-400">© <span id="year"></span> Haute Estate — All rights reserved.</div>
  </footer>

  <script>
    // Mobile menu
    document.getElementById('menuBtn').addEventListener('click', function(){
      const m = document.getElementById('mobileMenu');
      m.classList.toggle('hidden');
    });
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>

  <!-- NOTES:
    - Replace example images with your listing photos (optimize to web-sized images).
    - Replace Instagram links and consider adding an Instagram embed script or a 3rd-party plugin for live feed.
    - For production, replace mailto form with a backend (Formspree, Netlify Forms, or your own API) to capture leads.
  -->
</body>
</html>
