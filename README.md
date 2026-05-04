<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>نسق — نوثق اللحظة ونصنع أثر</title>

  <script src="https://cdn.tailwindcss.com"></script>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    *{
      font-family: 'Cairo', sans-serif;
    }

    body{
      background:#050505;
      color:white;
      overflow-x:hidden;
    }

    .glass{
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      border:1px solid rgba(255,255,255,0.08);
    }

    .glow{
      box-shadow:0 0 40px rgba(255,255,255,0.08);
    }

    .hero-bg{
      background:
      radial-gradient(circle at top right, rgba(255,255,255,0.12), transparent 30%),
      radial-gradient(circle at bottom left, rgba(255,255,255,0.08), transparent 30%),
      #050505;
    }

    .social-btn:hover{
      transform:translateY(-4px);
      transition:0.3s ease;
    }
  </style>
</head>

<body>

<!-- HERO (CENTER FIXED) -->
<section class="hero-bg min-h-screen flex items-center justify-center px-6 py-16 text-center">
  <div class="max-w-6xl mx-auto flex flex-col items-center text-center gap-10">

    <div class="flex flex-col items-center text-center">

      <span class="glass px-4 py-2 rounded-full text-sm inline-block mb-6">
        فريق نسق الإعلامي
      </span>

      <h1 class="text-5xl lg:text-7xl font-extrabold leading-tight mb-6">
        نسق
      </h1>

      <p class="text-2xl text-zinc-300 mb-8 leading-loose">
        نوثق اللحظة ونصنع أثر
      </p>

      <div class="flex flex-wrap justify-center gap-4">
        <a href="https://drive.google.com/drive/folders/1Gj6kYyi6ld1idqEorOPaF_dF2KGFODzR?usp=drive_link"
           target="_blank"
           class="bg-white text-black px-8 py-4 rounded-2xl font-bold hover:scale-105 transition">
           مشاهدة ملف الأعمال
        </a>

        <a href="#contact"
           class="glass px-8 py-4 rounded-2xl font-bold hover:scale-105 transition">
           تواصل معنا
        </a>
      </div>

    </div>

    <!-- SERVICES -->
    <div class="glass glow rounded-[40px] p-8 w-full max-w-4xl">
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 text-center">

        <div class="bg-zinc-900 rounded-3xl p-6">
          <div class="text-4xl mb-4">📸</div>
          <h3 class="font-bold text-xl mb-2">تصوير</h3>
          <p class="text-zinc-400 text-sm">تصوير فوتوغرافي وفيديو احترافي</p>
        </div>

        <div class="bg-zinc-900 rounded-3xl p-6">
          <div class="text-4xl mb-4">🎬</div>
          <h3 class="font-bold text-xl mb-2">مونتاج</h3>
          <p class="text-zinc-400 text-sm">مونتاج وصناعة محتوى إبداعي</p>
        </div>

        <div class="bg-zinc-900 rounded-3xl p-6">
          <div class="text-4xl mb-4">🎨</div>
          <h3 class="font-bold text-xl mb-2">تصميم بصري</h3>
          <p class="text-zinc-400 text-sm">هويات بصرية وتصاميم إعلامية</p>
        </div>

        <div class="bg-zinc-900 rounded-3xl p-6">
          <div class="text-4xl mb-4">🚀</div>
          <h3 class="font-bold text-xl mb-2">صناعة أثر</h3>
          <p class="text-zinc-400 text-sm">محتوى يترك انطباعًا لا يُنسى</p>
        </div>

      </div>
    </div>

  </div>
</section>

<!-- PORTFOLIO -->
<section class="px-6 py-24 text-center">
  <div class="max-w-4xl mx-auto">

    <span class="glass px-4 py-2 rounded-full text-sm inline-block mb-5">
      أعمالنا
    </span>

    <h2 class="text-4xl lg:text-5xl font-extrabold mb-6">
      ملف أعمال فريق نسق
    </h2>

    <p class="text-zinc-400 mb-12 leading-loose">
      استعرض نماذج من أعمالنا في التصوير وصناعة المحتوى والتغطيات الإعلامية.
    </p>

    <div class="glass rounded-[35px] p-10 glow">

      <div class="text-7xl mb-6">🎞️</div>

      <h3 class="text-3xl font-bold mb-5">
        اضغط للدخول إلى ملف الأعمال
      </h3>

      <p class="text-zinc-400 mb-8 leading-loose">
        جميع الأعمال والتغطيات والمشاريع موجودة داخل ملف Google Drive.
      </p>

      <a href="https://drive.google.com/drive/folders/1Gj6kYyi6ld1idqEorOPaF_dF2KGFODzR?usp=drive_link"
         target="_blank"
         class="inline-block bg-white text-black px-10 py-5 rounded-2xl font-extrabold hover:scale-105 transition">
         فتح ملف الأعمال
      </a>

    </div>

  </div>
</section>

<!-- SOCIAL -->
<section id="contact" class="px-6 pb-24 text-center">
  <div class="max-w-4xl mx-auto">

    <span class="glass px-4 py-2 rounded-full text-sm inline-block mb-5">
      التواصل
    </span>

    <h2 class="text-4xl lg:text-5xl font-extrabold mb-6">
      تواصل معنا
    </h2>

    <p class="text-zinc-400 mb-12 leading-loose">
      تابع أعمالنا أو تواصل معنا عبر حساباتنا الرسمية.
    </p>

    <div class="grid md:grid-cols-2 gap-6">

      <a href="https://www.instagram.com/nasaq_ar?igsh=MW41Mm03bHpzb2ExOA=="
         target="_blank"
         class="social-btn glass rounded-[30px] p-10 block">

        <div class="text-6xl mb-6">📷</div>
        <h3 class="text-2xl font-bold mb-3">Instagram</h3>
        <p class="text-zinc-400 mb-5">@nasaq_ar</p>

        <span class="bg-white text-black px-6 py-3 rounded-xl inline-block font-bold">
          زيارة الحساب
        </span>
      </a>

      <a href="https://www.tiktok.com/@nasaq_ar?_r=1&_t=ZS-965D8cJLkfc"
         target="_blank"
         class="social-btn glass rounded-[30px] p-10 block">

        <div class="text-6xl mb-6">🎵</div>
        <h3 class="text-2xl font-bold mb-3">TikTok</h3>
        <p class="text-zinc-400 mb-5">@nasaq_ar</p>

        <span class="bg-white text-black px-6 py-3 rounded-xl inline-block font-bold">
          زيارة الحساب
        </span>
      </a>

    </div>

  </div>
</section>

<!-- FOOTER -->
<footer class="border-t border-zinc-800 py-8 text-center text-zinc-500">
  <p>© 2026 Nasaq Media — جميع الحقوق محفوظة</p>
</footer>

</body>
</html>
