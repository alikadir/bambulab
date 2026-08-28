# BambuLab

### When change nozzle
Make Full Calibration

### Start/End Sound
[Wiki for MIDI sound](https://wiki.bambulab.com/tr/a1-mini/midi)

### File Transfer with FTP to Device
FileZilla
- **ftp:** <DEVICE_IP_ADDRESS>
- **port:** 990
- **user:** bblp (BamBuLabPrinter)
- **pass:** <DEVICE_ACCESS_CODE>

### Calibration
All details are in Whimsical

### QRCode or ArUco for Plate Detection
All details are in Figma

## X2D Combo 

### Textured PEI Plate - 0.2mm Nozzle
- didn't prove it

### Textured PEI Plate - 0.4mm Nozzle
- On Device Screen > Settings > Calibration > First Layer Calibration > Left Nozzle > -0.01 (not required this setting after calibration)
- On Device Screen > Settings > Calibration > First Layer Calibration > Right Nozzle > 0.00
- That's All

### Engineering Plate - 0.2mm Nozzle
- didn't prove it

### Engineering Plate - 0.4mm Nozzle
- On Device Screen > Settings > Calibration > First Layer Calibration > Left Nozzle > 0.00
- On Device Screen > Settings > Calibration > First Layer Calibration > Right Nozzle > didn't prove it

[First Layer Troubleshooting Wiki Page](https://wiki.bambulab.com/en/x2d/troubleshooting/first-layer-printing-optimization-guide)

### Support Settings (Support Interface Auxiliary Nozzle)
- View > Show Overhang (find areas require support)
- Support > Filament for Supports > Support/raft interface = PLA/PETG
- Support > Support > Style = Tree Organic
- Support > Support > On Build Plate Only = Selected
- Support > Advanced > Initial Layer Expansiyon = 5
- Support > Advanced > Top Z Distance = 0
- Support > Advanced > Top Interface Layer = 3
- Support > Advanced > Interface Pattern = Rectilinear Interlaced
- Support > Advanced > Top Interface Spacing = 0
- Support > Advanced > Support/Object XY Distance = 0.5mm
- Speed > Main and Auxiliary > Other Layers Speed > Support Interface = 50


### Bed Adhesion Problem

Wash the plate with **dish soap**, and wipe it with a microfiber or paper towel. (tou)

### Nice Settings (Best Speed/Quality Ratio)

- 0.12mm Fine for 0.4mm nozzle (equivalent 0.2mm nozzle)
- Sparse infill density (Seyrek Dolgu Yogunlugu) **%5**
- Sparse infill pattern **Gyroid**
- **0.1mm** tolerance for moving parts
- Elephant foot compensation **0.25mm** or **0.3mm**
- If there are objects with different heights, don’t use ironing.


------


## A1 Combo
### 0.2mm nozzle
- Textured PEI Plate Z offset **0.02**
- Flow Dynamic Calibration for General High Speed PLA / FactorK = **0.255**

### 0.4mm nozzle
- Textured PEI Plate Z offset **0.02**
- That's All




