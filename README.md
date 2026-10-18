# EXPERIMENT NO: 3

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

<img width="1130" height="513" alt="Direct_Circuit_1" src="https://github.com/user-attachments/assets/fb49908a-db6b-459c-adb7-caa8fd57029a" />

### 2. Cross Connection

<img width="1125" height="517" alt="Cross_Cicuit_1" src="https://github.com/user-attachments/assets/08d4fee7-004f-4d53-9dfb-0ad2b8cb35fa" />

## SIMULATION RESULTS

### 1. Direct Connection — Lamp Glowing

<img width="1127" height="521" alt="Direct_Circuit_2" src="https://github.com/user-attachments/assets/51bc84e2-3a11-4e8d-b447-28f92e7fae31" />

### 2. Cross Connection — Lamp Glowing

<img width="1123" height="546" alt="Cross_Circuit_2" src="https://github.com/user-attachments/assets/9ba08e93-0a31-4ae6-b155-aa671b3a0941" />

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
