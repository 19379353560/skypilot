# Project Status

SkyPilot H743 is an open hardware flight-controller project for INAV.

## Available In This Repository

- EasyEDA Pro PCB project file.
- Prebuilt INAV 9.0.1 firmware files.
- Hardware design notes for STM32H743, ICM42688P, DRDY interrupt wiring, and vibration isolation.

## Validation Status

This repository should be treated as a design and firmware reference unless a
specific build or flight-test result is documented. Review the schematic, PCB,
firmware target, and sensor wiring before manufacturing or flying.

## Review Needed

- PCB layout and grounding.
- IMU placement and DRDY wiring.
- Power filtering and regulator selection.
- INAV target configuration.
- Bench-test and flight-test reports.

## Safety

Flight-controller failures can cause loss of control. Test on the bench first,
remove props during configuration, and verify sensor orientation, failsafe, and
receiver behavior before any flight.

