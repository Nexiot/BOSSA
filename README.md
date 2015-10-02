# BOSSA
BOSSA ( Bangalore Open Solar Smart Automation)
This is a community project initiative of Bangalore Open Source Hardware Association sponsored by Nexiot.

The project is to design and develop a affordable solar based lighting & Smart Automation DIY solution.

OBJECTIVES :
The project has 5 Objectives as listed below :
   1. UNDERSTAND & LEARN the process of ideating a open source hardware project & APPLYING PRINCIPLES of open source hardware product development
   2. Create a open source product that will PROMOTE EDUCTAION & ADOPTION of solar power & SMART electronics
   3. Create a AFFORDABLE Do-It-Yourself Solution that will promote wide scale usage amongst community 
   4. Promote concepts of PERSONALIZATION/CUSTOMIZATION, which can be enabled by open source & 3D printing techniques
   5. Understand the process of creating a COMMERCIAL OPEN SOURCE product


System Hardware :
1. The sytem will be powered by a 20W solar panel. We are using a polycrystalline solar panel due its common availability & suits our simple offgrid application.
2. The battery for storing power is a 7.5Ah standard Sealed Maintenance Free (SMF) battery which is commonly available.
3. Charge Controller : This is the main open source electronic sub system. We are implementing a PWM ( Pulse width modulation) Charge controller . The Charge controller has the purpose to ensure the battery is charged from the solar panel in a effient and safe way and avoid overcharging. This is important to ensure long battery life and safe opertaion.
We are using Arduino UNO as a prototyping platform to implement the charge controller. Mosfets are used for implementing control charging & load voltages
4. We are implementing SMARTness and automation by providing Security features: Image/voice capture - Automated dusk to Dawn control control for LED Tubelights
5. Personalized packaging: The system will have custoom package using 3D printing and other digital printing techniques

