# 🟡 Orta Seviye

> Tahmini süre: **3–5 ay** (haftada 8–10 saat)
> Ön koşul: [Başlangıç Seviyesi](./beginner.md)

---

## Konular

### 1. Interrupt (EXTI / NVIC)
- Interrupt nedir, neden kullanılır?
- EXTI ile GPIO interrupt
- NVIC öncelik yapılandırması
- ISR içinde yapılmaması gerekenler

### 2. Timer / PWM
- Timer modları: Output Compare, Input Capture, PWM
- Servo motor ve LED dim kontrolü
- Encoder okuma

### 3. ADC
- Analog-digital dönüşüm temeli
- Tek kanal, çok kanal (scan mode)
- DMA ile ADC kullanımı
- Gürültü filtreleme (hareketli ortalama)

### 4. UART
- Polling, interrupt ve DMA tabanlı UART
- Circular buffer ile RX yönetimi
- UART üzerinden debug

### 5. I2C / SPI
- Protokol farkları ve ne zaman hangisi?
- HAL ile sensör okuma (BME280, MPU6050)
- Logic analyzer ile bus analizi

### 6. DMA
- DMA nedir, neden CPU'yu rahatlatır?
- Memory-to-memory, peripheral-to-memory transfer
- DMA interrupt ve transfer complete

### 7. Low Power Modları
- Sleep, Stop, Standby farkları
- Uyku modundan çıkış (wakeup)
- Batarya ömrü hesaplama

### 8. Non-Blocking Mimari
- `HAL_Delay()` bağımlılığından kurtulmak
- Tick tabanlı zamanlama
- Event-driven yapı

### 9. RTC
- Gerçek zamanlı saat yapılandırması
- Backup register kullanımı
- Alarm ile periyodik uyandırma

### 10. İleri Debug Teknikleri
- SWD / JTAG farkı
- Watch point ve memory view
- Hard fault analizi

---

## Kaynaklar

### Kitaplar
- **"Embedded Systems: Introduction to ARM Cortex-M Microcontrollers"** — Jonathan Valvano *(ücretsiz PDF mevcut)*
- **"The Definitive Guide to ARM Cortex-M3 and Cortex-M4"** — Joseph Yiu

### Videolar / Kurslar
- [Udemy — Embedded Systems Bare Metal Programming Ground Up (STM32)](https://www.udemy.com) — FastBit Academia
- [Phil's Lab YouTube](https://www.youtube.com/@PhilsLab) — STM32, PCB, sinyal işleme
- [DigiKey YouTube — Shawn Hymel Embedded C](https://www.youtube.com/@digikey) — ücretsiz, kapsamlı seri

### Araçlar
- Logic Analyzer (Saleae veya ucuz klonları) — protokol debug için şart
- Oscilloscope — timing analizi
- STM32CubeMX — DMA ve interrupt yapılandırması için kolaylık

---

## Proje Ödevleri

| # | Proje | Hedef |
|---|---|---|
| 1 | UART ile komut alma sistemi | Non-blocking UART, circular buffer |
| 2 | I2C sensör okuma + UART'a yazdırma | I2C, veri formatlama |
| 3 | PWM ile servo kontrol | Timer, PWM, duty cycle |
| 4 | ADC + DMA ile sürekli ölçüm | DMA, analog gürültü filtreleme |
| 5 | Low power buton uyandırma | Stop modu, EXTI wakeup |
| 6 | Dijital kronometre | RTC, UART çıktısı, state machine |

---

## Seviye Kontrol Listesi

- [ ] ISR içinde `HAL_Delay()` neden kullanılmamalıdır?
- [ ] DMA ile UART alımında circular buffer nasıl yönetilir?
- [ ] I2C'de ACK/NACK farkı nedir?
- [ ] PWM frekansı ve duty cycle nasıl hesaplanır?
- [ ] Stop modundan çıkmak için ne yapılır?
- [ ] ADC'de oversampling nedir, neden kullanılır?

---

## Sonraki Adım

➡️ [İleri Seviye](./advanced.md)
