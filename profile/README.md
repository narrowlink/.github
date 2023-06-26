# Narrowlink
Narrowlink is a versatile and secure bidirectional reverse proxy server tool that simplifies network connectivity, sharing of internet access, and webserver publication. Whether you're working in restricted network configurations or seeking enhanced security, Narrowlink provides a reliable solution to connect, share, and publish with ease.
<p align="center">
<img src="https://github.com/narrowlink/docs/blob/main/docs/assets/NarrowLink-888.svg" width="50%" height="50%" alt="Narrowlink Logo">
</p>

## Key Features

-   **Seamless Connectivity**: Enjoy low-latency connections between network nodes with support for both TCP and UDP protocols.
-   **Share Internet Access**: Narrowlink's SOCKS protocol support allows you to share internet access with machines in highly restricted network configurations.
-   **Publish Webservers**: Easily publish webservers behind restrictive network configurations, granting secure access to web content over the internet.
-   **Automatic TLS Certificate Management**: Narrowlink takes care of TLS certificate management for secure and encrypted communication.
-   **Privacy and Security**: Your data is protected with end-to-end encryption using XChaCha20, ensuring confidentiality. Data signing with HMAC-SHA256 enhances security.
-   **Efficient Data Transportation**: Narrowlink optimizes data transport using HTTP (WebSocket) protocols, minimizing overhead while concealing usage patterns.
-   **Cross-Platform Compatibility**: Run Narrowlink on Windows, macOS, or Linux, ensuring flexibility across different platforms.
-   **Small Footprint**: With its small binary size, Narrowlink consumes minimal resources, making it efficient for various deployment scenarios.
-   **User Management**: The server component allows easy management of multiple clients and agents, each with their own accounts.


## How Narrowlink Works

Narrowlink consists of three main components: the client, the agent, and the server.

<p align="center">
<img src="https://github.com/narrowlink/docs/blob/main/docs/assets/Diagram.svg" width="50%" height="50%" alt="Narrowlink Logo">
</p>

1.  **Server**: The server acts as a central hub, managing user accounts, routing client requests, and handling HTTP traffic. It requires internet access and serves as a bridge between agents and clients.
2.  **Agent**: The agent, located on the destination side, establishes a connection with the server. It can operate in both restricted and normal network environments, serving as the endpoint for incoming client requests.
3.  **Client**: The client initiates a connection request to access resources behind restricted networks. It connects to the agent through the server, enabling secure and efficient communication.

The server plays a crucial role in managing users, routing requests, and handling HTTP traffic. This architecture allows for flexible deployment scenarios, accommodating agents and clients in different network configurations while ensuring connectivity and security.
    
## Getting Started
To quickly get started with Narrowlink, please refer to the [documentation](https://docs.narrowlink.com/). It provides step-by-step instructions on how to install Narrowlink, configure it to meet your specific requirements, and start using its powerful features.

## Sponsorship

Narrowlink is an open-source project that relies on community support. Consider becoming a sponsor to contribute to its ongoing development, maintenance, and future enhancements.

## Licensing

Narrowlink is licensed under the AGPL (Affero General Public License) for the server component and the MPLv2 (Mozilla Public License v2.0) for the client and agent components. Please refer to the repository's license files for more details.

## Future Plans

The Narrowlink development team is dedicated to expanding its capabilities, improving the user interface, and adding more features based on user feedback. Future plans include protocol expansion, enhanced user experience, and ensuring reliable network connectivity.

