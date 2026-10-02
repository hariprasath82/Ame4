# exp_3_characteristics_of_directional_coupler

# Experiment 4 — Directional Coupler Characteristics

---

## Aim

To measure the directivity and coupling factor for the given directional couplers.

## Apparatus Required

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, directional coupler, detector mount / crystal detector, matched terminations, Power meter, waveguide stands.

---

## Theory

# Directional Coupler

<img width="549" height="200" alt="image" src="https://github.com/user-attachments/assets/58febc6f-896b-45ab-8f0a-d973b661f5b4" />


A directional coupler is a flanged, built-in waveguide assembly that samples a small amount of microwave power for measurement purposes. It can be designed to measure incident and/or reflected power, SWR values, provide a signal path to a receiver, or perform other desirable operations, and can be unidirectional or bidirectional.

In its most common form the directional coupler is a **four-port waveguide junction** consisting of a primary main waveguide and a secondary auxiliary waveguide. A small portion of the input power at port 1 is coupled to port 4, so this small power can be measured. Ideally, no power should come out of port 3.

The performance of a directional coupler is usually defined by two parameters:

1. **Coupling factor**
2. **Directivity**

---

## Experimental Setup

<img width="783" height="270" alt="image" src="https://github.com/user-attachments/assets/0b0576bb-4b6f-4e21-8a34-8f54ca04adf9" />

## Procedure

1. Switch ON the klystron supply with necessary precautions.
2. Operate the klystron in its best mode and note the corresponding output power as **P₁** (P₁ = incident power).
3. Connect the directional coupler as shown in the experimental setup.
4. Without disturbing the mode of the klystron, connect the directional coupler as shown in the bench setup.

---

## Measurements

P1 = Without directional coupler

P2 = Port 2 Output (P1 is input)

P3 = Port 3 Output (P1 is input)

P4 = Port 3 Output (P2 is input) [P1 is matched termination]

---
## Calculation

Instertion Loss (dB) = P1-P2

Coupling Factor (dB) = P1-P3

Isolation (dB) = P1-P4

Directivity (dB) = P3-P4

---

## Observation

Assume the measured power values are in dBm.

| Parameter | Measured Value |
|---|---:|
| P₁ — Without directional coupler | 10 dBm |
| P₂ — Port 2 Output | 9 dBm |
| P₃ — Port 3 Output | -20 dBm |
| P₄ — Port 3 Output with P₂ as input | -48 dBm |

### Calculation

#### 1. Insertion Loss

$$
\text{Insertion Loss} = P_1 - P_2
$$

$$
= 10 - 9 = \boxed{1\text{ dB}}
$$

#### 2. Coupling Factor

$$
\text{Coupling Factor} = P_1 - P_3
$$

$$
= 10 - (-20) = \boxed{30\text{ dB}}
$$

#### 3. Isolation

$$
\text{Isolation} = P_1 - P_4
$$

$$
= 10 - (-48) = \boxed{58\text{ dB}}
$$

#### 4. Directivity

$$
\text{Directivity} = P_3 - P_4
$$

$$
= -20 - (-48) = \boxed{28\text{ dB}}
$$

### Observation Table

| Quantity | Formula | Result |
|---|---|---:|
| Insertion Loss | $P_1-P_2$ | 1 dB |
| Coupling Factor | $P_1-P_3$ | 30 dB |
| Isolation | $P_1-P_4$ | 58 dB |
| Directivity | $P_3-P_4$ | 28 dB |

> **Note:** The above values are sample readings. Replace them with your actual experimental readings if required.

---



## Precautions

1. The beam voltage should be minimum and the repeller voltage should be normal before switching the klystron power supply ON/OFF.
2. Loose connections between the components should be avoided.
3. The directional coupler must be handled carefully while inserting it into the circuit

---

## Conclusion

The characteristics of the given directional coupler were determined experimentally. The insertion loss, coupling factor, isolation, and directivity were calculated from the measured power levels. The results demonstrate the directional nature of the coupler, where a small portion of the incident microwave power is coupled to the auxiliary port while the power at the isolated port is minimized.
