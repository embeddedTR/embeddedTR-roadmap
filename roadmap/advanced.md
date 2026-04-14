# 🔴 İleri Seviye

> Tahmini süre: **4–6 ay** (haftada 10–12 saat)
> Ön koşul: [Orta Seviye](./intermediate.md)

---

## Konular

### 1. RTOS ve Çoklu Görev
- FreeRTOS temelleri: task, scheduler, tick
- Senkronizasyon: semaphore, mutex, queue, event group
- Deadlock ve priority inversion
- Stack boyutu hesaplama ve izleme

### 2. State Machine Tasarımı
- Hierarchical State Machine (HSM)
- Event-driven mimari
- QP/C veya kütüphanesiz HSM implementasyonu

### 3. Bellek Yönetimi
- Stack vs Heap, `.bss`, `.data`, `.rodata`
- Linker script okuma ve yazma
- Memory alignment ve padding
- Embedded'da `malloc` neden tehlikelidir?

### 4. Driver Mimarisi
- HAL / LL ayrımı
- Platform bağımsız driver yazımı
- Abstraction layer tasarımı
- Callback mekanizması

### 5. Bootloader ve Firmware Güncelleme
- Flash bölümleme (boot + app)
- Jump to application
- CRC ile firmware doğrulama
- UART / CAN üzerinden OTA güncelleme

### 6. Güç Optimizasyonu
- Peripheral power gating
- Clock tree optimizasyonu
- Uyku modlarını doğru kullanmak
- Güç tüketimi profilleme (Power Profiler Kit II)

### 7. Kablosuz Sistemler
- UART-tabanlı RF modüller (HC-12, LoRa)
- Paket yapısı ve CRC
- Mesh vs Star topoloji

### 8. Donanım Düzeyinde Debug
- Oscilloscope ile timing analizi
- Logic analyzer ile protokol decode
- Bus Pirate, J-Link kullanımı

### 9. Performans Optimizasyonu
- Cache, pipeline, branch prediction
- `__attribute__((optimize))` ve `-O2/-O3`
- Cycle counting ve profiling
- Erken optimizasyon neden tehlikelidir?

### 10. Embedded Güvenlik
- Secure boot temelleri
- Firmware şifreleme
- Read-out protection (RDP)
- Güvenli OTA prensipleri

---

## Kaynaklar

### Kitaplar
- **"Making Embedded Systems"** — Elecia White *(üretim kalitesi kod yazımı)*
- **"Real-Time C++"** — Christopher Kormanyos *(C++ ile embedded, modern yaklaşım)*
- **"FreeRTOS Reference Manual"** — Richard Barry *(ücretsiz PDF)*

### Videolar / Kurslar
- [Udemy — RTOS Fundamentals using FreeRTOS](https://www.udemy.com) — Kiran Nayak
- [Jacob Beningo YouTube](https://www.youtube.com/@jacobbeningo) — üretim kalitesi embedded yazılım
- [Interrupt Blog — Memfault](https://interrupt.memfault.com) — ileri seviye teknik makaleler

### Araçlar
- SEGGER J-Link + Ozone (profiling)
- Nordic Power Profiler Kit II (güç ölçümü)
- QEMU (STM32 emülasyonu)
- Renode (çoklu cihaz simülasyonu)

---

## Proje Ödevleri

| # | Proje | Hedef |
|---|---|---|
| 1 | FreeRTOS'lu sensör veri loglama | Task, queue, UART |
| 2 | Platform bağımsız I2C driver | Abstraction layer, HAL ayrımı |
| 3 | UART Bootloader | Flash yazma, CRC, jump |
| 4 | Low-power IoT düğümü | Stop modu, LoRa, batarya profili |
| 5 | OTA firmware güncelleme | Dual bank, CRC doğrulama |
| 6 | FreeRTOS'lu HSM uygulaması | Event-driven, state machine |

---

## Seviye Kontrol Listesi

- [ ] Priority inversion nedir, FreeRTOS'ta nasıl önlenir?
- [ ] Linker script'te `AT > FLASH` ne anlama gelir?
- [ ] Bootloader'dan uygulama koduna nasıl geçilir?
- [ ] DMA kullanırken cache coherency neden sorun çıkarır?
- [ ] Secure boot zinciri nasıl çalışır?
- [ ] Embedded'da `malloc` kullanmak neden risklidir?

---

## Sonraki Adım

➡️ [Uzman Seviye](./expert.md)
