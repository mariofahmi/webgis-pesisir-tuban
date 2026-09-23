# WebGIS Pesisir Tuban — Portal Riset Foto GPS & AI Studio Assistant

> **Perancang / Developer:** **Mario Fahmi Syahrial**  
> **Wilayah Kajian:** Pesisir Kabupaten Tuban, Jawa Timur (Kecamatan Bancar, Jenu, Palang, Tambakboyo, Tuban)

---

## 📌 Gambaran Umum
**WebGIS Pesisir Tuban** adalah portal pemetaan geospasial interaktif berbasis web untuk mendokumentasikan, memvisualisasikan, dan menganalisis 212 foto survei lapangan ber-GPS di 77 titik klaster pesisir Kabupaten Tuban.

Aplikasi ini mengintegrasikan peta interaktif **Leaflet.js** dengan **Google Gemini AI Assistant** untuk analisis spasial berbasis percakapan (*Spatial Conversational AI*).

---

## ✨ Fitur Utama
* **Peta Interaktif (Leaflet.js & MarkerCluster):** Pengelompokan titik GPS otomatis dengan ikon SVG dinamis berbasis jumlah foto.
* **Multi-Basemap:** Satelit Esri, Hybrid (Satelit + Label Batas), OpenStreetMap, dan OpenTopoMap.
* **Sidebar & Pencarian Cepat:** Filter per kecamatan, live-search nama desa/file/koordinat, dan kartu detail lokasi.
* **Integrasi Google Gemini AI Studio:**
  * Terhubung dengan model Gemini 2.0 Flash via API Key.
  * Dilengkapi *Smart Local Engine Fallback* untuk menjawab statistik foto dan pencarian lokasi secara instan tanpa API key.
* **Pratinjau Foto & Navigasi Luar:** Pop-up detail foto dengan tautan langsung menuju Google Maps dan OpenStreetMap.

---

## 🛠️ Teknologi yang Digunakan
* **Frontend:** HTML5, CSS3 (Glassmorphism & Dark Mode), Vanilla JavaScript
* **GIS Library:** [Leaflet.js](https://leafletjs.com/), Leaflet.markercluster
* **AI Engine:** Google AI Studio (Gemini 2.0 Flash)
* **Automation:** PowerShell (.NET `System.Drawing` untuk kompresi foto & GitHub REST API uploader)

---

## 👤 Pengembang & Perancang
* **Mario Fahmi Syahrial**