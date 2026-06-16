## AxisCore
<img width="643" height="502" alt="Screenshot 2026-06-16 221846" src="https://github.com/user-attachments/assets/633d7529-9c0a-4d39-bf1e-ea35f9a883e3" />

AxisCore is a custom CNC controller platform developed for robotics, motion control, and industrial automation applications. The project was created to provide a reliable and flexible control solution capable of handling multiple motion axes, spindle control, isolated industrial inputs, and communication interfaces within a compact hardware design. The board was designed from the ground up with a strong focus on electrical reliability, noise immunity, maintainability, and future expandability.
## <img width="631" height="417" alt="Screenshot 2026-06-16 221829" src="https://github.com/user-attachments/assets/53815390-c457-4d4f-aab6-446ad93f1949" />
The controller serves as the central processing unit of a CNC machine or robotic system, coordinating motion commands, monitoring inputs, controlling spindle operations, and managing communication with external devices. Throughout the development process, special attention was given to signal integrity, electrical isolation, and industrial design practices to ensure dependable operation in electrically noisy environments commonly found in CNC machines and automation systems.

## Project Overview

AxisCore integrates multiple subsystems into a single controller board capable of supporting motion control and machine automation tasks. The design combines motion interfaces, spindle control circuitry, isolated inputs, communication hardware, and power management into a unified platform. Every subsystem was carefully engineered and validated during the schematic and PCB design stages to create a robust foundation for future firmware development and hardware testing.
<img width="1058" height="744" alt="Screenshot 2026-06-13 214117" src="https://github.com/user-attachments/assets/435039c9-b247-463d-85b0-8cff61b51772" />


The board architecture was organized to simplify wiring, improve accessibility, and allow seamless integration with external motor drivers, spindle systems, sensors, and machine peripherals. The final PCB layout incorporates dedicated grounding strategies, optimized routing paths, and component placement techniques intended to maximize reliability and reduce electrical interference.

Features

AxisCore provides support for multiple stepper driver interfaces, allowing the controller to manage several machine axes simultaneously. The board includes optically isolated digital inputs that help protect sensitive control electronics from external electrical noise and voltage spikes. A dedicated 0–10V spindle control interface enables compatibility with variable frequency drives and industrial spindle systems.
<img width="704" height="793" alt="Screenshot 2026-06-13 214214" src="https://github.com/user-attachments/assets/bb862419-8dd6-4f8f-9ffd-ef9e14069b15" />
The communication section incorporates electrical isolation to improve system stability and reduce the effects of ground loops. Integrated power regulation circuitry supplies stable operating voltages to onboard electronics while maintaining separation between critical subsystems. Diagnostic indicators and status LEDs assist during development, troubleshooting, and machine operation.

Hardware Design

The hardware was designed using a modular approach in which each major subsystem occupies a dedicated functional area within the schematic and PCB layout. Motion control interfaces, communication circuits, spindle control hardware, isolation circuitry, and power management blocks were separated to improve organization and reduce signal interference.
<img width="1019" height="704" alt="Screenshot 2026-06-14 124812" src="https://github.com/user-attachments/assets/27299daf-345d-4460-8725-86d0da01f3f5" />

The PCB was designed as a two layer board with extensive use of ground planes to provide stable return paths and improve electromagnetic compatibility. Routing was carefully optimized to minimize unnecessary crossings, shorten critical signal paths, and maintain clear separation between power and signal sections. Connector placement was selected to simplify machine wiring and improve serviceability.

Development Process

The development of AxisCore followed a complete hardware design workflow beginning with system architecture planning and component selection. Detailed schematic capture was performed to define all electrical connections and subsystem interactions. After schematic completion, extensive review and verification were carried out to ensure proper operation and compatibility between modules.
<img width="605" height="442" alt="Screenshot 2026-06-16 220354" src="https://github.com/user-attachments/assets/95492bed-9f3f-475a-bb22-55ba52628901" />

Once the schematic phase was completed, PCB development began with component placement and mechanical planning. Multiple placement iterations were performed to improve routing efficiency and board organization. The routing stage involved connecting all subsystems while maintaining signal integrity and manufacturability requirements. Final design verification was then performed to ensure readiness for fabrication.

Applications

AxisCore is intended for CNC machines, robotic arms, automated manufacturing equipment, educational robotics platforms, and custom motion control projects. The architecture allows it to serve as a versatile controller for both hobbyist and professional automation systems. Its combination of motion control capabilities, isolated interfaces, and spindle control functionality makes it suitable for a wide range of machine control applications.

## BOM

| Component        | Purpose                                                                                                                                                                        | Quantity | Total Cost (USD) | Distributor | Read                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ---------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| ESP32-S3-WROOM-1 | Main controller responsible for CNC motion control, communication, spindle management, and machine I/O                                                                         | 1        | $10.48           | DigiKey     | Manually soldered to reduce assembly costs and provide flexibility during development                                                         |
| Custom PCBA      | Complete AxisCore CNC controller board including isolated inputs, RS485 communication, spindle control, power regulation, protection circuitry, and external driver interfaces | 1        | $182.00          | JLCPCB      | Serves as the core hardware platform for CNC and automation applications, integrating all control and interface circuitry into a single board |
| **FINAL TOTAL**  |                                                                                                                                                                                |          | **$192.48**      |             | **Approx INR Cost: ₹16,500**                                                                                                                  |

Future Development

Future versions of AxisCore may include advanced communication protocols, closed loop motion control support, additional isolated outputs, enhanced diagnostic features, Ethernet connectivity, CAN bus integration, tool changer interfaces, and expanded machine monitoring capabilities. The current hardware platform was intentionally designed with scalability in mind to support these future enhancements.
