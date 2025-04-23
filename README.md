# SHADOW-SENSOR
 A simple burglar alarm produces LIGHT when  somebody crosses a protected area or door. 
his project demonstrates a basic **shadow detection system** using an **LDR (Light Dependent Resistor)** and a **BC547 transistor**. The sensor detects a drop in light intensity when a shadow falls over the LDR and turns on an LED to indicate detection.

---

## 🔍 What is a Shadow Sensor?

A **shadow sensor** is a light-based detection system that uses a photodetector (in this case, an LDR) to sense changes in surrounding light. When a shadow blocks light to the sensor:
- The **resistance of the LDR increases**
- The **voltage across the base of the transistor changes**
- The transistor either switches ON or OFF, controlling an LED or another output

---
## 🔧 How It Works

1. The LDR and a resistor form a **voltage divider** circuit.
2. When light falls on the LDR:
   - Resistance is low → Voltage at transistor base is high → Transistor conducts → LED OFF
3. When a **shadow** falls on the LDR:
   - Resistance increases → Voltage at base drops → Transistor turns OFF → LED turns ON
4. This acts as a **shadow-triggered LED alert system**.

---
