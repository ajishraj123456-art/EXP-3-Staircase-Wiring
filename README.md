# STAIRCASE WIRING USING TWO-WAY SWITCHES

## AIM
To control the ON and OFF status of a lamp using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the Apparatus | Range / Type | Quantity |
|---|---|---|---|
| 1 | Incandescent Lamp | 60 W | 1 No. |
| 2 | Lamp Holder | Pendant Type | 1 No. |
| 3 | SPDT Switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18 inch | As required |
| 5 | PVC Pipe | 1/4 inch | As required |
| 6 | Wooden Board | — | 1 No. |
| 7 | Round Block | — | 1 No. |

## THEORY

Staircase wiring is used to control a single lamp from two different locations using two SPDT (two-way) switches. It is commonly used in staircases, corridors and bedrooms.

The two switches are interconnected using two traveler wires. Changing the position of either switch changes the state of the lamp, allowing it to be switched ON or OFF from either location.

## PROCEDURE

1. Place the required components on the wiring board according to the circuit diagram.
2. Connect the phase supply to the common terminal of the first SPDT switch.
3. Connect the two contact terminals of the first switch to the corresponding terminals of the second switch using traveler wires.
4. Connect the common terminal of the second switch to one terminal of the lamp holder.
5. Connect the other terminal of the lamp holder to the neutral line.
6. Check all connections carefully.
7. Simulate the circuit and operate both switches to verify the lamp's ON/OFF operation.

## CIRCUIT DIAGRAMS

### 1. Direct Connection

<img width="1920" height="1080" alt="Direct_Circuit_1" src="https://github.com/user-attachments/assets/090e6ad2-892c-47df-a60f-d26991c98f26" />

### 2. Cross Connection

<img width="1920" height="1080" alt="Cross_Circuit_1" src="https://github.com/user-attachments/assets/be4ff375-f19e-422e-820d-f439d452ff9a" />

## SIMULATION RESULTS

### 1. Direct Connection — Lamp Glowing

<img width="1920" height="1080" alt="Direct_Circuit_2" src="https://github.com/user-attachments/assets/1cb8ade0-8ebc-47c5-bd78-cff29aba59f5" />

### 2. Cross Connection — Lamp Glowing

<img width="1920" height="1080" alt="Cross_Circuit_2" src="https://github.com/user-attachments/assets/734c4042-2650-4dc8-8fb3-8bcc958c6c7e" />

## TABULATION

### TABULATION 1: DIRECT CONNECTION

| S. No. | Switch 1 Position | Switch 2 Position | Lamp Status |
|---|---|---|---|
| 1 | Up | Up | ON |
| 2 | Up | Down | OFF |
| 3 | Down | Up | OFF |
| 4 | Down | Down | ON |

### TABULATION 2: CROSS CONNECTION

| S. No. | Switch 1 Position | Switch 2 Position | Lamp Status |
|---|---|---|---|
| 1 | Up | Up | OFF |
| 2 | Up | Down | ON |
| 3 | Down | Up | ON |
| 4 | Down | Down | OFF |

## RESULT

Thus, the staircase wiring circuit was constructed and tested using Proteus simulation. The lamp was controlled from two different locations using two-way switches.
