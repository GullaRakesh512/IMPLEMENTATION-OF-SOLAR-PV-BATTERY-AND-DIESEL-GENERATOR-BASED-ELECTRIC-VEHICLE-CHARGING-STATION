
# 🚗⚡ Solar PV-Battery-Diesel Generator Based EV Charging Station

## 📌 Project Overview
This project demonstrates the **implementation of a hybrid EV charging station** that integrates:
- **Solar PV Array**  
- **Battery Energy Storage (BES)**  
- **Diesel Generator (DG) Backup**  
- **Grid Connection**  

The system ensures **uninterrupted charging** for electric vehicles by intelligently switching between these energy sources based on availability and efficiency.

## 🔑 Features
- Priority use of **solar PV + battery storage** for eco-friendly charging.  
- Intelligent fallback to **grid power** when solar/battery is insufficient.  
- **Diesel Generator backup** ensures reliability during grid failure, operating at 80–85% load for fuel efficiency.  
- **Adaptive Notch Cancellation (ANC) based control algorithm** maintains **unity power factor (UPF)** and regulates voltage/frequency.  
- Supports **Vehicle-to-Grid (V2G)**, **Vehicle-to-Home (V2H)**, and **Vehicle-to-Vehicle (V2V)** power transfer.  

## 🛠️ Methodology
1. **Mathematical Modelling** of power converters and control strategies.  
2. **PWM Techniques**: Sine-triangle, POD, APOD, and Space Vector Modulation.  
3. **Control System**: PI Controller + ANC filter for stability.  
4. **Simulation**: MATLAB/Simulink-based analysis of hybrid charging station under different operating conditions.  

## 📊 Simulation Results
- Verified performance in **standalone, grid-connected, and DG-connected** modes.  
- System maintains **voltage stability** and **power quality** under dynamic conditions (solar variations, EV load changes, DG operation).  
- **Output waveforms** confirm reliable operation and seamless source switching.  

## ✅ Conclusion
The proposed **hybrid EV charging station** enhances sustainability, reliability, and efficiency by integrating renewable energy, storage, and backup systems.  
It demonstrates a **scalable model** for future smart cities and sustainable transportation infrastructure.  

## 📚 References
Key references include IEEE papers on EV charging strategies, hybrid renewable integration, and smart grid optimization. (See project report for detailed reference list.)  

---

👨‍💻 **How to Use in GitHub Repo:**  
- Add this `README.md` file to the root of your repository.  
- Upload supporting files (Simulink models, MATLAB code, reports, diagrams).  
- Document simulation steps and results for reproducibility.  
