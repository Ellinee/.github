# Eline

Eline connects families and caregivers with Eline Vest and Eline Radar for device monitoring and safety notifications at home.

## Repositories

| Repository | Stack | Purpose |
| --- | --- | --- |
| [Eline-Mobile](https://github.com/Ellinee/Eline-Mobile) | Expo, React Native, TypeScript | Household, device, account, and notification management |
| [Eline-Backend](https://github.com/Ellinee/Eline-Backend) | Express, Prisma, PostgreSQL | API, authentication, device events, and push notifications |
| [Eline-Webiste](https://github.com/Ellinee/Eline-Webiste) | Next.js, React, TypeScript | Product website, privacy information, and application downloads |
| [Eline-mmWave-IoT](https://github.com/Ellinee/Eline-mmWave-IoT) | ESP32, Arduino, LD2450 | Prototype Eline Radar firmware |

## System

The target architecture connects applications and devices through the backend, with PostgreSQL as the primary data store and Firebase Cloud Messaging for notifications.

Redis, Kafka, Prometheus, Grafana, and private object storage have been provisioned on Railway but are not yet integrated with the application. Firmware integration, device pairing, and validation of radar-based fall detection remain in development.

## Development

Each repository's README covers setup, environment configuration, and available checks. Never commit credentials, tokens, or device keys to source control.
