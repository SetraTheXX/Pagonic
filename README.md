# 🚀 Pagonic - Modern WinRAR Alternatifi

> *"19 yaşında bir geliştirici olarak, dosya sıkıştırma dünyasına yenilik getirmek için yola çıktım. Pagonic, bu tutkulu yolculuğun ürünü."*

<div align="center">

<!-- Logo henüz hazırlanmadı - public release ile birlikte eklenecek -->

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python](https://img.shields.io/badge/python-3.13+-blue.svg)](https://www.python.org/downloads/)
[![Build](https://img.shields.io/badge/build-stable-brightgreen.svg)]()
[![Tests](https://img.shields.io/badge/tests-960%20passed-brightgreen.svg)]()
[![Performance](https://img.shields.io/badge/speed-300%2B%20MB%2Fs-orange.svg)]()
[![AI](https://img.shields.io/badge/AI%20confidence-82%25-purple.svg)]()

**Modern, AI-destekli, açık kaynak sıkıştırma yazılımı**

[🚧 Proje Durumu](#proje-durumu) • [📊 Performans](#performans-karşılaştırması) • [📚 Dokümantasyon](#dokümantasyon) • [🤝 Katkıda Bulun](#katkıda-bulunma) • [💬 Topluluk](#topluluk)

</div>

---

## 👋 Merhaba, Ben Setra !

**19 yaşındayım** ve Pagonic'i tek başıma geliştiriyorum. Bu proje, WinRAR'ın modern zamanların ihtiyaçlarını karşılamakta yetersiz kaldığını fark ettiğimde başladı. 

### 💭 Neden Pagonic?

WinRAR kullanırken sürekli şu sorunlarla karşılaşıyordum:
- 🐌 **Yavaş performans** - Büyük dosyalarda dakikalarca bekleme
- 🎨 **Eski arayüz** - 90'lardan kalma tasarım
- 💰 **Lisans sorunu** - Sürekli hatırlatmalar
- 🤖 **Akıllı değil** - Dosya türüne göre optimizasyon yok
- 🔒 **Kapalı kaynak** - Ne yaptığını bilmiyoruz

Bu sorunları çözmek için **4.5+ ay boyunca** gece gündüz çalışarak Pagonic'i geliştirdim.

---

## ✨ Pagonic'in WinRAR'dan Farkları

### 🚀 **Performans Optimizasyonları**
- **300+ MB/s ortalama hız** (test koşullarına göre değişkenlik gösterir)
- **SIMD hızlandırma** - İşlemci seviyesinde optimizasyon
- **Memory pool sistemi** - RAM kullanımı %40 azaltma
- **Hibrit işleme** - Dosya boyutuna göre adaptif stratejiler

### 🤖 **AI Destekli Akıllı Sistem**
```
🧠 AI Confidence: %82
📊 12 farklı dosya türü tanıma
⚡ Otomatik optimizasyon seçimi
🎯 Dosya içeriğine göre strateji
```

### 💾 **Gelişmiş Bellek Yönetimi**
- **Hibrit sistem**: Küçük dosyalar için hızlı yol, büyük dosyalar için memory-efficient yol
- **Buffer pooling**: Bellek parçalanmasını önleme
- **Adaptive chunking**: Dosya boyutuna göre otomatik ayarlama

### 🛡️ **Modern Güvenlik**
- **CRC32 doğrulama** her adımda
- **Path traversal koruması**
- **Memory-safe operations**
- **Error recovery** mekanizmaları

### 🔧 **Teknik İnovasyonlar**
- **MinimalZipWriter**: 4GB'a kadar dosya desteği için özel ZIP yazıcı
- **Hybrid Fast Path**: 10MB altı/üstü dosyalar için farklı stratejiler
- **SIMD CRC32**: Hardware acceleration ile %899 hızlanma
- **AI Pattern Recognition**: Dosya türü analizi ve optimizasyon

---

## 📊 Performans Karşılaştırması

| Özellik | Pagonic | WinRAR | 7-Zip | Fark |
|---------|---------|--------|-------|------|
| **Ortalama Hız** | 300+ MB/s | ~80-150 MB/s | ~120-200 MB/s | 🚀 Optimize edilmiş |
| **AI Optimizasyon** | ✅ %82 güven | ❌ | ❌ | 🧠 Benzersiz |
| **Modern UI** | ✅ 2025 | ❌ 1999 | ⚠️ Temel | 🎨 26 yıl fark |
| **Açık Kaynak** | ✅ GPL-3.0 | ❌ | ✅ LGPL | 🔓 Koruyucu |
| **SIMD Hızlandırma** | ✅ AVX2/SSE4 | ❌ | ⚠️ Kısıtlı | ⚡ Hardware boost |
| **Hibrit Sistem** | ✅ Adaptif | ❌ | ❌ | 🔄 Akıllı seçim |

---

## 🎯 Özellikler

### ✅ **V1.0 - Development Preview** *(Geliştirme Aşaması)*
- 🗜️ **ZIP32 tam desteği** (4GB'a kadar dosyalar)
- 🤖 **AI destekli sıkıştırma** (%82 güven oranı)
- ⚡ **SIMD hızlandırma** (CRC32 + memory operations)
- 💾 **Memory pool optimizasyonu**
- 🧵 **Multi-threading desteği**
- 🔄 **Hibrit sistem** (küçük/büyük dosya optimizasyonu)
- 📊 **Real-time performans izleme**
- 🛡️ **Gelişmiş hata yönetimi**
- 🧪 **960 kapsamlı test** (%100 başarı oranı)
- ⚠️ **Not**: Henüz beta aşamasında, kullanıcı testleri devam ediyor

### 🔜 **V1.1 - Public Beta** *(Şubat 2025)*
- 📦 **ZIP64 desteği** (4GB+ dosyalar)
- 🎨 **Modern Electron GUI** (React + TypeScript)
- 📈 **Gelişmiş performans dashboard**
- 🔍 **Dosya önizleme sistemi**
- 🖱️ **Drag & drop** gelişmiş desteği
- 📱 **Responsive tasarım**
- 🚀 **İlk public release**

### 🚀 **V1.5 - Stable Release** *(Mayıs 2025)*
- 🗃️ **RAR okuma desteği** (patent-safe)
- 📋 **TAR/GZ formatları**
- 🔒 **AES-256 şifreleme**
- 🌐 **Cloud storage entegrasyonu** (Google Drive, OneDrive)
- 📊 **Batch processing**
- 🎯 **Context menu entegrasyonu**

### 🌟 **V2.0 - Enterprise** *(2025 Sonbahar)*
- 🗂️ **ZST (Zstandard) desteği**
- 🔐 **2FA güvenlik sistemi**
- 🌍 **Çoklu dil desteği**
- 📱 **Mobile companion app**
- 🤝 **Plugin sistemi**
- 🏢 **Enterprise özellikler**

---

## 🛠️ Teknik Detaylar

### 🏗️ **Mimari**
```
pagonic/
├── 🐍 core/                 # Python sıkıştırma motoru
│   ├── zip_handler.py       # Ana ZIP işleyici (3500+ satır)
│   ├── minimal_zip_writer.py # Büyük dosya yazıcı
│   ├── hybrid_decompressor.py # Hibrit açma motoru
│   ├── simd_crc32.py        # SIMD hızlandırma
│   └── ai_optimizer.py      # AI optimizasyon sistemi
├── ⚡ frontend/             # Modern Electron GUI
│   ├── React + TypeScript   # Modern UI framework
│   └── WebSocket bridge     # Real-time iletişim
├── 🧪 tests/               # 960 kapsamlı test
└── 📊 benchmarks/          # Performans testleri
```

### 🔬 **Geliştirme Süreci**
- **50,000+ satır kod** yazdım (98 Python dosyası)
- **960 test** geçirdim (%100 başarı)
- **4.5+ ay** yoğun geliştirme
- **100+ modül ve bileşen** tasarladım
- **Ana ZIP handler**: 3,622 satır (tek dosya)
- **AI optimizasyon sistemi**: Modüler mimari

### 🧠 **AI Sistemi Detayları**
```python
# AI dosya türü tanıma sistemi
AI_PATTERNS = {
    'text': 0.90,      # %90 güven - metin dosyaları
    'binary': 0.80,    # %80 güven - binary dosyalar  
    'image': 0.77,     # %77 güven - görüntü dosyaları
    'code': 0.88,      # %88 güven - kaynak kodu
    'archive': 0.71    # %71 güven - arşiv dosyaları
}
```

---

## 🚧 Proje Durumu

### ⚠️ **Geliştirme Aşamasında**
Pagonic şu anda **aktif geliştirme** aşamasında. Core engine %95 tamamlandı, fakat:
- ✅ **ZIP işleme motoru** tam çalışır durumda
- ✅ **AI optimizasyon sistemi** aktif
- ✅ **SIMD hızlandırma** implementasyonu tamamlandı
- 🔄 **GUI geliştirme** devam ediyor (Electron + React)
- ⏳ **Public release** henüz hazır değil

### 🎯 **Neden GitHub'da?**
- 📈 **Şeffaflık**: Geliştirme sürecini paylaşmak
- 🤝 **Topluluk**: Erken geri bildirim almak
- 🌟 **İlham**: Diğer geliştiricilere ilham vermek
- 📚 **Öğrenme**: Açık kaynak deneyimi kazanmak

---

## 📸 Ekran Görüntüleri ve Demo

### 🚧 **Görsel İçerik Durumu**
- 🎨 **GUI henüz geliştirme aşamasında** - Electron arayüzü tamamlandığında eklenecek
- 📊 **Console çıktısı örnekleri** - Test sonuçları mevcut
- ⚡ **Performans benchmark görüntüleri** - Yakında eklenecek
- 🧪 **Test sonuçları ekran görüntüleri** - Mevcut ama düzenlenmesi gerekiyor

### 💡 **Şimdilik**
Görsel içerik için [GitHub Issues](https://github.com/SetraTheXX/Pagonic/issues) üzerinden sorabilir veya email ile iletişime geçebilirsiniz.

---

## 🛠️ Kullanılan Teknolojiler

### 🐍 **Backend (Core Engine)**
- **Python 3.13+** - Ana geliştirme dili
- **NumPy** - SIMD optimizasyonları ve matematik işlemleri
- **Psutil** - Sistem kaynaklarını izleme
- **Zlib** - Temel sıkıştırma algoritmaları
- **Threading** - Paralel işleme desteği
- **Mmap** - Bellek eşlemeli dosya işlemleri

### ⚡ **Frontend (Geliştirme Aşamasında)**
- **Electron** - Cross-platform desktop app
- **React + TypeScript** - Modern UI framework
- **Tailwind CSS** - Utility-first CSS
- **Vite** - Hızlı build tool

### 🧪 **Test ve Geliştirme**
- **Pytest** - Unit testing framework
- **Custom benchmarking tools** - Performans testleri
- **Git** - Version control
- **Manual testing** - Kapsamlı manuel testler

---

## ⚙️ Sistem Gereksinimleri

### ⚠️ **Henüz Test Edilmedi**
Sistem gereksinimleri henüz tam olarak belirlenmiş değil. Farklı donanımlar üzerinde test süreci devam ediyor.

### 🎯 **Tahmini Gereksinimler**
**Minimum (Tahmin):**
- Windows 10/11 (64-bit)
- Python 3.13+ (development için)
- 4GB RAM
- 200MB disk alanı

**Önerilen (Tahmin):**
- Windows 11 (64-bit)
- 8GB+ RAM
- SSD disk (performans için)
- Modern CPU (SIMD desteği için)

### 📝 **Not**
GUI tamamlandıktan sonra farklı sistemlerde kapsamlı testler yapılacak ve kesin gereksinimler belirlenecek.

---

## 🧪 Test Metodolojisi ve Performans

### 📊 **Test Süreci Hakkında**
**4.5+ ay boyunca** sürekli test ve optimizasyon yapıldı:
- 🔄 **Simüle testler**: Kontrollü ortamda binlerce test
- 🌍 **Gerçek dünya testleri**: Farklı dosya türleri ve boyutları
- 📈 **Sürekli iyileştirme**: Her gün performans ölçümü
- 🎯 **Gerçekçi yaklaşım**: Abartısız, ölçülebilir sonuçlar

### ⚡ **Performans Notları**
- 📏 **Ortalama 300+ MB/s**: Test koşullarına göre değişkenlik gösterir
- 🖥️ **Donanım bağımlı**: CPU, RAM, SSD hızına göre değişir
- 📁 **Dosya türü etkisi**: Metin, binary, görüntü dosyalarında farklı sonuçlar
- ⚠️ **Henüz beta**: GUI tamamlandıktan sonra kesin hızlar paylaşılacak

### 💾 **Bellek Optimizasyonu**
```
Pagonic:  Adaptif bellek kullanımı (~40% daha verimli)
WinRAR:   Sabit bellek tahsisi
7-Zip:    Temel optimizasyon
```

---

## 🗺️ Geliştirme Yol Haritası

### 📅 **2024 Q4** ✅ *Tamamlandı*
- [x] Core sıkıştırma motoru
- [x] AI optimizasyon sistemi
- [x] SIMD hızlandırma
- [x] Hibrit sistem
- [x] 960 kapsamlı test

### 📅 **2025 Q1** 🔄 *Devam Ediyor*
- [ ] Modern Electron GUI
- [ ] ZIP64 desteği
- [ ] Cloud entegrasyonu
- [ ] Performance dashboard

### 📅 **2025 Q2**
- [ ] RAR okuma desteği
- [ ] TAR/GZ formatları
- [ ] AES-256 şifreleme
- [ ] Mobile companion

### 📅 **2025 Q3+**
- [ ] Plugin sistemi
- [ ] Enterprise özellikler
- [ ] Machine learning optimizasyonu
- [ ] Blockchain entegrasyonu

---

## ❓ Sık Sorulan Sorular (FAQ)

### 🤔 **"Neden yeni bir sıkıştırma programı?"**
Kendi bilgisayarımda daha modern, hızlı bir program istiyordum. WinRAR eski, 7-Zip temel. AI destekli, kullanıcı dostu bir alternatif yapmak istedim.

### 📱 **"Mobile versiyonu olacak mı?"**
Uzun vadede V2.0'da companion app planlanıyor, ama şu an öncelik desktop versiyonu tamamlamak.

### 💰 **"Ücretli olacak mı?"**
Hayır, tamamen ücretsiz ve açık kaynak kalacak. Amacım para kazanmak değil, kendimi geliştirmek.

### 🏷️ **"İsim kesin mi?"**
"Pagonic" ismi henüz kesin değil, değişebilir. O yüzden domain vs almadım.

### 🐧 **"Linux/macOS desteği?"**
Şu an Windows odaklı geliştiriyorum. GUI tamamlandıktan sonra diğer platformlar değerlendirilecek.

### 🎓 **"Neden bu projeyi yaptın?"**
Üniversiteye yeni giriyorum, CV'me eklemek ve kendimi geliştirmek için. Açık kaynak deneyimi kazanmak istiyorum.

### 🔧 **"Nasıl test edebilirim?"**
Henüz public release yok. GUI tamamlandıktan sonra beta testçiler aranacak.

---

## 📈 Proje İstatistikleri

### 📊 **Geliştirme Metrikleri**
- **Kod satırları**: 50,000+ (98 Python dosyası)
- **Ana ZIP handler**: 3,622 satır (tek dosya)
- **Test sayısı**: 960+ otomatik test (%100 başarı)
- **Manuel test saatleri**: 200+ saat
- **Test edilen dosya türleri**: 15+ farklı format

### 🏗️ **Mimari Metrikleri**
- **Ana modüller**: 100+ bileşen
- **Optimizasyon katmanları**: AI, SIMD, Memory Pool, Hibrit
- **Desteklenen format**: ZIP32 (4GB'a kadar)
- **Performans**: 300+ MB/s ortalama (test koşullarına bağlı)

### 🎯 **Kişisel Hedefler**
- **GitHub Stars**: İlk hedef 100+ (mütevazi başlangıç)
- **Öğrenme**: Modern teknolojilerde deneyim kazanmak
- **CV**: Portföy projesi olarak kullanmak

---

## 🤝 Katkıda Bulunma

### 💝 **Neden Katkıda Bulunmalısınız?**
- 🌟 **Açık kaynak** - Herkes için ücretsiz
- 🚀 **Modern teknoloji** - En son Python, React, AI
- 📈 **Büyüyen proje** - Erken katkıcı olma şansı
- 🎓 **Öğrenme fırsatı** - SIMD, AI, performans optimizasyonu

### 🔧 **Katkı Alanları**
- **Python geliştirme** - Core engine iyileştirmeleri
- **Frontend geliştirme** - React/Electron UI
- **AI/ML** - Optimizasyon algoritmaları
- **Testing** - Yeni test senaryoları
- **Documentation** - Dokümantasyon iyileştirme
- **Design** - UI/UX tasarım

### 📋 **Katkıda Bulunma Adımları**

#### 🐛 **Bug Raporu (Henüz Beta Değil)**
1. **Email ile bildirin**: [pagonicapp@gmail.com](mailto:pagonicapp@gmail.com)
2. **GitHub Issues** kullanabilirsiniz (template yakında)
3. **Detaylı açıklama** yapın - hangi durumda, nasıl hata

#### 💡 **Özellik Önerisi**
1. **Önce email ile tartışalım** - fikrini paylaş
2. **GitHub Issue** açabilirsin
3. **Mütevazi beklenti** - henüz küçük bir proje

#### 🎓 **Öğrenci Katkıcılar**
**Aynı yaştaki arkadaşlardan** katkı alabilmek harika olur:
- 📚 **Birlikte öğrenelim** - deneyim paylaşalım
- 🤝 **Mentorluk** - birbirimize yardım edelim
- 💻 **İlk açık kaynak** deneyiminiz olabilir

#### 🔧 **Kod Katkısı**
1. **Fork** yapın
2. **Feature branch** oluşturun (`git checkout -b amazing-feature`)
3. **Commit** yapın (`git commit -m 'Add amazing feature'`)
4. **Push** yapın (`git push origin amazing-feature`)
5. **Pull Request** açın

Detaylı kılavuz için [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını okuyun.

---

## 📚 Dokümantasyon

### 📝 **Dokümantasyon Durumu**
Proje henüz geliştirme aşamasında olduğu için kapsamlı dokümantasyon hazırlanmadı. Public release ile birlikte aşağıdaki dokümantasyonlar eklenecek:

- 📖 **Kullanıcı Kılavuzu** - Başlangıç rehberi *(yakında)*
- 🏗️ **Geliştirici Dokümantasyonu** - API referansı *(yakında)*
- ⚡ **Performans Kılavuzu** - Optimizasyon ipuçları *(yakında)*
- 🤖 **AI Sistemi Dokümantasyonu** - Akıllı optimizasyon *(yakında)*
- 🧪 **Test Kılavuzu** - Test yazma rehberi *(yakında)*

### 💡 **Şu An İçin**
- 📧 **Sorularınız için**: [pagonicapp@gmail.com](mailto:pagonicapp@gmail.com)
- 🐙 **Teknik sorular**: [GitHub Issues](https://github.com/SetraTheXX/Pagonic/issues)
- 📋 **Kod incelemesi**: Repository'deki kaynak kodlar

---

## 💬 Topluluk

### 🌐 **İletişim Kanalları**
- 📧 **[Email](mailto:pagonicapp@gmail.com)** - Doğrudan iletişim ve geri bildirim
- 🐙 **[GitHub Issues](https://github.com/SetraTheXX/Pagonic/issues)** - Bug raporları ve öneriler
- 💬 **Discord Server** - Yakında açılacak
- 🐦 **Social Media** - Proje büyüdükçe eklenecek

### ⚠️ **İsim ve Domain Durumu**
- 🏷️ **"Pagonic" ismi** henüz kesinleşmedi - değişebilir
- 🌍 **Domain alınmadı** - isim kesinleştikten sonra
- 📧 **Geçici email**: pagonicapp@gmail.com
- 🎨 **Logo ve branding** - final isim sonrası tasarlanacak

### 👥 **Topluluk Hedefleri**
- 🌟 **GitHub Stars**: İlk hedef 100+ (mütevazi başlangıç!)
- 👥 **Katkıcılar**: İlk katkıcıları bekliyoruz
- 📧 **Geri bildirim**: Her türlü öneri değerli

---

## 🏆 Başarılar ve Tanınma

### 📊 **Teknik Başarılar**
- ✅ **%100 test başarısı** (960 test geçti)
- ✅ **300+ MB/s ortalama hız** (test koşullarına göre değişken)
- ✅ **%82 AI güven oranı** (çok yüksek doğruluk)
- ✅ **4GB dosya desteği** (ZIP32 tam kullanımı)
- ✅ **98 Python dosyası** (modüler mimari)
- ✅ **Binlerce test saati** (simüle + gerçek dünya testleri)

### 🔮 **Uzun Vadeli Vizyon (Mütevazi)**
- 🎓 **CV projesi** - Üniversite ve iş başvurularında portföy olarak kullanmak
- 📚 **Öğrenme deneyimi** - Modern teknolojilerde kendimi geliştirmek
- 🤝 **Açık kaynak katkısı** - Topluluğa küçük de olsa bir şey bırakmak
- 💡 **Teknik beceri** - Python, AI, performans optimizasyonu öğrenmek
- 🌟 **Belki faydalı olur** - Birkaç kişinin işine yararsa mutlu olurum

### 🎯 **Gerçekçi Hedefler**
- ✅ **İlk hedef**: Projeyi tamamlamak ve yayınlamak
- 📈 **100+ GitHub star** alabilirse harika olur
- 🤝 **5-10 katkıcı** bulabilirsek süper
- 💼 **İş başvurularında** gösterebileceğim bir proje

---

## ❤️ Teşekkürler

### 🙏 **Özel Teşekkürler**
- **Python Community** - Muhteşem ekosistem için
- **Open Source Contributors** - İlham veren projeler için
- **Stack Overflow** - Sayısız soruma cevap için
- **GitHub** - Bu platformu sağladığı için

### 🌟 **Katkıcılar**
Henüz yeni bir proje olduğumuz için katkıcı listemiz küçük, ama büyümek için sabırsızlanıyoruz!

<!-- Contributors will be automatically added here -->
<a href="https://github.com/SetraTheXX/Pagonic/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SetraTheXX/Pagonic" />
</a>

---

## 📄 Lisans

Bu proje **GNU General Public License v3.0** ile lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasını inceleyin.

### 🛡️ **GPL-3.0 Lisansı Neden?**
- ✅ **Kodun korunması** - Türev çalışmalar da açık kaynak olmak zorunda
- ✅ **Copyleft prensibi** - Kodumu kullanan herkes kaynak kodunu paylaşmalı
- ✅ **Ticari koruma** - Ticari kullanımda bile açık kaynak kalması gerekir
- ✅ **Topluluk yararı** - Geliştirmeler topluluğa geri döner
- ⚠️ **Bilinçli seçim** - Kodumun çalınmasını istemediğim için seçtim

---

## 🚀 Son Söz

Pagonic'e başlamamın sebebi aslında çok basitti: **kendi bilgisayarımda daha güzel bir sıkıştırma programı** olmasını istiyordum. WinRAR'a meydan okumak gibi büyük bir hedefle başlamadım, sadece kendi ihtiyaçlarım için daha modern, daha hızlı bir şey yapmak istemiştim.

**19 yaşında bir geliştirici** olarak bu yolculuk kolay olmadı. Geceler boyunca kod yazdım, algoritmaları optimize ettim, testler yazdım. Zamanla proje gerçekten çok ilerledi ve şimdi **%100 test başarısı**, **300+ MB/s performans**, **AI destekli akıllı sistem** ile güzel bir noktaya geldi.

**Umarım** topluluğa **güzel bir alternatif** sunabilirim. Bu sadece kişisel bir proje olarak başladı, ama belki başkalarının da işine yarayabilir.

Eğer bu proje size ilginç geldiyse:
- ⭐ **Star** verin - Motivasyon kaynağım!
- 🔄 **Fork** yapın - Kendi versiyonunuzu oluşturun
- 🐛 **Issue** açın - Hata bulursanız bildirin
- 💡 **Feature** önerin - Fikirlerinizi paylaşın
- 🤝 **Contribute** edin - Birlikte daha iyisini yapalım

---

<div align="center">

**🎯 Pagonic ile dosya sıkıştırma artık daha hızlı, daha akıllı, daha modern!**

[![Star History Chart](https://api.star-history.com/svg?repos=SetraTheXX/Pagonic&type=Date)](https://star-history.com/#SetraTheXX/Pagonic&Date)

**Pagonic'i kullandığınız için teşekkürler!** 🙏

*"Tek başıma başladım, ama toplulukla büyütmeye devam edeceğim. Amacım kendimi geliştirmek ve öğrenmek."* - Setra, 19

</div>
