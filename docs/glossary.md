# Glossary

- **VPN**: Virtual Private Network; a technology that encrypts internet traffic to ensure privacy and security.  
- **WireGuard**: A modern, high-performance VPN protocol that utilizes state-of-the-art cryptography for secure network connections.  
- **Interface**: The configuration block in WireGuard that specifies connection settings such as private keys and listening ports.  
- **Peer**: A device (server or client) connected to the VPN network.  
- **Endpoint**: The public IP address and port associated with the WireGuard server, which peers use to establish connections.  
- **Public Key**: A cryptographic key shared with peers to encrypt data transmitted over the VPN.  
- **Private Key**: A confidential cryptographic key used to decrypt received data; it must be kept secure.  
- **Handshake**: The initial cryptographic process through which peers exchange keys and establish a secure communication session.  
- **Tunnel**: The encrypted pathway established between VPN endpoints for secure data transmission.  
- **AllowedIPs**: Specifies the IP ranges or subnets that are routed through the VPN tunnel.  
- **NAT (Network Address Translation)**: A technique that modifies network address information in IP packet headers while in transit, allowing multiple devices to share a single public IP.  
- **PersistentKeepalive**: A setting (typically 25 seconds by default) that helps maintain a NAT mapping by sending periodic keepalive messages, preventing timeouts.
