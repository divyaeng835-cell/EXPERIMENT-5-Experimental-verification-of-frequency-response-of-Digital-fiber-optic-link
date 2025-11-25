
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="595" height="365" alt="image" src="https://github.com/user-attachments/assets/9c285acf-0dc5-4c4b-a5af-e292a4747ded" />


---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Digital Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
| 800 Hz         |  2.5                         |  0.5         | -6.02      |
| 1 KHz          |  32                          |  6.4         |  16.12     |
| 2 KHz          |  34                          |  6.8         |  16.6      |
| 5 KHz          |  36                          |  7.2         |  17.14     |
| 10 KHz         |  37                          |  7.4         |  17.38     |
| 20 KHz         |  37                          |  7.4         |  17.38     |
| 50 KHz         |  27                          |  5.4         |  17.38     |
| 100 KHz        |  27                          |  5.4         |  14.64     |
| 250 KHz        |  12.7                        |  2.54        |  8.09      |

---
 
## MODEL GRAPH
![WhatsApp Image 2025-11-25 at 13 33 58_ae3a1eed](https://github.com/user-attachments/assets/472bd5b7-d60e-48e4-ac12-5047e2c0f780) 
## OUTPUT GRAPH
![WhatsApp Image 2025-11-25 at 13 40 54_1f8a029b](https://github.com/user-attachments/assets/c0f156c9-5f4e-4bd4-8d66-b016c643d2b2)


## RESULT
The relationship between input and received signal of a 600nm fiber optic cable using digital link are analyzed completely.
