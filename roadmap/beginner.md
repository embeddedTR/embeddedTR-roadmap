# 🟢 Başlangıç Seviyesi

> Tahmini süre: **2–4 ay** (haftada 8–10 saat)

---

## Konular

### 1. C Programlama Temelleri
Gömülü sistemlerin ~%90'ı C ile yazılır.
- Değişkenler, veri tipleri, döngüler, koşullar
- Fonksiyonlar ve kapsam (scope)
- Pointer ve adres kavramı
- Struct ve union
- Bitwise operatörler

### 2. Temel Elektronik
- Ohm yasası, direnç, kondansatör, LED
- Pull-up / pull-down dirençleri
- Breadboard ve basit devre okuma
- Multimetre kullanımı

### 3. Geliştirme Ortamı
- STM32CubeIDE veya Keil MDK kurulumu
- GPIO yapılandırması (input / output)
- LED yakma, buton okuma
- SWD ile debug ve breakpoint kullanımı

### 4. Timer ve Zamanlama
- `HAL_Delay()` neden kötü bir alışkanlıktır?
- Timer ile gecikme farkı
- Temel timer konfigürasyonu

### 5. State Machine Temeli
- Neden global değişken yerine state machine?
- Basit switch-case state machine

---

## Kaynaklar

### Kitaplar
- **"C Programming: A Modern Approach"** — K.N. King *(C öğrenmek için en iyi kaynaklardan biri)*
- **"Make: Electronics"** — Charles Platt *(temel elektronik için, Türkçe'ye de çevrildi)*

### Videolar / Kurslar
- [Mitch Davis — Bare Metal Embedded](https://www.youtube.com/@MitchDavis2) — STM32 ile bare-metal başlangıç, ücretsiz
- [Udemy — Mastering Microcontroller with Embedded C Programming](https://www.udemy.com) — FastBit Academia, ücretli ama kapsamlı
- [ST Microelectronics YouTube Kanalı](https://www.youtube.com/@STMicroelectronics) — resmi STM32 eğitimleri

### Araçlar
- STM32CubeIDE (ücretsiz)
- STM32CubeMX (ücretsiz, kod üretici)
- Proteus veya Wokwi (simülasyon)

---

## Proje Ödevleri

Aşağıdaki projeleri sırayla tamamla:

| # | Proje | Hedef |
|---|---|---|
| 1 | LED Blink | GPIO output, temel proje yapısı |
| 2 | Buton ile LED kontrolü | GPIO input, debounce |
| 3 | 7 Segment Sayaç | Çoklu GPIO, zamanlama |
| 4 | Trafik Işığı Simülasyonu | State machine, timer |
| 5 | Basit Hesap Makinesi (UART) | İlk iletişim deneyimi |

---

## Seviye Kontrol Listesi

Bu seviyeyi tamamladığını düşünüyorsan aşağıdaki soruları cevaplayabilmelisin:

- [ ] Pointer ile değişken adresi arasındaki fark nedir?
- [ ] Pull-up direnci neden gereklidir?
- [ ] `HAL_Delay()` neden interrupt tabanlı sistemlerde sorun çıkarır?
- [ ] State machine neden sonsuz döngü + bayrak'tan daha iyidir?
- [ ] Bir GPIO pinini input olarak nasıl yapılandırırsın?

---

## Sonraki Adım

➡️ [Orta Seviye](./intermediate.md)
