
# **Proposal for Experimental Setup: Demonstrating Pipe Friction and Venturi Meter using Wind Tunnel**

 **Submitted to:** Vellore Institute of Technology Chennai\
 **Submitted by:**  K L Mithunvel, Kiran T, Mirfaq M, Kishore Priyan S, Ashwin T E.
 **Date:**  
 **Department:** SMEC

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

* ( P₁,  P₂ ) \= pressure at different points  
* ( v₁, v₂ ) \= velocities at different points  
* ( ρ ) \= fluid density

We can calculate the airflow rate in the wind tunnel by measuring pressure differences.

Applications of the Venturi meter include:

* Flow meters  
* Fuel injection systems  
* Industrial process controls  
* Analysis of pressure-velocity relationships in airflow

### **2.2 Pipe Friction and the Darcy-Weisbach Equation**

Friction in pipes causes energy losses due to fluid-wall interactions, quantified by the Darcy-Weisbach equation:

ΔP = f⋅(L/D)⋅(ρv²/2)

Where:

* ( ΔP ) \= pressure drop due to friction  
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
* Data-driven analysis capabilities using automated measurement systems

## **5\. Budget Proposal**

### **Estimated Costs**

| S.No | Components | Description | Quantity |Cost (INR)|
| :---- | :---- | :---- | :----| :---- |
| 1 | Venturi Tube | Custom-made for wind tunnel and Fittings |  | 7,000.00 - 10,000.00 |
| 2 | Pressure Sensors | MPX5010DP differential pressure sensors | 3 | 4,980.00 - 6,000.00 |
| 3 | Raspberry Pi 4/5 | Data processing and logging system | 1 | 5,599.00 - 6,599.00|
| 4 | Arduino Nano | Data Conversion | 1 | 290.00 - 400.00 |
| 5 | SD card | Data Storage | 1 | 600.00 - 800.00 |
| 6 | Software | Python, data logging tools | 1 | 0.00 |
| 7 | Miscellaneous | Wiring, fittings, additional supplies | NA | 1000.00 |

**Total Estimated Cost:** 19,469.00 - 24,799.00

## **6\. Funding Justification**

* Enhances the fluid mechanics laboratory with modern experimental capabilities  
* Supports interdisciplinary applications across mechanical, aerospace, and civil engineering  
* Provides long-term utility for multiple fluid mechanics experiments  
* Strengthens the institution's research and learning capabilities

## **7\. Project Team**

* Project Lead: K L Mithunvel  
* Team Members: Kiran T, Mirfaq M, Kishore Priyan S, Ashwin T E.  
* Faculty Advisor: Dr.Vinayagamurthy.
* Technical Support: AUTOVIT Club.

## **8\. Conclusion**

This project bridges theoretical fluid mechanics and practical applications through an interactive, real-time experimental setup. By integrating advanced sensor technology and data analysis tools, the setup will provide valuable insights into Venturi flow measurement and pipe friction losses.

We request funding and approval from the college to implement this project, which will enhance the learning experience in fluid dynamics and contribute to the institution's research capabilities.




