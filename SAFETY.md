# Safety

SkyPilot H743 is an open hardware project under review. Treat all files,
firmware builds, and wiring notes as experimental until independently checked.

## Before Power

- Inspect the PCB, soldering, connector orientation, and all power rails.
- Check for shorts between VBAT, 5V, 3V3, and GND.
- Use current-limited bench power for first power-up.
- Confirm regulator output before connecting sensors, receiver, GPS, or ESCs.

## Before Flight

- Verify the INAV target, mixer, motor outputs, receiver mapping, failsafe, and
  sensor orientation.
- Remove propellers for all bench tests.
- Confirm arming behavior, motor order, and failsafe before any hover test.
- Start with conservative PID/filter settings and short low-risk tests.

## Reporting Issues

For hardware review, use:

https://github.com/19379353560/skypilot/issues/1

For general discussion, use:

https://github.com/19379353560/skypilot/discussions/2
