# The Humidifier Project: Integrated ECAD/MCAD Design
A study in miniaturized appliance design and power distribution

# Project Overview 
***This project focuses on the end-to-end development of innovative, small-scale humidifiers (1:6 scale). The goal is to blend aesthetic "toy-like" form factors with professional-grade engineering, specifically focusing on ECAD/MCAD co-design using Autodesk Fusion 360.***
<img width="1920" height="850" alt="Humidifier Assembly" src="https://github.com/user-attachments/assets/183350fd-7f4b-468f-8d59-3b978481b450" />**Hibachi Grill CAD Model**
<img width="1920" height="850" alt="Humidifier Section Analysis" src="https://github.com/user-attachments/assets/78e2e76c-311b-40b9-b316-311770287eed" />**Section Analysis of Hibachi Grill CAD Model**
<img width="1920" height="850" alt="Hibachi Grill Wireframe" src="https://github.com/user-attachments/assets/e98f6bfb-11fe-438e-91c6-7c62f3f5d724" /> **MCAD & ECAD Assembly**

# Technical Specifications & Features
The project explores multiple power and control configurations to suit different user needs:

  **Option A: USB-Powered (Current Revision)**
<img width="1920" height="850" alt="Humidifier (USB Only) Circuit" src="https://github.com/user-attachments/assets/70c5e551-3140-4dc5-90eb-f64ab6553b2d" />
    -Direct Power: Optimized for 5V USB input.

    -User Interface: Integrated physical toggle switch for post-plug-in control.

    -Circuit Protection: Includes a Schottky diode to prevent reverse current feedback, ensuring the longevity of the source port.

  **Option B: Li-Po Battery Integrated (Future Revision)**

    -Remote Operation: Designed for portability and remote control.

    -Safety Systems: Will feature a dedicated battery protection circuit (BMS) for overcharge/discharge protection, mirroring commercial safety standards.
*Connectors (JST-PHR-2) on PCB are added for DC fan and piezo ring's compatible connectors.*
# Engineering Workflow
  Mechanical Design (MCAD): Custom 3D-modeled bodies created in Fusion 360, designed with internal mounting bosses and clearances specifically for the custom PCBs.

  Electrical Design (ECAD): Schematics and layouts developed to minimize footprint while maintaining signal integrity.

  Manufacturing Ready: Designed with DFM (Design for Manufacturing) principles in mind, intended for fabrication via JLCPCB.
