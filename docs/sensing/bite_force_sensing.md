# Bite‑Force Sensing Concept

This document explains how SmartBite measures bite force, including sensor selection, placement, signal characteristics, and expected ranges.

---

## 1. Sensor Type

SmartBite may use one of the following sensor types:

- **Force‑Sensitive Resistor (FSR)**  
- **Piezoelectric sensor**  
- **Strain gauge**  
- **Miniature load cell**

The chosen sensor must balance sensitivity, durability, moisture resistance, and ergonomic integration.

---

## 2. Signal Characteristics

Key properties to document:

- Expected force range (light → strong bite)
- Voltage output curve
- Non‑linearity behaviour
- Temperature effects
- Moisture influence on readings

---

## 3. Mechanical Integration

- Sensor embedded inside the mouthpiece  
- Even pressure distribution  
- Protective layers to prevent damage  
- Isolation from saliva and moisture  

---

## 4. Electrical Integration

- ADC resolution requirements  
- Sampling frequency  
- Noise sources  
- Filtering requirements  

---

## Acceptance Criteria

- Document stored in `/docs/sensing/`  
- File name: `bite_force_sensing.md`  
- Includes diagrams or sketches  
- Linked from README  
