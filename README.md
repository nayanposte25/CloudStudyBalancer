**CloudSim-Based Cloud Resource Allocation and Performance Analysis**

**Overview**

This project uses the CloudSim simulation framework to model and analyze cloud computing environments. The simulation evaluates the performance of cloud resources, virtual machines (VMs), and task scheduling policies under different workloads.

The objective is to study cloud infrastructure behavior, resource utilization, execution time, and cost efficiency without deploying an actual cloud environment.

**Features**

- Creation of Cloud Data Centers
- Virtual Machine (VM) Provisioning
- Cloudlet (Task) Scheduling
- Resource Allocation Analysis
- Performance Metrics Evaluation
- Cost and Utilization Monitoring
- Scalable Cloud Environment Simulation

**Technologies Used**

- Java
- CloudSim Toolkit
- Eclipse/IntelliJ IDEA
- JDK 8 or later

**Project Structure**

CloudSimProject/
│
├── src/
│   ├── DatacenterCreation.java
│   ├── VMAllocation.java
│   ├── CloudletScheduling.java
│   └── MainSimulation.java
│
├── lib/
│   └── cloudsim.jar
│
└── README.md

**Prerequisites**

Before running the project, ensure the following are installed:

- Java Development Kit (JDK 8+)
- CloudSim Library
- Eclipse IDE or IntelliJ IDEA

**Installation**

1. Clone the repository:

git clone https://github.com/yourusername/cloudsim-project.git

2. Open the project in Eclipse or IntelliJ IDEA.

3. Add the CloudSim library to the project's build path.

4. Build the project.

**Running the Simulation**

Execute the main class:

java MainSimulation

or run the "MainSimulation.java" file directly from the IDE.

**Simulation Workflow**

1. Initialize CloudSim.
2. Create Datacenter.
3. Create Broker.
4. Create Virtual Machines.
5. Create Cloudlets (Tasks).
6. Submit VMs and Cloudlets to Broker.
7. Start Simulation.
8. Collect and Analyze Results.

**Performance Metrics**

The simulation evaluates:

- Cloudlet Execution Time
- VM Utilization
- Resource Allocation Efficiency
- Throughput
- Response Time
- Processing Cost
- Makespan

**Sample Output**

Cloudlet ID    Status     VM ID    Start Time    Finish Time
-----------------------------------------------------------
0              SUCCESS    1        0.1           12.5
1              SUCCESS    2        0.2           10.8

**Applications**

- Cloud Resource Management
- Load Balancing Research
- Task Scheduling Optimization
- Energy-Efficient Computing
- Academic and Research Studies

**Future Enhancements**

- AI-Based Resource Allocation
- Energy-Aware Scheduling
- Multi-Datacenter Support
- Hybrid Cloud Simulation
- Fault-Tolerant Scheduling

[CloudSim Report.pdf](https://github.com/user-attachments/files/29059643/CloudSim.Report.pdf)
