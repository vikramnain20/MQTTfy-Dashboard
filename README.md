# MQTTfy Dashboard for web
Your Unified Dashboard: Visualize MQTT, API &amp; Bluetooth Data with an AI Assistant. In Any Language.
 [MQTTfy](https://mqtt-ble.com) provides a powerful, real-time, and configurable dashboard to monitor and interact with your MQTT Bluetooth Rest API-enabled devices and applications. Perfect for IoT, IIoT, and home automation.
 
[The Internet of Things (IoT)](https://mqtt-ble.com) landscape has exploded with a diverse array of protocols, devices, and communication methods. Managing multiple devices across different protocols —[MQTT](https://mqtt-ble.com),[REST API](https://mqtt-ble.com), and [Bluetooth](https://mqtt-ble.com) — has traditionally required separate applications and complex integrations. MQTTfy unified dashboard emerges as a game-changing solution that consolidates all these communication channels into a single, powerful, and intuitive platform for real-time monitoring, control, and visualization of IoT devices.
In this comprehensive guide, we’ll explore how MQTTfy revolutionizes IoT device management through its multi-protocol support, extensive widget library, custom JavaScript capabilities, multilingual interface, and cutting-edge Web Bluetooth API integration for smart home automation.

Understanding the Need for Unified IoT Dashboards
Modern IoT ecosystems are inherently complex, with devices communicating through various protocols. MQTT ([Message Queuing Telemetry Transport](https://mqtt-ble.com)) has become the backbone of industrial IoT due to its lightweight nature and [publish-subscribe](https://mqtt-ble.com) architecture. Meanwhile, REST APIs provide flexibility for web-based integrations, and Bluetooth Low Energy (BLE) enables direct device-to-device communication for smart home applications. Managing these disparate systems traditionally required multiple applications, leading to fragmented workflows and reduced operational efficiency.​

## MQTTfy addresses this challenge by providing a unified interface that seamlessly integrates all major IoT communication protocols. This consolidation eliminates the need for switching between multiple dashboards, reduces training overhead, and provides a single source of truth for all IoT data.​

Core Features of [MQTTfy Unified Dashboard](https://mqtt-ble.com)
Multi-Protocol Support: MQTT, REST API, and Bluetooth Integration
The foundation of MQTTfy’s power lies in its comprehensive protocol support. The platform connects to MQTT brokers using industry-standard connections, supporting all three Quality of Service ([QoS](https://mqtt-ble.com)) levels — QoS 0 (at most once), QoS 1 (at least once), and QoS 2 (exactly once) — ensuring reliable message delivery based on application requirements.​

## For REST API integration, MQTTfy enables seamless data exchange between web services and IoT devices. This bidirectional communication allows the central dashboard to send control commands through REST API interfaces while receiving real-time data through MQTT protocols. This hybrid approach combines the real-time performance of MQTT with the flexibility and wide compatibility of REST APIs.​

## What truly sets MQTTfy apart is its implementation of the Web Bluetooth API for direct browser-to-device communication. Through Web Bluetooth integration, users can connect to Bluetooth Low Energy devices directly from their web browser without requiring native applications or plugins. This capability is transformative for smart home automation, enabling users to control lights, thermostats, door locks, and security systems directly from the dashboard.​

The Web Bluetooth API works through a discovery process that identifies available BLE devices and services, then provides access to the GATT (Generic Attribute Profile) for reading and writing data to device characteristics. MQTTfy leverages this technology to create a seamless experience where users can scan for nearby devices, establish secure connections, and control them — all within a single dashboard interface.​

## Extensive Widget Library for Data Visualization
MQTTfy provides a comprehensive collection of pre-built widgets designed for diverse visualization and control needs. The widget library includes:​

Charts and Graphs: Line charts, bar graphs, pie charts, and real-time streaming charts for visualizing time-series sensor data
Gauges and Indicators: Circular gauges, linear meters, and LED indicators for displaying temperature, pressure, speed, and other measurements
Text Displays: Dynamic text boxes that update in real-time with sensor readings and device status
Interactive Controls: Buttons, switches, sliders, and toggles for sending commands to devices
Maps: Geolocation widgets for tracking assets, vehicles, and mobile sensors
Image Feeds: Camera widgets for displaying live video feeds from API sources​
Iframe Widgets: Embed external web pages directly into your dashboard for extended functionality​
Each widget is fully configurable, allowing users to customize colors, thresholds, update intervals, and data sources to match their specific requirements. The dashboard supports multiple layouts optimized for different screen sizes, from large 4K displays in control rooms to mobile devices for field operators.​


MQTTfy Home automation with ESP32 Microcontroller
Custom JavaScript Widgets: Unlimited Flexibility
While the pre-built widget library covers most common use cases, MQTTfy recognizes that every IoT application has unique visualization needs. The platform’s custom JavaScript widget capability empowers developers to create any type of widget using HTML, CSS, and JavaScript.​

The custom widget framework provides a comprehensive JavaScript API that includes initialization functions, data operation methods, and lifecycle callbacks. Developers can create widgets that:​

Implement custom data transformations and calculations
Integrate third-party visualization libraries (D3.js, Chart.js, Three.js)
Create industry-specific displays (SCADA symbols, process flow diagrams, facility maps)
Build interactive control interfaces with complex logic
Fetch data from multiple sources and combine them in novel ways​.
The widget development process is streamlined through a built-in code editor within the dashboard interface. Developers can write HTML markup, CSS styling, and JavaScript logic in separate tabs, with real-time preview capabilities. Once created, custom widgets can be saved, shared across multiple dashboards, and reused throughout the organization.​​

For teams looking to standardize their visual language, custom widgets enable the implementation of corporate branding, industry-specific terminology, and compliance-required displays. This level of customization ensures that MQTTfy can adapt to virtually any industrial, commercial, or residential IoT application.​

Multilingual Interface: Global Accessibility
In today’s globalized world, IoT solutions must support international teams and customers. MQTTfy incorporates comprehensive multilingual support, allowing the entire interface to be displayed in the user’s preferred language.​​

## The internationalization system goes beyond simple UI translation. MQTTfy enables customization of:

Dashboard titles and descriptions
Widget labels and legends
Device names and categories
Telemetry keys and variable names
Alert messages and notifications
Help documentation and tooltips​​
The multilingual capabilities work through a translation key system where interface elements are assigned keys that map to language-specific values. Administrators can create translation maps for any supported language, and users can switch between languages seamlessly without losing their dashboard configuration.​​

This feature proves invaluable for multinational organizations managing IoT deployments across different regions, international equipment vendors serving global markets, and smart home solution providers targeting diverse consumer markets. By presenting information in the user’s native language, MQTTfy reduces training time, minimizes errors, and improves overall user experience.​

## MQTT: The Foundation of Real-Time IoT Communication
To understand why MQTTfy centers on MQTT as its primary protocol, it’s essential to understand MQTT’s advantages for IoT applications.​

MQTT is a lightweight, publish-subscribe messaging protocol designed specifically for constrained devices and unreliable networks. Its key characteristics include:​

Minimal Overhead: MQTT headers are as small as 2 bytes, making it ideal for low-bandwidth environments and battery-powered devices​
Publish-Subscribe Model: Devices publish data to topics, and interested parties subscribe to those topics, enabling efficient one-to-many communication​
Bidirectional Communication: Supports both device-to-cloud telemetry and cloud-to-device commands​
Quality of Service Levels: Three QoS options ensure messages are delivered with the appropriate reliability for each use case​
Persistent Sessions: Clients can reconnect and receive messages sent while offline​
Last Will and Testament: Automatic notifications when devices disconnect unexpectedly​
MQTT in [Industrial IoT](https://mqtt-ble.com) Applications
In industrial settings, MQTT has become the de facto standard for machine-to-machine communication. MQTTfy leverages MQTT to enable:
​Real-Time Machine Monitoring: Track machinery status, sensor readings (temperature, pressure, vibration), and production line performance with sub-second latency.​
Predictive Maintenance: Collect continuous data from industrial equipment to predict failures, schedule maintenance proactively, and reduce downtime. For example, vibration sensors on motor bearings can publish data via MQTT, triggering alerts when patterns indicate impending failure.​
Supply Chain Visibility: Monitor goods in transit, warehouse conditions, and fleet management using MQTT-enabled sensors and GPS trackers.​
Unified Namespace Architecture: MQTT serves as the backbone for creating a centralized data repository where all plant data resides, enabling real-time access across enterprise systems.​
By building on MQTT’s robust foundation, MQTTfy provides industrial organizations with the reliability, scalability, and real-time performance required for modern manufacturing and automation.
Web Bluetooth API: Revolutionizing Smart Home Automation
One of MQTTfy’s most innovative features is its integration of the Web Bluetooth API for smart home automation. This technology represents a paradigm shift in how users interact with Bluetooth-enabled smart home devices.​

How Web Bluetooth Works in MQTTfy
The Web Bluetooth API is a JavaScript interface that enables web applications to discover, connect to, and communicate with Bluetooth Low Energy devices directly from a browser. The process works through several stages:​

Device Discovery: When a user initiates a connection, MQTTfy requests access to nearby Bluetooth devices using the navigator.bluetooth.requestDevice() method.​
User Authorization: The browser displays a native dialog allowing users to select which device to connect to, ensuring security and user consent.​
GATT Connection: Once authorized, the application establishes a GATT (Generic Attribute Profile) connection to access the device’s services and characteristics.​
Data Exchange: MQTTfy can then read sensor data, write control commands, and subscribe to real-time notifications from the device.​
All of this happens without requiring any native applications or plugins — users simply open the dashboard in a compatible browser (Chrome, Edge, Opera on desktop and Android).​

Smart Home Automation Use Cases
The Web Bluetooth integration in MQTTfy enables numerous smart home applications:
Lighting Control: Connect to BLE-enabled smart bulbs to adjust brightness, color temperature, and create lighting scenes — all from the dashboard.​
Climate Management: Interface with smart thermostats and temperature sensors to monitor and control heating, cooling, and ventilation systems.​
Security Systems: Control BLE door locks, monitor motion sensors, and receive real-time alerts without separate mobile apps.​
Health Monitoring: Connect to BLE fitness trackers, heart rate monitors, and medical devices for health data visualization.​
Asset Tracking: Use BLE beacons to track items within your home or facility, displaying their location on the dashboard map widget.​

The beauty of this approach is consolidation — instead of juggling multiple proprietary apps from different device manufacturers, users control everything through the unified MQTTfy interface. This dramatically improves the smart home experience and reduces the complexity barrier that has historically limited smart home adoption.​

Building Custom Dashboards: From Concept to Deployment
MQTTfy’s flexibility shines when creating custom dashboards tailored to specific applications. The platform supports multiple dashboard types optimized for different use cases.​

Static vs. Dynamic Dashboards
Static dashboards display data from predetermined devices and variables. These are ideal for monitoring specific equipment or processes where the data sources don’t change.​

Dynamic dashboards include a device selector that allows users to switch between different devices or groups without reconfiguring widgets. All widgets automatically update to display data from the selected device, making these perfect for managing fleets of similar equipment or multi-tenant installations.​

Dashboard Design Best Practices
When creating dashboards in MQTTfy , consider these proven design principles:​
Information Hierarchy: Place critical information and alerts at the top of the dashboard, with detailed charts and historical data below.​
Drill-Down Navigation: Design dashboards with multiple levels — start with system overview, then allow users to click through to subsystems and individual devices.​
Responsive Layouts: Configure separate layouts for desktop and mobile viewing to ensure optimal display on all devices.​
Color Coding: Use consistent color schemes to indicate status (green for normal, yellow for warning, red for critical).​
Real-Time Updates: Configure appropriate update intervals — critical data may need sub-second updates, while historical trends can refresh less frequently.​

Sharing and Collaboration
MQTTfy supports multiple collaboration features to facilitate team workflows:​

Dashboard Export: Save dashboard configurations as JSON files for backup and version control​
Read-Only Links: Share dashboards with stakeholders via unique URLs that provide view-only access​
User Permissions: Implement role-based access control to restrict who can view, edit, or control specific devices​
Multi-Device Access: Access the same dashboard from multiple locations and devices simultaneously​.
Real-World Applications and Use Cases
MQTTfy serves diverse industries with specific IoT monitoring and control requirements:

Manufacturing and Industry 4.0
In smart factories, MQTTfy connects PLCs, SCADA systems, industrial sensors, and enterprise applications (MES, ERP) to provide unified visibility across the production environment. Real-time dashboards display OEE (Overall Equipment Effectiveness), machine status, quality metrics, and energy consumption. When anomalies occur, the system automatically alerts maintenance teams via MQTT publish to alert topics.​

Smart Buildings and Facilities Management
Building managers use MQTTfy to monitor HVAC systems, lighting, access control, and energy meters across multiple facilities. The platform’s ability to integrate REST APIs with MQTT streams enables connections to diverse building management systems. Web Bluetooth support allows direct connection to BLE sensors for temperature, humidity, occupancy, and air quality monitoring.​

Agriculture and Environmental Monitoring
Agricultural IoT deployments leverage MQTTfy to monitor soil moisture, temperature, rainfall, and crop conditions across distributed fields. The lightweight MQTT protocol is ideal for remote locations with limited connectivity, while the dashboard provides farmers with actionable insights for irrigation scheduling and pest management.​

Fleet Management and Logistics
Transportation companies use MQTTfy to track vehicle locations, monitor fuel consumption, receive maintenance alerts, and optimize routes. GPS-enabled trackers publish location data via MQTT, which appears on the dashboard’s map widgets in real-time.​

Healthcare and Remote Patient Monitoring
Healthcare providers leverage MQTTfy’s Bluetooth integration to connect to medical devices and wearables, displaying vital signs (heart rate, blood pressure, glucose levels) on centralized monitoring dashboards. This enables remote patient monitoring and early intervention when readings indicate potential health issues.​

Getting Started with MQTTfy
Beginning your journey with MQTTfy is straightforward:

Connect Your MQTT Broker: Enter your broker address, port, and authentication credentials to establish the connection.​
Configure Data Sources: Add REST API endpoints and enable Web Bluetooth access for direct device connections.​
Create Your First Dashboard: Choose from templates or start with a blank canvas.​
Add Widgets: Select from the widget library and configure them to display your data.​
Customize with JavaScript: For advanced needs, create custom widgets using the built-in code editor.​
Set Up Alerts and Automation: Configure threshold-based alerts and automated responses.​
Share and Collaborate: Export configurations, generate read-only links, and invite team members.​
The AI Assistant: Intelligent Support
MQTTfy includes a built-in AI chat assistant that provides contextual help, configuration guidance, and even performs data analysis. Users can ask questions like “How do I connect to my MQTT broker?” or “Show me the average temperature over the last week,” and receive immediate, actionable responses. This AI integration reduces the learning curve and accelerates dashboard development.​

Conclusion: The Future of Unified IoT Management
As IoT ecosystems continue to expand in complexity and scale, the need for unified management platforms becomes increasingly critical. MQTTfy addresses this need by consolidating MQTT, REST API, and Bluetooth protocols into a single, powerful dashboard environment.

The combination of extensive pre-built widgets, unlimited custom JavaScript flexibility, IoT agent protocol translation, multilingual support, and cutting-edge Web Bluetooth API integration positions MQTTfy as the comprehensive solution for IoT monitoring and control across industrial, commercial, and residential applications.​

Whether you’re managing a smart factory with thousands of sensors, monitoring a fleet of vehicles, controlling a smart home, or overseeing distributed environmental monitoring systems, MQTTfy provides the tools, flexibility, and integration capabilities to transform raw IoT data into actionable insights and effective control.

By breaking down protocol barriers and providing a truly unified interface, MQTTfy represents the next evolution in IoT dashboard technology — one where seamless connectivity, intelligent visualization, and user-centered design converge to unlock the full potential of connected devices.


## 🚀 How to Run in docker free full version
To start the dashboard immediately, run the following command in your terminal:

```bash
docker run -d -p 8080:8080 mqttfy/mqttfy-dashboard:latest
