# GNU Radio AM Transmitter

## Overview

This project implements an **Amplitude Modulation (AM) Transmitter** using GNU Radio. The transmitter accepts a real-time audio signal from the microphone, generates a carrier signal, performs amplitude modulation using signal multiplication, and visualizes the transmitted waveform in both the time and frequency domains.

The project demonstrates the fundamentals of **analog communication**, **Software Defined Radio (SDR)**, and **Digital Signal Processing (DSP)**.

---

## Features

- Real-time Audio Input
- Carrier Signal Generation
- Amplitude Modulation (AM)
- Time Domain Visualization
- Frequency Spectrum Visualization
- GNU Radio Flowgraph Implementation

---

## Flowgraph

```
Audio Source
      │
Multiply Const
      │
Add Const
      │
Signal Source (Carrier)
      │
Multiply
      ├────────► QT GUI Time Sink
      └────────► QT GUI Frequency Sink
```

---

## Software Used

- GNU Radio 3.10
- Python 3
- Qt GUI

---

## Concepts Covered

- Amplitude Modulation (AM)
- Carrier Signal Generation
- Analog Communication
- Software Defined Radio (SDR)
- Digital Signal Processing (DSP)
- Signal Visualization

---

## Real-World Applications

- AM Radio Broadcasting
- Analog Communication Systems
- SDR Research and Education
- Communication Engineering Laboratories
- Signal Processing Demonstrations

---

## Project Structure

```
gnu-radio-am-transmitter/
│
├── flowgraphs/
│   ├── am_transmitter.grc
│   └── am_transmitter.py
│
├── screenshots/
│   ├── am_flowgraph.png
│   ├── am_time_sink.png
│   └── am_frequency_sink.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## How to Run

1. Install GNU Radio (Version 3.10 or later).
2. Open `flowgraphs/am_transmitter.grc`.
3. Click **Run** in GNU Radio Companion.
4. Speak into the microphone.
5. Observe the AM waveform in the QT GUI Time Sink.
6. Observe the frequency spectrum in the QT GUI Frequency Sink.

---

## Future Improvements

- AM Receiver Implementation
- Envelope Detector
- Channel Noise Simulation
- Hardware Integration using PlutoSDR or RTL-SDR
- Performance Analysis under Different Noise Conditions

---

## Screenshots

Add screenshots of:

- Flowgraph
- Time Sink Output
- Frequency Sink Output

inside the `screenshots` folder.

---

## Author

**Saujanya Ch**

B.Tech – Electronics & Communication Engineering

Vasavi College of Engineering, Hyderabad

---

## License

This project is licensed under the MIT License.
