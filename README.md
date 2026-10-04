# rainbow.chic
# 🌈 RainbowChic — 3D Weather, Lifestyle & Cozy Companion Studio

<div align="center">
  <img src="https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js" alt="Three.js">
  <img src="https://img.shields.io/badge/TailwindCSS-v3.0-38bdf8?style=for-the-badge&logo=tailwind-css" alt="TailwindCSS">
  <img src="https://img.shields.io/badge/Web%20Audio%20API-Synthesized-a855f7?style=for-the-badge" alt="Web Audio API">
  <img src="https://img.shields.io/badge/Open--Meteo-Free%20API-emerald?style=for-the-badge" alt="Open-Meteo">
  <img src="https://img.shields.io/badge/License-MIT-f472b6?style=for-the-badge" alt="License">
</div>

<br>

**RainbowChic**, sıradan hava durumu panellerini interaktif bir masaüstü arkadaşı deneyimine dönüştüren modern bir web uygulamasıdır. Canlı hava tahminlerini; prosedürel 3D karakter animasyonları, atmosferik parçacık efektleri, Web Audio API tabanlı sentetik doğa sesleri, oyunlaştırma ve Polaroid kartpostal motoruyla bir araya getirir.

---

## ✨ Özellikler

###  1. İnteraktif 3D Karakter & Maskot Motoru (Three.js)
* **3 Farklı Karakter:** *Luna* (Pastel Chic), *Milo* (Sokak Tarzı) ve *Aria* (Cozy Kawaii).
* **Eklem & Poz Sistemi:** Doğal nefes alma (`idle`), el sallama (`wave`), kutlama dansı (`dance`), moda pozu (`pose`) ve göz kırpma mekaniği.
* **Uçan Maskot ("Puf"):** Karakterin yanında süzülen, kanat çırpan ve göz kırpan minik bulut kedi.
* **Tıklama Tepkileri (Raycasting):** Karakter veya maskota tıklandığında anlık hava durumu ve saate uygun konuşma balonları.

###  2. Sıfır Bağımlılıklı Doğa Sesi Motoru (Web Audio API)
Dışarıdan hiçbir `.mp3` dosyası indirmeden, doğrudan tarayıcının ses sentezleyicisiyle üretilen dinlendirici sesler:
* **Hafif Yağmur:** Pembe gürültü (Pink noise) + alçak geçiren filtre.

###  3. Canlı Hava Durumu & Yaşam Tarzı İçgörüleri
* **Open-Meteo Entegrasyonu:** API anahtarı gerektirmeden sıcaklık, nem, rüzgar ve yağış olasılığı.
* **24 Saatlik Akış:** Yatay kaydırılabilir saatlik sıcaklık ve yağış olasılığı çubuğu.
* **7 Günlük Tahmin:** Günlük en yüksek/en düşük sıcaklık kartları.
* **Altın Saat (Golden Hour) & Güneş Döngüsü:** Gün doğumu/batımı takibi ve fotoğrafçılık için en iyi ışığa kalan süreyi hesaplayan canlı sayaç.
* **Hava Kalitesi (AQI) & Mood Tavsiyesi:** Dışarı çıkma, kahve/kitap molası veya yürüyüş için anlık öneriler.

### 4. Mini Oyun & Seviye Sistemi (Affinity Engine)
* **Güneş Avcısı (Mini Game):** 3D sahnede klavye (`A`/`D` veya ok tuşları) ya da ekrandaki dokunmatik yön butonlarıyla gökyüzünden düşen yıldızları toplama oyunu.
* **Besleme & Sevgi:** Puf'a kurabiye verme ve sevme etkileşimleriyle kazanılan tecrübe puanı (XP) ve seviye artışı.
* **Başarım Rozetleri:** *Güneş Aşığı, Yağmur Dansçısı, Gece Kuşu, Gezgin Kaşif* gibi dinamik rozetler.

###  5. Polaroid Kartpostal Üreticisi
* HTML5 Canvas kompozitörü ile o anki 3D sahneyi, şehir bilgisini, dereceyi ve sevimli çıkartmaları birleştirip tek tıkla yüksek çözünürlüklü `.png` Polaroid kart olarak indirme özelliği.

---

## Teknolojiler

* **3D & Animasyon:** [Three.js (r128)](https://threejs.org/)
* **Arayüz & Stil:** [Tailwind CSS](https://tailwindcss.com/) (Cam efekti / Glassmorphism)
* **Ses:** Web Audio API (Prosedürel ses sentezleme)
* **API:** [Open-Meteo Geocoding & Weather Forecast](https://open-meteo.com/)
* **Veri Kalıcılığı:** HTML5 `localStorage` (Seviye, puanlar ve favori şehirler)
* **İkonlar & Tipografi:** FontAwesome 6, Google Fonts (Quicksand, Poppins, Caveat)
  

---
##  Kurulum ve Çalıştırma

Bu proje tamamen istemci taraflı (HTML, CSS ve JavaScript) olarak çalışır. Herhangi bir paket yükleme (Node.js, npm vb.), derleme (build) veya harici API anahtarı ayarı **gerektirmez**.

### Yöntem: Doğrudan Tarayıcıda Açma
1. Projeyi bilgisayarına indir veya GitHub üzerinden klonla:
   ```bash
   git clone [https://github.com/KULLANICI_ADINIZ/RainbowChic.git](https://github.com/KULLANICI_ADINIZ/RainbowChic.git)
   cd RainbowChic
## 📂 Dosya Yapısı

```text
├── index.html       # 3D sahne, ses motoru, arayüz ve API mantığını içeren tek parça uygulama
└── README.md        # Proje dokümantasyonu

##  İletişim
- GitHub: [aysgllngn](https://github.com/aysgllngn)
- E-mail: aysgllngn@gmail.com
