# BLE Communication Overview

This document describes how SmartBite communicates over BLE, including GATT services, characteristics, and packet structure.

---

## 1. BLE Role

- Peripheral device  
- Advertising interval  
- Connection parameters  

---

## 2. GATT Structure

### SmartBite Service  
Characteristics:

- Bite force value  
- Calibration status  
- Battery level  

---

## 3. Packet Format

- Byte layout  
- Timestamp  
- Force value  
- Flags  

---

## 4. Power Considerations

- Advertising vs. connected mode  
- Sleep cycles  
- Low‑power transmission strategy  

---

## Acceptance Criteria

- Document stored in `/docs/communication/`  
- File name: `ble_overview.md`  
- Includes packet diagrams  
- Linked from README  
