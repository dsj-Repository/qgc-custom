<div align="center">

# qgc-custom

**Professional QGroundControl customization for drone OEMs, integrators, and research teams.**

[中文](./README.zh-CN.md) · **English**

Built on Qt 6.x · C++17 · CMake · MAVLink · PX4 / ArduPilot

</div>

---

## What this is

A personal QGroundControl distribution and a public portfolio for **commercial QGC customization services**.

If you need a ground station that does *exactly* what your drone needs — not what off-the-shelf QGC does out of the box — this is what I do for a living.

## Who I work with

- **Drone OEMs** (industrial, agricultural, inspection, surveying, security)
- **System integrators** building turnkey UAV solutions
- **Research labs** and **universities** needing custom mission profiles
- **Flight controller vendors** shipping QGC as their reference GCS

## What I can build

### UI & branding
- Custom QML views, controls, toolbars
- Full re-skinning (theme, logos, splash, packaging)
- Tablet-optimized layouts (Android / iPad)

### Protocol & telemetry
- Custom MAVLink messages and dialects
- Multi-vehicle / swarm support
- Custom data link integration (4G/5G, mesh radios, satellite)
- Telemetry pipeline to cloud backends

### Mission planning
- Industry-specific mission item types (survey, spray, inspection patterns)
- Geofencing, no-fly zone enforcement, safety logic
- KML / GeoJSON / Shapefile import-export
- Offline map tile pipelines

### Payload & integration
- Gimbal, camera, sensor control
- AI inference overlays (object detection, segmentation)
- Real-time video streaming and recording
- Custom backend / fleet management connection

### Platform & build engineering
- **Qt 5 → Qt 6 migration** (a frequent pain point I've solved)
- Windows MSI packaging with code signing
- Android build pipeline for tablets
- GitHub Actions CI/CD
- Performance profiling and waypoint UI optimization

## Why work with me

- **Active Qt 6.x development experience** — many QGC consultants are still stuck on Qt 5
- **Windows-first toolchain mastery** (MSVC 2022) — the trickiest QGC build target
- **Embedded background** — I also do MCU + RTOS firmware, so I can debug the *whole stack* from flight controller to UI
- **Hardware access** — I can prototype with real PX4 / ArduPilot vehicles, not just simulators
- **AI-augmented workflow** — same scope, faster turnaround, lower price for you

## Project status

Active development. Public commits are landed progressively. Some commercial work is under NDA and is not visible here — feel free to ask for redacted case references.

## Engaging me

See **[docs/services.md](./docs/services.md)** for service tiers, typical pricing, and how the engagement process works.

Sample anonymized case studies will be added to **[docs/cases/](./docs/cases/)** as projects allow disclosure.

## Contact

- **Email**: `757010322@qq.com` 


When reaching out about commercial work, please include:
1. Project description and goals
2. Target flight stack and hardware (e.g. *ArduPilot on Pixhawk Cube Orange*)
3. Timeline
4. Indicative budget range — speeds up the proposal by a lot

## License

This repository is licensed under **Apache License 2.0** — consistent with upstream QGroundControl. See [LICENSE](./LICENSE).

QGroundControl is a trademark of the Dronecode Foundation. This is an independent customization and distribution effort and is not officially endorsed by the upstream project.
