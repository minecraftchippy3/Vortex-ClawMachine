
# Vortex-ClawMachine
**<img width="652" height="811" alt="Claw machine" src="https://github.com/user-attachments/assets/4256c675-0256-47f5-8cef-ab1d9dec1566" />**

Vortex is a working small claw machine powered by an esp32. Built for Hack Club Fallen 2026

It is intended to be used as a fun tiny claw machine that can fit on a desk. It uses a large glowing button, along with a fun arcade joystick to control a claw that can pick up small prizes.


# Features & Design

The Claw Machine uses an XY gantry design using 2 lead ball screws, inspired by 3D printers. The claw machine also includes a small prize chute that can handle prizes up to 6 cm wide. I first had this idea for a project a while ago, when I saw how cool the gantry design was in a claw machine at an arcade. I had the idea for a while until an event called HackClub Fallen occurred. I decided this would be the perfect opportunity to create the claw machine I wanted to build. 

This small claw machine that can fit on your desk uses a wall power supply and uses stepper motors to control the main claw carriage. It also has a claw with 3 grabbers, which are all controlled by one linear actuator. 2 Nema stepper motors control the Gantry system, while the claw lowering mechanism is controlled by a regular DC motor.
# PCB & Components
For each Motor and Linear Actuator, I have a different designated motor driver. Each motor driver also uses a decoupling capacitator, and I am using a step down converter to change the voltage from the wall power source to a suitable 5 volts for controlling the esp32. It uses two rows of pin headers to allow for each component to get plugged in easily. The PCB design fits all of this into a small board that allows for easy connections to the components. A full list of all components is provided in the tutorial section.
<img width="1112" height="846" alt="fgbc" src="https://github.com/user-attachments/assets/2f2a3e52-19c7-404c-8923-b38e57169751" />

# Firmware

# Tutorial
