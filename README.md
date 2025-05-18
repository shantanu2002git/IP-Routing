##IP Routing Cache Simulator using Splay Tree

A high-performance IP Routing Cache Simulator built in C++, featuring a self-adjusting Splay Tree for optimized routing and TTL-based LRU eviction, with support for packet history, load balancing, and full deletion support — all designed with clean OOP principles.

🚀 Key Features
🌳 1. Splay Tree Implementation
Fully functional Splay Tree with zig, zig-zig, and zig-zag rotations

Self-adjusting structure — frequently accessed IP nodes are moved to the root

⏱️ 2. TTL + LRU Cache Hybrid
Each IP node holds a Time-To-Live (TTL) value

Expired entries are marked and periodically cleaned

Mimics real-world caching behavior in routers

📦 3. Packet History Tracking
Each node maintains a history of packets

Tracks source, destination, packet size, and timestamp

❌ 4. Deletion Support
Fully supports node removal from the routing table

Ensures tree remains balanced after deletions

⚖️ 5. Load Balancing Across Subnets
Supports multiple subnet trees:

192.168.1.x

192.168.2.x

192.168.3.x

Packets are automatically routed to the correct subnet tree

🧱 6. OOP Architecture
Clean Object-Oriented Design for modularity & maintainability

Encapsulation of packet data, routing logic, and tree operations

Safe memory management via destructors

📊 Simulator Features
Simulates real-time packet flow

Visualizes internal routing tables

Demonstrates cache dynamics, LRU eviction, and packet routing logic

🔧 Technologies Used
C++

Object-Oriented Design

Custom Splay Tree + LRU logic

📂 Ideal For
Networking simulations

OS & systems course projects

Data structure visualizations

Advanced algorithmic interviews

📌 Upcoming Enhancements
CLI for real-time interaction

Graphical visualization of routing tables

IPv6 support

👨‍💻 Developed By
Shantanu Sahoo
Backend Engineer | C++ & Systems Enthusiast
