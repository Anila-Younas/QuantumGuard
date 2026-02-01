# Quantum Guard

Quantum Guard is a web-based Operating Systems simulator designed to help students understand and visualize core OS concepts through interactive and practical demonstrations. The project focuses on simulating fundamental algorithms and mechanisms commonly taught in operating systems courses.

The application is built using Node.js and Express, providing a modular backend with clear API endpoints and an interactive frontend for visualization. It runs locally and is intended purely for educational and academic use.

## Features

### CPU Scheduling Algorithms
The CPU Scheduling module supports the following algorithms:

- First Come First Served (FCFS)  
  Endpoint: `/cpu_scheduling/fcfs`

- Shortest Job First (SJF)
  - Non-preemptive: `/cpu_scheduling/sjf-nonpreemptive`
  - Preemptive: `/cpu_scheduling/sjf-preemptive`

- Round Robin Scheduling  
  Endpoint: `/cpu_scheduling/round_robin`

These algorithms allow users to observe scheduling behavior, waiting time, turnaround time, and execution order.

### Deadlock Detection and Prevention
- Banker’s Algorithm simulation for safe resource allocation
- Demonstrates deadlock detection and resolution strategies

### Additional Operating System Simulations

- Memory Management
- Disk Scheduling
- Page Replacement Algorithms
- Process Synchronization Problems
- File Allocation Techniques
- Socket Programming Demonstrations

### Advanced Implementations

- Multilevel Queue Scheduling
- Sleeping Barber Problem
- Second Chance Page Replacement Algorithm

### Interactive Terminal Interface
Quantum Guard includes a terminal-based GUI that simulates system calls, allowing users to interact with OS-level operations in a controlled environment.

### Real-Time Communication
Socket programming concepts are demonstrated using real-time chat functionality implemented with Socket.IO.

## Technology Stack

- Backend: Node.js, Express.js
- Frontend: HTML, CSS, JavaScript
- Real-Time Communication: Socket.IO
- Templating Engine: EJS / Jade
- Environment: Localhost

## Installation and Setup

1. Clone the repository:
```

git clone https://github.com/Anila-Younas/QuantumGuard

```

2. Navigate to the project directory:
```

cd quantum-guard

```

3. Install dependencies:
```

npm install

```

4. Start the server:
```

npm start

```

5. Open your browser and visit:
```

[http://localhost:3000](http://localhost:3000)

```

## Usage

Quantum Guard is intended for learning and demonstration purposes. Users can interact with different OS modules, input custom data, and observe how algorithms behave under various conditions.

## Project Purpose

This project was developed as part of an Operating Systems course to provide a practical and visual understanding of OS concepts that are often difficult to grasp through theory alone.


