# 🚀 INTISARI CLIPS: Ultimate Local Workstation Video Software

![Version](https://img.shields.io/badge/Version-Latest-blue.svg)
![Python](https://img.shields.io/badge/Python-3.11+-green.svg)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688.svg)
![FFmpeg](https://img.shields.io/badge/Engine-FFmpeg-ff6600.svg)

**Intisari Clips** adalah perangkat lunak otomatisasi video berbasis *localhost* (Workstation Lokal) yang dirancang untuk mengekstrak, memotong, dan merender klip video viral secara massal. Dilengkapi dengan teknologi AI untuk pelacakan wajah otomatis (*Face Tracking*) dan transkripsi suara (*Auto-Captioning*), software ini bekerja 100% menggunakan tenaga komputasi PC Anda sendiri.

Tidak ada biaya *cloud*, tidak ada batasan server. Semua berjalan secara lokal, cepat, dan privat.

🔥 **DAPATKAN PENGALAMAN MAKSIMAL:**
Kirim tugas ekstraksi video langsung dari browser Anda dengan satu klik menggunakan ekstensi resmi kami!

[![Download Ekstensi](https://img.shields.io/badge/Chrome_Web_Store-Download_Ekstensi_Terbaru-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/intisari-extractor/allogjafdnlfieffbhacnlbkgpklkdlg)

---

## 📺 VIDEO TUTORIAL

Berikut adalah panduan video untuk membantu Anda memulai dengan Intisari Clips, mulai dari instalasi hingga kustomisasi preset:

### 🎬 Fase 1: Instalasi & Klaim Uji Coba Gratis (Trial)
Pelajari cara mengunduh *Setup*, melakukan instalasi yang aman di PC Windows Anda, dan cara mengklaim Lisensi VIP Gratis (Trial 3 Hari) secara otomatis melalui sistem email kami.

[![Tutorial Trial](https://img.youtube.com/vi/UbXig_BG2GE/maxresdefault.jpg)](https://youtu.be/UbXig_BG2GE)

### 🎬 Fase 2 (1): Pengenalan Menu IntisariClips
Menjelaskan UI utama, dashboard, Command Center, History, dan cara mendapatkan path video hasil render.

[![Tutorial Menu](https://img.youtube.com/vi/PB10cObAXk8/maxresdefault.jpg)](https://youtu.be/PB10cObAXk8)

### 🎬 Fase 2 (2): Cara Penggunaan Preset Video (Preset & Subtitle Styling)
Panduan mendalam mengenai Tab Preset, pembuatan gaya subtitle kustom (Karaoke Mode), pengaturan posisi watermark/IntiTitle/IntiHook, serta konfigurasi mesin bypass hak cipta.

[![Tutorial Preset](https://img.youtube.com/vi/JiKGYIP1yQQ/maxresdefault.jpg)](https://youtu.be/JiKGYIP1yQQ)

### 🎬 Fase 3 (1): AutoCut via API Analyzer
Demo potong klip otomatis menggunakan API Key di dalam AI Studio, pengenalan dashboard rendering, dan log server.

[![Tutorial AutoCut API](https://img.youtube.com/vi/23nGnOpWL_0/maxresdefault.jpg)](https://youtu.be/23nGnOpWL_0)

### 🎬 Fase 3 (2): AutoCut via Ekstensi Chrome
Penggunaan Ekstensi Intisari Extractor untuk workflow gratis via Google Gemini Custom.

[![Tutorial Ekstensi](https://img.youtube.com/vi/zH3-xjvK39g/maxresdefault.jpg)](https://youtu.be/zH3-xjvK39g)

---

## ✨ FITUR UNGGULAN (CORE FEATURES)

### 1. 🤖 GOD MODE (AI-Powered Automation)
Ubah video *landscape* (YouTube) menjadi video *portrait* (TikTok/Reels/Shorts) secara otomatis tanpa perlu *editing* manual.
* **Smart Face Tracking:** Menggunakan algoritma AI untuk melacak pergerakan wajah pembicara, memastikan objek utama selalu berada di tengah layar (*Auto-Reframe / Crop* dinamis).
* **Whisper AI Auto-Captioning:** Terintegrasi langsung dengan model AI `ggml-medium.bin` untuk mentranskripsi audio secara *offline* dan membakarnya langsung ke dalam video (*Hardsub*) dengan akurasi tinggi.

### 2. ⚡ DYNAMIC PARALLEL ENGINE (Multi-Threading FFmpeg)
* **User-Defined CPU Workers:** Bebaskan batasan pemrosesan! Pengguna dapat mengatur jumlah proses paralel (contoh: 5 klip dirender sekaligus) langsung dari UI *Settings*.
* **CPU Starvation Mitigation:** FFmpeg berjalan di *background* dengan prioritas Windows yang disesuaikan (`BELOW_NORMAL_PRIORITY`), memastikan PC Anda tidak *freeze* atau *lag* meskipun CPU berjalan di 100%.

### 3. 🌐 COMMAND CENTER & CHROME EXTENSION SYNC
* **WebSocket Real-Time Sync:** Mengirim tugas ekstraksi video langsung dari Google Gemini ke mesin lokal Anda secara instan menggunakan ekstensi **Intisari Extractor**.
* **Live Dashboard Tracker:** Pantau progres *download*, status *render* klip individu, hingga log terminal mesin secara *real-time* langsung dari antarmuka web yang elegan.

### 4. 🎨 GLOBAL PRESET STUDIO
Sistem modifikasi *subtitle* visual yang komprehensif. Anda dapat membuat, melihat pratinjau (*live preview*), dan menyimpan gaya *subtitle* Anda sendiri:
* Kustomisasi jenis *Font* (mendukung instalasi font eksternal).
* Pengaturan ukuran teks, warna *Primary*, warna *Outline*, ketebalan *Stroke*, hingga jarak *Margin Vertical*.

### 5. 📥 MULTI-PLATFORM DOWNLOADER (Anti-403 Bypass)
Menggunakan mesin `yt-dlp` terenkapsulasi yang mampu mengunduh video mentah (Raw Media) dari berbagai *platform* sosial media dengan mulus.
* **Cookie Injection:** Bypass proteksi *Anti-Bot* dan batasan *Age-Restricted* secara otomatis menggunakan identitas `cookies.txt` tersimpan.
* **Auto-Typo Handler:** Mencegah *crash* jika pengguna salah memasukkan format URL (Link Typo).

### 6. 🔌 SEAMLESS HOOK MERGER
Sistem penjahit video (Muxer/Concat) yang menggabungkan video "Hook" (video pemancing) dengan klip utama Anda secara mulus tanpa mengorbankan kualitas audio atau framerate.

### 7. 🔄 INTISARI AUTO-UPDATER & PLUGIN MANAGER
* **Hot-Swap Updates:** Sinkronisasi pembaruan *blueprint* kode dari GitHub langsung melalui tombol di UI.
* **Dynamic Plugin Installer:** Unduh mesin AI berukuran besar (Whisper/Face AI) melalui sistem `aria2c` *multi-connection* langsung dari antarmuka Dashboard.

---

## 🏗️ ARSITEKTUR TEKNIS & TECH STACK

Intisari Clips dibangun dengan pendekatan hibrida (*Environment Agnostic*) yang memisahkan antara antarmuka web yang modern dengan mesin komputasi brutal di belakang layar.

* **Backend / Orchestrator:** `Python 3.11`, `FastAPI`, `Uvicorn` (Web Server), `WebSockets` (Live Comm).
* **Frontend UI:** `HTML5`, `Vanilla JavaScript`, `Tailwind CSS`, `FontAwesome`.
* **Video Engine:** `FFmpeg` (Binary Injected), `yt-dlp`.
* **AI Engine:** `Whisper.cpp` (OpenAI Audio), `OpenCV / MediaPipe` (Vision).

---

## 🚀 CEK PEMBARUAN TERBARU

Kami terus melakukan peningkatan arsitektur dan penambahan fitur baru untuk memastikan stabilitas dan performa terbaik dari Intisari Clips. Pastikan Anda selalu menggunakan versi terbaru!

👉 **[Klik di sini untuk melihat Changelog & Mengunduh Versi Terbaru di Halaman Rilis GitHub](https://github.com/intisariapps-com/intisariclips/releases)**

---

## 🔒 PERHATIAN & LISENSI
Software ini menggunakan jalur *Telemetry* dan validasi lisensi *Hardware ID (HWID)* khusus (*Trial/Premium*). Semua *rendering* video terjadi di dalam disk lokal (127.0.0.1).

**Intisari Clips - "Local Workstation Video Software"** *Built with ❤️ for Content Creators & Video Automation Engineers.*
