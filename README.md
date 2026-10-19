# Tello Control (showcase)

An Android flight controller for the Ryze/DJI Tello that speaks the drone's native Wi-Fi/UDP SDK protocol directly. Built as a maintainable Kotlin and Jetpack Compose app, not a demo.

> **This is a showcase repository.** The source code is private. Request access via [LinkedIn](https://id.linkedin.com/in/ferdinand-klasse).

## Status
Flight-tested on a real Tello: it connects, flies and responds correctly. Sensor/stick calibration is still being tuned.

## Features
- Live H.264 video with HUD
- Dual virtual sticks
- Telemetry and safety monitoring
- Flight logging
- Raw command console
- Simulation mode to run the whole stack without a drone

## Tech
Kotlin, Jetpack Compose, Android 10+ (API 29), UDP command and video streams. 138 Kotlin files, with written architecture, protocol, hardware-validation and troubleshooting docs.

## How it was built
Idea, requirements and testing by me, with AI-assisted coding.

## License
Copyright (c) 2026 Ferdinand Klasse. All rights reserved.

No permission is granted to copy, modify, distribute, or use this material or the related source code without written permission from the author.
