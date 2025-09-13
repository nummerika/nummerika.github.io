<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NUMMERIKA - Belajar Coding Python</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .hero {
            background: linear-gradient(135deg, #1f2937, #111827);
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header & Navbar -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto p-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-900">NUMMERIKA</a>
            <ul class="flex space-x-6">
                <li><a href="#beranda" class="text-gray-600 hover:text-blue-500 transition duration-300">Beranda</a></li>
                <li><a href="#profil" class="text-gray-600 hover:text-blue-500 transition duration-300">Profil</a></li>
                <li><a href="#layanan" class="text-gray-600 hover:text-blue-500 transition duration-300">Layanan</a></li>
                <li><a href="#kontak" class="text-gray-600 hover:text-blue-500 transition duration-300">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="beranda" class="hero text-white py-20 md:py-32 rounded-b-3xl">
            <div class="container mx-auto text-center px-4">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-4 animate-fade-in-up">
                    Membuka Wawasan, Membangun Keterampilan Digital Masa Depan.
                </h1>
                <p class="text-lg md:text-xl mb-8 opacity-90 animate-fade-in-up delay-200">
                    Platform edukasi online yang berfokus pada penguasaan Python untuk Scientific Computing, Data Science, dan AI.
                </p>
                <a href="#layanan" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transform hover:scale-105 transition-all duration-300 ease-in-out">
                    Lihat Layanan & Paket
                </a>
            </div>
        </section>

        <!-- Profil Perusahaan -->
        <section id="profil" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4">
                <div class="max-w-4xl mx-auto text-center">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 text-gray-900">Tentang NUMMERIKA</h2>
                    <p class="text-lg text-gray-600 mb-6">
                        NUMMERIKA adalah platform edukasi online yang berfokus pada penguasaan Python sebagai bahasa pemrograman utama dalam scientific computing, data science, dan artificial intelligence. Kami percaya bahwa keterampilan Python akan menjadi fondasi penting bagi generasi mendatang dalam menghadapi revolusi teknologi dan tantangan global, termasuk keberlanjutan dan transformasi digital.
                    </p>
                    <p class="text-lg text-gray-600">
                        Dengan menggabungkan pengajaran live interaktif dan materi praktis berbasis proyek, NUMMERIKA hadir untuk membantu mahasiswa, profesional, maupun siapa saja yang ingin meningkatkan kemampuan pemrogramannya dari level dasar hingga lanjut.
                    </p>
                </div>
            </div>
        </section>

        <!-- Layanan & Paket Belajar -->
        <section id="layanan" class="py-16 md:py-24 bg-gray-50">
            <div class="container mx-auto px-4">
                <div class="max-w-4xl mx-auto text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-900">Layanan & Paket Belajar</h2>
                    <p class="text-gray-600">Pilih program yang paling sesuai dengan kebutuhan Anda.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Kursus 1: Python Fundamental -->
                    <div class="bg-white p-6 rounded-xl shadow-md transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-bold mb-2 text-blue-600">1. Python Fundamental (Beginner)</h3>
                        <p class="text-sm text-gray-500 mb-4">Durasi: 4 pertemuan x 2 jam</p>
                        <ul class="text-gray-700 space-y-2 mb-4">
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Pengenalan Python & IDE</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Tipe data, variabel, operator</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Control flow (if, loop)</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Fungsi & modularisasi</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Mini project: kalkulator sederhana & data manipulation dasar</li>
                        </ul>
                        <p class="text-sm text-gray-600 italic">Cocok untuk: Mahasiswa baru, pemula tanpa pengalaman coding.</p>
                    </div>

                    <!-- Kursus 2: Python for Data Science -->
                    <div class="bg-white p-6 rounded-xl shadow-md transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-bold mb-2 text-blue-600">2. Python for Data Science (Intermediate)</h3>
                        <p class="text-sm text-gray-500 mb-4">Durasi: 6 pertemuan x 2 jam</p>
                        <ul class="text-gray-700 space-y-2 mb-4">
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Numpy & Pandas untuk analisis data</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Visualisasi data (Matplotlib, Seaborn)</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Data wrangling & preprocessing</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Mini project: analisis dataset publik</li>
                        </ul>
                        <p class="text-sm text-gray-600 italic">Cocok untuk: Mahasiswa tingkat akhir, profesional yang ingin belajar data.</p>
                    </div>

                    <!-- Kursus 3: Python for AI & Machine Learning -->
                    <div class="bg-white p-6 rounded-xl shadow-md transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-bold mb-2 text-blue-600">3. Python for AI & Machine Learning (Advanced)</h3>
                        <p class="text-sm text-gray-500 mb-4">Durasi: 8 pertemuan x 2 jam</p>
                        <ul class="text-gray-700 space-y-2 mb-4">
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Scikit-learn dasar: supervised & unsupervised learning</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Evaluasi model & problem data imbalance</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Pengenalan deep learning (Keras/TensorFlow/PyTorch)</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Mini project: klasifikasi dataset sederhana</li>
                        </ul>
                        <p class="text-sm text-gray-600 italic">Cocok untuk: Mahasiswa komputer/sains data, peneliti pemula, praktisi.</p>
                    </div>
                </div>

                <!-- Special Workshop / Mini Bootcamp -->
                <div class="bg-blue-50 p-6 rounded-xl shadow-md mt-8 max-w-2xl mx-auto">
                    <h3 class="text-xl font-bold mb-2 text-blue-700">Special Workshop / Mini Bootcamp</h3>
                    <p class="text-sm text-gray-600 mb-4">Format: 1–2 hari intensif, fokus ke aplikasi praktis.</p>
                    <ul class="text-gray-700 space-y-2">
                        <li><i class="fas fa-code text-blue-500 mr-2"></i> Python untuk Scientific Computing</li>
                        <li><i class="fas fa-leaf text-blue-500 mr-2"></i> Python untuk Zero Carbon Data Analysis</li>
                        <li><i class="fas fa-robot text-blue-500 mr-2"></i> Python untuk Otomasi & Scripting</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Metode Belajar -->
        <section class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4">
                <div class="max-w-4xl mx-auto text-center">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 text-gray-900">Metode Belajar Kami</h2>
                    <ul class="grid grid-cols-1 md:grid-cols-2 gap-8 text-gray-700 text-left">
                        <li class="flex items-start">
                            <i class="fas fa-video text-blue-500 text-2xl mr-4 mt-1"></i>
                            <div>
                                <h4 class="font-bold">Live Teaching via Zoom/Google Meet</h4>
                                <p class="text-sm">Pembelajaran interaktif dengan mentor berpengalaman.</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-book text-blue-500 text-2xl mr-4 mt-1"></i>
                            <div>
                                <h4 class="font-bold">Materi PDF + Notebook Interaktif</h4>
                                <p class="text-sm">Materi yang bisa Anda pelajari kapan pun dan di mana pun.</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-podcast text-blue-500 text-2xl mr-4 mt-1"></i>
                            <div>
                                <h4 class="font-bold">Rekaman Kelas Tersedia</h4>
                                <p class="text-sm">Jangan khawatir jika terlewat, Anda bisa menontonnya kembali.</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-users text-blue-500 text-2xl mr-4 mt-1"></i>
                            <div>
                                <h4 class="font-bold">Grup Diskusi (Telegram/WhatsApp)</h4>
                                <p class="text-sm">Dapatkan dukungan dari komunitas dan mentor.</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-award text-blue-500 text-2xl mr-4 mt-1"></i>
                            <div>
                                <h4 class="font-bold">Sertifikat Partisipasi/Proyek</h4>
                                <p class="text-sm">Bukti otentik atas pencapaian Anda.</p>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Kontak -->
        <section id="kontak" class="py-16 md:py-24 bg-gray-50 rounded-t-3xl">
            <div class="container mx-auto px-4 max-w-4xl">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-900">Hubungi Kami</h2>
                    <p class="text-gray-600">Punya pertanyaan? Kirimkan pesan Anda dan kami akan segera menghubungi Anda.</p>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-md">
                    <form id="contactForm" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700">Nama Lengkap</label>
                            <input type="text" id="name" name="name" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" required>
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                            <input type="email" id="email" name="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" required>
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700">Pesan Anda</label>
                            <textarea id="message" name="message" rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-blue-500 focus:ring-blue-500" required></textarea>
                        </div>
                        <div class="flex justify-center">
                            <button type="submit" id="submitBtn" class="w-full md:w-auto bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-colors duration-300">
                                Kirim Pesan
                            </button>
                        </div>
                    </form>
                    <div id="statusMessage" class="mt-4 text-center text-sm font-medium hidden"></div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="container mx-auto text-center px-4">
            <p class="text-lg font-bold mb-2">NUMMERIKA</p>
            <p class="text-sm opacity-75">Membuka Wawasan, Membangun Keterampilan Digital Masa Depan.</p>
            <div class="mt-4 flex justify-center space-x-6">
                <a href="#" class="hover:text-blue-500 transition-colors duration-300"><i class="fab fa-linkedin fa-lg"></i></a>
                <a href="#" class="hover:text-blue-500 transition-colors duration-300"><i class="fab fa-instagram fa-lg"></i></a>
                <a href="#" class="hover:text-blue-500 transition-colors duration-300"><i class="fab fa-facebook-square fa-lg"></i></a>
            </div>
            <p class="text-xs opacity-50 mt-4">&copy; 2025 NUMMERIKA. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- JavaScript untuk Form Submission -->
    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();

            const form = e.target;
            const statusMessage = document.getElementById('statusMessage');
            const submitBtn = document.getElementById('submitBtn');

            // URL dari Google Apps Script Web App Anda
            // PASTE URL SCRIPT ANDA DI SINI
            const googleAppsScriptURL = 'https://script.google.com/macros/s/AKfycbwqdC_hP_vX_Z2_x3_2-o_f-J-y_s-F-u-g-e-o/exec';
            
            submitBtn.textContent = 'Mengirim...';
            submitBtn.disabled = true;
            statusMessage.textContent = '';
            statusMessage.classList.add('hidden');

            const data = {
                name: form.name.value,
                email: form.email.value,
                message: form.message.value
            };

            fetch(googleAppsScriptURL, {
                method: 'POST',
                mode: 'no-cors',
                headers: {
                    'Content-Type': 'application/json',
                },
                body: JSON.stringify(data),
            })
            .then(response => {
                // Karena mode: 'no-cors', kita tidak bisa memeriksa respons.
                // Asumsi pengiriman berhasil jika tidak ada error jaringan.
                submitBtn.textContent = 'Terkirim!';
                submitBtn.disabled = false;
                form.reset();
                statusMessage.textContent = 'Pesan Anda berhasil terkirim! Kami akan segera menghubungi Anda.';
                statusMessage.classList.remove('hidden');
                statusMessage.classList.remove('text-red-600');
                statusMessage.classList.add('text-green-600');
            })
            .catch(error => {
                console.error('Error:', error);
                submitBtn.textContent = 'Kirim Pesan';
                submitBtn.disabled = false;
                statusMessage.textContent = 'Terjadi kesalahan saat mengirim pesan. Silakan coba lagi.';
                statusMessage.classList.remove('hidden');
                statusMessage.classList.remove('text-green-600');
                statusMessage.classList.add('text-red-600');
            });
        });
    </script>
</body>
</html>
