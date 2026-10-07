# Pulse Water Dashboard

Smart-water monitoring, AIoT visualization, SCADA-style control, PWA operation, simulated telemetry, and optional ThingSpeak integration.

## Overview

PULSE is the software interface for an IoT-based intelligent water conservation and monitoring workflow. The public release focuses on the dashboard, visualization, SCADA interaction, alarm handling, PWA experience, and data-source integration layer.

The current release can be evaluated in simulation mode and is structured for later connection to validated field telemetry.

## Current capabilities

- SCADA-style system overview
- Real-time charts and monitoring cards
- Alarm center and browser notifications
- Device-information and system-topology panels
- Simulation mode for reproducible demonstrations
- Optional ThingSpeak data-source adapter
- PWA installation and offline support
- Responsive desktop/mobile interface
- Settings, camera, control, and status modules

## Deployment

This is a static HTML/CSS/JavaScript application. It can be deployed on GitHub Pages, Netlify, or another static host.

## Integration

The software layer is designed around an ESP32 → data service → dashboard workflow. Public v1.0.0 focuses on the web interface and integration architecture; field hardware and firmware can be connected incrementally as validated deployments become available.

## Project context

Developed from an international smart-systems / IoT project experience and maintained as an independent software implementation for smart-water monitoring, visualization, and public demonstration.

## Version

Current public version: **v1.0.0**

## License

Source code is published for technical demonstration and further development. Third-party libraries retain their respective licenses.
