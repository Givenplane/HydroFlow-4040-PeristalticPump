# HydroFlow 4040 Peristaltic Pump 

![HydroFlow 4040 Peristaltic Pump](images/main.png)

HydroFlow 4040 is an open-source peristaltic pump designed to be simple, affordable and easy to manufacture using common 3D printing equipment and off-the-shelf components.

The project was developed as a practical solution for transferring liquids while keeping the fluid completely isolated from the mechanical components of the pump.

The suitability of the tubing for a specific fluid should be verified by the user according to the tubing manufacturer's specifications.

## Design Specifications

### Tubing

The pump is designed around Tygon F-4040-A tubing 3/16” ID × 5/16” OD (4.8 × 8 mm).
Using different tubing may require modifications to the pump body and rotor geometry.

### Drive Motor

Reference motor used during development:

- Model: JGB37-520-CE

- Voltage: 12 VDC

- Rated Speed: 200 RPM

- Shaft: 6 mm D-shaft

- Gearbox: Metal reduction gearbox

- Rotation: CW / CCW

### Printed Parts

Parts were developed and tested using:

- Printer: Bambu Lab X1 Carbon
- Material: Bambu Lab PETG-HF grey

Standard PETG should also be suitable provided dimensional tolerances are maintained.

### Critical Tolerances

Part accuracy is important for correct operation.

Particular attention should be paid to:

- Rotor-to-shaft fit
- Bearing seats

The rotor must fit the motor shaft without noticeable play.

Excessive clearance may cause vibration, wear and inconsistent pumping performance.

## Print Settings

Reference settings used during development:

- Nozzle: 0.6 mm
- Layer height 0.24 mm
- Perimeters: 4
- Infill: 25 %
- Top layers: 5
- Bottom layers: 5
- X-Y Hole Compensation: 0.10 mm
- X-Y Contour Compensation: 0.075 mm
- Supports: Enabled
- Support Style: Tree (Auto)
- Support Placement: Build Plate Only

Different printers may require calibration adjustments.

## Performance

Reference configuration:

- Tubing: Tygon® F-4040-A

- Tube OD: 5/16” (8.0 mm)

- Tube ID: 3/16” (4.8 mm)

- Motor: JGB37-520-CE

- Supply Voltage: 12 VDC

- Motor Speed: 200 RPM

Measured flow rate:

- Approximately 0.38 L/min

Actual performance may vary depending on tubing condition, fluid viscosity, roller pressure and manufacturing tolerances.


## Resources

[docs/BOM.md](docs/BOM.md)

[doc/WHERE_TO_BUY](docs/WHERE_TO_BUY.md)

- 🎥 YouTube Video: https://youtu.be/laEK1ZIJFD0
  
- 📐 Onshape CAD: https://cad.onshape.com/documents/38ce336f3ba945738ff4eab6/w/76177a23119b3794901f380b/e/51ffb88a154799f7188256b8?renderMode=0&uiState=6a1dac8e073fa82755694582
## License

This project is released under the terms described in LICENSE.txt.

Commercial manufacturing, selling or monetization requires a separate commercial license agreement.

## Author

Simon Given

GivenPlane