# ICE-to-Meet-You
### Imaginative Creative Engineering
**A magnetic dancing penguin music box powered by M5Stamp C3U with MIDI music.**
## About

Two little penguins meet for the first time on the ice.  
Using the force of magnets, they spin and dance together.

**ICE to Meet You** is a small electronic music box inspired by the classic ballerina music boxes of the past.

The nostalgic mechanism has been reimagined using an **M5Stamp C3U**, magnets, a motor, and MIDI music.

When the music begins, the M5Stamp C3U controls the motor beneath the iceberg, making the penguins dance on the ice.

---

## ICE = Imaginative Creative Engineering

The name **ICE to Meet You** is a play on “Nice to meet you.”

But **ICE** has another meaning:

**I.C.E. = Imaginative Creative Engineering**

For this project, it means taking a familiar mechanism from the past, imagining a new way to use it, and recreating it with modern technology.

The ballerina becomes two penguins.

The stage becomes an iceberg.

And the mechanical music box becomes an electronic music box powered by M5Stack.

---

## How It Works
A magnet is attached to a rotating mechanism underneath the iceberg.

Magnets are also attached to the penguins.

When the motor rotates the magnet beneath the surface, magnetic force makes the penguins move and spin across the ice.

The **M5Stamp C3U** controls the motor, including the timing of when the penguins start and stop dancing.

At the same time, the M5Stamp C3U sends MIDI data to an **M5Stack Unit Synth**.

The Unit Synth plays the music through its built-in speaker.

The music uses a **Music Box** instrument with reverb to give it a nostalgic, sparkling sound.

---

## Music

This project has its own original theme song:

### “ICE to Meet You”

The original song was created with the help of **Suno**.

The music was then converted to MIDI and simplified for playback on the M5Stack Unit Synth.

The M5Stamp C3U sends the MIDI notes to the Unit Synth while controlling the movement of the penguins.

This allows the music and the dance to become one small performance.

---
## Hardware

- M5Stamp C3U
- M5Stack Unit Synth (SAM2695)
- Mini DC gear motor
- 2SC1815 transistor
- 1N4007 diode
- Resistor
- Magnets
- USB 5V power supply
- Handmade iceberg
- Two handmade penguins

---

## System
```text
                    ┌── MIDI ──> M5Stack Unit Synth
                    │                │
                    │                └──> Built-in Speaker
                    │
M5Stamp C3U ────────┤
                    │
                    └── GPIO ──> Transistor ──> DC Motor
                                                │
                                                ▼
                                             Magnet
                                                │
                                                ▼
                                      Dancing Penguins
```
## Story

Two little penguins meet for the first time on the ice.

They look at each other.

The music begins.

And then...

ICE to Meet You!

The two penguins begin to dance together.

M5Stack Global Innovation Contest 2026

ICE to Meet You was created for the
M5Stack Global Innovation Contest 2026.
