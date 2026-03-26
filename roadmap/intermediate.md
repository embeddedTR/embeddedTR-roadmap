# 🟡 Intermediate Level

Temel bilgileri öğrenmiş ve artık gerçek gömülü sistem geliştirmeye başlayanlar için.

---

## ⚡ 1. Interrupt (Kesme Mekanizması)

❗ Neden önemli:  
Event-driven sistemlerin temelidir. CPU sürekli polling yapmak zorunda kalmaz.

📌 Öğrenmen gerekenler:
- External interrupt (EXTI)
- NVIC mantığı
- Interrupt priority

🧠 Gerçek kullanım:
- Buton tetikleme
- UART veri alımı
- Sensör tetikleme (PIR vs.)

⚠️ Yaygın hata:
- Interrupt içinde uzun işlem yapmak

---

## ⏱️ 2. Timer / Counter

❗ Neden önemli:  
Zaman tabanlı tüm sistemlerin kalbidir.

📌 Öğrenmen gerekenler:
- Basic timer
- PWM üretimi
- Input capture

🧠 Gerçek kullanım:
- LED blink (non-blocking)
- Motor kontrol
- Zaman ölçümü

⚠️ Yaygın hata:
- Delay kullanmaya devam etmek

---

## 🔊 3. ADC (Analog to Digital Converter)

❗ Neden önemli:  
Gerçek dünyadan veri almanın yolu.

📌 Öğrenmen gerekenler:
- ADC resolution
- Sampling
- Continuous vs single mode

🧠 Gerçek kullanım:
- NTC sıcaklık ölçümü
- Batarya voltajı ölçümü

⚠️ Yaygın hata:
- Gürültü ve filtreleme konusunu ihmal etmek

---

## 📡 4. UART (Serial Communication)

❗ Neden önemli:  
Debug ve cihazlar arası iletişimin en temel yolu.

📌 Öğrenmen gerekenler:
- Baudrate
- TX / RX mantığı
- Interrupt / DMA ile kullanım

🧠 Gerçek kullanım:
- Loglama
- Modül haberleşmesi

⚠️ Yaygın hata:
- Blocking UART kullanmak

---

## 🔗 5. I2C / SPI Haberleşme

❗ Neden önemli:  
Sensör ve çevre birimlerle iletişim.

📌 Öğrenmen gerekenler:
- Master / Slave
- Clock mantığı
- Addressing (I2C)

🧠 Gerçek kullanım:
- Sensör okuma (IMU, EEPROM)
- Display sürme

⚠️ Yaygın hata:
- Timing ve pull-up hataları

---

## 🕒 6. RTC (Real Time Clock)

❗ Neden önemli:  
Zaman bazlı sistemler için vazgeçilmez.

📌 Öğrenmen gerekenler:
- RTC clock source (LSI / LSE)
- Wakeup timer

🧠 Gerçek kullanım:
- Low power wakeup
- Zaman takibi

⚠️ Yaygın hata:
- RTC kalibrasyonu yapmamak

---

## 🔋 7. Power Modes (Low Power)

❗ Neden önemli:  
Batarya ile çalışan sistemlerin kalbi.

📌 Öğrenmen gerekenler:
- Sleep / Stop / Standby
- Wakeup kaynakları

🧠 Gerçek kullanım:
- PIR sensör sistemleri
- IoT cihazlar

⚠️ Yaygın hata:
- Gereksiz güç tüketimi (peripheral açık bırakmak)

---

## 🧠 8. DMA (Direct Memory Access)

❗ Neden önemli:  
CPU’yu yormadan veri transferi sağlar.

📌 Öğrenmen gerekenler:
- Memory to peripheral
- Peripheral to memory

🧠 Gerçek kullanım:
- ADC continuous sampling
- UART high-speed veri

⚠️ Yaygın hata:
- DMA callback yönetimini anlamamak

---

## 🔁 9. Non-Blocking Yazılım Mantığı

❗ Neden önemli:  
Gerçek zamanlı sistemlerin temelidir.

📌 Öğrenmen gerekenler:
- State machine
- Event-driven yapı

🧠 Gerçek kullanım:
- Çoklu görev yönetimi
- Low power sistemler

⚠️ Yaygın hata:
- Delay kullanmaya devam etmek

---

## 🛠️ 10. Debugging (Advanced)

📌 Öğrenmen gerekenler:
- SWD / JTAG
- Register debug
- Logic analyzer kullanımı

🧠 Gerçek kullanım:
- Protokol analizi
- Timing debug

⚠️ Yaygın hata:
- Sadece yazılım debug’a güvenmek

---

## 🎯 Bu seviyenin hedefi

Bu seviyeyi bitiren biri:

- Sensör okuyabilir  
- UART/I2C/SPI ile haberleşebilir  
- Low power sistem kurabilir  
- Non-blocking kod yazabilir  

---

## 🚀 Sonraki adım

➡️ Advanced level
