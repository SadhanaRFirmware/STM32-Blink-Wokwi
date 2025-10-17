#  STM32 Blink Simulation (Wokwi)

## Project Overview

This repository hosts a simulated project demonstrating basic **General-Purpose Input/Output (GPIO)** control on an STM32 microcontroller. The code is implemented using the **STM32Cube HAL** library and is fully simulatable in the Wokwi environment, providing a verifiable proof of concept.

### 🔧 Key Features
- **Board Used:** ST Nucleo-C031C6
- **Functionality:** Configures and toggles an onboard LED (LD4) connected to pin PA5.
- **Timing:** LED state is flipped every 500 milliseconds.
- **Implementation:** Utilizes the standard STM32Cube HAL initialization and configuration workflow.

---

## 🚀 Simulation

### Live Demo
You can view and interact with the live simulation directly on the Wokwi platform:
https://wokwi.com/projects/445104084101023745

### Setup & Usage

To run this simulation locally or explore the project:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/SadhanaRFirmware/STM32-Blink-Wokwi.git](https://github.com/SadhanaRFirmware/STM32-Blink-Wokwi.git)
    ```
2.  **Open in Wokwi:**
    * Navigate to your local repository.
    * Upload the project files (`main.c`, `wokwi.toml`, etc.) to the [Wokwi STM32 Simulator](https://wokwi.com/stm32). *Alternatively, simply use the **Live Demo** link above.*
3.  **Local Development:** The provided `main.c` can be integrated into an **STM32CubeIDE** project targeting the ST Nucleo-C031C6 board for physical deployment.

---

## Tools & Technologies

| Tool/Technology | Purpose |
| :--- | :--- |
| **STM32Cube HAL** | Hardware Abstraction Layer used for peripheral configuration. |
| **STM32CubeIDE** | Integrated Development Environment for code compilation and flashing. |
| **Wokwi STM32 Simulator** | Online environment for real-time simulation and verification of the logic. |

---
