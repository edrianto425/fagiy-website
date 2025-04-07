# fagiy-website<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fagiy - Percetakan Foto Elegan</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-white shadow-md">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-gray-800">Fagiy</h1>
      <nav class="space-x-4">
        <a href="#produk" class="hover:text-blue-600">Produk</a>
        <a href="#galeri" class="hover:text-blue-600">Galeri</a>
        <a href="#kontak" class="hover:text-blue-600">Kontak</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-[url('https://source.unsplash.com/1600x600/?photo,polaroid')] bg-cover bg-center text-white py-32 px-4">
    <div class="max-w-4xl mx-auto text-center backdrop-blur-sm bg-black/50 p-6 rounded-xl">
      <h2 class="text-4xl font-bold mb-4">Percetakan Foto Elegan</h2>
      <p class="text-lg">Spesialis Polaroid, Foto Strip, dan Stiker Kustom</p>
    </div>
  </section>

  <!-- Produk -->
  <section id="produk" class="py-16 px-4 max-w-6xl mx-auto">
    <h3 class="text-3xl font-semibold mb-8 text-center">Produk Unggulan</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white shadow-lg rounded-xl p-6 text-center">
        <img src="https://source.unsplash.com/300x200/?polaroid" alt="Polaroid" class="mx-auto rounded-md mb-4" />
        <h4 class="font-bold text-xl mb-2">Foto Polaroid</h4>
        <p>Hasil cetak klasik nan elegan dalam gaya retro yang tak lekang oleh waktu.</p>
      </div>
      <div class="bg-white shadow-lg rounded-xl p-6 text-center">
        <img src="https://source.unsplash.com/300x200/?photo,strip" alt="Foto Strip" class="mx-auto rounded-md mb-4" />
        <h4 class="font-bold text-xl mb-2">Foto Strip</h4>
        <p>Ideal untuk kenangan momen spesial bersama teman atau pasangan.</p>
      </div>
      <div class="bg-white shadow-lg rounded-xl p-6 text-center">
        <img src="https://source.unsplash.com/300x200/?sticker,custom" alt="Stiker" class="mx-auto rounded-md mb-4" />
        <h4 class="font-bold text-xl mb-2">Stiker Kustom</h4>
        <p>Desain bebas, cetakan tajam, cocok untuk dekorasi maupun branding produk.</p>
      </div>
    </div>
  </section>

  <!-- Galeri -->
  <section id="galeri" class="bg-gray-100 py-16 px-4">
    <h3 class="text-3xl font-semibold mb-8 text-center">Galeri Hasil Cetakan</h3>
    <div class="grid md:grid-cols-3 gap-6 max-w-6xl mx-auto">
      <img src="https://source.unsplash.com/400x400/?photo,print" class="rounded-lg shadow-md" />
      <img src="https://source.unsplash.com/400x400/?polaroid,print" class="rounded-lg shadow-md" />
      <img src="https://source.unsplash.com/400x400/?photostrip" class="rounded-lg shadow-md" />
    </div>
  </section>

  <!-- Kontak -->
  <section id="kontak" class="py-16 px-4 max-w-3xl mx-auto text-center">
    <h3 class="text-3xl font-semibold mb-6">Hubungi Kami</h3>
    <p class="mb-2">Telp/WA: <a href="tel:085379595724" class="text-blue-600">0853-7959-5724</a></p>
    <p class="mb-2">Email: <a href="mailto:edriantomfarhan@gmail.com" class="text-blue-600">edriantomfarhan@gmail.com</a></p>
    <p class="mb-2">Instagram: <a href="https://instagram.com/" class="text-blue-600">@fagiy</a></p>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-6 text-center">
    <p>&copy; 2025 Fagiy. All rights reserved.</p>
  </footer>

</body>
</html>
