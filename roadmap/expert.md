# ⚫ Uzman Seviye

> Tahmini süre: **6–12 ay** (haftada 10–15 saat)
> Ön koşul: [İleri Seviye](./advanced.md)

Bu seviyede artık tek bir "öğren ve uygula" döngüsü yoktur. Her konu kendi başına derin bir uzmanlık alanıdır. Hepsine hakim olmak beklenmez — odak noktanı seç, derinleş.

---

## Konular

### 1. Sistem Mimarisi
- Çok katmanlı yazılım mimarisi tasarımı
- Hardware abstraction layer (HAL) standartları
- AUTOSAR, MISRA-C gibi endüstri standartları
- Büyük kod tabanı yönetimi (modülerlik, bağımlılık yönetimi)

### 2. Donanım-Yazılım Co-Design
- Peripheral seçimi ve trade-off analizi
- PCB tasarım kısıtlarının yazılıma etkisi
- Signal integrity ve EMC temelleri
- Üretim için tasarım (DFM)

### 3. Özel Protokol Geliştirme
- CAN, LIN, Modbus, EtherCAT temelleri
- Özel ikili protokol tasarımı
- Framing, checksum, retry mekanizmaları
- Protocol state machine

### 4. Ultra Düşük Güç Tasarımı
- nA seviyesinde güç bütçesi
- Enerji toplama (energy harvesting)
- Supercapacitor ve batarya yönetimi
- Ölçüm ve doğrulama metodolojisi

### 5. Gerçek Zamanlı Analiz
- Worst-case execution time (WCET) analizi
- Schedulability analizi (Rate Monotonic, EDF)
- Jitter ölçümü ve azaltma
- Hard real-time garanti verme

### 6. Güvenlik Mühendisliği
- Threat modeling (STRIDE)
- Kriptografi temelleri (AES, RSA, ECDSA)
- Secure element ve TrustZone
- Güvenlik açığı analizi

### 7. Kalite ve Test
- Unit test (Unity, CMock)
- Hardware-in-the-loop (HIL) test
- Static analiz (PC-lint, Cppcheck, Coverity)
- Code coverage

### 8. Fonksiyonel Güvenlik
- IEC 61508 / ISO 26262 temelleri
- Safety integrity level (SIL/ASIL) kavramı
- Redundancy ve fault detection mekanizmaları
- Watchdog stratejileri

### 9. Linux Tabanlı Embedded
- Yocto / Buildroot ile minimal Linux
- Device tree
- Kernel driver yazımı temeli
- User-space vs kernel-space trade-off

### 10. Ürün Geliştirme Süreci
- Prototipten üretime geçiş
- Sertifikasyon süreçleri (CE, FCC, UL)
- Üretim testi ve programlama jig'leri
- Saha güncellemesi ve destek stratejisi

---

## Kaynaklar

### Kitaplar
- **"Software Engineering for Embedded Systems"** — Robert Oshana *(endüstriyel perspektif)*
- **"Embedded Software: The Works"** — Jack Ganssle *(ürün kalitesi yazılım)*
- **"Safety-Critical Systems Handbook"** — David J. Smith *(fonksiyonel güvenlik)*
- **"The Linux Programming Interface"** — Michael Kerrisk *(Linux embedded için)*

### Bloglar ve Siteler
- [Interrupt Blog — Memfault](https://interrupt.memfault.com) — üretim kalitesi embedded makaleler
- [Embedded Artistry](https://embeddedartistry.com) — mimari ve kalite odaklı
- [Jack Ganssle's The Embedded Muse](http://www.ganssle.com) — deneyimli bir mühendisten görüşler

### Konferanslar ve Topluluklar
- Embedded World (Nürnberg) — dünyanın en büyük embedded fuarı
- CppCon Embedded Track — C++ ile embedded
- OSELAS, Yocto Project toplulukları

---

## Proje Ödevleri

| # | Proje | Hedef |
|---|---|---|
| 1 | CAN tabanlı çoklu düğüm sistemi | Protokol, arbitration, hata yönetimi |
| 2 | Özel bootloader + OTA + imza doğrulama | Güvenlik, kriptografi, flash yönetimi |
| 3 | HIL test altyapısı | Kalite, CI/CD, otomatik test |
| 4 | Yocto ile minimal Linux imajı | Linux embedded, device tree |
| 5 | Fonksiyonel güvenlikli watchdog sistemi | ISO 26262, redundancy |
| 6 | Enerji toplayan kablosuz sensör | Ultra low power, LoRaWAN |

---

## Seviye Kontrol Listesi

- [ ] WCET analizinde hangi araçlar kullanılır?
- [ ] MISRA-C kuralları neden ve hangi bağlamlarda zorunludur?
- [ ] Secure boot zincirinde imza doğrulama nasıl çalışır?
- [ ] Rate Monotonic Scheduling ile schedulability nasıl hesaplanır?
- [ ] Device tree'de bir peripheral'ı nasıl tanımlarsın?
- [ ] SIL 2 seviyesinde bir sistem için hangi test kanıtları gerekir?

---

## Son Not

Bu seviyeye ulaşmak, öğrenmenin bittiği anlamına gelmez. Embedded mühendisliği sürekli gelişen bir alan. Bir konuyu derinlemesine öğrenmek, o konunun ne kadar geniş olduğunu anlamaktır.

➡️ [embeddedTR Topluluğuna Katkıda Bulun](https://github.com/embeddedTR)
