
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---

## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.



## 🔌 CONNECTION DIAGRAM

![WhatsApp Image 2025-11-19 at 18 43 47_547afbc6](https://github.com/user-attachments/assets/1c9c9665-0c30-469d-a4f5-ad6a0cee052e)



## 📊 TABULATION

![WhatsApp Image 2025-11-19 at 18 54 47_ac5fb20d](https://github.com/user-attachments/assets/4a06be2c-f9fb-483e-a55b-d1316cb568b5)

### LED Forward Characteristics

## 📈 MODEL GRAPH

![WhatsApp Image 2025-11-19 at 18 54 33_3455412e](https://github.com/user-attachments/assets/d653299d-7ebb-42a1-8062-0e13de70a514)

![WhatsApp Image 2025-11-19 at 18 53 51_94eba0f5](https://github.com/user-attachments/assets/0c520660-c1a5-4866-a98a-4a9e448fb416)

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
