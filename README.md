# physics---telecom---reports
Physics and telecom technical reports: antenna design, path loss modeling, EM field measurement.

# 📡 Radio Wave Attenuation Models

Repository containing technical implementations of radio wave propagation models for path loss prediction in different environments, based on ITU-R P.1411 and Weissberger models.

## 📊 Included Reports

### 1. **Design and Construction of Receiving Antennas**
   - **Objective**: Design and build two antennas (small loop and helical) for TV frequencies (MHz) and Wi-Fi frequencies (GHz)
   - **Key Results**: 
     - Helical antenna achieved 13.06 dB gain (3.25× improvement over reference)
     - Small loop antenna successfully captured VHF/UHF channels
   - **Technologies**: Python, LaTeX, RF measurement equipment

### 2. **Measurement of Earth's Magnetic Field Using Tangential Magnetometer**
   - **Objective**: Measure Earth's magnetic field using a custom-built coil and magnetic needle
   - **Key Results**: Measured value of 35.4 ± 0.9 μT (4.07% error vs theoretical value)
   - **Technologies**: Python, LaTeX, experimental physics setup

### 3. **Path Loss as Function of Environment Type**
   - **Objective**: Analyze path loss variations across 18 environment types using empirical models
   - **Key Results**: 
     - Urban dense environments show >114 dB/km additional losses
     - Comprehensive comparison across B2/B4/B5/B28 frequency bands
   - **Technologies**: Python, LaTeX, ITU-R P.1411, Weissberger models

## 🛠️ Technologies Used

- **Programming**: Python (NumPy, Matplotlib, SciPy)
- **Documentation**: LaTeX (IEEEAccess template)
- **Simulation**: RF propagation modeling
- **Hardware**: RF measurement equipment, custom antenna construction


