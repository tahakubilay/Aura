<div align="center">

# A.U.R.A.

### Autonomous Universal Resonant Assistant

<img src="./assets/hero.svg" alt="A.U.R.A. proje görsel kimliği" />

<p><a href="./README.md">English</a> · <a href="./README.de.md">Deutsch</a> · <a href="./README.tr.md"><strong>Türkçe</strong></a></p>

<p>
  <a href="https://github.com/tahakubilay"><img src="https://img.shields.io/badge/Taha%20Kubilay-GitHub-181717?style=for-the-badge&logo=github" alt="Taha Kubilay GitHub" /></a>
  <a href="https://github.com/tahakubilay/Aura"><img src="https://img.shields.io/badge/Repository-A.U.R.A.-0A66C2?style=for-the-badge&logo=github" alt="Repository" /></a>
  <img src="https://img.shields.io/badge/Physical%20AI-Experimental%20Prototype-7C3AED?style=for-the-badge" alt="Deneysel fiziksel AI prototipi" />
</p>

</div>

---

## Genel Bakış

A.U.R.A. — **Autonomous Universal Resonant Assistant** — konuşma zekâsına görünür, mekânsal ve ifade sahibi bir fiziksel varlık kazandırmayı amaçlayan deneysel bir fiziksel AI asistanıdır.

Konsept; embedded systems, yönsel ses algılama, manyetik levitasyon, kablosuz güç aktarımı, hareket kontrolü ve ifade odaklı dairesel arayüzü kompakt şeffaf küresel bir form içinde birleştirir.

## Fiziksel Konsept

- Yaklaşık 12 cm çapında şeffaf küresel çekirdek
- Özel taban üzerinde manyetik levitasyon
- Temassız kablosuz güç aktarımı
- Çoklu mikrofonla yönsel ses algılama
- Aktif konuşmacıya doğru 360° yönelim
- İfade odaklı göz animasyonları için dairesel ekran
- Fiziksel hareket ve görsel geri bildirimle bağlantılı AI katmanı

## Etkileşim Akışı

```mermaid
flowchart LR
    USER[Konuşmacı] --> MIC[Mikrofon Dizisi]
    MIC --> DOA[Yön / TDOA Tahmini]
    DOA --> MOTION[Yönelim Kontrolü]
    USER --> AI[AI Etkileşim Katmanı]
    AI --> DISPLAY[İfade Odaklı Dairesel Ekran]
    BASE[Manyetik Taban] --> LEV[Levitasyon]
    BASE --> WPT[Kablosuz Güç]
    WPT --> CORE[A.U.R.A. Çekirdeği]
    CORE --> MIC
    CORE --> DISPLAY
    CORE --> MOTION
```

## Yönsel Ses

A.U.R.A., cihaz çevresinde bir sesin hangi yönden geldiğini tahmin etmek için çoklu mikrofon yaklaşımını kullanır. Mikrofonlar arasındaki göreli varış zamanı farkları konuşmacı açısını hesaplamak ve fiziksel yönelimi kontrol etmek için kullanılabilir.

```mermaid
flowchart TD
    S[Konuşma] --> M1[Mikrofon 1]
    S --> M2[Mikrofon 2]
    S --> M3[Mikrofon 3]
    S --> M4[Mikrofon 4]
    M1 --> T[TDOA / Yön Tahmini]
    M2 --> T
    M3 --> T
    M4 --> T
    T --> A[Tahmini 0°–360° Yön]
    A --> R[Konuşmacıya Yönel]
```

## Temel Sistemler

| Sistem | Rol |
|---|---|
| **Manyetik Levitasyon** | Küresel çekirdeği görünür mekanik destek olmadan havada tutmak |
| **Kablosuz Güç** | Enerjiyi tabandan küreye fiziksel kablo olmadan aktarmak |
| **Mikrofon Dizisi** | Cihaz çevresinden yönsel ses bilgisi toplamak |
| **Yön Tahmini** | Varış zamanı farklarından konuşmacı açısını hesaplamak |
| **Yönelim Kontrolü** | Asistanı aktif konuşmacıya çevirmek |
| **İfade Odaklı Ekran** | Dikkat ve sistem durumunu göz animasyonlarıyla ifade etmek |
| **AI Katmanı** | Konuşma zekâsını fiziksel etkileşimle birleştirmek |

## Mühendislik Odağı

A.U.R.A., normalde ayrı geliştirilen yazılım ve donanım problemlerini tek projede birleştirir:

- Embedded systems
- Ses sinyal işleme
- Human-computer interaction
- Sensor fusion
- Hareket kontrolü
- Wireless power
- Fiziksel prototipleme
- AI entegrasyonu
- Gerçek zamanlı state koordinasyonu
- Ürün odaklı endüstriyel tasarım

## Projenin Niteliği

A.U.R.A. deneysel bir prototip konseptidir. Repository, donanımı tamamlanmış ticari ürün gibi sunmak yerine sistem mimarisini ve etkileşim tasarımını açıklar.

---

<div align="center">

### Geliştiren: [Taha Kubilay](https://github.com/tahakubilay)

`Physical AI` · `Embedded Systems` · `IoT` · `Audio Processing` · `Human-Computer Interaction`

</div>