# Railway Crossing Gate Control System

A robust, fail-safe logic controller designed to automate railway crossing gates, ensuring maximum safety through redundant sensors and fault-tolerant design.

## 🚦 Core Logic Principle

**Gates lower when it's unsafe:**
- Train is approaching **OR**
- Vehicle is detected on the tracks

**Gates raise only when it's safe:**
- No train is approaching **AND**
- No vehicle is on the tracks **AND**
- System confirms all sensors are functional

## 🛠️ Real-World Implementation Features

- **Fail-Safe Design:** Gates default to **closed** during power failures
- **Sensor Fusion:** Combines radar, LiDAR, and inductive loops for reliability
- **2-out-of-3 Voting:** Requires multiple sensor agreement before action
- **Battery Backup:** 72-hour UPS for power outage protection
- **Self-Diagnostics:** Continuous health monitoring and alerting

## 📁 Project Structure

- Exploring the Problem
- Exploring Alternatives
- Evaluating Alternatives
- Engineering Decision
- Planning and Implementing
- Testing and Refinement

## ⚠️ Safety Compliance

Designed to meet IEC 61508 SIL-2 standards for railway applications. Always prioritizes human safety over traffic flow efficiency.
