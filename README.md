# Network Configuration: DNS, Email, IoT, IPv6, IPv4 with Packet Tracer

This repository contains the files and configurations for a complex network setup, including DNS, web, and email servers, as well as IoT device control and IPv6/IPv4 tunneling. This project was developed as part of the CNCO2000 course assignment at Curtin University.

## Project Overview

The objective of this project is to configure a complex network to enable communication between multiple sites. The network setup includes DNS and email servers, IoT device control, FTP server configuration, and static NAT/PAT for public access. The configuration and validation of network connectivity are performed using Cisco Packet Tracer.

## Features

- **IPv6 and IPv4 Configuration**: Set up a dual-stack network with both IPv6 and IPv4 addressing.
- **DNS and Email Servers**: Configure DNS and email servers for internal and external communications.
- **IoT Device Control**: Set up an IoT server to control IoT devices like lamps.
- **FTP Server Configuration**: Establish an FTP server for file transfers.
- **Network Address Translation (NAT)**: Configure static NAT and PAT for public access to internal servers.
- **Tunneling**: Configure IPv6 tunnels for communication between different sites.

## Technologies Used

- **Cisco Packet Tracer v7.3.1**: Network simulation and configuration tool.
- **Networking Protocols**: IPv6, IPv4, DNS, SMTP, FTP, HTTP.
- **Network Services**: DNS Server, Web Server, Email Server, IoT Server.

## Configuration Components

### C1: Configure IPv6 Network

- Set up IPv6 addressing for PCs and routers.
- Configure IPv6 tunnels for inter-site communication.

### C2: Configure DNS/Web/Email Servers

- Configure DNS and email servers for the domains "curtin.com" and "cenergy.com".
- Ensure local accessibility of the servers.

### C3: Configure Office Networks

- Subnetting and configuring networks for Office A and Office B.
- Set up an IoT server to control IoT devices.

### C4: Configure WAN Network

- Configure WAN router interfaces with static IPs.
- Set up static routes for WAN connectivity.

### C5: Configure NAT (Network Address Translation) for Public Access

- Configure static NAT and PAT for public access to internal servers.

### C6: Validate Network Connectivity

- Create and test scenarios in Packet Tracer to ensure network connectivity.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RJTLM/Network-Configuration-DNS-Email-IoT-IPv6-IPv4-PacketTracer.git
   ```
2. **Open the Packet Tracer file**: Use Cisco Packet Tracer v7.3.1 to open the provided `.pkt` file.
3. **Follow the configuration steps**: Refer to the provided documentation and configuration scripts to set up and validate the network.

## Repository Structure

- `Assignment-T03.pkt`: Packet Tracer file containing the network configuration.
- `Documentation/`: Contains detailed configuration steps and diagrams.
- `Scripts/`: Contains any necessary configuration scripts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was developed as part of the CNCO2000 Computer Communications course assignment at Curtin University.
