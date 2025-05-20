# 🧩 Slide Puzzle

Rust ve Slint ile geliştirilmiş interaktif bir **slide puzzle (kaydırmalı yapboz)** oyunudur. Kullanıcılar, rastgele karıştırılmış parçaları yerlerine sürükleyerek orijinal görüntüyü yeniden oluşturmayı hedefler. Ayrıca kendi görsellerini yükleyerek kişiselleştirilmiş puzzle deneyimi yaşayabilirler.

> 🎓 Bu proje, Bilecik Şeyh Edebali Üniversitesi Bilgisayar Mühendisliği Bölümü “Tasarım I” dersi kapsamında hazırlanmıştır.

## 🎮 Oyun Görselleri

### Görsel tabanlı puzzle modu:
![Görsel Puzzle Modu](assets/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202025-05-20%20114713.png)

### Sayısal puzzle (default) görünüm:
![Sayısal Puzzle Modu](assets/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202025-05-20%20114731.png)

## 🚀 Özellikler

- 🔄 Shuffle (karıştır) butonu ile oyun sıfırlama
- 🧠 Oto çözümleme modu (demo amaçlı)
- 🖼️ Kendi resmini yükleyerek kişisel puzzle oluşturma
- 🎯 Spring (yay) animasyonu ile yumuşak geçişler
- 🧩 Sayılarla ya da görsellerle oynanabilen iki mod
- 🌐 WebAssembly (WASM) desteği sayesinde tarayıcıda çalışma
- 💻 Masaüstü desteği

## ⚙️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| 🦀 **Rust** | Sistem programlama dili |
| 🖼️ **Slint** | Modern reaktif UI framework |
| 🎲 **rand** | Puzzle karıştırma algoritmasında |
| 📁 **rfd** | Resim yükleme için dosya seçici |
| 🧮 **VecModel** | Puzzle veri modeli için |

## 🧪 Kurulum ve Çalıştırma

### 💻 Masaüstü İçin

```bash
git clone https://github.com/alim1202003/Slide_Puzzle.git
cd Slide_Puzzle
cargo run
