# Electronic technologies and biosensors laboratory
> 2021 - II semester - First Assignment

## Authors (Group 10)
  - [**Dario Comini**](https://github.com/DarioComini) 
  - [**Tommaso Ferri**](https://github.com/TommasoFerri97)

## Description
Design a schematic, a PCB, and custom devices using Autodesk EAGLE software.

### Context
Your company, the LTEBS srl, would like to use the PSoC 5LP micro-controller in a project requested by a customer. In order to evaluate the performance of the micro-controller and to determine if such uC is suitable for the project, the R&D department would like to design a PCB embedding the PSoC 5LP. This way, testing and assessment of the performance would be a lot easier than using a simple breadboard. As Cypress offers a development kit for the PSoC 5LP, namely the CY8CKIT-059, you are requested to design a PCB embedding suck kit, which will be soldered on male jumpers, and additional components required to conduct the proper testing by the R&D department. As some of the requested components are not present in EAGLE installation libraries, you are required to design a library containing such components. The PCB will be manufactured by [MDSrl](https://www.mdsrl.it/).

### Repository structure
- **Library**: Contains EAGLE library files
  - *"Group_10_Library.lbr"*: library file for devices [TMUX1208](https://www.ti.com/lit/ds/symlink/tmux1208.pdf) and [TCA9546A](https://www.ti.com/lit/ds/symlink/tca9546a.pdf)
- **Project**: Contains EAGLE schematic and board files
  - *"Group_10.sch"*: schematic file
  - *"Group_10.brd"*: board file
- **Design Rules**: Contains EAGLE design rules file
  - *"Group_10.dru"*: design rules file, following [manufacturer's specifications](https://www.mdsrl.it/mddesignrules.html)

### Additional resources
The following documents/tutorial can be useful for this assignment:
- [SparkFun EAGLE Tutorial](https://learn.sparkfun.com/tutorials/using-eagle-schematic/all)
- [EAGLE Layers](https://www.autodesk.com/products/eagle/blog/every-layer-explained-autodesk-eagle/)
- [Getting Started with EAGLE](https://www.autodesk.com/products/eagle/overview)
