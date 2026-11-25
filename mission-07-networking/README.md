# Mission 7 — Computer Networking

## Objective

Understand how computers communicate over networks, learn basic networking terms, and use safe Terminal commands to inspect connectivity and DNS.

## 1. Network Types

- **LAN (Local Area Network):** connects devices in a limited area, such as a home, lab or office.
- **MAN (Metropolitan Area Network):** connects networks across a city or large campus area.
- **WAN (Wide Area Network):** connects networks over large geographical distances. The Internet is the best-known example.

## 2. Important Networking Terms

- **Router:** forwards data between networks.
- **IP address:** identifies a device or network interface for communication.
- **DNS (Domain Name System):** translates domain names into IP addresses.
- **Protocol:** agreed rules for communication, such as TCP, IP, HTTP and HTTPS.
- **Packet:** a unit of data sent across a network.
- **Packet switching:** sends data in packets that can travel across network paths and be reassembled at the destination.

## 3. Safe Connectivity and DNS Checks

These commands make ordinary read-only checks:

```bash
ping -c 4 example.com
nslookup example.com
```

- `ping` sends a small number of test packets and reports replies or timeouts and response times.
- `nslookup` asks DNS for information about a domain, including returned address records.

The exact addresses and response times can change depending on DNS, network conditions and location. A timeout does not always mean the whole Internet connection is unavailable; some networks block ping replies.

## 4. Observations to Record

When running the commands on the computer, note the actual results rather than copying an example address: