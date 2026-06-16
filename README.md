## AxisCore
<img width="643" height="502" alt="Screenshot 2026-06-16 221846" src="https://github.com/user-attachments/assets/633d7529-9c0a-4d39-bf1e-ea35f9a883e3" />

AxisCore is a custom CNC controller platform developed for robotics, motion control, and industrial automation applications. The project was created to provide a reliable and flexible control solution capable of handling multiple motion axes, spindle control, isolated industrial inputs, and communication interfaces within a compact hardware design. The board was designed from the ground up with a strong focus on electrical reliability, noise immunity, maintainability, and future expandability.
## <img width="631" height="417" alt="Screenshot 2026-06-16 221829" src="https://github.com/user-attachments/assets/53815390-c457-4d4f-aab6-446ad93f1949" />![Uploading Screenshot 2026-06-16 220354.png…]()

The controller serves as the central processing unit of a CNC machine or robotic system, coordinating motion commands, monitoring inputs, controlling spindle operations, and managing communication with external devices. Throughout the development process, special attention was given to signal integrity, electrical isolation, and industrial design practices to ensure dependable operation in electrically noisy environments commonly found in CNC machines and automation systems.

Project Overview

AxisCore integrates multiple subsystems into a single controller board capable of supporting motion control and machine automation tasks. The design combines motion interfaces, spindle control circuitry, isolated inputs, communication hardware, and power management into a unified platform. Every subsystem was carefully engineered and validated during the schematic and PCB design stages to create a robust foundation for future firmware development and hardware testing.

The board architecture was organized to simplify wiring, improve accessibility, and allow seamless integration with external motor drivers, spindle systems, sensors, and machine peripherals. The final PCB layout incorporates dedicated grounding strategies, optimized routing paths, and component placement techniques intended to maximize reliability and reduce electrical interference.

Features

AxisCore provides support for multiple stepper driver interfaces, allowing the controller to manage several machine axes simultaneously. The board includes optically isolated digital inputs that help protect sensitive control electronics from external electrical noise and voltage spikes. A dedicated 0–10V spindle control interface enables compatibility with variable frequency drives and industrial spindle systems.

The communication section incorporates electrical isolation to improve system stability and reduce the effects of ground loops. Integrated power regulation circuitry supplies stable operating voltages to onboard electronics while maintaining separation between critical subsystems. Diagnostic indicators and status LEDs assist during development, troubleshooting, and machine operation.

Hardware Design

The hardware was designed using a modular approach in which each major subsystem occupies a dedicated functional area within the schematic and PCB layout. Motion control interfaces, communication circuits, spindle control hardware, isolation circuitry, and power management blocks were separated to improve organization and reduce signal interference.

The PCB was designed as a two layer board with extensive use of ground planes to provide stable return paths and improve electromagnetic compatibility. Routing was carefully optimized to minimize unnecessary crossings, shorten critical signal paths, and maintain clear separation between power and signal sections. Connector placement was selected to simplify machine wiring and improve serviceability.

Development Process

The development of AxisCore followed a complete hardware design workflow beginning with system architecture planning and component selection. Detailed schematic capture was performed to define all electrical connections and subsystem interactions. After schematic completion, extensive review and verification were carried out to ensure proper operation and compatibility between modules.

Once the schematic phase was completed, PCB development began with component placement and mechanical planning. Multiple placement iterations were performed to improve routing efficiency and board organization. The routing stage involved connecting all subsystems while maintaining signal integrity and manufacturability requirements. Final design verification was then performed to ensure readiness for fabrication.

Applications

AxisCore is intended for CNC machines, robotic arms, automated manufacturing equipment, educational robotics platforms, and custom motion control projects. The architecture allows it to serve as a versatile controller for both hobbyist and professional automation systems. Its combination of motion control capabilities, isolated interfaces, and spindle control functionality makes it suitable for a wide range of machine control applications.

Current Status

The schematic design has been completed and verified. The PCB layout has been completed and routed. Manufacturing files are currently being prepared for fabrication. Future stages include prototype assembly, hardware validation, firmware integration, system testing, and machine deployment.

Future Development

Future versions of AxisCore may include advanced communication protocols, closed loop motion control support, additional isolated outputs, enhanced diagnostic features, Ethernet connectivity, CAN bus integration, tool changer interfaces, and expanded machine monitoring capabilities. The current hardware platform was intentionally designed with scalability in mind to support these future enhancements.<img width="643" height="502" alt="Screenshot 2026-06-16 221846" src="https://github.com/user-attachments/assets/0ccfc88c-51a9-4348-854c-003a3444114d" />
<img width="777" height="521" alt="Screenshot 2026-06-16 220520" src="https://github.com/user-attachments/assets/f427eccc-a551-47cf-9926-32649820c4ed" />
