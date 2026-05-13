---
marp: true
theme: default
paginate: true
---

# Day 1

## CS Hardware - Ohm's Law

---

# Goal for Today

By the end of today you will:

- Build your first circuit
- Learn about Ohm's Law
- Control LED (light emitting diode) brightness using a resistor
- Use a multimeter to measure voltage, current, resistance, and continuity
- Learn how to troubleshoot circuits

![bg contain right](assets/led-circuit-breadboard.jpg)

---

# Today's Workflow

1. Build a circuit virtually in Tinkercad
2. Build the same circuit physically on a breadboard
3. Measure and analyze the circuit
4. Extend the circuit using potentiometer, switch, and/or button

---

# Demo: LED (Light Emitting Diode) Circuit in Tinkercad

![w:600](assets/tinkercad-resistor-led-circuit.png)

<!-- 

INSTUCTOR NOTES:

Build out the circuit in Tinkercad. Start with point to point wiring. Show what happens without a resistor, then move to breadboard

Important Observation

- Changing resistance changes current
- Changing current changes brightness

Questions:
- What's the relationship between resistance, current and brightness?
- Why does the LED burn out?

-->

---

# What Happens Without a Resistor?

- Resistors convert electrical energy into heat.
- We use a resistor to safely limit current.
- This protects the LED from too much current.

![bg contain right](assets/too-much-current.png)

---

# Ohm's Law

## V = I × R

Voltage (V) = Current (I) * Resistance (R)

<!-- 

INSTUCTOR NOTES:

This is one of the most important equations in electronics

More voltage -> more current
More resistance -> less current 

-->

---

# Short Circuit

- A short circuit happens when too much current flows due to too little resistance
- An open circuit is the opposite (too much resitance)
- Large batteries can produce a dangerous levels of current and possibly risk starting a fire
- Do NOT short large batteries

[Video: ElectroBOOM](https://www.youtube.com/watch?v=i04y5n2oTsw)

---

# LAB BREAKOUT #1

## Tinkercad Build

Goal: *make this circuit in Tinkercad to make the LED light safely*

![bg contain right](assets/tinkercad-resistor-led-circuit.png)

<!-- 

INSTUCTOR NOTES:

Expect mistakes

Your circuit may:

- not work
- work partially
- behave strangely

Professional engineers spend huge amounts of time debugging.

If your circuit does not work immediately **THAT IS NORMAL**

-->

---

# What Is Electricity?

Electricity is the movement of electrons.

Three important ideas:

- Voltage (V)
- Current (I)
- Resistance (R)

![bg contain right](assets/electric-energy-physics-definition-vector-illustration-educational-poster-closed-electrical.webp)

---

# Voltage

- Voltage is electrical potential difference
- Voltage pushes electrons through a circuit
- Measured in Volts (V)

![bg contain right](assets/potential-energy.webp)

---

# Current

- Current is flow
- Current is the movement of electrical charge.
- Measured in Amps (A)

![bg contain right](assets/electric-current-vector-diagram.webp)

---

# Resistance

- Resistance opposes current flow
- Higher resistance, less current
- Lower resistance, more current
- Measured in Ohms (Ω)

![bg contain right](assets/hose-analogy.png)

---

# Water Analogy

| Electricity | Water |
| ----------- | ----- |
| Voltage | Pressure |
| Current | Flow |
| Resistance | Narrow pipe |

![bg contain right](assets/water-analogy.png)

---

# Polarity

- *Direction matters*
- Electricity flows through a circuit in a direction
- Some components only work when electricity flows the correct way

This is called *polarity*

![bg contain right](assets/electric-energy-physics-definition-vector-illustration-educational-poster-closed-electrical.webp)

---

# LEDs Have Polarity

LED (Light Emitting Diode)

Diodes only allow current in one direction.

- Long leg = positive (+) anode
- Short leg = negative (-) cathode

![bg contain right](assets/led-polarity.webp)

---

# Demo: Physical Breadboard

![w:600](assets/led-circuit-breadboard.jpg)

---

# Safety

- Disconnect power before rewiring
- Avoid short circuits
- Wear safety glasses
- 1 hand trick 👋

![bg contain right](assets/safety-glasses.jpg)

---

# LAB BREAKOUT #2

## Physical Breadboard Build

Goal: *Recreate the same circuit physically*

![bg contain right](assets/led-circuit-breadboard.jpg)

---

# Troubleshooting

If it does NOT work:

- check polarity
- check wiring
- check loose connections
- swap components
- test battery

(sometimes you just need to take a break)

---

# Tinkercad vs Physical

What are your first impressions?

<!--

INSTRUCTOR NOTES:

Tinkercad:
- easier wiring
- easier visibility

Real hardware:
- loose wires
- bad connections
- physical constraints

-->

---

# The Multimeter

## Most important electronics tool

A multimeter measures:

- voltage
- resistance
- current
- continuity
- and more!

<!-- TODO: image? tinkercad and physical multimeter -->
![bg contain right](assets/multimeter-tinkercad.png)
![bg contain right](assets/multimeter.webp)


---

# Demo: Multimeter

![bg contain right](assets/multimeter-tinkercad.png)
![bg contain right](assets/multimeter.webp)

<!-- 

INSTUCTOR NOTES:

Use Tinkercad and the live breadboard to make measurements using the multimeter

Measure:
- battery voltage
- LED voltage (parallel - on)
- resistance (off)
- current (series - on)
- continuity (off)

Show probes placed in parallel vs. series

-->

---

# Battery

A battery provides voltage.

Battery terminals:

- Positive (+)
- Negative (-)

![bg contain right](assets/battery-multimeter.png)

---

# Forward Voltage

- A green LED typically uses about 2.2 V
- This is called *forward voltage*
- In a 9V circuit some voltage appears across the LED
- The rest appears across the resistor(s)

![bg contain right](assets/led-forward-voltage.png)

---

# Calculating Forward Voltage

Assume:

- Battery = 9V
- LED forward voltage = 2.2V
- Resistance = 500 Ω

Remaining voltage: `9V − 2.2V = 6.8V`

Using Ohm's Law:

```
I = V / R
I = 6.8V / 500Ω
I = 0.0136 A = 13.6 mA
```

---

# Resistor

- Color bands indicate resistance
- Use multimeter to measure resistance

![bg contain right](assets/6-Band-Resistor-120-Ohms.webp)
![bg contain right](assets/multimeter-resistor.png)

---

# Current

- In a series circuit, the current is the same everywhere because there’s only one path for charge to flow.

![bg contain right](assets/led-forward-voltage.png)

---

# Continuity

- Verifies that an electrical path is complete and unbroken by sending a small current through the circuit

![bg contain right](assets/continuity.webp)

---

# LAB BREAKOUT #3

## Multimeter Measurements

Measure:

- Battery voltage
- Forward voltage
- Current
- Resistance
- Continuity

---

# Demo: LED Brightness Control

Adjust LED brightness using:

- Resistor
- Potentiometer
- Button and/or switch

![bg contain right](assets/led-brightness-control.gif)

---

# Potentiometer (Variable resistor)

- Turning the knob increases (or decreases) resistance.
- Use center pin and one outside pin
- Leave the other outside pin disconnected.

![bg contain right](assets/potentiometer.png)

---

# Buttons

A button only changes the circuit while pressed.

Examples:

- Keyboard keys
- Doorbells
- Game controller buttons

![bg contain right](assets/pushbutton.png)

---

# Switches

A switch stays in its position until changed.

Examples:

- Room light switch
- Power strip
- Flashlight switch

![bg contain right](assets/switch.png)

---

# LAB BREAKOUT #4

## LED Dimmer Switch

Goal: *Add the potentiometer, button, and/or switch to control LED brightness*

![bg contain right](assets/led-brightness-control.gif)

---

# Key Takeaways

<!--

INSTRUCTOR NOTES:

- Voltage pushes current
- Resistance limits current
- Current controls LED brightness
- Polarity matters
- Multimeters let us observe circuits

-->
