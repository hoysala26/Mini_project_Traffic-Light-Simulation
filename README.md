# 🚦 Traffic Light Simulation (Java)

This is a simple **Java program** that simulates a traffic light system using **multithreading** and **synchronization**.

---

## 🧠 Description

- The simulation has three lights: **RED**, **GREEN**, and **YELLOW**.  
- Each light runs in its own **thread**.  
- Threads take turns based on the current light color.  
- Synchronization is handled using `synchronized`, `wait()`, and `notifyAll()` methods.

---

## 🧩 Classes

1. **TrafficSignal** – Controls which light is ON and manages synchronization.  
2. **TrafficLightThread** – Represents each light (thread).  
3. **TrafficLightSimulation** – Main class that starts the simulation.

---

## ⚙️ How to Run

1. Compile the Java files:
   ```bash
   javac TrafficSignal.java TrafficLightThread.java TrafficLightSimulation.java
