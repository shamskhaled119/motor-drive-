## Hardware Part 🔧⚙️

The hardware side of this Motor Driver project is responsible for driving DC motors safely and efficiently.

The circuit is based on the L298N motor driver IC, which allows the control circuit to drive motors without connecting them directly to the controller pins.

It also includes a power supply section to provide a stable 5V output for the control side, along with protection diodes to protect the circuit from motor back EMF.

In simple words:  
the controller sends the signal, the driver handles the power, and the motor moves. 🔥

---

## Hardware Design Photos 📸

### Schematic Design
<img src="Screenshot%202026-06-09%20073747.png" alt="Motor Driver Schematic Design" width="700">

### PCB Routing
<img src="Screenshot%202026-06-09%20073834.png" alt="Motor Driver PCB Routing" width="700">

### PCB Layout / Board View
<img src="Screenshot%202026-06-09%20073736.png" alt="Motor Driver PCB Layout" width="700">

---

## Hardware Components Used

- L298N Motor Driver IC  
  Used as the main motor driver to control the direction and operation of DC motors.

- 7805 Voltage Regulator  
  Used to provide a stable 5V supply for the control part of the circuit.

- Protection Diodes  
  Used to protect the circuit from reverse voltage spikes caused by the motors.

- Capacitors  
  Used for filtering and stabilizing the power supply.

- Resistor and LED Indicator  
  Used as a power indicator to show that the circuit is powered.

- Heatsink  
  Used with the L298N to reduce heat during motor operation.

- Motor Output Connectors  
  Used to connect the DC motors to the driver circuit.

- Input Control Connectors  
  Used to connect the control signals such as IN1, IN2, IN3, IN4, ENA, and ENB.

- Power Connectors  
  Used to connect the motor supply voltage, 5V, and GND.

---

## Hardware Role

- Drives DC motors using the L298N driver
- Controls motor direction
- Supports motor enable control
- Provides stable 5V for the control circuit
- Protects the circuit from motor voltage spikes
- Allows safe connection between the controller and motors
- Makes the motor control circuit more reliable and practical
