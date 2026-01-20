*This project has been created as part of the 42 curriculum by rsommer.*

# NetPractice

## Description

NetPractice is a networking project from the 42 curriculum designed to introduce the basics of computer networking. The goal is to configure small-scale networks by solving 10 levels of networking problems, making non-functioning network diagrams work properly.

Through this project, you will learn how to:
- Configure IP addresses
- Connect devices through routers
- Understand the role of a gateway within a network
- Apply TCP/IP addressing concepts including subnet masks and default gateways

## Instructions

### Running the Training Interface

1. Extract the `net_practice.1.6.tgz` file (or use the already extracted `net_practice/` folder)
2. Open `net_practice/index.html` in a web browser
   - **Important**: Use Google Chrome or a Chromium-based browser (Firefox may not work properly)
3. Enter your intranet login in the field provided
4. Click "Start!" to begin training

### Solving Levels

- Each level presents a non-functioning network diagram
- Modify the unshaded fields (IP addresses, masks, routes) until the network configuration is correct
- Use **[Check again]** to verify your configuration
- Use **[Get my config]** to export your configuration file
- When a level is completed, click **[Next level]** to proceed

### Exporting Configurations

Before moving to the next level:
1. Click the **[Get my config]** button
2. Save the downloaded configuration file
3. The file will be named according to the level (e.g., `level1.json`)

### Submission Requirements

- 10 exported configuration files (one per level) must be placed at the root of the repository
- Make sure to enter your login in the training interface before exporting
- File naming should correspond to each level completed

## Resources

### Networking Concepts Studied

- **TCP/IP Addressing**: The fundamental protocol suite for internet communication, defining how data is packetized, addressed, transmitted, routed, and received
- **Subnet Mask**: A 32-bit number that divides an IP address into network and host portions, determining which part identifies the network and which identifies the device
- **Default Gateway**: The router interface that serves as the access point to other networks; devices send packets to the gateway when the destination is outside their local network
- **Routers**: Network devices that forward data packets between computer networks, operating at Layer 3 (Network layer) of the OSI model
- **Switches**: Network devices that connect devices within the same network, operating at Layer 2 (Data Link layer) of the OSI model
- **OSI Layers**: The seven-layer model (Physical, Data Link, Network, Transport, Session, Presentation, Application) that standardizes network communication functions

### Reference Materials

- RFC 791 - Internet Protocol (IP)
- RFC 1918 - Address Allocation for Private Internets
- CIDR (Classless Inter-Domain Routing) notation for subnet masks

### AI Usage

AI tools were used in this project for:
- Generating this README documentation structure
- Clarifying networking concepts and terminology
- All AI-generated content was reviewed and validated for accuracy
