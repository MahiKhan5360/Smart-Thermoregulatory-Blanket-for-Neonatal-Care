System Overview
The Smart Thermoregulatory Blanket includes:
Hardware:
4–6 NTC thermistors for temperature sensing (±0.1°C accuracy).

Kapton heating pads (5V, 10W) for uniform warming.

STM32L4 MCU (ARM Cortex-M4) for PID control.

BLE module (Bluetooth 5.0) for wireless communication.

0.96-inch OLED display for local status.

3.7V 2000 mAh battery or 5V 2W solar panel.

Software:
Embedded C firmware with FreeRTOS for real-time control.

Mobile app (Android/iOS) for remote monitoring and alerts.

Interfaces:
OLED display and buttons for local interaction.

BLE GATT profile for app communication.

USB-C for charging.

Key Features
Maintains 36.5–37.5°C with 1 Hz sampling and 60-second heating response.

Alerts for temperature deviations (<36.3°C or >37.7°C) via display and app.

Logs 1 hour of data on MCU, 7 days on app.

Safety features: 40°C max heating limit, fail-safe shutdown.

Methodology
The specification development follows these steps:
Requirements Gathering: Engage stakeholders (neonatologists, caregivers) to define needs.

System Analysis: Specify functional (e.g., temperature control) and non-functional (e.g., power, safety) requirements.

Specification Drafting: Create a structured document with diagrams and traceability matrix.

Validation: Review with stakeholders and test against use cases.

Tools:
STM32CubeIDE for firmware development.

Draw.io for system diagrams.

Kotlin/Swift for mobile app.

