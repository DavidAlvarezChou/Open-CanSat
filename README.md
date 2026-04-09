# Open-CanSat
A flight-tested versatile open-source atmospheric probe designed for the European Space Agency's CanSat competition with modularity and affordability in mind.

While we designed it with our own mission in mind, we encourage others to use our designs for their own CanSat projects and competitions, as long as our project is credited appropriately. You can freely download the design files and modify them to your own mission requirements.
<p align="center">
<img align = "center" width="484" height="809" alt="Screenshot 2026-04-09 at 17 40 46" src="https://github.com/user-attachments/assets/862a15a0-187c-4e09-8068-1cea6381264b" />
<img align = "center" width="905" height="725" alt="Screenshot 2025-04-09 at 15 20 26" src="https://github.com/user-attachments/assets/d1dc5324-e887-4992-9edf-0f330b416fa4" />
</p>
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
13. Stripboard (not critical, but recommended for VBAT power bus)
14. Pull-up resistors (recommended for I2C bus)

Hardware:
1. 70 cm orange parachute
2. 2x ø6 mm OD, ø4 mm ID, 100 mm long carbon fiber rods.
3. 4x 4 mm expansion screw anchors
4. 4x M2.5x20 mm or M3x20 mm long screws
5. 3D printed section components
6. 3D printed outer shield
7. M4 eye bolt
8. M4 locking nut
9. Rubber band

<p align="center">
<img width="542" height="900" alt="vertical" src="https://github.com/user-attachments/assets/2f1fb635-88e0-4f38-a5fc-8830bdc97600" />


</p>
