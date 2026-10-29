<div align="center">

# A.U.R.A.

### Autonomous Universal Resonant Assistant

<img src="./assets/hero.svg" alt="Visuelle Projektidentität von A.U.R.A." />

<p><a href="./README.md">English</a> · <a href="./README.de.md"><strong>Deutsch</strong></a> · <a href="./README.tr.md">Türkçe</a></p>

<p>
  <a href="https://github.com/tahakubilay"><img src="https://img.shields.io/badge/Taha%20Kubilay-GitHub-181717?style=for-the-badge&logo=github" alt="Taha Kubilay auf GitHub" /></a>
  <a href="https://github.com/tahakubilay/Aura"><img src="https://img.shields.io/badge/Repository-A.U.R.A.-0A66C2?style=for-the-badge&logo=github" alt="Repository" /></a>
  <img src="https://img.shields.io/badge/Physical%20AI-Experimental%20Prototype-7C3AED?style=for-the-badge" alt="Experimenteller Physical-AI-Prototyp" />
</p>

</div>

---

## Überblick

A.U.R.A. — **Autonomous Universal Resonant Assistant** — ist ein experimenteller physischer KI-Assistent, der konversationeller Intelligenz eine sichtbare, räumliche und ausdrucksstarke Präsenz geben soll.

Das Konzept verbindet Embedded Systems, richtungsabhängige Audioerfassung, magnetische Levitation, drahtlose Energieübertragung, Bewegungssteuerung und eine ausdrucksstarke runde Oberfläche in einer kompakten transparenten Kugelform.

## Physisches Konzept

- Transparenter kugelförmiger Kern mit etwa 12 cm Durchmesser
- Magnetische Levitation über einer speziellen Basis
- Kontaktlose drahtlose Energieübertragung
- Richtungsabhängige Audioerfassung mit mehreren Mikrofonen
- 360°-Ausrichtung zum aktiven Sprecher
- Rundes Display für ausdrucksstarke Augenanimationen
- KI-Interaktionsschicht verbunden mit Bewegung und visuellem Feedback

## Interaktionsablauf

```mermaid
flowchart LR
    USER[Sprecher] --> MIC[Mikrofonarray]
    MIC --> DOA[Richtung / TDOA-Schätzung]
    DOA --> MOTION[Ausrichtungssteuerung]
    USER --> AI[KI-Interaktionsschicht]
    AI --> DISPLAY[Ausdrucksstarkes Runddisplay]
    BASE[Magnetbasis] --> LEV[Levitation]
    BASE --> WPT[Drahtlose Energie]
    WPT --> CORE[A.U.R.A. Core]
    CORE --> MIC
    CORE --> DISPLAY
    CORE --> MOTION
```

## Richtungsabhängiges Audio

A.U.R.A. nutzt ein Multi-Mikrofon-Konzept, um die Richtung einer Stimme rund um das Gerät zu bestimmen. Relative Laufzeitunterschiede zwischen den Mikrofonen können zur Schätzung des Sprecherwinkels und zur Steuerung der physischen Ausrichtung verwendet werden.

```mermaid
flowchart TD
    S[Sprache] --> M1[Mikrofon 1]
    S --> M2[Mikrofon 2]
    S --> M3[Mikrofon 3]
    S --> M4[Mikrofon 4]
    M1 --> T[TDOA / Richtungsschätzung]
    M2 --> T
    M3 --> T
    M4 --> T
    T --> A[Geschätzte Richtung 0°–360°]
    A --> R[Zum Sprecher ausrichten]
```

## Kernsysteme

| System | Rolle |
|---|---|
| **Magnetische Levitation** | Den kugelförmigen Kern ohne sichtbare mechanische Stütze schweben lassen |
| **Wireless Power** | Energie kontaktlos von der Basis zur Kugel übertragen |
| **Mikrofonarray** | Richtungsinformationen rund um das Gerät erfassen |
| **Richtungsschätzung** | Sprecherwinkel aus Laufzeitunterschieden bestimmen |
| **Ausrichtungssteuerung** | Den Assistenten zum aktiven Sprecher drehen |
| **Ausdrucksstarkes Display** | Aufmerksamkeit und Systemzustand durch Augenanimationen vermitteln |
| **KI-Schicht** | Konversationelle Intelligenz mit physischer Interaktion verbinden |

## Engineering-Fokus

A.U.R.A. verbindet Software- und Hardwarethemen, die üblicherweise getrennt entwickelt werden:

- Embedded Systems
- Audiosignalverarbeitung
- Human-Computer Interaction
- Sensor Fusion
- Bewegungssteuerung
- Wireless Power
- Physisches Prototyping
- KI-Integration
- Echtzeit-State-Koordination
- Produktorientiertes Industriedesign

## Projektcharakter

A.U.R.A. ist ein experimentelles Prototypkonzept. Das Repository beschreibt Systemarchitektur und Interaktionsdesign, ohne die Hardware als fertiges kommerzielles Produkt darzustellen.

---

<div align="center">

### Entwickelt von [Taha Kubilay](https://github.com/tahakubilay)

`Physical AI` · `Embedded Systems` · `IoT` · `Audio Processing` · `Human-Computer Interaction`

</div>