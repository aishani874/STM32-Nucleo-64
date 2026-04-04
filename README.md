# STM32-Nucleo-64
1. Project Overview
    This project establishes a high-speed data acquisition and processing framework on the STM32 Nucleo-F446RE. It serves as the "Base Work" for     future Edge AI (TinyML) applications by providing a reliable pipeline for sensor data and real-time telemetry.

2. Technical Features & Performance
    Core Speed: Configured the ARM Cortex-M4 CPU to 180 MHz for maximum processing power.

    Data Pipeline: Implemented I2C for sensor communication and UART (115200 bps) for stable data monitoring.

    Low Latency: Optimized GPIO interrupts to ensure fast response times for hardware triggers and OLED updates.

    Memory Efficiency: Used only 5% of Flash and 3% of SRAM, leaving over 90% of resources available for future AI model storage.

3. Future Roadmap
    The next phase of this project will integrate Machine Learning directly onto the board:

    Data Logging: Using the current UART bridge to collect training datasets.

    Model Training: Developing a lightweight Neural Network on a PC.

    On-Device Inference: Quantizing the model and deploying it via STM32Cube.AI for real-time local decision-making.
Tools Used
    Hardware: STM32 Nucleo-F446RE Board

    Software: STM32CubeIDE & STM32CubeMX

    Language: C (HAL Drivers)
