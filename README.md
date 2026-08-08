**PPROJECT PLAN**
Judul Proyek: WebGIS Monitoring Perubahan Mangrove dan Prioritas Rehabilitasi Pesisir Jawa Timur Menggunakan Citra Sentinel-2

**Latar Belakang**
Mangrove berperan penting dalam melindungi wilayah pesisir dari abrasi dan menjaga ekosistem pantai. Namun, perubahan tutupan mangrove di beberapa wilayah pesisir Jawa Timur perlu dipantau untuk mendukung upaya rehabilitasi dan konservasi.

**Tujuan**
1. Memetakan sebaran mangrove di Jawa Timur.
2. Menganalisis perubahan luas mangrove dari citra Sentinel-2.
3. Mengidentifikasi wilayah prioritas rehabilitasi.
4. Menyajikan informasi dalam bentuk WebGIS interaktif.

**Target Pengguna**
1. Dinas Kelautan dan Perikanan
2. Dinas Lingkungan Hidup
3. Peneliti dan mahasiswa
4. Komunitas konservasi pesisir

**Data yang Digunakan**
1. Citra Sentinel-2 (2020 & 2025)
2. Batas administrasi kabupaten/kota Jawa Timur
3. Garis pantai
4. Data jalan dan permukiman (OpenStreetMap)

**Metodologi**
1. Pengumpulan data Sentinel-2 dan data pendukung.
2. Pengolahan citra di ENVI (NDVI/Klasifikasi Mangrove).
3. Analisis perubahan mangrove.
4. Penentuan prioritas rehabilitasi berdasarkan perubahan luas mangrove.
5. Konversi hasil ke GeoJSON.
6. Pengembangan WebGIS.

**Fitur WebGIS**
-Peta Interaktif
1. Layer Mangrove 2020
2. Layer Mangrove 2025
3. Layer Perubahan Mangrove
4. Layer Prioritas Rehabilitasi

-Spatial Features
1. Popup informasi setiap kabupaten
2. Radius/Buffer area pesisir untuk analisis wilayah terdampak

-Dashboard
1. Total luas mangrove
2. Luas mangrove bertambah/berkurang
3. Kabupaten prioritas rehabilitasi

-Filter
1. Filter kabupaten
2. Filter tingkat prioritas

**Tech Stack**
1. HTML, CSS, Tailwind CSS
2. JavaScript
3. MapLibre GL JS
4. Chart.js
5. ENVI & QGIS
6. GitHub Pages
   
**Output**
WebGIS yang dapat memantau perubahan mangrove dan membantu mengidentifikasi wilayah prioritas rehabilitasi pesisir di Jawa Timur secara interaktif.
