# FPV Drone Build Documentation

## Overview

This project involves building a 5" freestyle FPV (First Person View) drone from scratch, utilizing various components from well-known manufacturers. The goal of this project was to gain hands-on experience with soldering, configuring, and troubleshooting a drone build from the ground up. The entire process, from assembly to flight configuration, was self-taught.

## Components Used

- **Frame:** [Source One V4 5" Frame](https://www.racedayquads.com/products/rdq-source-one-v4-5-freestyle-frame?keyword=sourceone&aff=58)
- **Flight Controller & ESC Stack:** [Speedybee F405 V3 Stack (F405 FC + 50A BLS ESC)](https://www.speedybee.com/speedybee-f405-v3-bls-50a-30x30-fc-esc-stack/?ref=TRONCATFPV)
- **Motors:** [Emax Eco ii 2306 2400kv Motors](https://bit.ly/3eCkTRI)
- **Camera:** [Foxeer Razer Mini (4:3)](https://bit.ly/3B2kDDh)
- **Receiver:** [BetaFPV 2.4ghz ELRS Rx](https://bit.ly/3qpAhUi)
- **Video Transmitter (VTX):** [JHEMCU 600mw VTX](https://bit.ly/3RzIdyq)
- **Battery:** [Ovonic 4s 1550mah LiPo](https://amzn.to/3RNKaH5)
- **Radio Controller:** [Radiomaster Boxer](https://www.radiomasterrc.com/products/boxer-radio-controller-m2)
- **FPV Goggles:** [FatShark HDO2](https://www.fatshark.com/product-page/hdo2)

---

## Build Process

### 1. **Frame Assembly**
   - The Source One V4 5" frame was selected for its durability and modular design. Assembling the frame involved mounting arms, standoffs, and plates using provided hardware.

### 2. **Motor Mounting and Soldering**
   - Installed the Emax Eco ii 2306 2400kv motors onto the arms of the frame.
   - Each motor was soldered directly to the ESC pads on the Speedybee F405 V3 stack.

### 3. **Flight Controller and ESC Integration**
   - The Speedybee F405 V3 Stack was mounted on the frame using soft rubber mounts to dampen vibrations.
   - Power wires were soldered to the ESCs, and signal wires connected the ESC to the flight controller.
   - Configured ESCs using BLHeli32.

### 4. **Camera and VTX Installation**
   - The Foxeer Razer Mini camera was mounted in the camera cage of the frame. Signal, power, and ground wires were soldered to the flight controller.
   - Installed the JHEMCU 600mw VTX on the frame, ensuring proper heat dissipation, and wired it to the flight controller.

### 5. **Receiver Installation**
   - The BetaFPV 2.4ghz ELRS receiver was soldered to the flight controller and properly positioned for optimal range and signal strength.

### 6. **Power Supply**
   - The Ovonic 4s 1550mah LiPo battery was selected for its balance between capacity and weight, offering sufficient power without compromising agility.

### 7. **Radio and Goggle Setup**
   - Configured the Radiomaster Boxer controller using EdgeTX.
   - Set up and calibrated the FatShark HDO2 goggles for clear video reception.

---

## Configuration

### 1. **Firmware**
   - Flashed Betaflight firmware onto the Speedybee F405 flight controller using Betaflight Configurator.
   - Calibrated accelerometer, set PID tuning, and configured various flight modes such as Angle, Horizon, and Acro.

### 2. **Motor & ESC Configuration**
   - Configured motor directions and ESC settings via BLHeli32.
   - Calibrated throttle endpoints and motor idle values.

### 3. **VTX and Camera Setup**
   - Set VTX power levels to optimize video transmission without overloading the system.
   - Adjusted camera settings such as exposure and contrast for better visibility.

### 4. **Failsafe and ELRS Receiver**
   - Configured failsafe options in Betaflight to prevent fly-aways.
   - Bound and configured the BetaFPV ELRS 2.4GHz receiver, ensuring low-latency communication with the Radiomaster Boxer.

---

## Test Flights

- Performed multiple test flights to ensure stability, tune PID settings, and test VTX range.
- Fine-tuned rates and expo to match personal flying style for freestyle flying.

---

## Challenges & Learning Outcomes

- **Soldering:** Learning proper soldering techniques was crucial to ensuring reliable connections, especially for small pads on the flight controller and ESC.
- **Firmware Configuration:** Understanding Betaflight’s various settings and troubleshooting issues such as gyro calibration and motor direction required persistence and attention to detail.
- **Receiver and VTX Setup:** Configuring the ELRS system for optimal range and troubleshooting video signal issues from the VTX and camera was an in-depth learning experience.

---

## Conclusion

Building this FPV drone was an insightful project that taught me about both the hardware and software aspects of drone technology. This hands-on experience helped develop problem-solving skills, attention to detail, and a deep understanding of FPV flight dynamics. I plan to continue refining my skills and take on more complex drone projects in the future.
