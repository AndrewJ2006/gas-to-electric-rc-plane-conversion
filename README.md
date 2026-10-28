# Gas-to-Electric RC Aircraft Conversion


This project involved converting a gas-powered radio-controlled (RC) aircraft to electric propulsion. The original power system was replaced with an electric motor and propeller setup, with a rechargeable battery and electronic speed controller (ESC) powering the aircraft.
The converted aircraft was successfully flown, demonstrating that the electric propulsion conversion worked in real-world operation.



 <img width="300" height="400" alt="Full Airframe" src="https://github.com/user-attachments/assets/bcfb56df-36a9-4201-89fb-f2bd0cd81123" />  <img width="300" height="400" alt="Motor Installation" src="https://github.com/user-attachments/assets/1e226f17-bb05-44b7-bdbe-8b459d52ecba" />  <img width="400" height="400" alt="Screenshot 2026-10-27 202449" src="https://github.com/user-attachments/assets/c21ad854-8265-4cfb-ac69-3b015f667a90" />


## Objectives

*  Match or exceed original glow-engine thrust performance using a Spektrum Avian brushless outrunner motor and matching ESC.
*  Design internal component placement and battery mounting to preserve the original Center of Gravity (CoG) within existing balsa fuselage limits.
*  Integrate a 4-channel DSMX receiver with BEC power distribution, eliminating the need for a secondary receiver battery pack.
*  Reconstruct the airframe, motor mount, and electronics layout in SOLIDWORKS for 3D packaging documentation.
*  Test and successfully fly the converted plane. 

## Main Components

|      |      |
|---|---|
| **Airframe** | Balsa wood high-wing RC trainer |
| **Brushless Motor** | Spektrum Avian Brushless Outrunner Series |
| **Electronic Speed Controller (ESC)** | Avian Smart ESC (integrated BEC for receiver power) |
| **Radio Receiver** | Spektrum AR410 4-Channel DSMX (internal antenna) |
| **Power Supply** | Multi-cell LiPo flight battery (XT60 connector) |

## Conversion Process

1. Removed the original gas engine and retrofitted the front firewall to mount the Spektrum Avian brushless motor. Adjusted motor standoffs to line up the prop shaft with the cowl and ensure sufficient ventilation for cooling.

2. Wired the ESC directly to Channel 1 (Throttle) on the Spektrum AR410 receiver. This allows the ESC to control motor speed while supplying 5V BEC power to the receiver and servos, eliminating the need for a secondary receiver battery.

3. Mounted the ESC and LiPo battery tray inside the forward fuselage bay. Placing the heavy battery toward the front compensated for the lighter electric motor and kept the plane’s Center of Gravity balanced.

4. Modeled the original airframe, motor mount, and internal electronics layout in SOLIDWORKS to document component packaging and clearance for future modifications.


## Results

- Successfully converted the airframe from gas to electric propulsion and achieved stable, repeatable test flights.
- Reconstructed the complete airframe and component packaging in SOLIDWORKS to document the conversion process.




