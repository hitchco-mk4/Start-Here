_This repo is a part of the Hitchco MK4 project. You can read more about the project [here](http://www.esologic.com/hitchco-mk4/)._

# Start Here

This project is a fully customizable, open-source, **digital dashboard** for a replica 1965 Ford Shelby Cobra, the [Factory 5 MK4 Roadster](https://www.factoryfive.com/roadster/mk4/complete-kit/).  It is a fusion of the classic stylings of the Cobra, with the convince and features that come with modern digital dashboards. This work should serve as a primer for those who want to get into taking DIY automotive to the next level. This car was **not** equipped with a CAN bus so control had to be implemented bare-metal.

This repository serves a hub for this project on the web, and gives a high-level overview of this project. You can find all other components of this project in the github organization or by following these links:
 * [Controller Electrical Schematics](https://github.com/hitchco-mk4/Controller-Electrical-Schematics)
 * [Controller Firmware](https://github.com/hitchco-mk4/Controller-Firmware)
 * [Display Software](https://github.com/hitchco-mk4/Display-Software)
 * [Mechanical CAD](https://github.com/hitchco-mk4/Mechanical-CAD)
 * [MK4 Tools](https://github.com/hitchco-mk4/MK4-Tools)
 * [MK4 Media](https://github.com/hitchco-mk4/MK4-Media)

## Demo

Pending

## Coolest Features

* **Fully customizable dashboard gauges layout.** The display is driven by a Raspberry Pi 3 running electron, so you tuning the layout is as simple as a CSS style sheet.
* **Keypad locking and unlocking.** Enter your secret pin and you can operate the car. 
* **Push to start** Using oil pressure & tachometer.
* **Integrated backup camera.** Turns on when the car is put into reverse.
* **Day/Night driving modes.** Using an embedded LDR, the dashboard gauges automatically change color depending on ambient light level for maximum visibility
* **Integrated cruise control.** Using the [Rostra Ultracruise](http://www.rostra.com/manuals/ultracruise-2_Form2784A.pdf) module.

## High Level Diagrams

These diagrams are models of how this project should work. 

### Dashboard Diagram
![dashboard diagram](https://user-images.githubusercontent.com/3516293/39070218-7565bd24-44b0-11e8-893b-3ba861702e3e.png)

### Signals
![signals](https://user-images.githubusercontent.com/3516293/39070219-7575feaa-44b0-11e8-8ef9-cee0a8054c1d.png)

### Software Data Flow
![software data flow](https://user-images.githubusercontent.com/3516293/39070220-7587746e-44b0-11e8-97f2-8d20e8ba16bc.png)


 
# Authorship
 
 All bugs or problems should be sent to [Devon Bray](mailto:dev@esologic.com).