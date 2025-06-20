# Li-Fi Audio Transmission using Laser/Torch and Solar Cell

This project demonstrates a simple analog **Li-Fi (Light Fidelity)** system using laser light and torch LED to transmit audio over distance using light as the medium.

## 📡 Project Summary

- **Transmitter:** Audio source (phone) connected to a **laser pointer** or **focused torchlight** via a resistor and battery (DC biasing).
- **Receiver:** A **solar panel** receives modulated light and feeds it into an op-amp **amplifier and filter circuit** to reconstruct the audio signal.

## 📏 Range Achieved
- ✅ Laser Pointer: ~500 meters in line-of-sight
- ✅ Focused Torchlight: ~2 meters

## 🔧 Components
- Laser pointer / LED torch
- Solar panel or photodiode
- 3.5mm audio jack
- 9V Battery + series resistor (for transmitter bias)
- Op-amp (e.g., LM386 / TL072) for audio amplification
- Capacitors and resistors for simple low-pass filter

## 🎙️ How It Works
- The audio waveform rides on top of a DC voltage, modulating the light's brightness.
- The solar panel converts this varying light into a small AC signal.
- The amplifier boosts the signal and removes noise, restoring clean sound output.

## 🎯 Key Learnings
- Analog modulation over light
- Use of DC bias to transmit AC signal via light
- Signal amplification and filtering using op-amps
- Optical alignment for efficient signal reception

## 📸 Images & Demo
- Circuit diagram for short distance communication
- 
  ![image](https://github.com/user-attachments/assets/5ee4ca9b-9d19-42af-bd29-10c7b13fd9b4)
  ![image](https://github.com/user-attachments/assets/3bb02518-d771-48a5-99e3-71c3ab8ff304)



## 🔄 Future Ideas
- Try stereo audio
- Replace solar panel with photodiode + transimpedance amp for higher bandwidth
- Add envelope detector for digital data transfer
- Implement the idea in real world scenarios

## 📬 Contact
Hemant Maruti Patil

[LinkedIn Profile ]   ( www.linkedin.com/in/hemantmpatil0103 )  

Open to feedback, improvements, or collaborations on optical DIY projects.
