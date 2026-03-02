# The Humidifier Project: Integrated ECAD/MCAD Design
A study in miniaturized appliance design and power distribution

# Project Overview 
***This project focuses on the end-to-end development of innovative, small-scale humidifiers (1:6 scale). The goal is to blend aesthetic "toy-like" form factors with professional-grade engineering, specifically focusing on ECAD/MCAD co-design using Autodesk Fusion 360.***
<img width="1920" height="850" alt="Hibachi Grill" src="https://github.com/user-attachments/assets/802e79f9-5e40-4ca4-aa7b-4801a3c10e77" />
**Hibachi Grill CAD Model**
<img width="1920" height="850" alt="Hibachi Grill Inside Compartment" src="https://github.com/user-attachments/assets/2a186841-89d4-451f-9cfa-d298694336ae" />
**Section Analysis of Hibachi Grill CAD Model**
# Technical Specifications & Features
The project explores multiple power and control configurations to suit different user needs:

  **Option A: USB-Powered (Current Revision)**
  <img width="1920" height="850" alt="Humidifier (USB Only) PCB" src="https://github.com/user-attachments/assets/579e3ed5-2536-48d2-966b-a480d99a28ef" />

    -Direct Power: Optimized for 5V USB input.

    -User Interface: Integrated physical toggle switch for post-plug-in control.

    -Circuit Protection: Includes a Schottky diode to prevent reverse current feedback, ensuring the longevity of the source port.

  **Option B: Li-Po Battery Integrated (Future Revision)**

    -Remote Operation: Designed for portability and remote control.

    -Safety Systems: Will feature a dedicated battery protection circuit (BMS) for overcharge/discharge protection, mirroring commercial safety standards.

# Engineering Workflow
  Mechanical Design (MCAD): Custom 3D-modeled bodies created in Fusion 360, designed with internal mounting bosses and clearances specifically for the custom PCBs.

  Electrical Design (ECAD): Schematics and layouts developed to minimize footprint while maintaining signal integrity.

  Manufacturing Ready: Designed with DFM (Design for Manufacturing) principles in mind, intended for fabrication via JLCPCB.
