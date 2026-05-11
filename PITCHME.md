---
marp: true
theme: default
paginate: true
---

# Day 1
## Introduction to Electricity & Electronics

---

# Goal for Today

By the end of today you will:

- Build your first circuit
- Control LED (light emitting diode) brightness
- Use a multimeter
- Learn voltage, current, and resistance
- Learn how to troubleshoot circuits

---

# Live Demo

## What are we building today?

<!-- LIVE DEMO -->
<!-- Show physical LED dimmer circuit -->

<!-- Questions:
- Why does the LED change brightness?
- What controls the current?
- Why doesn't the LED burn out? -->

![bg contain right](assets/resistor-led-circuit.png)

---

# Today's Workflow

## Step 1
Build the circuit virtually in Tinkercad

## Step 2
Build the same circuit physically on a breadboard

## Step 3
Measure and analyze the circuit

---

# Why Start with Tinkercad?

Advantages:
- easier wiring
- instant feedback
- safer experimentation
- easier troubleshooting
- no damaged components

We can focus on *understanding the circuit first*

---

# Electronics Is About Control

We use electronics to control:

- Light
- Motion
- Sound
- Information
- Energy

---

# Learning by Discovery

## Expect mistakes

Your circuit may:
- not work
- work partially
- behave strangely

That is normal.

---

# Important Mindset

Professional engineers spend huge amounts of time debugging.

If your circuit does not work immediately:

**THAT IS NORMAL**

---

# LAB BREAKOUT #1

## Tinkercad Build

Build a battery, resistor, LED circuit

Goal: *make the LED light safely*

---

# Tinkercad Time

## Build your first circuit virtually

Components:
- battery
- resistor
- LED
- wires

Goal: *make the LED light safely*

---

# Virtual Circuit

Battery positive →
Resistor →
LED →
Battery negative

<!-- TODO: insert Tinkercad screenshot -->

---

# Before Starting Simulation

## Double check:

- LED polarity
- resistor present
- correct wiring
- battery orientation

---

# Prediction

Before starting the simulation:

- What happens if the LED is reversed?
- What happens if the resistor is removed?
- Will the LED always light?

---

# Start the Simulation

## What do you observe?

- Is the LED on?
- Is it bright?
- What happens if wiring changes?

---

# Intentional Failure Test

Try:
- reversing the LED
- removing the resistor

Observe what changes.

---

# Debrief

- Why did reversing the LED matter?
- Why was the resistor necessary?
- Why did some circuits fail?

---

# What Is Electricity?

Electricity is the movement of electrons.

Three important ideas:

- Voltage (V)
- Current (I)
- Resistance (R)

![bg contain right](assets/water-analogy.png)

---

# Voltage

## Voltage is electrical pressure

Voltage pushes electrons through a circuit.

Analogy:
- water pressure in a pipe

Measured in:
# Volts (V)

---

# Current

## Current is flow

Current is the movement of electrical charge.

Analogy:
- water flowing through a pipe

Measured in:
# Amps (A)

---

# Resistance

## Resistance opposes current flow

Higher resistance:
- less current

Lower resistance:
- more current

Measured in:
# Ohms (Ω)

![bg contain right](assets/hose-analogy.png)

---

# Water Analogy

| Electricity | Water |
|---|---|
| Voltage | Pressure |
| Current | Flow |
| Resistance | Narrow pipe |

![bg contain right](assets/water-analogy.png)

---

# The Battery

A battery provides voltage.

Battery terminals:

- Positive (+)
- Negative (-)

![bg contain right](assets/battery-multimeter.png)

---

# Polarity

**Direction matters**

- Electricity flows through a circuit in a direction
- Some components only work when electricity flows the correct way

This is called *polarity*

---

# LEDs Have Polarity

LED:
- Light Emitting Diode

LEDs only work in one direction.

- Long leg = positive (+) anode
- Short leg = negative (-) cathode

![bg contain right](assets/led-polarity.webp)

---

# What Happens Without a Resistor?

## Bad idea

An LED connected directly to a battery can:
- draw too much current
- overheat
- burn out

---

# Current Limiting

We use a resistor to safely limit current.

This protects the LED from too much current.

---

# Debugging Is Engineering

There are:
- some ways to wire it correctly
- many ways to wire it incorrectly

Debugging is part of electronics.

---

# LAB BREAKOUT #2

## Physical Breadboard Build

Recreate the same circuit physically.

Goal:
- LED lights
- correct polarity
- clean wiring

Time:
15 minutes

---

# Build It Physically

## Now recreate the same circuit

Using:
- breadboard
- real LED
- resistor
- battery
- jumper wires

---

# Breadboard

## Rapid circuit prototyping

- no soldering
- reusable
- easy to modify

---

# Breadboard Layout

## Rows are electrically connected

<!-- TODO: Insert breadboard diagram -->

---

# Physical Circuit

Battery positive →
Resistor →
LED →
Battery negative

---

# Before Powering On

## Double check:

- LED polarity
- resistor present
- loose wires
- battery orientation

---

# Instructor Demo

## Common failure modes

<!-- LIVE DEMO -->

Try:
- reversing the LED
- loose wire
- missing resistor
- wrong breadboard row

Ask:
# Why did it fail?

---

# Success!

If the LED lights:

# You built your first physical circuit

---

# Troubleshooting

If it does NOT work:

- check polarity
- check wiring
- check loose connections
- swap components
- test battery

---

# Compare Virtual vs Physical

What are your first impressions?

<!--

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

---

# Instructor Demo

## Measuring voltage

<!-- LIVE DEMO -->

Measure:
- battery voltage
- LED voltage

Show:
- probes placed in parallel

---

# Measuring Voltage

## Voltage is measured in parallel

Place probes across the component.

<!-- TODO: Insert diagram -->

---

# LAB BREAKOUT #3

## Multimeter Measurements

Measure:
- battery voltage
- current
- resistor value
- continuity

Optional:
- LED current

Time:
10–15 minutes

---

# Measure the Battery

## Prediction

What voltage do you expect from a 9V battery?

Now measure it.

---

# Measuring Resistance

## Important Rule: **POWER OFF FIRST**

Resistance is measured on unpowered circuits.

---

# Measure a Resistor

- Use the multimeter to measure different resistors
- Compare measured values to color bands.

---

# Measuring Continuity

Continuity means:
- electrical connection exists

The multimeter beeps when connected.

---

# Continuity Demo

<!-- LIVE DEMO -->

Test:
- jumper wires
- buttons
- switches
- breadboard rows

---

# Ohm’s Law

# V = I × R

This is one of the most important equations in electronics.

---

# Ohm's Law Intuition

More voltage:
- more current

More resistance:
- less current

---

# LED Brightness Control

## New goal

Control LED brightness using:
- resistor
- potentiometer

---

# Potentiometer

## Variable resistor

Turning the knob changes resistance.

More resistance:
- less current
- dimmer LED

---

# Potentiometer Wiring

Use:
- center pin
- one outside pin

Leave the other outside pin disconnected.

<!-- TODO: insert potentiometer diagram -->

---

# Prediction

Before building:

- What happens as resistance increases?
- Will brightness increase or decrease?
- Will the change feel linear?

---

# LAB BREAKOUT #4

## LED Dimmer

Add the potentiometer.

Goal:
# control LED brightness

Time:
15–20 minutes

---

# LED Dimmer Circuit

Battery positive →
Fixed resistor →
Potentiometer →
LED →
Battery negative

---

# Experiment Time

Slowly rotate the potentiometer.

Observe:
- brightness
- smoothness of control

---

# Why Does Brightness Change?

Brightness depends on:
# current

Current depends on:
# resistance

---

# Forward Voltage

LEDs are not ordinary resistors.

A green LED typically uses:
# about 2.2 V

This is called:
# forward voltage

---

# Circuit Voltage

In a 9V circuit:

Some voltage appears across:
- the LED

The rest appears across:
- the resistor
- potentiometer

---

# Example Calculation

Assume:
- Battery = 9V
- LED forward voltage = 2.2V
- Resistance = 500 Ω

Remaining voltage:

# 9V − 2.2V = 6.8V

---

# Current Calculation

Using Ohm's Law:

# I = V / R

# I = 6.8V / 500Ω

# I = 0.0136 A

# 13.6 mA

---

# Important Observation

Changing resistance changes:
- current

Changing current changes:
- brightness

---

# Heat and Energy

Resistors convert electrical energy into heat.

LEDs convert energy into:
- light
- heat

---

# Common Mistakes

- reversed LED
- missing resistor
- loose wires
- wrong breadboard row
- dead battery

---

# Safety

## Always:

- disconnect power before rewiring
- avoid short circuits
- wear safety glasses
- check polarity

---

# Battery Safety

Do NOT short:
- lithium batteries
- car batteries

Large batteries can produce dangerous currents.

---

# Engineering Mindset

Good engineers:
- test
- predict
- measure
- debug
- iterate

---

# Key Ideas from Today

- Voltage pushes current
- Resistance limits current
- Current controls LED brightness
- Polarity matters
- Multimeters let us observe circuits

---

# Key Takeaways

<!--

- Why is a resistor needed?
- What happens if resistance increases?
- What does voltage measure?
- Why do LEDs have polarity?

-->

---

<!--

TODO: extra steps

- change the order of components
- change resistance / potentiometer
- add a button and/or switch

-->

---

# Next Time

Next steps:
- capacitors
- series vs parallel
- sensors
- transistors
