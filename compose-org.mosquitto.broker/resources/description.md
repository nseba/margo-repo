# Eclipse Mosquitto MQTT Broker

Eclipse Mosquitto is an open-source (EPL/EDL licensed) message broker that implements the MQTT protocol versions 5.0, 3.1.1, and 3.1. MQTT provides a lightweight method of carrying out messaging using a publish/subscribe model, making it ideal for Internet of Things (IoT) applications and machine-to-machine communication.

## Key Features

### Lightweight and Efficient
- Small footprint with minimal resource requirements
- Ideal for embedded systems and resource-constrained devices
- Supports thousands of concurrent connections on modest hardware

### MQTT Protocol Support
- Full support for MQTT 5.0, 3.1.1, and 3.1
- Quality of Service (QoS) levels 0, 1, and 2
- Retained messages and last will and testament
- Persistent sessions for reliable message delivery

### Security
- TLS/SSL encryption with OpenSSL support
- Username and password authentication
- Access control lists (ACLs) for fine-grained permissions
- Client certificate authentication

### Connectivity
- Standard MQTT port (1883) for unencrypted connections
- Secure MQTT port (8883) for TLS/SSL connections
- WebSocket support for browser-based clients
- Bridge support for connecting multiple brokers

## Use Cases

- **IoT Device Communication**: Connect sensors, actuators, and smart devices
- **Home Automation**: Control and monitor smart home devices
- **Industrial Automation**: SCADA systems and real-time monitoring
- **Mobile Applications**: Push notifications and real-time messaging
- **Telemetry**: Collect and distribute sensor data at scale

## Architecture

Mosquitto operates as a message broker, receiving messages from publishers and routing them to subscribers based on topic filters. The publish/subscribe pattern decouples message producers from consumers, enabling scalable and flexible communication architectures.

## Getting Started

This deployment includes the Mosquitto broker with OpenSSL support, enabling secure TLS/SSL connections out of the box. Configure ports, persistence, logging, and authentication settings through the provided parameters to customize the broker for your specific needs.

For detailed documentation, visit [mosquitto.org](https://mosquitto.org)
