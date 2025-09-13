<html lang="id" class="scroll-smooth">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NUMMERIKA - Python untuk Masa Depan</title>
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }

        .cta-button {
            transition: transform 0.2s ease-in-out;
        }

        .cta-button:hover {
            transform: translateY(-2px);
        }
    </style>
</head>

<body class="bg-gray-50 text-gray-800">

    <!-- Header & Navigation -->
    <header class="bg-white sticky top-0 z-50 shadow-sm">
        <nav class="container mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-indigo-600">
                NUMMERIKA
            </a>
            <div class="hidden md:flex space-x-6">
                <a href="#hero" class="text-gray-600 hover:text-indigo-600 transition duration-300">Beranda</a>
                <a href="#courses" class="text-gray-600 hover:text-indigo-600 transition duration-300">Layanan</a>
                <a href="#about" class="text-gray-600 hover:text-indigo-600 transition duration-300">Tentang Kami</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-600 transition duration-300">Kontak</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-md">
            <a href="#hero" class="block py-3 px-4 text-gray-700 hover:bg-gray-100 transition duration-300">Beranda</a>
            <a href="#courses" class="block py-3 px-4 text-gray-700 hover:bg-gray-100 transition duration-300">Layanan</a>
            <a href="#about" class="block py-3 px-4 text-gray-700 hover:bg-gray-100 transition duration-300">Tentang Kami</a>
            <a href="#contact" class="block py-3 px-4 text-gray-700 hover:bg-gray-100 transition duration-300">Kontak</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="bg-indigo-600 text-white py-16 md:py-24">
            <div class="container mx-auto px-4 text-center">
                <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-4 animate-fade-in-up">
                    NUMMERIKA: <br class="md:hidden"> Membangun Keterampilan Digital Masa Depan
                </h1>
                <p class="text-lg md:text-xl max-w-2xl mx-auto mb-8 opacity-90 animate-fade-in">
                    Platform edukasi online yang berfokus pada penguasaan Python untuk scientific
                    computing, data science, dan artificial intelligence.
                </p>
                <a href="#courses"
                    class="cta-button inline-block bg-white text-indigo-600 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-indigo-50 transition duration-300">
                    Lihat Layanan & Paket
                </a>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-16 md:py-20 bg-gray-100">
            <div class="container mx-auto px-4 flex flex-col md:flex-row items-center gap-10">
                <div class="w-full md:w-1/2">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Membangun Fondasi untuk Revolusi Teknologi</h2>
                    <p class="text-gray-600 mb-4">
                        Kami percaya bahwa keterampilan Python akan menjadi fondasi penting bagi generasi
                        mendatang dalam menghadapi revolusi teknologi dan tantangan global. NUMMERIKA
                        hadir untuk membantu mahasiswa, profesional, maupun siapa saja yang ingin
                        meningkatkan kemampuan pemrogramannya dari level dasar hingga lanjut.
                    </p>
                    <p class="text-gray-600">
                        Dengan menggabungkan pengajaran live interaktif via Zoom/Google Meet dan materi
                        praktis berbasis proyek, kami memastikan Anda mendapatkan pengalaman belajar yang
                        mendalam dan relevan dengan kebutuhan industri.
                    </p>
                </div>
                <div class="w-full md:w-1/2">
                    <img src="https://placehold.co/800x600/E0E7FF/5C6BC0?text=Tim+NUMMERIKA" alt="Tim NUMMERIKA"
                        class="rounded-xl shadow-lg">
                </div>
            </div>
        </section>

        <!-- Courses Section -->
        <section id="courses" class="py-16 md:py-20">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Layanan & Paket Belajar</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Course Card 1: Python Fundamental -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Python Fundamental (Beginner)</h3>
                        <p class="text-gray-600 mb-4">
                            Pengenalan Python dari nol, cocok untuk pemula tanpa pengalaman coding.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1 mb-4">
                            <li>Durasi: 4 pertemuan x 2 jam</li>
                            <li>Materi: Tipe data, control flow, fungsi, mini project.</li>
                            <li>Cocok untuk: Mahasiswa baru, pemula.</li>
                        </ul>
                        <a href="#contact"
                            class="inline-block bg-indigo-600 text-white py-2 px-6 rounded-lg text-sm font-semibold hover:bg-indigo-700 transition duration-300">
                            Daftar Sekarang
                        </a>
                    </div>
                    <!-- Course Card 2: Python for Data Science -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Python for Data Science (Intermediate)</h3>
                        <p class="text-gray-600 mb-4">
                            Kuasai analisis data dengan library populer seperti Numpy & Pandas.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1 mb-4">
                            <li>Durasi: 6 pertemuan x 2 jam</li>
                            <li>Materi: Analisis data, visualisasi, data preprocessing.</li>
                            <li>Cocok untuk: Mahasiswa tingkat akhir, profesional yang ingin belajar data.</li>
                        </ul>
                        <a href="#contact"
                            class="inline-block bg-indigo-600 text-white py-2 px-6 rounded-lg text-sm font-semibold hover:bg-indigo-700 transition duration-300">
                            Daftar Sekarang
                        </a>
                    </div>
                    <!-- Course Card 3: Python for AI & Machine Learning -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Python for AI & ML (Advanced)</h3>
                        <p class="text-gray-600 mb-4">
                            Masuk ke dunia kecerdasan buatan dengan machine learning dan deep learning dasar.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1 mb-4">
                            <li>Durasi: 8 pertemuan x 2 jam</li>
                            <li>Materi: Scikit-learn, evaluasi model, Keras/TensorFlow/PyTorch.</li>
                            <li>Cocok untuk: Mahasiswa komputer, peneliti, praktisi.</li>
                        </ul>
                        <a href="#contact"
                            class="inline-block bg-indigo-600 text-white py-2 px-6 rounded-lg text-sm font-semibold hover:bg-indigo-700 transition duration-300">
                            Daftar Sekarang
                        </a>
                    </div>
                    <!-- Course Card 4: Special Workshop -->
                    <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition duration-300">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Special Workshop</h3>
                        <p class="text-gray-600 mb-4">
                            Mini bootcamp tematik dengan fokus pada aplikasi praktis yang intensif.
                        </p>
                        <ul class="text-sm text-gray-500 space-y-1 mb-4">
                            <li>Durasi: 1–2 hari intensif</li>
                            <li>Contoh Topik: Python for Zero Carbon Data Analysis, Otomasi & Scripting.</li>
                            <li>Cocok untuk: Siapa saja yang ingin belajar topik spesifik secara cepat.</li>
                        </ul>
                        <a href="#contact"
                            class="inline-block bg-indigo-600 text-white py-2 px-6 rounded-lg text-sm font-semibold hover:bg-indigo-700 transition duration-300">
                            Daftar Sekarang
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16 md:py-20 bg-indigo-600 text-white">
            <div class="container mx-auto px-4 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Siap untuk Memulai Perjalanan Coding Anda?</h2>
                <p class="text-lg md:text-xl max-w-2xl mx-auto mb-8 opacity-90">
                    Isi formulir di bawah ini dan tim kami akan segera menghubungi Anda.
                </p>
                <div class="bg-white p-8 md:p-12 rounded-xl shadow-lg max-w-lg mx-auto">
                    <!-- Form dengan ID -->
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 text-left">Nama Lengkap</label>
                            <input type="text" id="name" name="name"
                                class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm focus:ring-indigo-500 focus:border-indigo-500 text-gray-800"
                                placeholder="Nama Anda" required>
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 text-left">Alamat Email</label>
                            <input type="email" id="email" name="email"
                                class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm focus:ring-indigo-500 focus:border-indigo-500 text-gray-800"
                                placeholder="alamat@email.com" required>
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 text-left">Pesan</label>
                            <textarea id="message" name="message" rows="4"
                                class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm focus:ring-indigo-500 focus:border-indigo-500 text-gray-800"
                                placeholder="Pesan Anda" required></textarea>
                        </div>
                        <button type="submit" id="submit-button"
                            class="w-full bg-indigo-600 text-white font-bold py-3 px-4 rounded-lg shadow-md hover:bg-indigo-700 transition duration-300">
                            Kirim Pesan
                        </button>
                    </form>
                    <!-- Loading & Success Message -->
                    <div id="status-message" class="mt-4 text-center font-bold"></div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 text-center text-sm md:flex justify-between items-center">
            <p>&copy; 2024 NUMMERIKA. Semua Hak Dilindungi.</p>
            <div class="flex justify-center md:justify-end space-x-4 mt-4 md:mt-0">
                <a href="#" class="text-gray-400 hover:text-white transition duration-300">Beranda</a>
                <a href="#courses" class="text-gray-400 hover:text-white transition duration-300">Layanan</a>
                <a href="#about" class="text-gray-400 hover:text-white transition duration-300">Tentang</a>
                <a href="#contact" class="text-gray-400 hover:text-white transition duration-300">Kontak</a>
            </div>
        </div>
    </footer>

    <!-- JavaScript untuk Mobile Menu -->
    <script>
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            var menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // =================================================================
        // Skrip untuk mengirim data formulir ke Google Sheets
        // =================================================================
        const form = document.getElementById('contact-form');
        const submitButton = document.getElementById('submit-button');
        const statusMessage = document.getElementById('status-message');

        // GANTI DENGAN URL WEB APP ANDA DARI LANGKAH 3
        const googleAppsScriptURL = 'https://script.google.com/macros/s/AKfycbzdIAgHKCM5Jf9s_8X0n9mdfBSBZPHpyOJLRPPKZTwWqygTva8TJg8PThialhYnSBCasw/exec';

        form.addEventListener('submit', function(event) {
            event.preventDefault(); // Mencegah form dari refresh halaman
            
            // Tampilkan pesan loading dan nonaktifkan tombol
            submitButton.disabled = true;
            statusMessage.textContent = 'Mengirim pesan...';
            statusMessage.classList.add('text-yellow-500');

            const formData = new FormData(form);
            const data = Object.fromEntries(formData.entries());

            fetch(googleAppsScriptURL, {
                method: 'POST',
                body: JSON.stringify(data),
                headers: {
                    'Content-Type': 'application/json'
                }
            })
            .then(response => {
                if (response.ok) {
                    return response.text();
                }
                throw new Error('Terjadi kesalahan saat mengirim pesan.');
            })
            .then(text => {
                if (text === 'Success') {
                    statusMessage.textContent = 'Pesan berhasil terkirim! Tim kami akan segera menghubungi Anda.';
                    statusMessage.classList.remove('text-yellow-500', 'text-red-500');
                    statusMessage.classList.add('text-green-500');
                    form.reset(); // Reset form
                } else {
                    throw new Error('Respon tidak valid dari server.');
                }
            })
            .catch(error => {
                console.error('Error:', error);
                statusMessage.textContent = 'Gagal mengirim pesan. Silakan coba lagi.';
                statusMessage.classList.remove('text-yellow-500', 'text-green-500');
                statusMessage.classList.add('text-red-500');
            })
            .finally(() => {
                submitButton.disabled = false;
            });
        });
    </script>
</body>

</html>
