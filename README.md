# embeddedTR Roadmap 🇹🇷

🇹🇷 Türkçe | 🇬🇧 [English](./README.en.md)

Gömülü sistem mühendisliği öğrenmek isteyenler için seviyelere ayrılmış kapsamlı bir yol haritası.

---

## Öğrenme Yolu

```mermaid
flowchart TD
    START([📍 Başlangıç Noktası]) --> B

    subgraph B ["🟢 Başlangıç — 2 to 4 ay"]
        B1[C Programlama Temelleri]
        B2[Temel Elektronik]
        B3[GPIO ve Geliştirme Ortamı]
        B4[Timer ve Zamanlama]
        B5[State Machine Temeli]
        B1 --> B2 --> B3 --> B4 --> B5
    end

    B --> I

    subgraph I ["🟡 Orta — 3 to 5 ay"]
        I1[Interrupt / NVIC]
        I2[Timer / PWM]
        I3[ADC ve DMA]
        I4[UART / I2C / SPI]
        I5[Low Power Modları]
        I6[Non-Blocking Mimari]
        I1 --> I2 --> I3 --> I4 --> I5 --> I6
    end

    I --> A

    subgraph A ["🔴 İleri — 4 to 6 ay"]
        A1[RTOS ve Çoklu Görev]
        A2[Driver Mimarisi]
        A3[Bellek Yönetimi]
        A4[Bootloader ve OTA]
        A5[Güç Optimizasyonu]
        A6[Embedded Güvenlik]
        A1 --> A2 --> A3 --> A4 --> A5 --> A6
    end

    A --> E

    subgraph E ["⚫ Uzman — 6 to 12 ay"]
        E1[Sistem Mimarisi]
        E2[Özel Protokol Geliştirme]
        E3[Gerçek Zamanlı Analiz]
        E4[Fonksiyonel Güvenlik]
        E5[Linux Tabanlı Embedded]
        E6[Ürün Geliştirme Süreci]
        E1 --> E2 --> E3 --> E4 --> E5 --> E6
    end

    E --> FINISH([🏁 Sektör Hazır Mühendis])
```

---

## Seviyeler

| Seviye | Süre | Hedef Kitle |
|---|---|---|
| [🟢 Başlangıç](./roadmap/beginner.md) | 2–4 ay | Hiç gömülü deneyimi olmayanlar |
| [🟡 Orta](./roadmap/intermediate.md) | 3–5 ay | GPIO ve C temelini bilenler |
| [🔴 İleri](./roadmap/advanced.md) | 4–6 ay | Peripheral'larla çalışabilenler |
| [⚫ Uzman](./roadmap/expert.md) | 6–12 ay | Üretim deneyimi kazananlar |

---

## Proje Hedefleri

- 🇹🇷 Türkiye'de embedded için referans kaynak oluşturmak
- 📐 Öğrenme sürecini sistematik hale getirmek
- 🔧 Pratik mühendislik yetkinliklerini ön plana çıkarmak

---

## Katkıda Bulun

Eksik gördüğün konu, yanlış bilgi veya kaynak önerisi için PR aç ya da issue oluştur.

Her katkı topluluğu güçlendirir. 🙌

➡️ [embeddedTR Ana Sayfa](https://github.com/embeddedTR)
