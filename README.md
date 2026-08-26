# Automatic Power Factor Correction (APFC) System using MATLAB Simulink

## 📌 Project Overview

This project presents the design and simulation of an **Automatic Power Factor Correction (APFC) system** using **MATLAB/Simulink**.

The system is designed for an industrial three-phase electrical load with a low initial power factor. The APFC controller automatically switches capacitor-bank stages according to the reactive power demand of the load to improve the power factor toward a predefined target value.

The simulation demonstrates how automatic capacitor switching can reduce reactive power demand, improve power factor, and reduce electrical losses in an industrial distribution system.

---

## 🎯 Objectives

* Design an Automatic Power Factor Correction system using MATLAB Simulink.
* Improve the power factor of an industrial electrical load.
* Automatically control capacitor-bank switching based on reactive power demand.
* Maintain the power factor close to the desired reference value.
* Analyze the effect of power-factor correction on current and system losses.
* Demonstrate the practical application of APFC in industrial power systems.

---

## ⚙️ System Specifications

| Parameter            |                        Value |
| -------------------- | ---------------------------: |
| System               |               Three-Phase AC |
| Supply Voltage       |                        415 V |
| Frequency            |                        50 Hz |
| Industrial Load      |                       500 kW |
| Initial Power Factor |                         0.72 |
| Target Power Factor  |                         0.95 |
| Capacitor Stages     |                            6 |
| Capacitor Rating     |            50 kVAR per stage |
| Switching Method     | Automatic / Staged Switching |
| Switching Delay      |           Approximately 30 s |

---

## 🔧 Software Used

* **MATLAB**
* **Simulink**
* **Simscape Electrical / Specialized Power Systems**

---

## 🏗️ System Architecture

The APFC system consists of the following major sections:

1. Three-phase AC supply
2. Industrial electrical load
3. Voltage and current measurement
4. Power-factor / reactive-power measurement
5. APFC controller
6. Capacitor-bank switching logic
7. Multiple capacitor stages
8. Feedback and monitoring system
9. Scope blocks for simulation results

The controller continuously monitors the electrical conditions and determines the required capacitor compensation. Capacitor stages are switched automatically to supply the required reactive power.

---

## 🔄 Working Principle

The industrial load initially operates at a low power factor of approximately **0.72**, resulting in a higher reactive current.

The APFC controller measures the electrical parameters of the system and compares the measured power factor with the target value of **0.95**.

When additional reactive-power compensation is required, the controller switches appropriate capacitor stages into the circuit.

The capacitor bank supplies leading reactive power, which compensates for the lagging reactive power consumed by the industrial load.

As a result:

**Lower Reactive Power → Lower Line Current → Improved Power Factor → Reduced I²R Losses**

The capacitor stages are switched according to the required compensation, allowing the system to maintain the power factor near the desired reference.

---

## 📊 Simulation Results

The simulation demonstrates significant improvement in system performance after applying automatic power-factor correction.

### Power Factor Improvement

The initial power factor is approximately:

**PF ≈ 0.72**

The APFC system is designed to improve the power factor toward:

**Target PF = 0.95**

Add your Simulink power-factor waveform here:

![Power Factor Improvement](images/pf_waveform.png)

*Figure: Power factor response before and after APFC operation.*

---

## 🔌 Capacitor Bank Switching

The system uses six capacitor stages, with each stage rated at approximately **50 kVAR**.

The APFC controller automatically switches these capacitor stages according to the reactive-power requirement of the load.

Add your capacitor switching waveform here:

![Capacitor Switching](images/capacitor_switching.png)

*Figure: Automatic staged capacitor-bank switching response.*

---

## 🖥️ Simulink Model

The complete MATLAB Simulink model contains the electrical load, measurement blocks, APFC control logic, capacitor-bank stages, switching system, and monitoring scopes.

Add your main Simulink screenshot here:

![APFC Simulink Model]([Uploading Screenshot 2026-08-26 at 8.59.25 PM.png…]()
)

*Figure: Complete Automatic Power Factor Correction Simulink model.*

---

## 📉 Loss Reduction

Power-factor correction reduces the current required to deliver the same active power.

The estimated I²R distribution losses in the simulation are:

| Condition             | Estimated I²R Loss |
| --------------------- | -----------------: |
| Before APFC           |            18.4 kW |
| After APFC            |            10.6 kW |
| Approximate Reduction |                42% |

Add your loss-comparison result here:

![Loss Reduction](images/line_loss_comparison.png)

*Figure: Estimated reduction in distribution losses after power-factor correction.*

---

## ✅ Key Outcomes

* Improved power factor from approximately **0.72 toward 0.95**.
* Automatic switching of capacitor-bank stages.
* Reduced reactive-power demand from the supply.
* Reduced line current.
* Estimated **~42% reduction in I²R distribution losses**.
* Demonstration of an industrial APFC control strategy using MATLAB Simulink.

---

## 🏭 Applications

APFC systems are commonly used in:

* Manufacturing industries
* Industrial motor loads
* Pumping stations
* HVAC systems
* Process industries
* Large commercial buildings
* Industrial distribution networks
* Power-factor penalty reduction systems

---

## 🚀 Future Improvements

The model can be further developed by:

* Adding harmonic analysis and THD measurement.
* Implementing detuned capacitor banks.
* Adding real-time monitoring.
* Developing an automatic alarm system for abnormal conditions.
* Implementing the controller on a PLC or microcontroller.
* Developing an IoT-based power monitoring system.
* Comparing APFC performance with different industrial load profiles.

---

## ▶️ How to Run

1. Install **MATLAB** with the required Simulink/Simscape Electrical components.
2. Clone or download this repository.
3. Open MATLAB.
4. Open the `APFC_Model.slx` file.
5. Run the simulation.
6. Observe the power factor, capacitor switching, current, voltage, and other measured parameters using the Scope blocks.
7. Analyze the system response before and after APFC operation.

---

## 🧠 Skills Demonstrated

* MATLAB
* Simulink
* Power Systems
* Power Factor Correction
* Reactive Power Compensation
* Capacitor Bank Switching
* Industrial Load Modelling
* Control System Design
* Electrical System Simulation
* Simulation Result Analysis

---

## 📌 Project Type

**Electrical Engineering | Power Systems | MATLAB/Simulink | Industrial Automation**

---

## 👨‍💻 Author

**Azmeera Bhuvaneshwar**

Electrical Engineering Student

---

## ⭐ Project Highlights

> **Designed and simulated an Automatic Power Factor Correction system for a 500 kW, 415 V three-phase industrial load, using staged capacitor-bank switching to improve the power factor toward 0.95 and reduce estimated I²R distribution losses.**

