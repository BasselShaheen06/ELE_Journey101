# Electronics Labs - A walkthrough in our journey⚡

This repository contains the simulation files, schematics, and detailed reports for the electronics lab sessions conducted throughout the semester. The experiments focus on analyzing the practical characteristics of fundamental electronic components compared to their theoretical and simulated models.

## 🛠 Tools Used

* 
**Simulation:** MATLAB Simulink & Simscape 


* **Hardware:** Oscilloscopes, Function Generators, DC Power Supplies, Breadboards.
* **Components:** LM324 Op-Amp, 1N4007 Diodes, 2N7000 MOSFETs.

---

## 📂 Lab Summaries

### Lab 01: Weighted Summer (Op-Amp)

**Focus:** Operational Amplifier configurations and Saturation limits.

In this session, we designed and simulated a weighted summer circuit using the **LM324** Quad Op-Amp.

* 
**Theory:** We utilized the superposition principle to derive the output voltage equation:  (Inverting Configuration where ).


* **Observations:** We tested the circuit with supply voltages of . A key takeaway was observing the **saturation effect**; when the theoretical output exceeded the supply rails, the practical output was capped (clipped), resulting in a massive error percentage (535% in extreme cases). This highlighted the physical limitations of amplification gain relative to  and .



### Lab 02: Full-Wave Bridge Rectifier

**Focus:** AC to DC conversion, Ripple Voltage, and Filtering.

We constructed a full-wave bridge rectifier to convert a sinusoidal AC input into a DC output.

* **Simulation vs. Hardware:**
* 
**Simulation:** mode led a step-down transformer (220V to 110V) feeding a bridge rectifier with a  smoothing capacitor.


* 
**Lab:** We used a 1V peak AC source, a **1N4007 diode**, and a  capacitor.




* 
**Challenges:** We encountered significant noise in the lab output, likely due to breadboard capacitance or probe grounding issues. Despite a ~29% measurement error due to this noise, we successfully observed the ripple voltage reduction and the peak output behavior ().



### Lab 03: MOSFET Characteristics (2N7000)

**Focus:** N-Channel Enhancement-Mode MOSFETs.

We investigated the I-V characteristics of the **2N7000** Vertical DMOS FET.

* 
**Method:** We swept the Gate voltage () using a tunable DC supply and measured the resulting Drain current () to determine the transition between the Triode and Saturation regions.


* **Key Findings:**
* We calculated the transconductance parameter, finding .


* Initially, our Drain voltage () readings were near zero, so we adjusted the drain resistor to  to stabilize the readings and verify the device's threshold voltage ().





---

## 📚 Study Resources

For a deeper theoretical understanding of these experiments, we relied on:

* **Microelectronic Circuits** by Adel S. Sedra & Kenneth C. Smith.

---

## 👥 Contributors (Team 02) ~ The Dream Team

* 
**Abdullah Gamil** - [@3bdullah-Gamil](https://github.com/3bdullah-Gamil) 


* 
**Abdelrahman Hassan** - [@abdulrahman-hassan-74](https://github.com/abdulrahman-hassan-74) 


* 
**Kareem Taha** - [@Kareem-Taha-05](https://github.com/Kareem-Taha-05) 


* 
**Bassel Ahmad** 



---

### 🚀 Next Step

Would you like me to generate the **README for the final project** you mentioned? If you upload the project file, I can format it to match this style.
