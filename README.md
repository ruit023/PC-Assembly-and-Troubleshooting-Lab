# 🖥️ Practical Case Study: PC Assembly, Disassembly & Hardware Troubleshooting

![Course](https://img.shields.io/badge/Course-SECP1513_TIS-00FF66?style=for-the-badge&logo=github&logoColor=black)
![Institution](https://img.shields.io/badge/UTM-Faculty_of_Computing-00FF66?style=for-the-badge&logo=university&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-00FF66?style=for-the-badge)

A practical hands-on documentation and e-Portfolio case study on personal computer assembly, component identification, and hardware troubleshooting conducted during the SECP1513 TIS Lab session at Universiti Teknologi Malaysia (UTM).

---

### 📋 Overview & Disassembly Steps

Under the guidance of our Lab Assistant, our team (Group of 6) performed a step-by-step disassembly and reassembly process of standard desktop computers:

1. **Side Cover Removal**: Accessing the chassis interior safely.
2. **Power Disconnection**: Unplugging all PSU power connectors (24-pin mainboard, CPU power, SATA).
3. **PSU Unmounting**: Removing the Power Supply Unit (PSU).
4. **Storage Unit Removal**: Disconnecting and removing Hard Disk Drives (HDD) / Solid State Drives (SSD).
5. **RAM Module Extraction**: Removing Random Access Memory (RAM) sticks from DIMM slots.
6. **CPU Cooler Disassembly**: Safely unmounting the CPU heatsink/fan assembly.

*The reassembly followed the exact reverse sequence before final hardware validation.*

---

### 🔍 Real-World Hardware Troubleshooting (Case Study)

#### Issue Encountered:
During the initial boot-up validation (connecting power and monitor), the computer failed to display output (No POST / Blank Screen).

#### Root Cause Analysis:
After systematic isolation, the issue was identified in the **RAM modules**. During manual disassembly, a group member accidentally touched the gold contacts (pins) of the RAM module with bare hands. Fingerprint oils and moisture created a micro-insulation layer, leading to poor pin contact with the DIMM slot.

#### Resolution:
Replaced the contaminated RAM module with a clean module (or cleaned contacts thoroughly) and reseated it firmly into the slot. The system subsequently successfully powered on and booted to screen.

---

### 💡 Personal Reflection
> *"Hardware failure analysis is a critical foundational skill in computer infrastructure—minor physical contact issues can prevent complex systems from functioning."*

As a Year 1 Computer Network & Security student at UTM, this lab session reinforced that hardware maintenance requires strict adherence to operating procedures (ESD safety, handling components by edges). Solving the boot failure by isolating RAM pin contamination gave me practical insights into physical layer diagnostics that software engineers often overlook.

---

👥 **Team Collaboration**:
- **Participant**: TEY HAO RUI (Matric: A26CS038)
- **Course**: SECP1513 Technology and Information System (TIS)
- **Institution**: Universiti Teknologi Malaysia (UTM)
