# TEAM BAITUSSALAM
<img width="197" height="256" alt="download" src="https://github.com/user-attachments/assets/82e81ef4-3dae-4078-aa70-dd35e0646484" />

This repository presents our documentation of the WRO 25(Future Engineers).

# Table Of Contents
.TEAM INTRODUCTION
1. [WHO ARE WE?](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#who-are-we)
2. [Our Journey](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#our-journey-)

# [Mobility Management](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#mobility-management)
1. [Motor Selection](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#motor-selection)
2. [Steering Mechanism](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#steering-mechanism)
3. [Chassis](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#chassis)
4. [Mounting](https://github.com/user-attachments/assets/f114bbc2-4523-4d2e-b8ea-52cbe363f821)
5. [Engineering Principals](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/edit/main/README.md#engineering-principals)




# TEAM INTRODUCTION
## Who are we?
Our team consists of three memebers-Taha Umer, Zulqarnain, and Sikandar.

## Our journey 🚀


# Mobility Management
## Motor Selection
| MOTOR | Specification |
|-------|---------------|
| ![DC Gear motor](https://github.com/user-attachments/assets/7a80326e-b20d-45d9-98cf-7f79c16cb125) | • Type = DC Gear Motor with Encoder <br> • 280 RPM (GA25-370) Voltage: 6–12V DC (12V typical) <br> • Speed: 280 RPM @ 12V <br> • Gear Ratio: ~1:30 <br> • Torque: ~1.5–3 kg·cm @ 12V <br> • Current: No-load 100–200 mA, stall ~2 A <br> • Encoder: 2-channel, ~330 pulses per output shaft revolution <br> • Shaft: 4 mm D-shaft <br> • Size: 25 mm diameter, ~50–60 mm length (with encoder)  |

## The reason for selection
We're using this DC gear motor with an encoder because it's the perfect tool for precise movement. The gear motor itself gives us a lot of power in a small package, while the built-in encoder acts like a digital eye, letting the robot know exactly how far and how fast its wheels are turning. This real-time feedback is crucial for tasks like accurate navigation and maintaining a steady speed, which are a big part of the challenge.

| MOTOR | Specification |
|-------|---------------|
| ![Servo Motor](https://github.com/user-attachments/assets/ea462489-d1eb-4ebb-8d32-c183a7b89744) | <br> • Model: MG996R <br> • Type: High Torque Digital Servo Motor <br> • Operating Voltage: 4.8V - 7.2V (often listed as 5V) <br> • Stall Torque (at 6V): Approximately 10 kg·cm to 13 kg·cm (kilogram-force per centimeter) <br> • Operating Speed (at 6V): Around 0.16 sec/60° <br> • Gear Material: Metal gears <br> • Dimensions: Approximately 40.7mm x 19.7mm x 42.9mm <br> • Weight: Around 55g <br> • Rotation: 0° to 180°  |

## The reason for selection
We chose this servo motor for its robust performance and durability. Its high torque and metal gears are essential for the demanding tasks of our robot, while its affordability and availability make it a practical and reliable choice for our project's development.


# Steering Mechanism
## Parallel Steering Mechanism(Lego)
![Parallel steering mechanism(LEGO)](https://github.com/user-attachments/assets/35e0c66f-db4e-409f-828a-46ba96dee5bf)
This steering system, built using LEGO Technic components, ensures that both front wheels of the robot always turn by the same amount and in the same direction. It's a simple, reliable design where a motor—typically a servo like the MG996R—pushes or pulls on a central arm. This motion is then transferred through a series of connected linkages that turn the wheel hubs. The symmetrical layout of these linkages keeps the wheels parallel throughout the entire steering range, which is perfect for consistent and predictable movement.

# Chassis

Our chassis is a mixture of components made of lego blocks, 3D designs made by PETG as well as PLA, and also Acryllic sheet espically designed for stability and modularity. It features a rear-wheel drive system powered by DC gear motors for consistent motion. For steering, we implemented a parallel steering mechanism driven by the MG996R servo, ensuring precise and predictable turns. All sensors are strategically mounted to provide optimal track visibility, and the overall design maintains a low center of gravity for balanced performance.

- Material: lightweight and strong usnig parts made with PETG and PLA, Lego blocks, and Acrallyic sheet
- Shape: rectangular stability
- Size: fits robot components and competition rules
- Motor & wheel mounting: securely attached with brackets/screws
- Component placement: Arduino, sensors, battery positioned for balance
- Stability: reinforced to prevent tipping or bending
- Easy maintenance: components are accessible for troubleshooting

# Mounting

- All components securely fixed on the chassis using screws, nuts, and 3D-printed brackets
- Raspberry Pi mounted centrally for balance; camera at front for clear view
- Sensors and IMU placed near center of gravity for accuracy
- Motors aligned with wheels and pulleys for smooth motion
- Wires neatly routed to avoid interference with moving parts
- Components accessible for easy maintenance and troubleshooting

# Engineering Principals

1. Wheel RPM from motor:
Wheel_RPM = Motor_RPM / Gear_Ratio

2. Robot linear speed:
v = (2 * π * Wheel_radius * Wheel_RPM) / 60

3. Wheel torque:
Wheel_Torque = Motor_Torque * Gear_Ratio

4. Force at wheels:
F = Wheel_Torque / Wheel_radius

5. Mechanical power:
P = Torque * Angular_speed
P = F * v

6. Motor electrical power:
P_elec = P_mech / Motor_efficiency
I = P_elec / Voltage

​




