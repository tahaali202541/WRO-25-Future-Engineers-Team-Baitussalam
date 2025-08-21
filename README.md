# TEAM BAITUSSALAM
<img width="197" height="256" alt="download" src="https://github.com/user-attachments/assets/82e81ef4-3dae-4078-aa70-dd35e0646484" />

This repository presents our documentation of the WRO 25(Future Engineers).

# Content Table
# [TEAM INTRODUCTION](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#our-journey-)
1. [WHO ARE WE?](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#who-are-we)
2. [Our Journey](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#our-journey-)

# [Mobility Management](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#mobility-management-1)
1. [Motor Selection](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#motor-selection)
2. [Steering Mechanism](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#steering-mechanism)
3. [Chassis](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#chassis)
4. [Mounting](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#mounting)
5. [Engineering Principals](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#engineering-principals)

# [Power and Sense Management](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#power-and-sense-managemnet)
1.[POWER SOURCE](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#power-source)<br>
2.[Sensors Used](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#sensors-used)<br>
3.[Wiring Diagram](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#wiring-diagram)<br>

# [Obstacle Management(Open challenge round)](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#obstacle-managementopen-challenge-round-1)
1.[Strategy for Open Challenge round](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam?tab=readme-ov-file#strategy-for-open-challenge-round)

# TEAM INTRODUCTION
## Who are we?
We are a team from Pakitan representing our country/institute. Our team consists of three members – Taha Umer, Zulqarnain, and Sikandar.It is our first time participating in WRO. Together, we focus on different parts of the project such as coding, mechanical design, and documentation. By combining our efforts, we aim to build a functional and well-prepared robot for the Future Engineers category. 
## Our journey 
Our journey strated when we were first informed about our participation in WRO 25(Future Engineers), by our management team. Our journey is not quite smooth full of problems, misatkes, headaches, and even moments of 'Just leaving!' but what makes our jouney interesting are moements of success, seeing the hardwork pay-off, and at last 'The Victory'. This repository not only holds the designs, codes, and components but it also holds our feelings our way through all the stages, 'THE NATIONAL CHAMPIONSHIP' and One day 'INTERNATIONAL CHAMPIONSHIP' too.<br>
## THE HURDLES <br>
 1. STEERING MECHANISM
Eveyting seems too easy and simple until you are hands-on with it. Although, it was not our first time participating in any robotics competition, we have partipated in many national competitions before such as NERC(For the last 4 years), Headstarts, Air university and many other but this competition hit different. Speaking faithfully, the journey had just barely begun that 'The Steering Mechanism' stood tall infront of us. We had thought of using 'Ackerman Steering Mechanism' which first seemed easy but after working on many protytypes we changed our mind and decided to use the simple 'Parallel Steering Mechanism' made with Lego Blocks. This was the first problem that we faced.

# Mobility Management
## Motor Selection
| MOTOR | Specification |
|-------|---------------|
| <img src="https://github.com/user-attachments/assets/7a80326e-b20d-45d9-98cf-7f79c16cb125" width="275" height="350"/> | • Type = DC Gear Motor with Encoder <br> • 280 RPM (GA25-370) Voltage: 6–12V DC (12V typical) <br> • Speed: 280 RPM @ 12V <br> • Gear Ratio: ~1:30 <br> • Torque: ~1.5–3 kg·cm @ 12V <br> • Current: No-load 100–200 mA, stall ~2 A <br> • Encoder: 2-channel, ~330 pulses per output shaft revolution <br> • Shaft: 4 mm D-shaft <br> • Size: 25 mm diameter, ~50–60 mm length (with encoder)  |

## The reason for selection
We're using this DC gear motor with an encoder because it's the perfect tool for precise movement. The gear motor itself gives us a lot of power in a small package, while the built-in encoder acts like a digital eye, letting the robot know exactly how far and how fast its wheels are turning. This real-time feedback is crucial for tasks like accurate navigation and maintaining a steady speed, which are a big part of the challenge.

| MOTOR |  Specification |
|-------|---------------|
| <img src="https://github.com/user-attachments/assets/ea462489-d1eb-4ebb-8d32-c183a7b89744" width="275" height="350"/> | • Model: MG996R <br> • Type: High Torque Digital Servo Motor <br> • Operating Voltage: 4.8V - 7.2V (often listed as 5V) <br> • Stall Torque (at 6V): Approximately 10 kg·cm to 13 kg·cm (kilogram-force per centimeter) <br> • Operating Speed (at 6V): Around 0.16 sec/60° <br> • Gear Material: Metal gears <br> • Dimensions: Approximately 40.7mm x 19.7mm x 42.9mm <br> • Weight: Around 55g <br> • Rotation: 0° to 180° |


## The reason for selection
We chose this servo motor for its robust performance and durability. Its high torque and metal gears are essential for the demanding tasks of our robot, while its affordability and availability make it a practical and reliable choice for our project's development.


# Steering Mechanism
## Parallel Steering Mechanism(Lego)
<img src="https://github.com/user-attachments/assets/35e0c66f-db4e-409f-828a-46ba96dee5bf" width="400" height="450"/> <br>
This steering system, built using LEGO Technic components, ensures that both front wheels of the robot always turn by the same amount and in the same direction. It's a simple, reliable design where a motor—typically a servo like the MG996R—pushes or pulls on a central arm. This motion is then transferred through a series of connected linkages that turn the wheel hubs. The symmetrical layout of these linkages keeps the wheels parallel throughout the entire steering range, which is perfect for consistent and predictable movement.

# Chassis

Our chassis is a mixture of components made of lego blocks, 3D designs made by PETG as well as PLA, and also Acryllic sheet espically designed for stability and modularity. It features a rear-wheel drive system powered by DC gear motors for consistent motion. For steering, we implemented a parallel steering mechanism driven by the MG996R servo, ensuring precise and predictable turns. All sensors are strategically mounted to provide optimal track visibility, and the overall design maintains a low center of gravity for balanced performance.

- Material: lightweight and strong usnig parts made with PETG and PLA, Lego blocks, and Acrallyic sheet

| PETG | Specifications |
|------|----------------|
| ![istockphoto-2169621495-612x612](https://github.com/user-attachments/assets/ce83a410-5170-49d6-bf49-9376ce2b19a7) | • Definition: A thermoplastic combining the easy printing of PLA with the strength of ABS. <br> • Key Properties: Strong, durable, slightly flexible, and more heat/chemical resistant than PLA. <br> • Advantages: Good for mounts and moving parts, excellent layer adhesion, less warping than ABS. <br> • Limitations: Can string during printing, heavier and softer than PLA. <br> • Print Settings: Nozzle 230–250 °C, Bed 70–80 °C. |

| PLA | Specifications |
|------|----------------|
| ![images](https://github.com/user-attachments/assets/aaae6af8-e30e-462a-9c2f-0a3c510f4e44) | •  Definition: A biodegradable thermoplastic made from renewable resources like corn starch. <br> • Key Properties: Easy to print, lightweight, good surface finish, but brittle. <br> • Advantages: Low warping, ideal for prototypes and lightweight robot parts. <br> • Limitations: Low heat resistance, weaker under stress compared to PETG/ABS. <br> • Print Settings: Nozzle 190–220 °C, Bed 20–60 °C. |

| Arcylic Sheet | Specifications |
|------|----------------|
| ![images (1)](https://github.com/user-attachments/assets/334ceaf3-b745-4f87-bee2-9ad51a4ab8d4) | •  Definition: Acrylic (PMMA) is a lightweight, transparent plastic often used as a glass substitute. <br> • Key Properties: Rigid, smooth, lightweight, and visually clear. <br> • Usage in Our Robot: We used acrylic sheets for both the upper and lower decks to provide a stable, flat surface for mounting components. <br> • Advantages: Easy to cut, lightweight, gives a neat look, and provides good electrical insulation. <br> • Limitations: Brittle compared to PETG/PLA (can crack under heavy stress). |

| Lego blocks | Specifications |
|------|----------------|
| ![images (2)](https://github.com/user-attachments/assets/07c342e6-875c-43b3-ba6e-4deda8ebb5fa) | <br> •  Definition: Standard LEGO Technic blocks used as modular mechanical components. <br> • Usage in Our Robot: We used LEGO parts to build the steering mechanism, as they provide precise alignment and easy prototyping. <br> • Advantages: Strong interlocking fit, reusable, lightweight, and allows quick adjustments during testing. |


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
- Components accessible for easy maintenance and troubleshooting <br>
 Link for all the mounts and components-> [(Models)](https://github.com/tahaali202541/WRO-25-Future-Engineers-Team-Baitussalam/tree/main/Models)

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


# Power and Sense Managemnet
## POWER SOURCE
| Battery | Specifications |
|---------|----------------|
|  |  |

Reason for Selection :

## Sensors Used


| Sharp IR sensor(Long Range) | Specifications |
|---------|----------------|
| <img src="https://github.com/user-attachments/assets/760067e4-7547-49fe-ae45-c57afee131b1" width="300" height="350"/>| • Model: Sharp GP2Y0A02YK0F (Long Range IR Sensor) <br> • Detection Range: 20 cm – 150 cm <br> • Output Type: Analog voltage (distance → voltage curve, non-linear) <br> • Operating Voltage: 4.5V – 5.5V (typ. 5V) <br> • Current Consumption: ~33 mA (typical) <br> • Response Time: ~39 ms <br> • Output Voltage Range: ~2.8V (near) to ~0.4V (far) <br> • Dimensions: ~29.5 × 13 × 21.6 mm <br> • Applications: Obstacle detection, distance measurement for navigation, wall following |

Reason for Selection :



## Wiring Diagram
![visual circuit diagram](https://github.com/user-attachments/assets/1ea23832-5366-4719-8e31-d01cfa2f2ce0)


# Obstacle Management(Open challenge round)

## Strategy for Open Challenge round

Open Challenge Round, which is simpler and easier than The Obstacle avoiding Round and does not need very big algorithms, so we decided to use a very simple 'Stategy'. For the Open Challenge round we are using PD for keeping our Robot at a specific distance from the outer and the inner walls, using the IR sensors. The IR sensors help the Robot mantain a safe ditance from the inner and outer boundaries. The IR sensor sends data to the Arduino Nano and than the Arduino using PD sets the direction of the Robot through the Servo.














