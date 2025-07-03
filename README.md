# Operating System Simulator

This project is a simulation of key Operating System components such as process scheduling, memory partitioning, and kernel/user-level request handling. It is developed using the **Processing** environment (Java-based) and emphasizes modular design and visual simulation.

---

## 💡 Features

- Process Control Block (PCB) management  
- Partition-based memory allocation  
- Simulation of user and kernel processes  
- Interactive visual simulation using Processing  
- Request queuing and response handling  
- Scheduling algorithms (e.g., FIFO, Round Robin)

---

## 🛠 Technologies Used

- **Language:** Java (Processing PDE format)  
- **Environment:** [Processing IDE](https://processing.org/download/)  
- **Design:** Object-Oriented Programming (OOP)

---

## 📁 File Descriptions

| File                  | Description                                       |
|-----------------------|---------------------------------------------------|
| `Algorithms.pde`      | Core scheduling and simulation algorithms         |
| `Hardware.pde`        | Simulated hardware layer (CPU, memory, timers)    |
| `KernelProcess.pde`   | Kernel-level request handling logic               |
| `OperatingSys.pde`    | OS orchestration logic                            |
| `OSCW2024.pde`        | Entry point for simulation (main sketch file)     |
| `Partition.pde`       | Logic for managing memory partitions              |
| `PCB.pde`             | Defines process control blocks                    |
| `ProcessStats.pde`    | Handles process performance/statistics tracking   |
| `Request.pde`         | User/system request representation and logic      |
| `Simulator.pde`       | Coordinates visual and logical simulation steps   |
| `UserProcess.pde`     | Defines user-level processes and actions          |
| `sketch.properties`   | Specifies `main=OSCW2024.pde` for the IDE         |

---

## ▶️ How to Run

1. Download and install [Processing IDE](https://processing.org/download/)  
2. Open the `src/` folder inside Processing  
3. Ensure `sketch.properties` contains:  
main=OSCW2024.pde

yaml
Copy code
4. Click the **Run** button

---

## 📜 License

This project is released under the **MIT License**. You are free to use, modify, and distribute it with attribution.

---

## 🙋 Author

**Ertrim Grabanica**
**Marios Zouzounis**  
**Guri Gacaferi**  
**Ajan Abazi**  
BSc Computer Science – University of York Europe Campus  
2024  
