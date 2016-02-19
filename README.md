# freeze-scream
IoT project to alert user of freezer malfunction

## Hardware

  - Photon from https://store.particle.io
  - Temperature sensors (DS18b20): http://www.amazon.com/Vktech-DS18b20-Waterproof-Temperature-Transmitter/dp/B00CHEZ250

## Software

  - https://github.com/Hotaman/OneWireSpark

## Integrations
  - ifttt:
    - Particle -> IF (push notification)
    - Particle -> Gmail (email notifications and SMS)
    - Particle -> Drive (simple temp variable value tracking)
