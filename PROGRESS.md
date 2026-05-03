# 🚁 UAV Embedded Systems — Learning Journal

**Board:** STM32F429I-DISC1  
**Track:** UAV / Defence Aerospace (UK)  
**Goal:** Career switch into embedded systems for UAV/drone industry  
**Target Companies:** BAE Systems · QinetiQ · Blue Bear Systems · Windracers · Cobham  

---

## 📊 Overall Progress

| Stage | Topic | Status | Completed |
|-------|-------|--------|-----------|
| 1 | STM32 Bare-Metal Basics | 🔄 In Progress | 0/6 |
| 2 | Sensor Interfacing | ⏳ Not Started | 0/6 |
| 3 | FreeRTOS on STM32 | ⏳ Not Started | 0/6 |
| 4 | Flight Control Theory | ⏳ Not Started | 0/6 |
| 5 | Communication & GCS | ⏳ Not Started | 0/5 |
| 6 | Industry & Safety | ⏳ Not Started | 0/6 |

**Legend:** ✅ Complete · 🔄 In Progress · ⏳ Not Started

---

## 🗂️ Stage Details

### Stage 1 — STM32 Bare-Metal Basics (2–3 weeks)
> UAV relevance: ESCs are driven by PWM signals — fundamental to all flight hardware

- [ ] Setup STM32CubeIDE / VS Code + OpenOCD + GDB
- [ ] Blink LED via direct register access (no HAL)
- [ ] UART printf debugging setup
- [ ] Understand RCC clock tree & PLL (180MHz)
- [ ] Timer configuration & PWM generation for ESC signals
- [ ] Read STM32F429 reference manual key sections

**Notes:**

---

### Stage 2 — Sensor Interfacing (3–4 weeks)
> UAV relevance: IMU fusion is the heart of any flight controller

- [ ] SPI → Read L3GD20 gyroscope on-board
- [ ] I2C → Read accelerometer & magnetometer
- [ ] Understand sensor datasheets & register maps
- [ ] Sensor calibration & noise filtering
- [ ] Complementary filter for roll/pitch estimation
- [ ] Intro to Kalman Filter theory & implementation

**Notes:**

---

### Stage 3 — FreeRTOS on STM32 (3 weeks)
> UAV relevance: PX4 and Betaflight both use RTOS architectures

- [ ] Port FreeRTOS to STM32F429
- [ ] Create sensor task & control task
- [ ] Task priorities for real-time guarantees
- [ ] Queues between sensor reading & control loop
- [ ] Achieve stable 1kHz control loop timing
- [ ] Semaphores & mutexes for resource sharing

**Notes:**

---

### Stage 4 — Flight Control Theory (4–5 weeks)
> UAV relevance: This is the core of a real flight controller

- [ ] PID controller implementation in C from scratch
- [ ] Cascaded PID (rate loop + angle loop)
- [ ] Quadcopter X-frame motor mixing algorithm
- [ ] PWM → DSHOT protocol implementation
- [ ] RC receiver decoding — PPM, SBUS, DSM2
- [ ] Failsafe logic & arming/disarming sequence

**Notes:**

---

### Stage 5 — Communication & GCS (3 weeks)
> UAV relevance: Industry standard for drone telemetry

- [ ] MAVLink protocol implementation
- [ ] Telemetry over UART
- [ ] GPS NMEA parsing / uBlox UBX protocol
- [ ] Build simple Ground Control Station interface
- [ ] Bidirectional command & telemetry link

**Notes:**

---

### Stage 6 — Industry & Safety (2–3 weeks)
> UAV relevance: Required knowledge for UK defence roles

- [ ] DO-178C aviation software standard awareness
- [ ] Redundancy design patterns
- [ ] Failsafe & fault-tolerant architecture
- [ ] Study PX4 / ArduPilot source code
- [ ] Open-source contribution to PX4 or ArduPilot
- [ ] UK Security Clearance application

**Notes:**

---

## 📅 Session Log

<!-- Copy from your web tracker after each session -->

### Template
```
## DD Mon YYYY
- **Stage/Topic:** 
- **What I learned:**
- **Code written:** 
- **Blockers/Questions:**
- **Next session goal:**
- **GitHub commit:** yes / no — [link]
```

---

## 🏗️ Projects Built

| Project | Stage | Description | Repo Link |
|---------|-------|-------------|-----------|
| LED Blink (register level) | S1 | | |
| UART Debug Logger | S1 | | |
| Gyroscope Reader | S2 | | |
| Attitude Estimator | S2 | | |
| RTOS Sensor System | S3 | | |
| PID Controller | S4 | | |
| Mini Flight Controller | S4 | | |
| MAVLink Telemetry | S5 | | |

---

## 🎯 Career Milestones

- [ ] GitHub repo created with first commit
- [ ] STM32 toolchain setup complete
- [ ] First bare-metal LED blink (no HAL)
- [ ] Gyroscope data reading working
- [ ] Mini flight controller project on GitHub
- [ ] First PX4/ArduPilot open-source contribution
- [ ] LinkedIn updated with embedded skills
- [ ] SC Clearance application started
- [ ] First UAV role application sent

---

## 🔧 Resources & References

### Datasheets (bookmark these)
- [STM32F429 Reference Manual](https://www.st.com/resource/en/reference_manual/rm0090-stm32f405415-stm32f407417-stm32f427437-and-stm32f429439-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)
- [L3GD20 Gyroscope Datasheet](https://www.st.com/resource/en/datasheet/l3gd20.pdf)
- [STM32F429I-DISC1 User Manual](https://www.st.com/resource/en/user_manual/um1670-discovery-kit-with-stm32f429zi-mcu-stmicroelectronics.pdf)

### Open Source Flight Stacks
- [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot)
- [ArduPilot](https://github.com/ArduPilot/ardupilot)
- [Betaflight](https://github.com/betaflight/betaflight)

### UK Industry
- [UKESF — UK Electronics Skills Foundation](https://www.ukesf.org)
- [DSEI London](https://www.dsei.co.uk)

---

## 💷 UK Salary Targets

| Level | UAV/Defence |
|-------|-------------|
| Junior (0–2 yrs) | £38–50k |
| Mid (2–5 yrs) | £55–75k |
| Senior (5+ yrs) | £75–95k+ |

---

*Last updated: — · Board: STM32F429I-DISC1 · Track: UK UAV/Defence*
