# 🔆 LED Chaser PCB – Instructions

## 1. Introduction
The LED Chaser PCB is a simple electronics project that creates a moving light effect using 10 LEDs.  
It is based on two popular ICs: the NE555 timer and the 74HC4017 decade counter.

---

## 2. Required Components
See the **Bill of Materials (BOM)** for a complete list of components.  
Main parts include:
- NE555 timer IC  
- 74HC4017 counter IC  
- 10 resistors (100Ω each) for LEDs  
- 10 LEDs (5mm)  
- 10kΩ and 1kΩ resistors  
- 30µF electrolytic capacitor  
- Push button (reset)  
- 2-pin screw terminal for power  

---

## 3. Assembly Instructions
1. **Prepare the PCB**: Ensure it is clean and free of dust.  
2. **Insert Resistors**: Start with the smallest components (R1–R12).  
3. **Insert Capacitor**: Place the 30µF capacitor in C1. Check polarity.  
4. **Insert IC Sockets (Optional)**: For NE555 and 74HC4017, use sockets for easy replacement.  
5. **Place LEDs**: Insert 10 LEDs. Note polarity (long leg = anode).  
6. **Insert Switch**: Place the tactile switch for reset.  
7. **Insert Connector**: Fit the 2-pin terminal block for power input.  
8. **Solder Carefully**: Use leaded solder at ~350°C. Trim leads.  
9. **Check Continuity**: Verify no short circuits exist.  
10. **Insert ICs**: Place NE555 and 74HC4017 into their sockets.  

---

## 4. Powering the Circuit
- Connect a **5–12V DC supply** to the screw terminal.  
- The LEDs will begin chasing sequentially.  
- Press the push button to reset the sequence.  

---

## 5. Troubleshooting
- **No LEDs lighting**: Check power polarity and solder joints.  
- **All LEDs ON**: Verify NE555 connections and capacitor polarity.  
- **LEDs too dim**: Reduce series resistors from 100Ω to 68Ω.  
- **Speed too fast/slow**: Adjust R1 (10kΩ) or C1 (30µF). Larger capacitor = slower speed.  

---

## 6. Safety Notes
- Use regulated DC supply (do not exceed 12V).  
- Ensure correct polarity for capacitor and ICs.  
- Do not short circuit the power supply.  

---
