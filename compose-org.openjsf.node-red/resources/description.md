# Node-RED

Node-RED is a flow-based programming tool for wiring together hardware devices, APIs, and online services in new and interesting ways. Built on Node.js, it provides a browser-based editor that makes it easy to create event-driven applications using a visual programming approach.

## Key Features

### Visual Flow Editor
- Intuitive browser-based flow editor with drag-and-drop interface
- Wide palette of pre-built nodes for common tasks
- Real-time deployment and testing of flows
- Built-in debugging and logging tools

### Extensive Node Library
- Over 5,000 community-contributed nodes available
- Core nodes for HTTP, MQTT, WebSocket, TCP/UDP, and more
- Database connectors (MySQL, MongoDB, InfluxDB, etc.)
- Social platform integrations (Twitter, Telegram, Slack)
- Cloud service connectors (AWS, Azure, Google Cloud)

### IoT and Integration Focused
- Native MQTT support for IoT device communication
- Easy integration with industrial protocols (Modbus, OPC-UA)
- Dashboard nodes for creating real-time monitoring UIs
- GPIO access for Raspberry Pi and other hardware platforms

### Low-Code Development
- Create complex workflows without extensive coding
- Function nodes for custom JavaScript logic when needed
- Template nodes for HTML, JSON, and text manipulation
- Context storage for maintaining state across flows

## Use Cases

- **Home Automation**: Connect smart devices and create automation rules
- **IoT Data Processing**: Collect, process, and visualize sensor data
- **API Integration**: Bridge different services and APIs together
- **Industrial Automation**: SCADA systems and manufacturing process control
- **Prototyping**: Rapidly prototype and test integration scenarios
- **Dashboard Creation**: Build real-time monitoring and control interfaces

## Architecture

Node-RED runs as a Node.js application, providing a web server for the editor and runtime for executing flows. Flows are stored as JSON and can be version controlled. The modular architecture allows easy extension through custom nodes.

## Projects Feature

Node-RED's Projects feature enables version control integration (Git), making it easy to:
- Track changes to your flows
- Collaborate with team members
- Manage different versions and environments
- Share flows through repositories

## Getting Started

This deployment provides Node-RED with persistent storage for your flows and configuration. Access the editor through your browser on the configured port (default 1880), and start creating flows immediately. The credential secret ensures your sensitive data is encrypted at rest.

For detailed documentation and tutorials, visit [nodered.org](https://nodered.org)
