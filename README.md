# EXPERIMENT NO. 4 – HALF WAVE AND FULL WAVE BRIDGE RECTIFIERS

| **Name:** | GUGAN U| **Reg. No.:** | 26017494 |
|---|---|---|---|
| **Date:** | 23-11-2026 | **Batch / Section:** | 19EE305 |

---

## AIM

To study the half wave and full wave bridge rectifiers with and without filter and to observe their input and output waveforms using Proteus.

## COMPONENTS AND EQUIPMENT REQUIRED

| S. No. | Components / Equipment |
|:---:|:---|
| 1 | Diodes |
| 2 | Resistor (load) |
| 3 | Capacitors (filter) |
| 4 | Step-down transformer |
| 5 | Voltmeter |
| 6 | Ammeter |
| 7 | Breadboard |
| 8 | CRO |
| 9 | Connecting wires |
| 10 | Simulation software – Proteus Design Suite |

## THEORY

A rectifier changes AC to DC and is an essential part of a power supply. The unique property of a diode, permitting current to flow in only one direction, is utilised in rectifiers.

### Half wave rectifier

Mains supply is applied to the primary of the step-down transformer. All the positive half cycles of the stepped-down AC supply pass through the diode and all the negative half cycles are eliminated. The peak value of the output voltage is less than the peak value of the input voltage by about 0.6 V because of the voltage drop across the diode. For a half wave rectifier, **Vrms = Vm/2** and **Vdc = Vm/π**, where Vrms is the RMS value of the output, Vdc is the average value of the output and Vm is the peak value of the output.

### Full wave bridge rectifier

During the positive half cycle of the secondary voltage, diodes D1 and D3 are forward biased and D2 and D4 are reverse biased, so current flows through the secondary winding, D1, the load resistor and D3. During the negative half cycle, D2 and D4 are forward biased and D1 and D3 are reverse biased, so current flows through the secondary winding, D2, the load resistor and D4. In both half cycles the current through the load resistor is in the same direction. The peak output voltage is less than the peak input voltage by about 1.2 V due to the drop across two diodes. For a full wave bridge rectifier, **Vrms = Vm/√2** and **Vdc = 2Vm/π**.

### Filters

All rectifier outputs contain a considerable amount of ripple in addition to the DC component. To remove the AC components, a filter is connected at the output of the rectifier. Capacitor input, choke input, RC, CRC, LC and CLC filters are commonly used; the capacitor input filter is the simplest and cheapest. A high-value capacitor C is connected in shunt with the load resistor RL. The capacitor charges to the peak voltage when a half cycle appears at the output. After the peak, the capacitor discharges slowly through RL, since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, the next output cycle arrives and the capacitor recharges to the peak.

## PROCEDURE

1. Wire up the half wave rectifier circuit without capacitor after testing all the components.
2. Switch on the mains supply. Observe the transformer secondary voltage waveform and the output voltage waveform across the load resistor simultaneously on the CRO.
3. Connect the capacitor filter across the load and observe the waveforms. Repeat for different capacitor values.
4. Repeat the above steps for the full wave bridge rectifier.
5. Simulate both rectifiers, with and without filter, in Proteus and capture the input and output waveforms on the virtual oscilloscope.

## CIRCUIT DIAGRAMS

<img width="1082" height="695" alt="Screenshot 2026-11-15 135152" src="https://github.com/user-attachments/assets/f4e70519-6768-4234-bcbc-5566ee877c6a" />
<img width="1600" height="875" alt="WhatsApp Image 2026-11-23 at 7 29 52 PM" src="https://github.com/user-attachments/assets/823fe223-b8a6-458d-98b3-be2900335f08" />

<img width="1106" height="705" alt="Screenshot 2026-11-15 140645" src="https://github.com/user-attachments/assets/b48333c2-1390-4027-a672-8636162af5e5" />
<img width="1600" height="1012" alt="WhatsApp Image 2026-11-23 at 7 30 12 PM" src="https://github.com/user-attachments/assets/c6e2cc8c-f682-4aa1-a6a1-cd8a3b6b4d5c" />





## SIMULATION AND WAVEFORMS USING PROTEUS
<img width="1367" height="852" alt="Screenshot 2026-11-15 134708" src="https://github.com/user-attachments/assets/3816ff49-165f-4c7d-8a30-24945c81bccf" />


<img width="1377" height="882" alt="Screenshot 2026-11-15 140600" src="https://github.com/user-attachments/assets/4c32dccb-6bfb-43c0-be36-f275498acf63" />

##TABULATION

<img width="1599" height="869" alt="WhatsApp Image 2026-11-23 at 7 30 34 PM" src="https://github.com/user-attachments/assets/0296678c-9aef-4d26-a2c0-1aec4a3adbd2" />



<img width="1600" height="741" alt="WhatsApp Image 2026-11-23 at 7 30 46 PM" src="https://github.com/user-attachments/assets/31fe6a22-54c3-462a-854f-2907c1505beb" />

##GRAPH

<img width="1600" height="687" alt="WhatsApp Image 2026-11-23 at 7 31 02 PM" src="https://github.com/user-attachments/assets/ebee2ae3-7505-476d-83ea-e851e81afcec" />

<img width="1600" height="1069" alt="WhatsApp Image 2026-11-23 at 7 31 18 PM" src="https://github.com/user-attachments/assets/99127527-e5b7-4834-b991-1366541b1b43" />

## FORMULAE

### A. Half wave rectifier

- Average (DC) voltage: **Vdc = Vm / π**
- Average (DC) current: **Idc = Im / π**
- RMS voltage: **Vrms = Vm / 2**
- RMS current: **Irms = Im / 2**
- Ripple factor: **γ = √[(Vrms / Vdc)² − 1] = 1.21**
- Rectification efficiency: **η = Pdc / Pac × 100 = (Idc² RL) / (Irms² RL) × 100 = 40.6 %**
- Form factor: **FF = Vrms / Vdc = 1.57**
- Peak factor: **PF = Vm / Vrms = 2**
- Peak inverse voltage: **PIV = Vm**

### B. Full wave bridge rectifier

- Average (DC) voltage: **Vdc = 2Vm / π**
- Average (DC) current: **Idc = 2Im / π**
- RMS voltage: **Vrms = Vm / √2**
- RMS current: **Irms = Im / √2**
- Ripple factor: **γ = √[(Vrms / Vdc)² − 1] = 0.482**
- Rectification efficiency: **η = Pdc / Pac × 100 = (Idc² RL) / (Irms² RL) × 100 = 81.2 %**
- Form factor: **FF = Vrms / Vdc = 1.11**
- Peak factor: **PF = Vm / Vrms = √2 = 1.414**
- Peak inverse voltage: **PIV = Vm**

### C. With capacitor filter

- Half wave: **γ = 1 / (2√3 f C RL)**
- Full wave bridge: **γ = 1 / (4√3 f C RL)**

### D. Regulation

- **% Regulation = (VNL − VFL) / VFL × 100**

Vm – peak output voltage; Im – peak load current (Im = Vm / RL); RL – load resistance; f – supply frequency (50 Hz); C – filter capacitance; VNL – no-load voltage; VFL – full-load voltage.

## RESULT

Thus, the input and output waveforms of the half wave and full wave bridge rectifiers with and without filter were observed using Proteus.
