# 🎮 Bilfen Oyunları

Tarayıcıda çalışan, kurulum gerektirmeyen 3B eğitim oyunları — Three.js ile.

## 🧊 Buz Kırıcı — Canlı Sensörler ve Akıllı Araç

Buz Fırtınası Akıllı Şehri dondurdu! Akıllı araç ROBI gözleri kapalı yola çıkar — ona **canlı sensörler** eşlik eder: 📡 Mesafe Sensörü (bip hızı + Buz Radarı) ve 🖐 Tampon Sensörü (SPACE ile buz kırma / dur sinyali). 6 buzlu binayı sensör takım work'iyle kır, buz kristallerini topla!

**🎮 Oyna:** [https://bilfen.github.io/bilfen-games/akilli-sehir.html](https://bilfen.github.io/bilfen-games/akilli-sehir.html)

Kontroller: **WASD** yürü · **Shift** koş · **SPACE** buz kır / dur sinyali · **R** rol değiştir. Roller: Akıllı Araç 🚗 / Mesafe Sensörü 📡 / Tampon Sensörü 🖐 — 15 dakikalık sınıf etkinliği, yönerge paneli sağ altta.

---

## 🌊 Deniz Dibi — Çöp Avcısı

Bilfen robotla denize dal, çöpleri topla, denizanalarından kaç! Tarayıcıda çalışan 3D oyun — Three.js ile, kurulum gerektirmez.

**🎮 Oyna:** [https://bilfen.github.io/bilfen-games/denizalti-cop.html](https://bilfen.github.io/bilfen-games/denizalti-cop.html)

## 🕹️ Kontroller
- **W A S D / Ok tuşları** — Yüz
- **Space** — Yüksel · yüzeyde nefes al
- **Shift** — Alçal · dip ve dipte yürü
- **1** ⚡ Turbo · **2** 🫧 O₂ Şoku · **3** 🧲 Mıknatıs · **4** 📡 Sonar
- **P** Duraklat · **R** Yeniden · **M** Ses

Her topladığın çöp sana oksijen kazandırır: 🥤 Şişe +10 · 🥫 Kutu +15 · 🛍 Poşet +25 · 🛞 Lastik +40. Nefesin azalırsa yüzeye çık, denizanasına dokunma! Seri yaptıkça çöpün puanı katlanır.

Mobilde dokunmatik joystick + butonlar otomatik açılır.

## 💻 Yerelde çalıştırma

```bash
python -m http.server 8126
# http://localhost:8126/denizalti-cop.html
```

Windows'ta `DenizOyunuBaslat.bat` ile tek tıkla başlat.

## 🛠️ Teknoloji
- Three.js (modül, yerel `lib/` içinde — CDN bağımlılığı yok)
- GLTF modeller: `Bilfen_Robot.glb` (animasyonlu), `model-hq.glb` (yedek)
- Dosyasız prosedürel Web Audio müziği ve ses efektleri
- Tek dosyalık HTML oyun — build gerektirmez
