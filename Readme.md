
## NAME: SUNDARRAJAN K
## REG NO: 212223060279

# Gaussian-Pulse-Propagation
# Broadening of Gaussian Pulses

## Objective:

Compare the results predicted by the linear system model of an optical fiber with the results of simulation.

---

## Theory:

An optical fiber can be represented approximately by a linear system with an impulse response \(h(t)\) or a transfer function \(H(j\omega)\).  

If the optical source has a spectral width much greater than the signal bandwidth (e.g., the source is a directly modulated laser diode) and the operating wavelength is far from the zero-dispersion wavelength, then \(H(j\omega)\) is approximately Gaussian:

<img width="1482" height="1120" alt="image" src="https://github.com/user-attachments/assets/83f63473-b1b3-4afc-ad17-9e9850041cae" />


---

### Output Pulse Broadening:

If a Gaussian pulse is input to a linear system with a Gaussian impulse response, the output is also Gaussian with RMS width:

<img width="340" height="102" alt="image" src="https://github.com/user-attachments/assets/c60d35c1-8a0f-4c50-873d-1314ec59a29f" />



---

## Calculations:

**System Parameters:**

<img width="832" height="340" alt="image" src="https://github.com/user-attachments/assets/e43e85b4-86bc-42cd-bfad-c3d2760a5965" />



**Required Calculations:**

<img width="1548" height="298" alt="image" src="https://github.com/user-attachments/assets/b2fb676a-afb0-48ef-914b-309b2ea38a17" />


## Layout:

Place and connect the following components:
1. **User-defined bit sequence generator** – set to generate a single pulse of the specified width  
2. **Optical Gaussian pulse generator** – enter the chirp factor as a negative number  
3. **Optical fiber** – set according to specifications  
4. **Optical spectrum analyzers** and **optical time domain visualizers** at input and output of fiber  

---

## Simulation:

- Set the parameters and run the simulation.  
- Use the visualizer displays to measure:  
  - FWHM width of input and output pulses  
  - FWHM width of optical spectra  

---

## Analysis
Compare the simulation results with the theoretical calculations and discuss any observed differences.

<img width="1448" height="1015" alt="Screenshot 2026-02-05 113211" src="https://github.com/user-attachments/assets/5a7b450e-e6d6-4efc-8c33-791775fdfa8c" />

## Calaculation:

<img width="1421" height="2203" alt="image" src="https://github.com/user-attachments/assets/21364ef3-93c1-4588-96f2-d6c5f9c4f028" />



<img width="1427" height="462" alt="image" src="https://github.com/user-attachments/assets/f5afcd71-1bdc-44a2-bafa-f59ac835f323" />







## OUTPUT:

<img width="722" height="1020" alt="image" src="https://github.com/user-attachments/assets/55570d01-22d1-4571-997a-f43850ea1640" />



---
## Results to Record:

Hence,the results predicted by the linear system model of an optical fiber with the results of simulation.
