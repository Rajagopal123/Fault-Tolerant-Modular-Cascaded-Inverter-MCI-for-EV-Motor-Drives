# Fault-Tolerant-Modular-Cascaded-Inverter-MCI-for-EV-Motor-Drives
“Designed a fault-tolerant modular cascaded inverter (5/7/9-level) for EV motor drives using H-bridge topology and hysteresis current control. Implemented fault detection and isolation to maintain operation under module failure, achieving THD reduction (~46.9%→27.9%) and stable PMSM performance.”


## Overview

This project presents a fault-tolerant Modular Cascaded Inverter (MCI) designed for PMSM-based EV motor drives. The system ensures continuous operation even under module failure using real-time fault detection and isolation.

## Key Features

* Multilevel inverter (5, 7, 9-level configurations)
* Cascaded H-bridge topology
* Fault detection and isolation mechanism
* Hysteresis Current Control (HCC) for PMSM
* Improved waveform quality and reduced THD

## System Architecture

* Each phase consists of multiple H-bridge modules
* Independent DC sources per module
* Modular structure enables scalability and fault bypass

## Control Strategy

* Hysteresis Current Control (HCC) for fast dynamic response
* Maintains current within tolerance band
* Ensures stable torque and speed in PMSM

## Fault-Tolerant Operation

* Real-time monitoring of voltage/current
* Faulty H-bridge module is detected and isolated
* System continues operation in reduced-level mode

## Simulation Cases

1. 5-Level MCI (Normal Operation)
2. 9-Level MCI (Improved THD)
3. Fault Condition (Module Isolation)

## Results

* THD reduced from ~46.9% (5-level) to ~27.9% (9-level)
* Fault condition increases THD (~68%) but maintains operation
* PMSM speed remains stable under both normal and fault scenarios

## Tools Used

* MATLAB/Simulink
* Power Electronics Modeling
* PMSM Drive Simulation

## Key Insight

Modular inverter architecture enables fault resilience, allowing EV drives to operate safely without complete shutdown, improving reliability and system robustness.

## How to Run

1. Open Simulink model
2. Select inverter level (5/7/9)
3. Introduce fault condition (optional)
4. Observe voltage, THD, and motor speed response
