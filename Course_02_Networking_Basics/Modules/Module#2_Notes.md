# 🌐 Module 2: Network Components, Types, and Connections

> **Course:** Networking Basics  
> **Objective:** Explain network types, components, and connections.

---

## 📚 Module Overview

This module covers three major topics:

- 👥 **Clients and Servers**
- 🧩 **Network Components**
- 🌍 **ISP Connectivity Options**

---

# 2.1 👥 Clients and Servers

## 🎯 Learning Objective

- Explain the roles of **clients and servers** in a network.

## 🖥️ Host

A **host** is any computer or device connected to a network that participates directly in network communication.

A host can:

- 📤 Send messages
- 📥 Receive messages
- 👤 Act as a client
- 🖥️ Act as a server
- 🔄 Act as both

> 💡 **Key Point:** The software installed on a computer determines the role it performs.

## 🖥️ Server

A **server** is a host running software that provides information or services to other hosts.

### Examples

- 📧 **Email server** — provides email services
- 🌐 **Web server** — provides web pages
- 📁 **File server** — stores and provides files

Each service requires appropriate server software.

## 💻 Client

A **client** is a host running software that requests and displays information or uses services provided by a server.

### Examples of Client Software

- 🌐 Chrome, Edge, Firefox, Safari
- 📧 Microsoft Outlook
- 📁 File access software

### 🔄 Client–Server Process

```text
Client → Request → Server
Client ← Response ← Server
```

### 🌐 Web Example

1. The browser acts as the **client**.
2. It requests a webpage.
3. The **web server** receives the request.
4. The server sends the webpage.
5. The browser displays it.

---

# 2.1.3 🤝 Peer-to-Peer (P2P) Networks

A **Peer-to-Peer (P2P) network** allows computers to act as both **clients and servers**.

### Typical Uses

- 📁 File sharing
- 🖨️ Printer sharing
- 📄 Resource sharing
- 💬 Direct communication

### ✅ Advantages

- Easy to set up
- Less complex
- Lower cost
- Dedicated servers may not be required
- Good for simple file/printer sharing

### ❌ Disadvantages

- No centralized administration
- Less secure
- Not scalable
- Performance may decrease when a device acts as both client and server

> 🧠 **Exam Tip:** P2P is best suited to small networks and simple resource sharing. Larger networks commonly use dedicated servers.

---

# 2.1.4 🔄 Peer-to-Peer Applications

A P2P application allows a device to act as **both client and server during the same communication**.

### Example: Instant Messaging

Both devices can simultaneously:

- 📤 Send messages
- 📥 Receive messages

### 🔀 Hybrid P2P

Some P2P applications use a hybrid model:

- Resource sharing is decentralized.
- A centralized index/directory keeps track of resource locations.
- Peers use the index to find resources on other peers.

---

# 2.1.5 🧑‍💻 Multiple Roles in a Network

One computer can run several server applications at the same time.

### Example

A single computer may act as:

- 📧 Email server
- 🌐 Web server
- 📁 File server

A host can also run multiple client applications simultaneously.

### Example

A user can:

- Check email
- Browse the web
- Use instant messaging
- Listen to Internet radio

---

# 2.2 🧩 Network Components

## 🎯 Learning Objective

- Explain the roles of **network infrastructure devices**.

## 🏗️ Network Infrastructure

**Network infrastructure** is the platform that supports network communication and provides a reliable path for data.

It has three major categories:

1. 💻 **End Devices**
2. 🔀 **Intermediate Devices**
3. 🔌 **Network Media**

---

## 💻 End Devices

**End devices**, also called **hosts**, are the source or destination of network messages.

### Examples

- 🖥️ Desktop computers
- 💻 Laptops
- 🖨️ Network printers
- ☎️ IP phones
- 📹 Teleconferencing equipment
- 📷 Security cameras
- 📱 Smartphones
- 📱 Tablets
- 💳 Wireless card readers
- 🔎 Barcode scanners
- 📁 File servers
- 🌐 Web servers

### Key Concept

```text
Source End Device
       ↓
    Network
       ↓
Destination End Device
```

An end device uses an address to identify the destination of a message.

---

## 🔀 Intermediate Devices

Intermediate devices connect end devices and help direct/control traffic.

| Device | Main Role |
|---|---|
| 🔀 **Switch** | Connects devices within a LAN |
| 🌐 **Router** | Connects different networks and forwards packets |
| 📡 **Wireless Access Point** | Provides wireless connectivity |
| 📡 **Wireless Router** | Combines routing, switching, and wireless functions |
| 🔥 **Firewall** | Controls traffic and helps protect a network |
| 🔀 **Multilayer Switch** | Performs switching and routing functions |

---

## 🔌 Network Media

Network media carries signals between devices.

### Main Categories

- 🧵 **LAN media** — commonly Ethernet/copper or fiber connections
- 🌍 **WAN media** — used for larger geographic connections
- 📡 **Wireless media** — uses signals through the air

### Common Media

- Copper cable ⚡
- Fiber-optic cable 💡
- Wireless radio signals 📶

> 💡 **Remember:** End devices are normally the source/destination; intermediate devices help data travel through the network.

---

# 🗺️ Network Diagram Symbols

### End Devices

- 🖥️ Desktop
- 💻 Laptop
- 🖨️ Printer
- ☎️ IP Phone
- 📱 Wireless Tablet
- 🎥 TelePresence Endpoint

### Intermediate Devices

- 📡 Wireless Router
- 🔀 LAN Switch
- 🌐 Router
- 🔀 Multilayer Switch
- 🔥 Firewall Appliance

### Media

- 📡 Wireless Media
- ━ LAN Media
- ⚡ WAN Media
- ☁️ Cloud — another network or the Internet

---

# 2.3 🌍 ISP Connectivity Options

## 🎯 Learning Objective

- Describe **ISP connectivity options**.

## 🌐 What is an ISP?

**ISP** means **Internet Service Provider**.

An ISP provides the connection between a home/local network and the Internet.

### ISP Examples

- 📺 Cable provider
- ☎️ Landline telephone provider
- 📱 Cellular provider
- 🌐 Independent Internet provider

ISPs connect to other ISPs, forming a global network of interconnected networks.

---

## 🌎 Internet Backbone

The Internet backbone is high-speed infrastructure connecting major service-provider networks.

It commonly uses:

- 💡 Fiber-optic cables
- 🔀 High-performance switches
- 🌐 Routers

Fiber-optic cables can run:

- Underground
- Between cities
- Across continents
- Under oceans

> ⭐ **Key Point:** The Internet is a collection of interconnected networks, not one single network.

---

## 🛠️ Services Provided by ISPs

Depending on the provider, services can include:

- 🌐 Web hosting
- 📁 FTP hosting
- 🎬 Application/media hosting
- 🏢 Equipment co-location
- 📞 Voice over IP (VoIP)
- 🧑‍💻 Technical support
- 🌍 POP Internet access
- 💾 Network storage
- 🔐 Backup/security services
- 📧 Email services

---

# 2.3.2 🔌 ISP Connections

A typical home network uses a **router and modem** to connect to an ISP.

### Direct Connection

```text
PC → Modem → ISP → Internet
```

A direct computer-to-modem connection is not recommended because the computer is directly exposed to the Internet.

### Common Home Setup

```text
PC / Laptop / Phone
        ↓
Wireless Router
        ↓
      Modem
        ↓
       ISP
        ↓
    Internet
```

A wireless integrated router may provide:

- 🔀 Built-in switch
- 📡 Wireless access point
- 🌐 Routing
- 🔢 IP addressing
- 🔐 Security

---

# 2.3.3 📺 Cable Internet

**Cable Internet** is commonly provided by cable television companies.

### Features

- Uses coaxial cable infrastructure
- High bandwidth
- Always-on connection
- Uses a cable modem
- Provides Ethernet connectivity to a host or LAN

```text
Home Network → Cable Modem → ISP → Internet
```

---

# 2.3.3 ☎️ DSL

**DSL = Digital Subscriber Line**

DSL provides a high-bandwidth, always-on connection using telephone lines.

### Features

- ☎️ Uses telephone lines
- 🔄 Always on
- 📡 Requires a DSL modem
- 📥 Faster download channel
- 📤 Upload channel
- ☎️ Voice calls can operate simultaneously

### DSL Performance

DSL speed depends mainly on:

- Quality of the telephone line
- Distance from the telephone company's central office

> ⚠️ **Remember:** The farther the user is from the central office, the slower the DSL connection generally becomes.

---

# 2.3.4 📱 Cellular Connectivity

Cellular Internet uses **mobile phone networks** to transmit data.

### Useful For

- 📱 Smartphones
- 🚗 Users on the move
- 🌍 Locations with cellular coverage
- 🔌 Areas without fixed wired connections

```text
Device → Cellular Network → ISP → Internet
```

---

# 2.3.4 🛰️ Satellite Connectivity

Satellite Internet uses satellites to provide Internet access.

```text
User Device
    ↓
Satellite Modem
    ↓
Dish
    ↓
Satellite
    ↓
ISP
    ↓
Internet
```

### Useful For

- 🏞️ Rural areas
- 🌾 Remote locations
- 🏔️ Places without wired infrastructure

### Limitation

- ⏱️ Satellite connections can have relatively high latency.

---

# 2.3.4 ☎️ Dial-Up Telephone

Dial-up uses traditional telephone lines to connect to an ISP.

### Characteristics

- ☎️ Telephone network
- 🐢 Very low speed compared with modern broadband
- 🔌 Requires a modem
- 📉 Legacy technology

---

# ⚡ ISP Connectivity Comparison

| Connection | Medium | Key Feature |
|---|---|---|
| 📺 **Cable** | Coaxial cable | High bandwidth, always on |
| ☎️ **DSL** | Telephone line | Broadband over phone infrastructure |
| 📱 **Cellular** | Radio waves | Mobile Internet |
| 🛰️ **Satellite** | Satellite link | Useful in remote areas |
| ☎️ **Dial-up** | Telephone line | Very slow, legacy |
| 💡 **Fiber** | Fiber-optic cable | Very high bandwidth |

---

# 🧠 Module 2 Quick Revision

## 👥 Clients & Servers

- **Host** → Network-connected device participating in communication.
- **Client** → Requests/uses services.
- **Server** → Provides services.
- **P2P** → Devices can act as both client and server.
- **Dedicated server** → Designed to provide services to clients.

## 🧩 Network Components

- **End devices** → Source or destination.
- **Intermediate devices** → Connect networks and direct traffic.
- **Network media** → Carries network signals.

## 🌍 ISP

- **ISP** → Provides Internet connectivity.
- **Internet backbone** → High-speed interconnected infrastructure.
- **Router** → Connects networks and provides routing/security functions.
- **Modem** → Provides the physical/service connection to the ISP technology.

---

# 📝 Knowledge Check — Answers

## Clients and Servers

1. A computer providing email or web pages is a **Server**. ✅
2. A smartphone using a browser to request a webpage is a **Client**. ✅
3. A network where computers act as both client and server is a **Peer-to-Peer network**. ✅

## Network Components

1. Likely Internet-connected mobile end devices: **Smartphone and Wireless Tablet**. ✅
2. For connecting a home network to a cable modem: **Wireless Router**. ✅
3. For mobile patient visits: **Tablet and Wireless Media**. ✅

## ISP Connectivity

1. Internet service using the same network as broadcast television: **Cable Internet**. ✅
2. High-bandwidth, always-on service over landline telephone wires: **DSL**. ✅
3. Internet service using mobile phone networks: **Cellular Data**. ✅

---

# 🎯 Exam-Focused Must Remember

> 🔑 **Client = Requests**  
> 🔑 **Server = Provides**  
> 🔑 **P2P = Client + Server**  
> 🔑 **End Device = Source/Destination**  
> 🔑 **Intermediate Device = Connects/Forwards**  
> 🔑 **Network Media = Carries Signals**  
> 🔑 **ISP = Connects users to the Internet**  
> 🔑 **Cable = Coaxial/Cable-TV infrastructure**  
> 🔑 **DSL = Telephone line**  
> 🔑 **Cellular = Mobile network**  
> 🔑 **Satellite = Satellite link**

---

# 🗺️ Module Concept Map

```text
NETWORK COMPONENTS, TYPES & CONNECTIONS
│
├── 👥 Clients & Servers
│   ├── Host
│   ├── Client
│   ├── Server
│   └── P2P
│
├── 🧩 Network Infrastructure
│   ├── End Devices
│   ├── Intermediate Devices
│   └── Network Media
│
└── 🌍 ISP Connectivity
    ├── Cable
    ├── DSL
    ├── Cellular
    ├── Satellite
    ├── Dial-up
    └── Fiber
```

---

# 🏁 Final Takeaways

After completing Module 2, you should be able to:

- ✅ Explain client and server roles.
- ✅ Explain peer-to-peer networking.
- ✅ Identify advantages and disadvantages of P2P.
- ✅ Explain how one device can perform multiple network roles.
- ✅ Identify end devices, intermediate devices, and network media.
- ✅ Explain the purpose of switches, routers, wireless APs, and firewalls.
- ✅ Explain what an ISP does.
- ✅ Describe the Internet backbone.
- ✅ Compare Cable, DSL, Cellular, Satellite, Dial-up, and Fiber connectivity.
- ✅ Identify the most appropriate connectivity option for different situations.

> 🚀 **Study Tip:** Focus especially on **Client vs Server**, **P2P vs Client-Server**, **End vs Intermediate Devices**, and **Cable vs DSL vs Cellular vs Satellite**. These are foundational networking concepts.
