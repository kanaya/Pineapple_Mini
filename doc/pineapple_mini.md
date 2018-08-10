# Pineapple Mini

## Description

Pineapple Mini is a MIDI-connected relay driver.

## Overview

Pineapple Mini has followirng ports.

* MIDI IN port
* Relay port

## Protocol

Pineapple Mini has a relay that can be controlled by MIDI signal.

MIDI Note On signal (channel 0, note 60, velocity >=1) turns the relay on. MIDI Note Off signal (channel 0, note 60) or MIDI Note On with zero velocity (channel 0, note 60, velocity 0) turns the relay off.

## Hardware

### Overview of Connectors

* Power -- DC Input (+5V)
* Relay
* MIDI IN

## MIDI IN

| MIDI IN Pin   | Meaning |
|---------------|---------|
| m1            | NC      |
| m2            | NC      |
| m3            | NC      |
| m4            | Source  |
| m5            | Drain   |

## MPU Pinout

| Arduino Pro Mini   | Meaning   |
|--------------------|-----------|
| D0 (RX, INT)       | MIDI IN   |
| D2                 | RELAY 0   |
