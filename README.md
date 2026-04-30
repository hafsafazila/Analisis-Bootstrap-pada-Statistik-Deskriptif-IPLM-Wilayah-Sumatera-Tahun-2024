# Analisis-Bootstrap-pada-Statistik-Deskriptif-IPLM-Wilayah-Sumatera-Tahun-2024
```md id="52184"
# Deskripsi Proyek Poster Komputasi Statistika

## Pendahuluan  
Proyek ini disusun oleh Kelompok 1 dalam mata kuliah Komputasi Statistika dengan fokus pada analisis perbandingan statistik deskriptif Indeks Pembangunan Literasi Masyarakat (IPLM) di wilayah Sumatera tahun 2024. Penelitian ini bertujuan mengevaluasi kestabilan estimasi statistik deskriptif menggunakan metode bootstrap sebagai pendekatan resampling untuk menghasilkan analisis yang lebih akurat, stabil, dan reliabel meskipun data terbatas.

## Variabel Penelitian  
Penelitian menggunakan variabel utama sebagai berikut:  
- **Indeks Pembangunan Literasi Masyarakat (IPLM):** indikator tingkat pembangunan literasi masyarakat di wilayah Sumatera tahun 2024  
- **Mean (Rata-rata):** ukuran pemusatan data IPLM  
- **Median:** nilai tengah distribusi data IPLM  
- **Standar Deviasi (SD):** ukuran penyebaran atau variasi data IPLM  
- **Bootstrap Resampling:** metode statistik untuk mengestimasi kestabilan parameter melalui pengambilan sampel ulang  

## Metode yang Digunakan  
Analisis dilakukan menggunakan pendekatan kuantitatif berbasis data IPLM tahun 2024 dari 135 kabupaten/kota di Sumatera. Metode utama yang diterapkan adalah bootstrap dengan 5000 replikasi menggunakan RStudio dan berbagai library statistik untuk:  
- Import dan preprocessing data  
- Resampling bootstrap dengan pengembalian (replacement)  
- Perbandingan statistik deskriptif sebelum dan sesudah bootstrap  
- Visualisasi distribusi data dan hasil estimasi  

## Hasil dan Insight  
Hasil analisis menunjukkan bahwa nilai mean, median, dan standar deviasi sebelum dan sesudah bootstrap relatif hampir sama. Kondisi ini menandakan bahwa data IPLM memiliki estimasi yang stabil dan tidak sensitif terhadap variasi sampel. Distribusi data juga cenderung mendekati normal dengan sebagian besar wilayah berada pada rentang nilai menengah, sehingga hasil bootstrap memperkuat reliabilitas estimasi serta meningkatkan kepercayaan terhadap hasil analisis statistik.

## Kesimpulan  
Metode bootstrap terbukti efektif dalam menghasilkan estimasi statistik deskriptif yang lebih stabil, akurat, dan dapat dipercaya pada data IPLM Sumatera 2024. Dengan pendekatan ini, analisis tidak bergantung pada satu sampel saja dan mampu memberikan gambaran distribusi yang lebih representatif untuk evaluasi pembangunan literasi masyarakat.

## Saran  
Metode bootstrap disarankan untuk digunakan pada penelitian sosial maupun regional dengan keterbatasan data karena mampu meningkatkan stabilitas estimasi. Untuk penelitian selanjutnya, analisis dapat diperluas dengan membandingkan wilayah prioritas literasi, menambahkan variabel sosial-ekonomi pendukung, serta mengintegrasikan metode inferensial lain agar hasil kebijakan pembangunan literasi menjadi lebih tepat sasaran.
```
