# 🌐 Module 4 --- Build a Home Network

> **Cisco Networking Academy --- Study Notes**
>
> **Module Objective:** Configure an integrated wireless router and
> wireless client to connect securely to the internet.

------------------------------------------------------------------------

## 📚 Table of Contents

1.  🏠 Home Network Basics
2.  📡 Network Technologies in the Home
3.  📶 Wireless Standards
4.  🔐 Set Up a Home Router
5.  📝 Knowledge Check --- Important Answers
6.  🧠 Memory Tricks
7.  🎯 Exam-Focused Revision
8.  🗺️ Module Concept Map
9.  🔖 Important Definitions & Keywords

------------------------------------------------------------------------

# 1. 🏠 Home Network Basics

## 1.1 What is a Home Network?

A home network is a small **LAN (Local Area Network)** where devices
connect to an integrated router and to each other in order to exchange
information.

Most home networks consist of at least two separate networks:

-   🌐 **Public network** --- comes from the Internet Service Provider
    (**ISP**).
-   🏠 **Home LAN** --- connects devices inside the home.

The **router** connects the home network to the internet.

### Common Devices on a Home Network

-   💻 Desktop computers
-   🎮 Gaming systems
-   📺 Smart TVs
-   🖨️ Printers
-   📄 Scanners
-   📷 Security cameras
-   ☎️ Telephones
-   🌡️ Climate-control devices

------------------------------------------------------------------------

## 1.2 Wireless LAN Advantages

Wireless technology is relatively easy and inexpensive to install.

### Advantages of Wireless LAN

-   🚶 **Mobility** --- devices can move while remaining connected.
-   📈 **Scalability** --- devices can be added more easily.
-   🔄 **Flexibility** --- useful where cables are difficult to install.
-   💰 **Cost savings**
-   ⏱️ **Reduced installation time**
-   🛡️ **Reliability in harsh environments**

------------------------------------------------------------------------

## 1.3 Home Router Ports

Small business and home routers typically have two primary types of
ports.

  -----------------------------------------------------------------------
  Port                                Purpose
  ----------------------------------- -----------------------------------
  🔌 **Ethernet Port**                Connects wired devices to the
                                      internal switch/LAN

  🌐 **Internet Port**                Connects the router to another
                                      network, commonly the ISP/modem
  -----------------------------------------------------------------------

Many home routers also contain:

-   📡 Radio antennas
-   📶 Built-in wireless access point
-   🔌 Multiple Ethernet/LAN ports

### ⭐ Important

The **Internet port** is on a different network from the Ethernet/LAN
ports in the default configuration.

### 🧠 Memory Trick

> **Ethernet = Inside the home LAN**\
> **Internet/WAN = Outside → ISP/another network**

------------------------------------------------------------------------

# 2. 📡 Network Technologies in the Home

## 2.1 Wireless Technologies

Wireless technologies use **electromagnetic waves** to carry information
between devices.

The electromagnetic spectrum includes:

-   Radio
-   Television broadcast bands
-   Visible light
-   X-rays
-   Gamma rays
-   Other frequency ranges

Some parts of the spectrum are regulated or licensed, while certain
areas can be used without a permit.

------------------------------------------------------------------------

## 2.2 Common Home Wireless Frequencies

The wireless technologies most frequently used in home networks operate
in:

-   📶 **2.4 GHz**
-   📶 **5 GHz**

### Bluetooth

Bluetooth uses the **2.4 GHz** band.

It is designed for:

-   Short-range communication
-   Low-power communication
-   Low-speed communication
-   Connecting multiple devices

### Bluetooth Examples

-   🖱️ Wireless mouse
-   ⌨️ Wireless keyboard
-   🖨️ Wireless printer
-   🔊 Speakers
-   🎧 Headphones

Bluetooth is particularly useful for peripherals and audio devices.

------------------------------------------------------------------------

## 2.3 Wi-Fi / IEEE 802.11

Modern wireless LAN technologies conform to various **IEEE 802.11**
standards.

Compared with Bluetooth:

-   802.11 devices transmit at a higher power level.
-   They provide greater range.
-   They provide improved throughput.

### ⭐ Remember

> **Bluetooth → Short range + Low power**\
> **802.11/Wi-Fi → Greater range + Higher throughput**

------------------------------------------------------------------------

# 3. 🔌 Wired Network Technologies

## 3.1 Ethernet

The most commonly implemented wired protocol is **Ethernet**.

Ethernet allows network devices to communicate over a wired LAN
connection.

Directly connected devices commonly use an:

> **Ethernet patch cable**

Usually this is an **Unshielded Twisted Pair (UTP)** cable.

------------------------------------------------------------------------

## 3.2 Category 5e Cable

**Category 5e (Cat5e)** is commonly used for LAN wiring.

Ethernet patch cables can use **RJ-45 connectors**.

Recently constructed homes may have Ethernet jacks already installed in
the walls.

------------------------------------------------------------------------

## 3.3 Coaxial Cable

A coaxial cable contains:

1.  **Inner wire/conductor**
2.  **Tubular insulating layer**
3.  **Tubular conducting shield**

### 🧠 Memory Trick

> **Coaxial = Conductor → Insulation → Shield**

------------------------------------------------------------------------

## 3.4 Fiber-Optic Cable

Fiber-optic cable is another wired network technology listed in the
module's home-network technologies.

------------------------------------------------------------------------

## 3.5 Powerline Technology

For homes without UTP wiring, technologies such as **powerline** can
distribute wired connectivity throughout the premises.

------------------------------------------------------------------------

# 4. 📶 Wireless Standards

## 4.1 What is IEEE 802.11?

The **IEEE 802.11 standard** governs the WLAN environment.

Wireless LAN standards use:

-   **2.4 GHz**
-   **5 GHz**

Collectively, these wireless LAN technologies are referred to as:

> **Wi-Fi**

------------------------------------------------------------------------

## 4.2 IEEE vs Wi-Fi Alliance

Two organizations/concepts are especially important.

  -----------------------------------------------------------------------
  Organization                        Main Role
  ----------------------------------- -----------------------------------
  🏛️ **IEEE**                         Creates wireless technical
                                      standards

  📶 **Wi-Fi Alliance**               Tests wireless LAN devices from
                                      different manufacturers
  -----------------------------------------------------------------------

### ⭐ Exam Point

> **IEEE = Standards**\
> **Wi-Fi Alliance = Testing/Interoperability**

The Wi-Fi logo on a device indicates that the equipment meets relevant
standards and should operate with compatible devices.

------------------------------------------------------------------------

# 5. ⚙️ Wireless Settings

Wireless routers using 802.11 standards have several settings that need
to be configured.

The important settings are:

1.  **Network Mode**
2.  **Network Name (SSID)**
3.  **Standard Channel**
4.  **SSID Broadcast**

------------------------------------------------------------------------

## 5.1 Network Mode

Network mode determines which wireless technology the router supports.

Examples include:

-   802.11b
-   802.11g
-   802.11n
-   Mixed Mode

If the access point accepts only one 802.11 standard, devices that do
not use that standard cannot connect.

### Mixed Mode

A **mixed mode** wireless network can include devices using different
existing Wi-Fi standards.

### 🧠 Memory Trick

> **Mixed Mode = Mixed Wi-Fi standards**

------------------------------------------------------------------------

## 5.2 Network Name --- SSID

**SSID = Service Set Identifier**

The SSID identifies a specific wireless network.

### Important SSID Facts

-   It is the **name of the wireless network**.
-   It is **case-sensitive**.
-   It can contain up to **32 characters**.
-   Wireless stations (**STAs**) use it to identify their WLAN.
-   Devices joining the same WLAN use the same SSID.

### 🧠 Memory Trick

> **SSID = Wi-Fi Network Name**

------------------------------------------------------------------------

## 5.3 Standard Channel

The **standard channel** specifies the channel over which wireless
communication occurs.

By default, it can be set to:

> **Auto**

This allows the access point (**AP**) to determine an appropriate
channel.

------------------------------------------------------------------------

## 5.4 SSID Broadcast

SSID Broadcast determines whether the SSID is broadcast to devices
within range.

### If SSID Broadcast is Enabled

Devices can automatically discover the wireless network name.

### If SSID Broadcast is Disabled

Wireless clients must manually enter the SSID.

### ⚠️ Security Warning

Disabling SSID broadcast is **not sufficient security** by itself.

Wireless networks should use the **strongest available encryption** to
restrict unauthorized access.

------------------------------------------------------------------------

# 6. 🔐 Set Up a Home Router

## 6.1 First-Time Setup

Many home wireless routers provide an automatic setup utility for
configuring basic settings.

A wired setup commonly follows these steps:

1.  🔌 Connect an Ethernet patch cable to the computer's network port.
2.  🔌 Connect the other end to a **LAN/Ethernet port** on the router.
3.  ❌ Do **not** connect the computer to the port labeled **Internet**.
4.  💡 Confirm that the NIC link lights show a working connection.
5.  🌐 Obtain an IP address.

------------------------------------------------------------------------

## 6.2 LAN Port vs Internet Port

  -----------------------------------------------------------------------
  Connection                          Purpose
  ----------------------------------- -----------------------------------
  💻 Computer → **LAN/Ethernet Port** Connects the computer to the home
                                      network

  🌐 Router → **Internet Port**       Connects the router to another
                                      network/ISP
  -----------------------------------------------------------------------

### ⭐ Exam Trap

> When configuring a computer through a wired connection, connect it to
> a **LAN/Ethernet port**, **not** the Internet port.

------------------------------------------------------------------------

## 6.3 DHCP and IP Addressing

After connecting to the router, the computer needs an IP address.

Most home routers have a local **DHCP server** configured automatically.

### DHCP

**DHCP** automatically provides IP addressing information to network
clients.

If a computer does not receive an IP address, it may need configuration
for:

-   IP address
-   Subnet mask
-   Default gateway
-   DNS information

### 🧠 Memory Trick

> **DHCP = Automatically gives IP information**

------------------------------------------------------------------------

## 6.4 Modem Connections

The Internet port commonly connects the router to a modem.

### Cable Modem

Uses a **coaxial terminal** to accept a BNC-type connector.

### DSL

Uses a telephone-type cable, commonly an **RJ-11 connector**.

------------------------------------------------------------------------

# 7. 🧩 Router Design Considerations

Before configuring a router, consider how the network will be used.

### Question 1 --- What should my network be called?

Choose an appropriate SSID.

Avoid including the device's model or brand name as part of the SSID
because internet searches can expose security weaknesses.

### Question 2 --- What types of devices will attach to my network?

Determine which devices need access to the network.

Examples:

-   Computers
-   Smartphones
-   Smart TVs
-   Gaming systems
-   Printers
-   Security cameras

### Question 3 --- How do I add new devices?

Consider how new devices will be connected and allowed to access the
network.

------------------------------------------------------------------------

# 8. 📝 Knowledge Check --- Important Answers

## Home Network Basics

  -----------------------------------------------------------------------
  Question                            Correct Answer
  ----------------------------------- -----------------------------------
  A home router typically only        ❌ **False**
  provides wired access. True or      
  False?                              

  Which port connects a wired device  ✅ **Ethernet Port**
  to the internal switch?             
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Network Technologies in the Home

  -----------------------------------------------------------------------
  Question                            Correct Answer
  ----------------------------------- -----------------------------------
  Certain areas of the                ✅ **True**
  electromagnetic spectrum can be     
  used without a permit.              

  Wi-Fi, Bluetooth, and cordless      ❌ **False**
  phones all use the same frequency   
  ranges.                             

  Which technology has an inner wire, ✅ **Coaxial Cable**
  insulation, and conducting shield?  
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Wireless Standards

  -----------------------------------------------------------------------
  Question                            Correct Answer
  ----------------------------------- -----------------------------------
  Which organization tests wireless   ✅ **Wi-Fi Alliance**
  LAN devices?                        

  What identifies a specific wireless ✅ **SSID**
  network?                            

  If devices use different 802.11     ❌ **False**
  standards, set the network only to  
  the highest standard.               
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 9. 🧠 Memory Tricks

### 🔌 Ports

> **LAN/Ethernet = Local devices**\
> **Internet/WAN = Outside network**

### 📶 Wireless

> **Bluetooth = Short + Low Power**\
> **Wi-Fi = Greater Range + Higher Throughput**

### 🏷️ SSID

> **SSID = Wi-Fi Network Name**

### 🏛️ Organizations

> **IEEE → Creates standards**\
> **Wi-Fi Alliance → Tests devices**

### 🌐 DHCP

> **DHCP → Automatically provides IP information**

### 📡 Frequencies

> **Home Wi-Fi → 2.4 GHz + 5 GHz**\
> **Bluetooth → 2.4 GHz**

### ⚙️ Mixed Mode

> **Mixed Mode → Different Wi-Fi standards can coexist**

------------------------------------------------------------------------

# 10. 🎯 Exam-Focused Revision

## ⭐ Must-Know Concepts

### 1. Home Network

A home network is a small **LAN** connecting devices to an integrated
router and to each other.

### 2. Ethernet Port

Used to connect wired devices to the internal switch/LAN.

### 3. Internet Port

Connects the router to another network, commonly the ISP/modem.

### 4. Bluetooth

Low-power, short-range wireless technology commonly used for peripherals
and audio.

### 5. IEEE 802.11

Standard governing WLAN technologies.

### 6. Wi-Fi Alliance

Tests wireless LAN devices from different manufacturers.

### 7. SSID

Identifies a specific wireless network.

### 8. SSID Broadcast

Allows devices to automatically discover the network name when enabled.

### 9. DHCP

Automatically provides IP addressing information to clients.

### 10. Mixed Mode

Allows devices using different 802.11 standards to connect.

------------------------------------------------------------------------

# 11. 📊 Quick Comparison Table

  Feature       Bluetooth           Wi-Fi / 802.11           Ethernet
  ------------- ------------------- ------------------------ --------------------------
  Type          Wireless            Wireless                 Wired
  Typical use   Peripherals/audio   LAN & internet access    Wired LAN
  Power         Low                 Higher than Bluetooth    Wired
  Range         Short               Greater than Bluetooth   Depends on cable/network
  Frequency     2.4 GHz             2.4 GHz / 5 GHz          Not wireless

------------------------------------------------------------------------

# 12. 🗺️ Module Concept Map

``` text
                    🏠 BUILD A HOME NETWORK
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
   🏠 Home Network      📡 Network Tech.    📶 Wireless Standards
          │                   │                   │
      ┌───┴───┐          ┌────┴────┐       ┌─────┴─────┐
      │       │          │         │       │           │
     LAN    Router     Wireless   Wired   802.11      SSID
      │       │          │         │       │           │
   Devices  Ports    2.4/5 GHz  Ethernet  Wi-Fi    Broadcast
              │          │         │
        ┌─────┴─────┐  Bluetooth  ├── Cat5e
        │           │              ├── Coaxial
      LAN        Internet          └── Fiber
      Port          Port
          │
          ▼
      🔐 Router Setup
          │
      ┌───┴────┐
      │        │
     DHCP   Security
      │        │
   IP Info  Encryption
```

------------------------------------------------------------------------

# 13. 🔖 Important Definitions & Keywords

  -----------------------------------------------------------------------
  Term                                Definition
  ----------------------------------- -----------------------------------
  **LAN**                             Local Area Network

  **ISP**                             Internet Service Provider

  **WLAN**                            Wireless Local Area Network

  **Wi-Fi**                           Wireless LAN technologies based on
                                      IEEE 802.11 standards

  **IEEE 802.11**                     Standard governing the WLAN
                                      environment

  **SSID**                            Service Set Identifier; identifies
                                      a wireless network

  **AP**                              Access Point

  **STA**                             Wireless Station

  **DHCP**                            Automatically provides IP
                                      addressing information

  **WAN / Internet Port**             Port used to connect the router to
                                      another network

  **Ethernet Port**                   Port used to connect wired devices
                                      to the internal LAN

  **UTP**                             Unshielded Twisted Pair

  **Cat5e**                           Category 5e Ethernet cable

  **NFC**                             Wireless communication technology
                                      for very close proximity

  **Bluetooth**                       Low-power, short-range wireless
                                      technology

  **Mixed Mode**                      Wireless mode supporting different
                                      802.11 standards
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🏁 Final One-Minute Revision

> 🏠 **Home Network = Small LAN**
>
> 🔌 **Ethernet Port = Connect wired LAN devices**
>
> 🌐 **Internet/WAN Port = Connect to another network/ISP**
>
> 📡 **Wi-Fi = IEEE 802.11**
>
> 🏛️ **IEEE = Creates standards**
>
> 📶 **Wi-Fi Alliance = Tests wireless devices**
>
> 🏷️ **SSID = Wireless network name**
>
> 📡 **Wi-Fi = 2.4 GHz + 5 GHz**
>
> 🎧 **Bluetooth = 2.4 GHz + Short range + Low power**
>
> 🌐 **DHCP = Automatic IP addressing**
>
> ⚙️ **Mixed Mode = Different Wi-Fi standards**
>
> 🔐 **SSID Broadcast OFF does not equal complete security**
>
> 🛡️ **Strong encryption = Essential wireless protection**

------------------------------------------------------------------------

## 🎯 Packet Tracer Activity

### Configure a Wireless Router and Client

The activity objectives are:

1.  **Connect the Devices**
2.  **Configure the Wireless Router**
3.  **Configure IP Addressing and Test Connectivity**

------------------------------------------------------------------------

# ✅ Module 4 Completed

**Core focus:** 🏠 Home networking → 📡 Wireless/Wired technologies → 📶
Wi-Fi standards → ⚙️ Router configuration → 🔐 Secure connectivity
