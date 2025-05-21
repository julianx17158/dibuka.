<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Ucapan Selamat Ulang Tahun untuk Asfa Ilham
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <style>
   @keyframes confetti-fall {
      0% {
        transform: translateY(-100%) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }
    .confetti {
      position: fixed;
      width: 10px;
      height: 10px;
      background-color: #f43f5e;
      opacity: 0.9;
      animation-name: confetti-fall;
      animation-timing-function: linear;
      animation-iteration-count: infinite;
      border-radius: 2px;
      z-index: 50;
      pointer-events: none;
    }
    .confetti:nth-child(2n) {
      background-color: #fbbf24;
      width: 8px;
      height: 8px;
      border-radius: 50%;
    }
    .confetti:nth-child(3n) {
      background-color: #3b82f6;
      width: 12px;
      height: 6px;
      border-radius: 1px;
    }
    .confetti:nth-child(4n) {
      background-color: #10b981;
      width: 6px;
      height: 12px;
      border-radius: 3px;
    }
    #message {
      transition: opacity 0.6s ease-in-out;
      opacity: 0;
    }
    #message.show {
      opacity: 1;
    }
  </style>
 </head>
 <body class="bg-gradient-to-br from-pink-400 via-purple-500 to-indigo-600 min-h-screen flex items-center justify-center p-6 relative overflow-hidden">
  <div aria-hidden="true" id="confetti-container">
  </div>
  <main class="relative z-10 max-w-lg w-full bg-white bg-opacity-90 rounded-3xl shadow-2xl p-10 text-center select-text">
   <h1 class="text-4xl font-extrabold text-pink-600 mb-6 drop-shadow-lg flex items-center justify-center gap-3">
    <i class="fas fa-birthday-cake">
    </i>
    Selamat Ulang Tahun, Asfa Ilham!
    <i class="fas fa-birthday-cake">
    </i>
   </h1>
   <img alt="A birthday cake with lit candles and colorful decorations on a festive table" class="mx-auto rounded-full shadow-lg mb-8" height="200" loading="lazy" src="https://storage.googleapis.com/a1aa/image/7fdab3be-1f51-4102-302a-2c66f02faf9f.jpg" width="200"/>
   <p aria-atomic="true" aria-live="polite" class="min-h-[6rem] text-lg text-gray-800 font-semibold px-4 mb-8" id="message">
   </p>
   <button aria-label="Tampilkan ucapan selamat ulang tahun untuk Asfa Ilham" class="inline-flex items-center gap-3 bg-pink-600 hover:bg-pink-700 focus:ring-4 focus:ring-pink-300 focus:outline-none text-white font-bold py-3 px-8 rounded-full shadow-lg transition-colors duration-300 mx-auto" onclick="showMessage()">
    <i class="fas fa-envelope-open-text text-xl">
    </i>
    Tampilkan Ucapan
   </button>
  </main>
  <script>
   // Create confetti elements with random positions and animation delays
    const confettiContainer = document.getElementById("confetti-container");
    const confettiCount = 60;

    for (let i = 0; i < confettiCount; i++) {
      const confetti = document.createElement("div");
      confetti.classList.add("confetti");
      confetti.style.left = Math.random() * 100 + "vw";
      confetti.style.animationDuration = 3 + Math.random() * 3 + "s";
      confetti.style.animationDelay = Math.random() * 5 + "s";
      confetti.style.top = "-10px";
      confettiContainer.appendChild(confetti);
    }

    function showMessage() {
      const messages = [
        "Maaf lambat, tapi semoga ulang tahunmu penuh kebahagiaan dan cinta!",
        "Selamat ulang tahun, Asfa Ilham! Semoga semua impianmu menjadi kenyataan.",
        "Hari ini adalah hari spesialmu, nikmati setiap momennya dengan bahagia!",
        "Semoga tahun baru usiamu membawa kesuksesan, kesehatan, dan kebahagiaan.",
        "Selamat ulang tahun! Teruslah bersinar dan menjadi inspirasi bagi banyak orang.",
        "Maaf lambat, tapi doa terbaik selalu menyertai langkah hidupmu, Asfa Ilham.",
        "Hari ini kamu bertambah usia, semoga semakin bijaksana dan penuh berkah.",
        "Selamat ulang tahun! Semoga hari-harimu selalu cerah dan penuh tawa.",
        "Semoga ulang tahun ini menjadi awal dari petualangan baru yang menyenangkan.",
        "Terima kasih telah menjadi teman yang luar biasa, selamat ulang tahun, Asfa Ilham!"
      ];
      const msg = document.getElementById("message");
      const random = Math.floor(Math.random() * messages.length);
      msg.textContent = messages[random];
      msg.classList.remove("show");
      void msg.offsetWidth; // Reset animation
      msg.classList.add("show");
    }
  </script>
 </body>
</html>
