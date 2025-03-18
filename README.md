# Two Trees SK1 3D Printer Repository

This repository provides detailed resources, configurations, and guides for the **Two Trees SK1 3D Printer**, a CoreXY-based machine designed for high-speed printing. The goal is to assist users in setting up, troubleshooting, and optimizing their printers effectively.

---

## Features of the Two Trees SK1

- **CoreXY Structure**: Stable and precise motion system.
- **Print Volume**: 256 × 256 × 256 mm.
- **High-Speed Printing**: Up to 700 mm/s (recommended: 300 mm/s).
- **Hotend & Extruder**:
  - All-metal hotend supporting up to 300°C.
  - Dual Gear Direct Drive Extruder with a gear ratio of 9.5:1.
- **Bed Leveling**: Automatic Z-Tilt leveling with three independent Z-motors.
- **Build Surface**: PEI-coated spring steel sheet for excellent adhesion and easy removal.
- **Electronics**:
  - Silent TMC2209 stepper drivers.
  - STM32F4 32-bit controller board.
- **Connectivity**: USB, Ethernet, Wi-Fi.
- **User Interface**: 4.3-inch color touchscreen.
- **Additional Features**:
  - Filament run-out detection.
  - Resume print function.
  - Open-source firmware (Klipper).
- **Optional Add-ons**: AI camera, enclosure.

---

## Repository Structure

### **1. Klipper**
Contains Klipper firmware configurations and macros for advanced users:
- Installation guides for Klipper firmware.
- Customizable `printer.cfg` files.
- Pre-configured macros for common tasks.

### **2. Board**
Includes hardware-related resources:
- Wiring diagrams and schematics for the mainboard.
- Technical specifications of the electronics.

### **3. Originais TT**
Original files provided by Two Trees:
- Stock firmware and factory configurations.
- Official user manuals.

### Planned Additions
Future updates may include slicer profiles, calibration models, and troubleshooting resources.

---

## Getting Started

### Assembly
1. Follow the assembly instructions in the [official manual](https://wiki.twotrees3d.com/en/3DPrinterSeries/SK1) or included PDF files in the repository.
2. Install optional components such as Wi-Fi antennas or enclosures if needed.

### Firmware Setup
1. Use the stock firmware or install Klipper for advanced features.
2. For Klipper:
   - Refer to the `Klipper` folder for installation steps and configuration files.
   - Update via SSH using pre-installed tools like KIAUH if necessary.

### Slicer Configuration
1. Set up your slicer (e.g., Cura or PrusaSlicer) using recommended profiles (to be added soon).
2. Adjust print settings for optimal results based on material and speed.

### Test Prints
Run test prints to verify proper setup:
- Use included calibration models or download additional ones from the repository.

---

## Troubleshooting

Common issues and solutions will be documented in a dedicated section (coming soon). For now:
- Refer to `Originais TT` for factory defaults if you encounter problems.
- Check `Klipper` folder for updated macros or configurations.

---

## Contributing

We welcome contributions to improve this repository! You can:
- Submit pull requests with enhanced configurations or tested modifications.
- Report issues or suggest improvements in documentation.

---

## Additional Resources

### Official Links
- [Product Page](https://br.twotrees3dofficial.com/products/sk1-corexy-3d-printer-twotrees)
- [Official Wiki](https://wiki.twotrees3d.com/en/3DPrinterSeries/SK1)

### Reviews & Guides
For more insights into the SK1's performance and potential upgrades:
- [Tom's Hardware Review](https://www.tomshardware.com/3d-printing/two-trees-sk1-review)
- [3DWithUs Review](https://3dwithus.com/two-trees-sk1-review-3d-printer-testing)

---

By leveraging its robust hardware and open-source firmware, the Two Trees SK1 can be a powerful tool when properly configured. This repository aims to help users unlock its full potential!

