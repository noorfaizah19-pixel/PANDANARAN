<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Belajar Surah Al-Kautsar - Kelas 3 SD</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Fredoka', sans-serif; }
  </style>
</head>
<body class="bg-emerald-50 min-h-screen pb-10">

  <!-- Header -->
  <header class="bg-emerald-600 text-white p-6 shadow-lg text-center rounded-b-3xl">
    <h1 class="text-3xl md:text-4xl font-bold tracking-wide">📖 Belajar Surah Al-Kautsar</h1>
    <p class="text-emerald-100 text-sm md:text-base mt-1">Materi PAI & BP Kelas 3 SD</p>
  </header>

  <!-- Navigasi Tab -->
  <div class="max-w-2xl mx-auto mt-6 px-4 flex justify-center gap-2">
    <button onclick="switchTab('materi')" id="btn-materi" class="tab-btn bg-emerald-600 text-white font-semibold py-2 px-4 rounded-xl shadow transition">
      📚 Materi
    </button>
    <button onclick="switchTab('ayat')" id="btn-ayat" class="tab-btn bg-white text-emerald-700 font-semibold py-2 px-4 rounded-xl shadow hover:bg-emerald-100 transition">
      🕌 Ayat & Arti
    </button>
    <button onclick="switchTab('tajwid')" id="btn-tajwid" class="tab-btn bg-white text-emerald-700 font-semibold py-2 px-4 rounded-xl shadow hover:bg-emerald-100 transition">
      ✨ Mad Thabi'i
    </button>
    <button onclick="switchTab('kuis')" id="btn-kuis" class="tab-btn bg-white text-emerald-700 font-semibold py-2 px-4 rounded-xl shadow hover:bg-emerald-100 transition">
      ⭐ Kuis
    </button>
  </div>

  <main class="max-w-2xl mx-auto mt-6 px-4">

    <!-- TAB 1: MATERI UMUM -->
    <section id="tab-materi" class="tab-content bg-white p-6 rounded-3xl shadow-md border-2 border-emerald-100 space-y-6">
      <!-- Identitas -->
      <div>
        <h2 class="text-xl font-bold text-emerald-700 mb-3 border-b-2 border-emerald-200 pb-1">
          📌 Identitas Surah
        </h2>
        <ul class="space-y-2 text-gray-700">
          <li class="flex items-center gap-2"><span class="text-emerald-500">▪</span> <b>Urutan:</b> Surah ke-108 dalam Al-Qur'an</li>
          <li class="flex items-center gap-2"><span class="text-emerald-500">▪</span> <b>Jumlah Ayat:</b> 3 Ayat</li>
          <li class="flex items-center gap-2"><span class="text-emerald-500">▪</span> <b>Tempat Turun:</b> Kota Mekah (Surah Makkiyah)</li>
          <li class="flex items-center gap-2"><span class="text-emerald-500">▪</span> <b>Arti Nama:</b> Nikmat yang banyak</li>
        </ul>
      </div>

      <!-- Asbabun Nuzul -->
      <div>
        <h2 class="text-xl font-bold text-emerald-700 mb-3 border-b-2 border-emerald-200 pb-1">
          📜 Asbabun Nuzul (Sebab Turunnya Surah)
        </h2>
        <p class="text-gray-700 leading-relaxed bg-amber-50 p-4 rounded-2xl border border-amber-200">
          Surah ini turun ketika Nabi Muhammad SAW merasa sedih karena putranya meninggal dunia. Kaum kafir Quraisy mengejek Nabi terputus keturunannya. Allah SWT lalu menurunkan Surah Al-Kautsar untuk <b>menghibur dan membela Nabi Muhammad SAW</b>.
        </p>
      </div>

      <!-- Pesan Pokok -->
      <div>
        <h2 class="text-xl font-bold text-emerald-700 mb-3 border-b-2 border-emerald-200 pb-1">
          💡 Pesan Pokok
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-3 text-center">
          <div class="bg-emerald-100 p-3 rounded-2xl">
            <div class="text-2xl mb-1">🤲</div>
            <p class="text-sm font-semibold text-emerald-900">Bersyukur atas nikmat Allah</p>
          </div>
          <div class="bg-emerald-100 p-3 rounded-2xl">
            <div class="text-2xl mb-1">🕋</div>
            <p class="text-sm font-semibold text-emerald-900">Rajin sholat dan berkurban</p>
          </div>
          <div class="bg-emerald-100 p-3 rounded-2xl">
            <div class="text-2xl mb-1">❤️</div>
            <p class="text-sm font-semibold text-emerald-900">Mencintai Nabi Muhammad SAW</p>
          </div>
        </div>
      </div>
    </section>

    <!-- TAB 2: AYAT & ARTI -->
    <section id="tab-ayat" class="tab-content hidden space-y-4">
      <!-- Ayat 1 -->
      <div class="bg-white p-5 rounded-3xl shadow-md border-2 border-emerald-100">
        <span class="bg-emerald-600 text-white px-3 py-1 rounded-full text-xs font-bold">Ayat 1</span>
        <p class="text-right text-3xl font-bold text-emerald-800 my-3 leading-loose">اِنَّآ أَعْطَيْنَاكَ الْكَوْثَرَ</p>
        <p class="text-emerald-700 font-semibold italic text-sm">Innaa a'tainaakal-kausar</p>
        <p class="text-gray-600 text-sm mt-1">"Sungguh, Kami telah memberimu (Muhammad) nikmat yang banyak."</p>
      </div>

      <!-- Ayat 2 -->
      <div class="bg-white p-5 rounded-3xl shadow-md border-2 border-emerald-100">
        <span class="bg-emerald-600 text-white px-3 py-1 rounded-full text-xs font-bold">Ayat 2</span>
        <p class="text-right text-3xl font-bold text-emerald-800 my-3 leading-loose">فَصَلِّ لِرَبِّكَ وَانْحَرْ</p>
        <p class="text-emerald-700 font-semibold italic text-sm">Fa salli lirabbika wanhar</p>
        <p class="text-gray-600 text-sm mt-1">"Maka laksanakanlah sholat karena Tuhanmu, dan berkurbanlah."</p>
      </div>

      <!-- Ayat 3 -->
      <div class="bg-white p-5 rounded-3xl shadow-md border-2 border-emerald-100">
        <span class="bg-emerald-600 text-white px-3 py-1 rounded-full text-xs font-bold">Ayat 3</span>
        <p class="text-right text-3xl font-bold text-emerald-800 my-3 leading-loose">إِنَّ شَانِئَكَ هُوَ الْأَبْتَرُ</p>
        <p class="text-emerald-700 font-semibold italic text-sm">Inna sani'aka huwal-abtar</p>
        <p class="text-gray-600 text-sm mt-1">"Sungguh, orang-orang yang membencimu, dialah yang terputus (dari rahmat Allah)."</p>
      </div>
    </section>

    <!-- TAB 3: MATERI MAD THABI'I -->
    <section id="tab-tajwid" class="tab-content hidden bg-white p-6 rounded-3xl shadow-md border-2 border-emerald-100 space-y-5">
      <h2 class="text-xl font-bold text-emerald-700 border-b-2 border-emerald-200 pb-2">
        ✨ Hukum Tajwid: Mad Thabi'i (Mad Asli)
      </h2>

      <!-- Penjelasan Dasar -->
      <div class="bg-emerald-50 p-4 rounded-2xl border border-emerald-200 text-gray-700 text-sm leading-relaxed">
        <p><b>Mad</b> artinya <i>panjang</i>, sedangkan <b>Thabi'i</b> artinya <i>biasa/asli</i>.</p>
        <p class="mt-2"><b>Mad Thabi'i</b> terjadi apabila ada huruf hijaiyah yang bertemu dengan huruf mad:</p>
        <ul class="list-disc list-inside mt-2 space-y-1 font-semibold text-emerald-900">
          <li>Fathah ( َ ) bertemu Alif ( ا )</li>
          <li>Kasrah ( ِ ) bertemu Ya Sukun ( يْ )</li>
          <li>Dhammah ( ُ ) bertemu Wawu Sukun ( وْ )</li>
        </ul>
        <p class="mt-2 text-xs bg-emerald-200 text-emerald-900 px-3 py-1 rounded-lg inline-block font-bold">
          📏 Cara membaca: Dibaca panjang 2 Harakat (1 Alif / 2 ketukan).
        </p>
      </div>

      <!-- Contoh Pada Surah Al-Kautsar -->
      <div>
        <h3 class="font-bold text-emerald-800 text-base mb-3">🔍 Contoh Mad Thabi'i dalam Surah Al-Kautsar:</h3>
        
        <div class="space-y-3">
          <!-- Contoh 1 -->
          <div class="flex items-center justify-between bg-amber-50 p-3 rounded-2xl border border-amber-200">
            <div>
              <p class="text-xs text-amber-700 font-bold">Ayat 1</p>
              <p class="text-sm font-semibold text-gray-800">أَعْطَيْنَاكَ <span class="text-xs text-gray-500">(a'tai<span class="text-amber-700 font-bold underline">naa</span>ka)</span></p>
              <p class="text-xs text-gray-600">Huruf <b>Nun fathah (نَ)</b> bertemu <b>Alif (ا)</b></p>
            </div>
            <span class="text-2xl font-bold text-amber-800">نَا</span>
          </div>

          <!-- Contoh 2 -->
          <div class="flex items-center justify-between bg-amber-50 p-3 rounded-2xl border border-amber-200">
            <div>
              <p class="text-xs text-amber-700 font-bold">Ayat 3</p>
              <p class="text-sm font-semibold text-gray-800">شَانِئَكَ <span class="text-xs text-gray-500">(<span class="text-amber-700 font-bold underline">shaa</span>ni'aka)</span></p>
              <p class="text-xs text-gray-600">Huruf <b>Syin fathah (شَ)</b> bertemu <b>Alif (ا)</b></p>
            </div>
            <span class="text-2xl font-bold text-amber-800">شَا</span>
          </div>
        </div>
      </div>
    </section>

    <!-- TAB 4: KUIS -->
    <section id="tab-kuis" class="tab-content hidden bg-white p-6 rounded-3xl shadow-md border-2 border-emerald-100">
      <h2 class="text-xl font-bold text-emerald-700 mb-4 text-center">🎯 Kuis Latihan Soal</h2>
      
      <form id="quiz-form" class="space-y-6">
        <!-- Soal 1 -->
        <div>
          <p class="font-semibold text-gray-800">1. Surah Al-Kautsar terdiri dari berapa ayat?</p>
          <div class="mt-2 space-y-2">
            <label class="block bg-emerald-50 p-3 rounded-xl cursor-pointer hover:bg-emerald-100"><input type="radio" name="q1" value="A"> A. 3 ayat</label>
            <label class="block bg-emerald-50 p-3 rounded-xl cursor-pointer hover:bg-emerald-100"><input type="radio" name="q1" value="B"> B. 5 ayat</label>
          </div>
        </div>

        <!-- Soal 2 -->
        <div>
          <p class="font-semibold text-gray-800">2. Al-Kautsar artinya...</p>
          <div class="mt-2 space-y-2">
            <label class="block bg-emerald-50 p-3 rounded-xl cursor-pointer hover:bg-emerald-100"><input type="radio" name="q2" value="A"> A. Pertolongan</label>
            <label class="block bg-emerald-50 p-3 rounded-xl cursor-pointer hover:bg-emerald-100"><input type="radio" name="q2" value="B"> B. Nikmat yang banyak</label>
          </div>
        </div>

        <!-- Soal 3 -->
        <div>
          <p class="font-semibold text-gray-800">3. Panjang bacaan Mad Thabi'i adalah...</p>
          <div class="mt-2 space-y-2">
            <label class="block bg-emerald-50 p-3 rounded-xl cursor-pointer hover:bg-emerald-100"><input type="radio" name="q3" value="A"> A. 2 harakat</label>
            <label class="block bg-emerald-50 p-3 rounded-xl cursor-pointer hover:bg-emerald-100"><input type="radio" name="q3" value="B"> B. 6 harakat</label>
          </div>
        </div>

        <button type="button" onclick="submitQuiz()" class="w-full bg-emerald-600 text-white font-bold py-3 rounded-2xl shadow hover:bg-emerald-700 transition">
          Kirim Jawaban
        </button>
      </form>

      <!-- Hasil Kuis -->
      <div id="quiz-result" class="hidden mt-6 text-center p-4 bg-amber-100 rounded-2xl border border-amber-300">
        <h3 class="text-2xl font-bold text-amber-800" id="score-text"></h3>
        <p class="text-amber-700 mt-1" id="feedback-text"></p>
      </div>
    </section>

  </main>

  <script>
    function switchTab(tabName) {
      document.querySelectorAll('.tab-content').forEach(tab => tab.classList.add('hidden'));
      document.querySelectorAll('.tab-btn').forEach(btn => {
        btn.classList.remove('bg-emerald-600', 'text-white');
        btn.classList.add('bg-white', 'text-emerald-700');
      });

      document.getElementById('tab-' + tabName).classList.remove('hidden');
      const activeBtn = document.getElementById('btn-' + tabName);
      activeBtn.classList.add('bg-emerald-600', 'text-white');
      activeBtn.classList.remove('bg-white', 'text-emerald-700');
    }

    function submitQuiz() {
      const answers = { q1: 'A', q2: 'B', q3: 'A' };
      let score = 0;
      
      const q1 = document.querySelector('input[name="q1"]:checked')?.value;
      const q2 = document.querySelector('input[name="q2"]:checked')?.value;
      const q3 = document.querySelector('input[name="q3"]:checked')?.value;

      if (!q1 || !q2 || !q3) {
        alert("Jawab semua pertanyaan dulu ya!");
        return;
      }

      if (q1 === answers.q1) score += 33.3;
      if (q2 === answers.q2) score += 33.3;
      if (q3 === answers.q3) score += 33.4;

      const finalScore = Math.round(score);
      const resultDiv = document.getElementById('quiz-result');
      const scoreText = document.getElementById('score-text');
      const feedbackText = document.getElementById('feedback-text');

      resultDiv.classList.remove('hidden');
      scoreText.innerText = "Nilai Kamu: " + finalScore;

      if (finalScore === 100) {
        feedbackText.innerText = "Hebat sekali! Kamu sudah paham Surah Al-Kautsar dan Mad Thabi'i! 🎉";
      } else {
        feedbackText.innerText = "Bagus! Coba baca lagi materinya dan ulangi kuisnya ya! 💪";
      }
    }
  </script>
</body>
</html>
