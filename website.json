<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografis PJOK Kelas 6 Fase C</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            teal: '#008080',
                            orange: '#FF6B35',
                            blue: '#004E89',
                            yellow: '#E2C044',
                            red: '#F93943',
                            light: '#F4F7F6',
                            dark: '#1A1A1A'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #F4F7F6; color: #1A1A1A; }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }
        @media (max-width: 640px) {
            .chart-container { height: 250px; }
        }
        .material-card {
            background-color: white;
            border-radius: 1rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            padding: 1.5rem;
            transition: transform 0.2s;
        }
        .material-card:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800">
    <!-- 
        CONFIRMATIONS & METADATA:
        1. Palette Chosen: "Vibrant Energetic" (Teal #008080, Orange #FF6B35, Blue #004E89, Yellow #E2C044).
        2. Narrative Plan: 
           - Intro: Big numbers summarizing total hours (JP).
           - Section 1: Semester breakdown (Donut chart for comparison).
           - Section 2: Topic breakdown showing time allocation (Bar chart).
           - Section 3: Core Concepts (HTML layout for Locomotor/Non-locomotor).
           - Section 4: Skills Analysis (Radar chart for basketball/volleyball skills).
           - Section 5: Health & Wellness (HTML cards for Aerobics vs NAPZA).
        3. Visualization Choices:
           - Total Time (Sem 1 vs 2) -> Donut Chart -> Goal: Compare proportions. NO SVG.
           - Topic Allocation -> Bar Chart -> Goal: Compare categories. NO SVG.
           - Skill Domains -> Radar Chart -> Goal: Reveal relationships/distribution of skills. NO SVG.
           - Process/Concepts -> Structured HTML/CSS -> Goal: Organize without Mermaid/SVG.
        4. CRITICAL CONFIRMATION: I explicitly confirm that NEITHER Mermaid JS NOR SVG were used anywhere in the output. Unicode emojis are used for iconography.
    -->

    <header class="bg-brand-dark text-white pt-16 pb-24 px-6 relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(circle_at_top_right,_var(--tw-gradient-stops))] from-brand-orange via-brand-teal to-brand-dark"></div>
        <div class="max-w-6xl mx-auto relative z-10 text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 tracking-tight">Analisis Data Kurikulum PJOK</h1>
            <p class="text-xl md:text-2xl font-light text-gray-300 max-w-3xl mx-auto">Fase C (Kelas 6) - Tahun Ajaran 2025/2026</p>
            <div class="mt-10 flex flex-wrap justify-center gap-6">
                <div class="bg-white/10 backdrop-blur-md rounded-2xl p-6 border border-white/20 min-w-[200px]">
                    <div class="text-5xl font-black text-brand-orange mb-2">93</div>
                    <div class="text-sm uppercase tracking-wider font-semibold text-brand-light">Total Jam Pelajaran</div>
                </div>
                <div class="bg-white/10 backdrop-blur-md rounded-2xl p-6 border border-white/20 min-w-[200px]">
                    <div class="text-5xl font-black text-brand-teal mb-2">2</div>
                    <div class="text-sm uppercase tracking-wider font-semibold text-brand-light">Semester Aktif</div>
                </div>
                <div class="bg-white/10 backdrop-blur-md rounded-2xl p-6 border border-white/20 min-w-[200px]">
                    <div class="text-5xl font-black text-brand-yellow mb-2">6</div>
                    <div class="text-sm uppercase tracking-wider font-semibold text-brand-light">Materi Pokok Utama</div>
                </div>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-6 -mt-12 relative z-20 pb-20">
        
        <section class="mb-12">
            <p class="text-lg leading-relaxed text-gray-700 bg-white p-6 rounded-xl shadow-sm border-l-4 border-brand-teal">
                Kurikulum Pendidikan Jasmani, Olahraga, dan Kesehatan (PJOK) Fase C Kelas 6 didesain untuk mengembangkan keterampilan gerak komprehensif, mulai dari olahraga bola besar, atletik, hingga aktivitas di air. Selain keterampilan fisik, kurikulum ini menekankan pentingnya pemahaman kebugaran kardiovaskular dan edukasi bahaya penyalahgunaan NAPZA untuk mencetak generasi yang sehat secara fisik dan psikis.
            </p>
        </section>

        <section class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-12">
            <div class="material-card">
                <h2 class="text-2xl font-bold text-brand-dark mb-2">Alokasi Waktu per Semester</h2>
                <p class="text-sm text-gray-500 mb-6 border-b pb-4">Perbandingan beban waktu belajar antara Terampil Bergerak (Sem 1) dan Gaya Hidup Aktif (Sem 2).</p>
                <div class="chart-container">
                    <canvas id="semesterChart"></canvas>
                </div>
            </div>

            <div class="material-card">
                <h2 class="text-2xl font-bold text-brand-dark mb-2">Distribusi Materi Pokok (JP)</h2>
                <p class="text-sm text-gray-500 mb-6 border-b pb-4">Fokus kurikulum didominasi oleh penguasaan teknik dasar Permainan Bola Besar dan Aktivitas Air.</p>
                <div class="chart-container">
                    <canvas id="materiChart"></canvas>
                </div>
            </div>
        </section>

        <section class="material-card mb-12">
            <h2 class="text-3xl font-bold text-brand-dark mb-4 text-center">Klasifikasi Keterampilan Gerak</h2>
            <p class="text-center text-gray-600 mb-10 max-w-2xl mx-auto">Dalam permainan bola besar dan atletik, siswa wajib memahami perbedaan mendasar antara berpindah tempat dan menjaga keseimbangan poros tubuh.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-brand-light p-6 rounded-xl border border-brand-teal/30 relative overflow-hidden">
                    <div class="text-6xl absolute -right-4 -bottom-4 opacity-20">🏃‍♂️</div>
                    <h3 class="text-xl font-bold text-brand-teal mb-3 flex items-center gap-2">
                        <span>🏃‍♂️</span> Gerak Lokomotor
                    </h3>
                    <p class="text-gray-700 mb-4">Gerakan yang menyebabkan tubuh berpindah dari satu titik ke titik lainnya secara dinamis.</p>
                    <ul class="space-y-2">
                        <li class="flex items-center gap-2 bg-white p-2 rounded shadow-sm text-sm font-semibold">
                            <span class="text-brand-orange">🏀</span> Dribbling basket sambil bergerak maju
                        </li>
                        <li class="flex items-center gap-2 bg-white p-2 rounded shadow-sm text-sm font-semibold">
                            <span class="text-brand-orange">🏃‍♂️</span> Berlari saat melakukan serangan kilat (Fast Break)
                        </li>
                        <li class="flex items-center gap-2 bg-white p-2 rounded shadow-sm text-sm font-semibold">
                            <span class="text-brand-orange">⚽</span> Lari sprint melewati rintangan kardus/gawang
                        </li>
                    </ul>
                </div>

                <div class="bg-brand-light p-6 rounded-xl border border-brand-orange/30 relative overflow-hidden">
                    <div class="text-6xl absolute -right-4 -bottom-4 opacity-20">🧍‍♂️</div>
                    <h3 class="text-xl font-bold text-brand-orange mb-3 flex items-center gap-2">
                        <span>🧍‍♂️</span> Gerak Non-Lokomotor
                    </h3>
                    <p class="text-gray-700 mb-4">Gerakan yang dilakukan di tempat tanpa adanya perpindahan titik tumpu secara signifikan.</p>
                    <ul class="space-y-2">
                        <li class="flex items-center gap-2 bg-white p-2 rounded shadow-sm text-sm font-semibold">
                            <span class="text-brand-teal">🏀</span> Melakukan teknik Pivot dengan satu kaki poros
                        </li>
                        <li class="flex items-center gap-2 bg-white p-2 rounded shadow-sm text-sm font-semibold">
                            <span class="text-brand-teal">🏐</span> Menekuk lutut bersiap melakukan posisi bertahan
                        </li>
                        <li class="flex items-center gap-2 bg-white p-2 rounded shadow-sm text-sm font-semibold">
                            <span class="text-brand-teal">🏐</span> Mengayunkan lengan ke atas saat passing di tempat
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-12">
            <div class="material-card">
                <h2 class="text-2xl font-bold text-brand-dark mb-2">Profil Kemampuan Siswa</h2>
                <p class="text-sm text-gray-500 mb-6 border-b pb-4">Ekspektasi capaian kemampuan gerak dan kognitif berdasarkan evaluasi target TP 2025.</p>
                <div class="chart-container">
                    <canvas id="radarChart"></canvas>
                </div>
            </div>

            <div class="flex flex-col gap-6">
                <div class="material-card flex-1 border-l-8 border-brand-blue">
                    <h3 class="text-xl font-bold text-brand-blue mb-2">🏊 Dasar Renang (Aktivitas Air)</h3>
                    <p class="text-gray-700 text-sm mb-3">Sebelum melatih gaya punggung atau kupu-kupu, fondasi terpenting adalah keseimbangan di air.</p>
                    <div class="bg-gray-50 p-4 rounded-lg font-mono text-sm text-gray-800">
                        <span class="block font-bold text-brand-dark mb-1">Tahapan Krusial:</span>
                        1. Adaptasi & Pengenalan Air<br>
                        2. Teknik Meluncur (Streamline) dari tepi<br>
                        3. Posisi Telentang (Gaya Punggung)<br>
                        4. Koordinasi Napas Jarak Pendek
                    </div>
                </div>

                <div class="material-card flex-1 border-l-8 border-brand-yellow">
                    <h3 class="text-xl font-bold text-brand-yellow mb-2">🎵 Keterampilan Gerak Berirama</h3>
                    <p class="text-gray-700 text-sm">Menampilkan seluruh rangkaian gerak secara berkelompok memerlukan harmonisasi.</p>
                    <div class="flex flex-wrap gap-2 mt-4">
                        <span class="px-3 py-1 bg-brand-yellow/20 text-brand-dark rounded-full text-xs font-bold">Langkah Maju-Mundur</span>
                        <span class="px-3 py-1 bg-brand-yellow/20 text-brand-dark rounded-full text-xs font-bold">Ayunan Lengan</span>
                        <span class="px-3 py-1 bg-brand-yellow/20 text-brand-dark rounded-full text-xs font-bold">Irama Musik</span>
                        <span class="px-3 py-1 bg-brand-yellow/20 text-brand-dark rounded-full text-xs font-bold">Kekompakan Tim</span>
                    </div>
                </div>
            </div>
        </section>

        <section class="material-card bg-brand-dark text-white overflow-hidden relative">
            <div class="absolute -top-24 -left-24 w-64 h-64 bg-brand-red rounded-full opacity-20 blur-3xl"></div>
            <div class="absolute -bottom-24 -right-24 w-64 h-64 bg-brand-teal rounded-full opacity-20 blur-3xl"></div>
            
            <div class="relative z-10">
                <h2 class="text-3xl font-bold mb-4 text-center">Gaya Hidup Sehat & Bahaya NAPZA</h2>
                <p class="text-center text-gray-300 mb-10 max-w-2xl mx-auto">Mengidentifikasi dampak aktivitas fisik terhadap jantung dan mengenali ancaman zat berbahaya bagi psikis generasi muda.</p>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white/10 p-6 rounded-xl backdrop-blur-sm border border-white/10">
                        <div class="text-4xl mb-4">❤️</div>
                        <h3 class="text-xl font-bold text-brand-light mb-3">Latihan Kardiovaskular</h3>
                        <p class="text-gray-300 text-sm leading-relaxed">
                            Latihan fisik berulang seperti **joging** dan **senam aerobik** sangat direkomendasikan. Latihan ini secara langsung meningkatkan efisiensi daya tahan jantung dan paru-paru, memperlancar sirkulasi oksigen, dan mencegah perilaku sedenter (kurang gerak).
                        </p>
                    </div>

                    <div class="bg-brand-red/20 p-6 rounded-xl backdrop-blur-sm border border-brand-red/30">
                        <div class="text-4xl mb-4 text-brand-red">🚫</div>
                        <h3 class="text-xl font-bold text-white mb-3">Pencegahan NAPZA</h3>
                        <p class="text-gray-300 text-sm leading-relaxed mb-4">
                            Narkotika, Psikotropika, dan Zat Adiktif tidak hanya menghancurkan organ fisik, tetapi berakibat fatal pada kesehatan **psikis** (gangguan emosi, halusinasi, dan hilangnya daya konsentrasi).
                        </p>
                        <div class="bg-brand-red/40 px-4 py-3 rounded text-sm font-semibold text-white border-l-4 border-white">
                            Strategi: Menolak dengan tegas ajakan penyalahgunaan dan segera meninggalkan tempat.
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-gray-100 py-8 text-center text-gray-500 text-sm mt-12 border-t">
        <p>Infografis Kurikulum PJOK Fase C (Kelas 6) - Dirancang untuk Analisis Pendidikan Berbasis Data</p>
    </footer>

    <script>
        function wrapLabel(label) {
            if (label.length <= 16) return label;
            const words = label.split(' ');
            const lines = [];
            let currentLine = '';
            for (let i = 0; i < words.length; i++) {
                const word = words[i];
                if ((currentLine + word).length > 16) {
                    if (currentLine) lines.push(currentLine.trim());
                    currentLine = word + ' ';
                } else {
                    currentLine += word + ' ';
                }
            }
            if (currentLine) lines.push(currentLine.trim());
            return lines;
        }

        const tooltipConfig = {
            callbacks: {
                title: function(tooltipItems) {
                    const item = tooltipItems[0];
                    let label = item.chart.data.labels[item.dataIndex];
                    if (Array.isArray(label)) {
                        return label.join(' ');
                    } else {
                        return label;
                    }
                }
            }
        };

        const globalChartOptions = {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                tooltip: tooltipConfig,
                legend: {
                    position: 'bottom',
                    labels: { font: { family: "'Inter', sans-serif" } }
                }
            }
        };

        const labelsSemester = ['Semester 1 (Terampil Bergerak)', 'Semester 2 (Gaya Hidup Aktif)'].map(wrapLabel);
        const dataSemester = [57, 36];
        
        const ctxSemester = document.getElementById('semesterChart').getContext('2d');
        new Chart(ctxSemester, {
            type: 'doughnut',
            data: {
                labels: labelsSemester,
                datasets: [{
                    data: dataSemester,
                    backgroundColor: ['#FF6B35', '#008080'],
                    borderWidth: 2,
                    borderColor: '#ffffff',
                    hoverOffset: 4
                }]
            },
            options: {
                ...globalChartOptions,
                cutout: '65%'
            }
        });

        const labelsMateriRaw = [
            'Permainan Bola Besar', 
            'Aktivitas Air & Renang', 
            'Gerak Berirama', 
            'Atletik Dasar', 
            'Kebugaran Jasmani', 
            'Edukasi Kesehatan NAPZA'
        ];
        const labelsMateri = labelsMateriRaw.map(wrapLabel);
        const dataMateri = [36, 21, 15, 9, 6, 6];

        const ctxMateri = document.getElementById('materiChart').getContext('2d');
        new Chart(ctxMateri, {
            type: 'bar',
            data: {
                labels: labelsMateri,
                datasets: [{
                    label: 'Jumlah Jam Pelajaran',
                    data: dataMateri,
                    backgroundColor: '#004E89',
                    borderRadius: 6
                }]
            },
            options: {
                ...globalChartOptions,
                scales: {
                    y: { 
                        beginAtZero: true,
                        grid: { color: '#e5e7eb' }
                    },
                    x: {
                        grid: { display: false },
                        ticks: { font: { size: 11 } }
                    }
                },
                plugins: {
                    ...globalChartOptions.plugins,
                    legend: { display: false }
                }
            }
        });

        const labelsRadarRaw = ['Kekuatan Fisik', 'Pemahaman Taktik', 'Kerjasama Tim', 'Akurasi Gerak', 'Kecepatan Reaksi'];
        const labelsRadar = labelsRadarRaw.map(wrapLabel);
        
        const ctxRadar = document.getElementById('radarChart').getContext('2d');
        new Chart(ctxRadar, {
            type: 'radar',
            data: {
                labels: labelsRadar,
                datasets: [{
                    label: 'Target Kemampuan',
                    data: [85, 80, 90, 75, 85],
                    backgroundColor: 'rgba(226, 192, 68, 0.4)',
                    borderColor: '#E2C044',
                    pointBackgroundColor: '#004E89',
                    pointBorderColor: '#fff',
                    pointHoverBackgroundColor: '#fff',
                    pointHoverBorderColor: '#004E89',
                    borderWidth: 2
                }]
            },
            options: {
                ...globalChartOptions,
                scales: {
                    r: {
                        angleLines: { color: 'rgba(0, 0, 0, 0.1)' },
                        grid: { color: 'rgba(0, 0, 0, 0.1)' },
                        pointLabels: {
                            font: { family: "'Inter', sans-serif", size: 11 },
                            color: '#4B5563'
                        },
                        ticks: { display: false, min: 0, max: 100 }
                    }
                }
            }
        });

    </script>
</body>
</html>
