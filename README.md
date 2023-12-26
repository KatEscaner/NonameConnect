# NonameConnect: A Decentralized Social Network in Rust

NonameConnect is an open-source project that aims to build a decentralized social network using the Rust programming language. Inspired by privacy, security, and user empowerment, NonameConnect leverages Rust's performance and safety features to create a robust and resilient network.

## Key Features

1. **Peer-to-Peer (P2P) Connections**: NonameConnect supports both P2P and public connections. In P2P mode, users can directly connect using their public IP addresses and specified ports. These connections enable secure file sharing and multimedia exchange.

2. **Public Connections**: Public servers act as hubs, allowing users to connect without knowing each other's IP addresses. Users can share content within these hubs, and the server assigns friendly aliases ("noname") to enhance user experience.

3. **Shared Content**: NonameConnect organizes shared content in a folder called "share." Each user's folder is named after their IP address. Inside, multimedia files are associated with metadata (creation date, comments) in JSON format. Additionally, a "public" subfolder allows content to be shared across all connections.

4. **Front-End with Tauri and React**: The user interface combines Tauri (for cross-platform desktop apps) and React (for web-based interactions). Users can seamlessly navigate the network, view shared content, and manage connections.

5. **Tokio for Asynchronous Communication**: NonameConnect relies on Tokio for asynchronous communication between servers. Tokio's event-driven model ensures efficient data exchange and responsiveness.
