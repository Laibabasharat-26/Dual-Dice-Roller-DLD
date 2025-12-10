
# 🎯 Digital Logic Design Final Project
# Dual Dice Roller Using Counters & 555 Timer (Proteus Simulation)

## Overview

The Dual Dice Roller is a fully digital, hardware-based random number generator designed using 555 Timers, Decade Counters, Seven-Segment Displays, and logic gates.
Instead of software or microcontrollers, this project showcases how pure digital logic can simulate the rolling of two dice simultaneously.

Each die operates independently, receiving clock pulses from its own 555 timer. The counters cycle rapidly, and when the clock stops, each display freezes at a random number between 1 and 6 — exactly like real dice.

This project demonstrates key concepts from Digital Logic Design:

✔ Pulse generation

✔ Sequential logic

✔ Counter control

✔ Display decoding

✔ Reset logic


# ✨ Key Features
## 🎲 Random Number Generation (Two Dice)

Independent clock pulses for each die

Output range: 1–6

Displayed using seven-segment displays

## ⏱️ 555 Timer in Astable Mode

Acts as the rolling mechanism

Generates continuous square-wave pulses

Frequency controls the dice-rolling speed

## 🔢 Counter Logic (4017 / Mod-6 Counter)

Converts pulses into sequential outputs

Logic gates limit count from 1 → 6

Auto-reset after reaching 6

## 📟 Display Decoding

BCD-to-7-segment decoding

Clear and correct representation of digits 1–6

## 💡 Fully Digital — No Microcontroller

Entire project uses ICs + logic gates only

Ideal demonstration of DLD hardware fundamentals


## 🛠️ Components
Hardware

555 Timer IC (x2)

4017 Decade Counter (x2)

Seven-Segment Displays (x2)

AND / OR Logic Gates

Resistors & Capacitors

Push Buttons / Switches

Software

Proteus 8 Professional (simulation)


## 👥 The Team

This project was built by:

Laiba Basharat

Imtishal Haq

Maheen Irfan

##  Acknowledgements

Special thanks to our instructors for their guidance and support:

Sir Sohail Abbas

Sir Talha Tariq
