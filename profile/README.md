# Eline

Eline connects families and caregivers with Radar and Vest devices for non-medical home monitoring and safety notifications.

Radar fall inference is experimental and not field-validated. Vest provides IoT telemetry only, with no AI or fall detection.

## Repositories

| Repository | Purpose | Stack |
| --- | --- | --- |
| [Eline-Mobile](https://github.com/Ellinee/Eline-Mobile) | Household, device, account, and notification management | Expo, React Native, TypeScript, NativeWind, FCM |
| [Eline-Backend](https://github.com/Ellinee/Eline-Backend) | Main API, access control, safety notifications, and event delivery | Express, TypeScript, Prisma, PostgreSQL, Kafka, Redis, FCM |
| [Eline-Webiste](https://github.com/Ellinee/Eline-Webiste) | Product website, privacy information, and Android downloads | Next.js, React, TypeScript, Tailwind CSS |
| [Eline-Radar-IoT](https://github.com/Ellinee/Eline-Radar-IoT) | Radar and environmental sensor firmware | ESP32, Arduino, LD2450, DHT22, MQTT/WSS |
| [Eline-Vest-IOT](https://github.com/Ellinee/Eline-Vest-IOT) | Wearable motion telemetry; IoT only, no AI | ESP32-C3, Arduino, MPU6050, MQTT/WSS |
| [Eline-AI-Radar](https://github.com/Ellinee/Eline-AI-Radar) | Experimental Radar datasets, training, and model artifacts | Python, Jupyter, NumPy, pandas, scikit-learn RandomForest |
| [Eline-Radar-BE](https://github.com/Ellinee/Eline-Radar-BE) | Experimental Radar inference and raw Vest telemetry gateway | FastAPI, scikit-learn RandomForest, MQTT, Kafka, PostgreSQL |
