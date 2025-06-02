# TomoSense

A modular IoT sensor dashboard ecosystem that collects, visualizes, and automates sensor data from your 37-sensor kit (and more in the future) via ESP32, Bluetooth, and WiFi, using an expandable microservice-based architecture.

```bash
tomo-sense/
├── esp32_firmware/             # Arduino/PlatformIO code
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── db/
│   │   └── models/
│   └── main.py
├── frontend/
│   └── src/
│       ├── components/
│       └── pages/
├── docker/
│   ├── docker-compose.yml
│   └── grafana/
└── docs/
    └── sensor_docs.md
```
