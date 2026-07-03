# LDR-Based Automatic Light Sensor Circuit

An automatic light sensing circuit designed using **EasyEDA**. The circuit uses an **LDR (Light Dependent Resistor)** and a **UA741 operational amplifier** configured as a comparator to detect changes in ambient light intensity. A potentiometer is used to adjust the switching threshold.

---

## Project Overview

This project demonstrates the design of a simple light detection circuit capable of sensing ambient light levels and producing an output when the light intensity crosses a user-defined threshold. The complete schematic and PCB layout were designed in EasyEDA.

---

## Features

- Automatic light detection using an LDR
- Adjustable sensitivity using a 100 kΩ potentiometer
- Comparator-based switching using UA741 op-amp
- Custom PCB designed in EasyEDA
- Suitable for basic automation and educational applications

---

## Applications

- Automatic street lighting
- Smart home lighting systems
- Light-sensitive alarm systems
- Educational electronics projects
- Ambient light detection

---

## Components Used

| Component | Value |
|----------|-------|
| LDR | GL4549 (100–200 kΩ) |
| Operational Amplifier | UA741IP |
| Resistor R2 | 100 kΩ |
| Potentiometer | 100 kΩ |
| Resistor R3 | 470 Ω |
| Connectors | WJ129V-5.00-2P |

---

## Software Used

- EasyEDA Standard
- EasyEDA PCB Editor

---

## Project Files

```
├── README.md
├── Schematic
│   ├── LDR_Schematic.pdf
│   └── EasyEDA_Source.json
├── PCB
│   └── LDR_PCB.pdf
```

---

## Circuit Description

The LDR and resistor form a voltage divider whose output varies with ambient light intensity. This varying voltage is compared with a reference voltage set by the potentiometer. The UA741 op-amp acts as a comparator and changes its output state whenever the LDR voltage crosses the reference voltage.

---

## PCB Design

The PCB was designed in EasyEDA with through-hole components for ease of fabrication and assembly.

---

## Future Improvements

- Replace UA741 with LM358 for better single-supply operation.
- Add a relay module for AC load control.
- Include an LED status indicator.
- Add power supply filtering capacitors.
- Reduce PCB size for compact applications.

---

## Repository Contents

- EasyEDA source files
- Circuit schematic
- PCB layout
- Documentation

---

## Author

**Nainika L**

Electronics and Communication Engineering  
Global Academy of Technology

Interested in VLSI Design, Embedded Systems, PCB Design, and Digital Electronics.

---

## License

This project is shared for educational and learning purposes.
