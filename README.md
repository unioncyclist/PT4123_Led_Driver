# PT4123_Led_Driver
Adjustable Constant current LED driver using the PT4123


## Schematics
<img width="1853" height="921" alt="Image_1780645594746_109" src="https://github.com/user-attachments/assets/dae10385-2fcd-4555-8f55-02e8da2860c3" />

## PCB
<img width="2200" height="1123" alt="Image_1780645596703_233" src="https://github.com/user-attachments/assets/1ba3405b-1cc0-4994-aca8-cdf5193f3d93" />


## Setting Output

Max output current is set by 0.2/R4. Here R4=75mA, so the max output is 2.67A if following the BOM

DO NOT test the circuit without any LED connected to the output, possible damage to the chip


## Control

Method1. The R2 can be replaces by a variable resistor, no need for the control pin

Method2. Input DC voltage source 0-2.5v, no need for R2

Method3. Input PWM 0-3.3v, no need for R2


## Finished prototype

<img width="3072" height="4096" alt="1780661271353" src="https://github.com/user-attachments/assets/0f6591e6-e139-455a-8126-6899359d5f48" />

<img width="3072" height="4096" alt="1780661271304" src="https://github.com/user-attachments/assets/77afbc99-8843-49ae-850e-be071e113b2b" />

-the TVS protection at the input is optional

## Special thanks

This prototype used Kicad(https://github.com/kicad), thanks to the contributers of the project
