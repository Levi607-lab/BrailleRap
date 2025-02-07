<figure> 
 
 # BrailleRAP
 This fork is based on the BrailleRap project: [https://github.com/braillerap/BrailleRap](https://github.com/braillerap/BrailleRap).

After building three BrailleRap machines in the OpenLab at Helmuth Schmidt University, this repository aims to contribute to this fantastic project by:  
- Adding a complete Bill of Materials (BOM) with all necessary screws.  
- Providing a remodeled STL file for the electromagnet guide, designed to fit 4.6 mm spacers.  
- Including pre-configured Marlin firmware for the BrailleRap machine, which only needs to be flashed to the control board using Visual Studio Code.

### Findings
- **Spacer Issue:** The spacers listed in the BOM are too long. The solenoid hits the heatsinks of the stepper motor drivers. To address this, we used self-locking nuts and M3 screws to create custom spacers for the controller board. This solution worked well.  
- **Stylus Punch Calibration:** After calibrating the height of the stylus punch, we applied Loctite to the part of the solenoid that screws into the spacer and the stylus. This prevents the parts from coming loose.  
  - We neglected to do this initially, which caused the machine to become unstable and ultimately damaged one of the stepper drivers.
:)
---
