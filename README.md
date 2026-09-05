# Electric Vehicle (EV) Powertrain Telemetry & ThingsBoard Edge Monitoring

[![Platform: Orange Pi SBC](https://img.shields.io/badge/Host-Orange%20Pi%20SBC%20(NVMe)-red.svg)]()
[![Platform: ThingsBoard IoT](https://img.shields.io/badge/Platform-ThingsBoard%20IoT%20Gateway-blue.svg)]()
[![Protocol: MQTT / CAN-Bus](https://img.shields.io/badge/Protocol-MQTT%20%2F%20CAN--Bus-green.svg)]()
[![Target: Electric Vehicle](https://img.shields.io/badge/Target-Electric%20Vehicle%20Powertrain-orange.svg)]()

Industrial telemetry and fleet monitoring station for lightweight electric vehicles (EVs). Houses edge server deployment configurations on Single Board Computers (Orange Pi with high-speed NVMe storage), ThingsBoard IoT telemetry pipelines, and interactive vehicle telemetry dashboards.

---

## ⚡ Key Capabilities

- **Real-Time Battery Management System (BMS) Telemetry**:
  - Continuous tracking of pack voltage, cell balance, bus current, state-of-charge (SoC), and thermal sensors.
- **ThingsBoard Dashboard Integration**:
  - Includes pre-configured ThingsBoard dashboard export (ev-power_monitoring(2).json) featuring real-time speedometer, power wattage gauges, historical energy consumption graphs, and battery health indicators.
- **Ruggedized Edge Server Deployment**:
  - Technical runbook for provisioning high-reliability SBC operating systems (Orange Pi OS) running off fast NVMe PCIe storage instead of fragile SD cards for vehicle vibration resistance.
  - On-vehicle standalone Wi-Fi Access Point configuration for field diagnostics and wireless telemetry upload.

---

## 📄 License

MIT License © [Fitra Nurmayadi](https://github.com/fitranurmayadi).