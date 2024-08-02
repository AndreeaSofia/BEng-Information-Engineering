# Course Overview

- This README provides a detailed outline of the topics covered in the **Design with Microprocessors** course during the fifth semester of my BEng in _Information Engineering_. This outline is designed to facilitate quick identification of relevant weeks for specific topics, especially when engaging with lab work or other course materials.
- This course covers key topics relating to **Microprocessor Design**, including an overview of **Embedded Systems**, **ARM Cortex Microcontrollers**, **Internal Structure** of the microcontroller, **Clock System Operation**, **GPIO Peripheral and Driver Development**, **Interrupt System**, **HAL programming**, **DMA unit**, **Timer Usage**, **ADC and DAC Peripherals**, **USART Peripheral**, **I2C Peripheral**, **SPI and I2S Peripherals**, and **CAN Peripheral**.

## Weekly Topics

**Week 1:** 
- Overview of embedded systems.
- The Corex ARM microcontrollers.
- STM32CubeIDE, CubeMX, CubeProgrammer environment.
- Documents used: datasheet, reference manual, programming manual.

**Week 2:**
- Internal structure of the microcontroller.
- AHB/APB buses, address map, peripherals, RCC module.

**Week 3:**
- Clock system operation.
- General considerations about oscillators and PLL circuits.
- The connection between the consumption of CMOS circuits and the frequency of the oscillator.

**Week 4:**
- GPIO peripheral; related registers.
- Configuration types (In/Out, Pull Up/Down, PushPull/OpenDrain, Alternative Functionalities)
- GPIO driver development.

**Week 5:**
- The interrupt system, the NVIC controller, and the EXTI controller used at the register level.

**Week 6:**
- Introduction to STM-specific HAL programming: a comparison between GPIO usage and interrupts using registry-level programming and the HAL-API.

**Week 7:**
- The DMA unit.
- Modes of operation and examples of GPIO applications using synchronous, asynchronous, and DMA models.

**Week 8:**
- Types of timers used by STM32 microcontrollers (basic timer, general purpose timer, advanced control timer).

**Week 9:**
- Timers operation modes (Output compare mode, PWM mode, Input capture mode, Encoder interface).

**Week 10:**
- The ADC and DAC peripherals, their operating principles, and usage in the three modes (synchronous, interrupt, DMA).

**Week 11:**
- The USART peripheral, its operating principle, and its usage in all 3 modes using HAL-API.

**Week 12:**
- The I2C peripheral, its operating principle, and its usage in all 3 modes, using the HAL-API programming.

**Week 13:**
- The SPI and I2S peripherals, their operating principles, and usage in the three modes using HAL-API.

**Week 14:**
- The CAN peripheral, its operating principle, and its use in all 3 modes.
- Applications using the HAL-API.

## How to Navigate This Course

Each course directory contains the following subfolders:

- **Courses**: Course notes and suggested bibliography.
- **Seminaries**: Seminary work and suggested bibliography.
- **Laboratories**: Lab work and related materials.
- **ExamPrep**: Exam papers, preparation materials/examples, and grade specifications (including a breakdown of weights for different parts of the final grade, such as course participation, oral exams, seminar activities, laboratory work, projects, etc.).
- **ExtraResources**: Additional exercises and work I did for certain chapters, along with personal tips and tricks, including tools, references, or books that helped me improve my understanding and performance in the subject. These are my own experiences and may not necessarily be useful for others, and were not required or endorsed by the course instructors.
