# Open-CanSat
A flight-tested versatile open-source atmospheric probe designed for the European Space Agency's CanSat competition with modularity in mind.

<img width="905" height="725" alt="Screenshot 2025-04-09 at 15 20 26" src="https://github.com/user-attachments/assets/d1dc5324-e887-4992-9edf-0f330b416fa4" />

# Design overview:
Our design of Open CanSat integrates 5 sensing units to provide 9 different environmental measurements listed below. It also integrates a Meshtastic LoRa unit to enable the probe to act as an airborne repeater to extend the range of off-grid text-messaging Meshtastic infrastructure during its descent. 

Sensors:
BME 280: Temperature, humidity, and pressure.
MICS–4515: Relative concentrations of oxidizing and reducing gasses.
QMC5883L: Magnetic field intensity in 3 different axes.
MPU6500: Acceleration and rotation measurements in 3 axes each.
NEO–6M: Position and velocity measurements.

The basic structure of the probe is based on twin 6 millimeter carbon fiber rods upon which all the individual 3D–printed sections mount to. This system is designed to come apart with simply unscrewing two screws at the top or the bottom of the probe, making it extremely easy to open to modify and repair.

# Bill of materials (BOM):

Avionics:
1. ESP–32 microcontroller
2. Seeed ESP32 + SX1262 combination unit
3. ASR 6601 LoRa unit
4. QMC5883L magnetometer
5. SD card module
6. MPU6500 Inertial Measurement Unit
7. BME 280 barometer/hygrometer/thermometer
8. NEO–6M GNSS unit
9. 2x 26350 2000 mAh 3.7V Lithium-ion cells
10. MICS–4514 dual gas sensing unit
11. 3.3V–5V step up DC-DC voltage converter
12. 2 gram servomotor
13. Stripboard (not critical, but recommended for BAT voltage bus)
14. Pull-up resistors (recommended for I2C bus)

Hardware:
1. 70 cm orange parachute
2. 2x ø6 mm OD, ø4 mm ID carbon fiber rods X millimeters long.
3. 4x 4 mm expansion screw anchors
4. 4x M2.5 or M3 20 mm long screws
5. 3D printed section components
6. 3D printed outer shield
7. 304L stainless steel M4 eye bolt
8. M4 locking nut
9. Rubber band
