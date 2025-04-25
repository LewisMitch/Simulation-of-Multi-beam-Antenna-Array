# Simulation-of-Multi-beam-Antenna-Array
undergrad Dis for Poster QR code

# 🛰️ Phased Array Satellite Tracking Simulation

This project simulates real-time beam steering for tracking LEO and VLEO satellites using a ground-based phased antenna array. It uses orbital data from TLE files and plots signal strength, tracking accuracy, and antenna behavior.

---

## 📌 Features

- Multi-beam phased array steering (electronic, no mechanical motion)
- Real satellite tracking using Two-Line Element (TLE) data
- Signal-to-noise ratio (SNR) based satellite selection
- Beam clipping and gain loss estimation
- Real-time 3D visualization of beams and satellite orbits
- Automatic video export of the full simulation

---

## 🔧 Inputs

- **Array parameters** (frequency, size, spacing, power, gain, etc.)
- **TLE file** containing satellite orbit data
- **Simulation time** and number of beams to track

---

## 📊 Outputs

- 3D animated beam pattern (Figure 1)
- Real-time satellite tracking and orbit plotting (Figure 2)
- SNR tracking performance graph (Figure 4)
- `.mp4` video output showing the full simulation

---

## ▶️ How to Run

1. Open `main_tracking_simulation.m` in MATLAB.
2. Make sure the `celestrak_TLE_DATA.txt` file is in the same folder.
3. Click **Run**. The script will execute and save results automatically.
4. View the saved video (`satellite_tracking_demo.mp4`) and SNR plot.

---

## 📁 Files

- `main_tracking_simulation.m` – Main simulation script  
- `process_TLE.m` – Parses TLE data and computes satellite positions  
- `celestrak_TLE_DATA.txt` – Sample TLE input  
- `satellite_tracking_snr_summary.png` – SNR graph  
- `satellite_tracking_demo.mp4` – Combined figure animation

---

## 📷 Demo Output

<p align="center">
  <img src="satellite_tracking_snr_summary.png" alt="SNR Tracking Plot" width="500"/>
</p>

---

## 🧠 Project Purpose

This simulation helps visualize and design phased array systems for satellite tracking.  
It is useful for studying beam behavior, tracking performance, and antenna response to LEO/VLEO satellite movement.

---

## 📚 License

MIT License – Feel free to reuse and adapt for academic or research use.
