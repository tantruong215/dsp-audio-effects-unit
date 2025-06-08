# DSP Audio Effects Unit

A real-time audio signal processor that applies effects (echo, reverb, distortion) to live microphone input using FIR/IIR filters.

---

### ⚙️ Hardware Design
- STM32F4 MCU with ADC/DAC
- Op-amp preamp + speaker driver
- MEMS microphone + 3.5 mm output

---

### 🧠 Control/Software Features
- Implement FIR and IIR filters
- Add reverb/echo using circular buffers
- Push-button effect cycling (3 modes)

---

### 📊 Results (Expected)
- <5 ms latency from input to output
- 44.1 kHz sample rate
- Clean signal reproduction (THD < 0.2%)

---

### 🧰 Tools Used
- STM32CubeIDE
- MATLAB (filter design)
- Logic analyzer + oscilloscope

---

### 🚧 Project Status
🛠️ Status: In Progress – Summer 2025
