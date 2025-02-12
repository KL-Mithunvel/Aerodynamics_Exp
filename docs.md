
# **Proposal for Experimental Setup: Demonstrating Pipe Friction and Venturi Meter using Wind Tunnel**

 **Submitted to:** Vellore Institute of Technology Chennai\
 **Submitted by:** \[Your Name / Team Name\]  
 **Date:** \[Date of Submission\]  
 **Department:** \[Your Department Name\]

## **1\. Introduction**

### **1.1 Overview**

Fluid dynamics plays a crucial role in engineering applications, including aerodynamics, hydraulics, and industrial fluid transport. Two fundamental principles in fluid mechanics—Bernoulli's Principle (demonstrated via the Venturi meter) and pipe friction—are essential for understanding fluid behaviour under different conditions.

This project proposes developing a hands-on experimental setup to study Bernoulli's principle using a Venturi meter and pressure losses due to friction in pipes, utilizing an existing wind tunnel for controlled airflow.

### **1.2 Objectives**

Our project aims to:

* Experimentally verify Bernoulli's principle using a Venturi meter inside the wind tunnel  
* Study frictional losses in pipe flow and measure pressure drop across different pipe sections  
* Develop a real-time data acquisition system using Raspberry Pi 4 and sensors for measuring pressure, velocity, and friction losses  
* Enable students to visualise airflow and validate theoretical fluid dynamics concepts through direct experimentation

## **2\. Theory and Background**

### **2.1 Venturi Meter and Bernoulli's Principle**

A Venturi meter measures the fluid flow rate through a pipe. It incorporates a narrowing section that increases velocity and decreases pressure, as described by Bernoulli's equation:

P₁ + ½ρv₁² = P₂ + ½ρv₂²

Where:

* ( P\_1, P\_2 ) \= pressure at different points  
* ( v\_1, v\_2 ) \= velocities at different points  
* ( \\rho ) \= fluid density

We can calculate the airflow rate in the wind tunnel by measuring pressure differences.

Applications of the Venturi meter include:

* Flow meters  
* Fuel injection systems  
* Industrial process controls  
* Analysis of pressure-velocity relationships in airflow

### **2.2 Pipe Friction and the Darcy-Weisbach Equation**

Friction in pipes causes energy losses due to fluid-wall interactions, quantified by the Darcy-Weisbach equation:

\[ \\Delta P \= f \\cdot \\frac{L}{D} \\cdot \\frac{\\rho v^2}{2} \]

Where:

* ( \\Delta P ) \= pressure drop due to friction  
* ( f ) \= friction factor  
* ( L ) \= pipe length  
* ( D ) \= pipe diameter  
* ( v ) \= fluid velocity

Understanding pipe friction is crucial for designing efficient piping systems for water, gas, and industrial fluid transport.

## **3\. Experimental Approach**

### **3.1 System Integration with Wind Tunnel**

We will integrate our setup with the existing wind tunnel in the college laboratory, providing a controlled environment for airflow experiments and ensuring consistent, measurable conditions.

### **3.2 Setup Components**

1. Venturi Meter Experiment:  
   * Venturi tube placed inside the wind tunnel  
   * Pressure taps at inlet, throat, and outlet for pressure differential measurements  
   * MPX5010DP differential pressure sensors connected to Raspberry Pi 4  
2. Pipe Friction Experiment:  
   * Long pipe section with pressure sensors at regular intervals  
   * Multiple pipe materials (PVC, copper) for comparative friction loss analysis  
   * Velocity measurements using an anemometer  
3. Real-time Data Collection & Analysis:  
   * Raspberry Pi 4 for data collection and logging  
   * Python-based software for generating live pressure-velocity graphs

### **3.3 Flow Visualization**

* Implementation of smoke generators or laser sheet visualization to demonstrate air movement  
* Visual analysis of turbulence, laminar flow, and pressure variations

## **4\. Expected Outcomes**

* Experimental validation of Bernoulli's Principle through pressure-velocity data comparison  
* Comprehensive understanding of pipe friction through pressure drop measurements  
* Enhanced hands-on learning experience for students  
* Data-driven analysis capabilities using automated measurement systems

## **5\. Budget Proposal**

### **5.1 Estimated Costs**

| S.No | Components | Description | Cost (INR) |
| :---- | :---- | :---- | :---- |
| 1 | Venturi Tube | Custom-made for wind tunnel |  |
| 2 | Pipes | PVC and Copper pipes (various diameters) |  |
| 3 | Pressure Sensors | MPX5010DP differential pressure sensors |  |
| 4 | Anemometer | Air velocity measurement device |  |
| 5 | Raspberry Pi 4 | Data processing and logging system |  |
| 6 | Smoke Generator | Flow visualization equipment |  |
| 7 | Mounting Hardware | Tube and pipe fixtures |  |
| 8 | Software | Python, data logging tools |  |
| 9 | Miscellaneous | Wiring, fittings, additional supplies |  |

**Total Estimated Cost:** XXXX

## **6\. Funding Justification**

* Enhances the fluid mechanics laboratory with modern experimental capabilities  
* Supports interdisciplinary applications across mechanical, aerospace, and civil engineering  
* Provides long-term utility for multiple fluid mechanics experiments  
* Strengthens the institution's research and learning capabilities

## **7\. Implementation Plan**

### **7.1 Project Timeline**

| Phase | Task | Duration |
| :---- | :---- | :---- |
| Phase 1 | Design and Procurement |  |
| Phase 2 | Fabrication and Assembly |  |
| Phase 3 | Sensor Integration and Testing |  |
| Phase 4 | Calibration and Data Collection |  |
| Phase 5 | Analysis and Documentation |  |
| Total | Project Completion |  |

### **7.2 Project Team**

* Project Lead: K L Mithunvel  
* Team Members: Kiran T, Mirfaq M, Kishore Priyan S, Ashwin T E.  
* Faculty Advisor: \Vin 
* Technical Support: \[Lab Technician or Support Staff\]

## **8\. Conclusion**

This project bridges theoretical fluid mechanics and practical applications through an interactive, real-time experimental setup. By integrating advanced sensor technology and data analysis tools, the setup will provide valuable insights into Venturi flow measurement and pipe friction losses.

We request funding and approval from the college to implement this project, which will enhance the learning experience in fluid dynamics and contribute to the institution's research capabilities.

## **9\. References**
