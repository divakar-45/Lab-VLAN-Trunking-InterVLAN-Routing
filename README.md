# Cisco Packet Tracer Lab  – VLANs, Trunking & Inter-VLAN Routing

## Project Overview

This project demonstrates how to configure multiple VLANs on a Layer 2 switch, establish a trunk link using IEEE 802.1Q, and enable communication between VLANs using Router-on-a-Stick.

The network is built and tested in Cisco Packet Tracer using static IP addressing.

---

## Objectives

- Create VLANs
- Assign switch ports to VLANs
- Configure trunk links
- Configure Router-on-a-Stick
- Enable Inter-VLAN Routing
- Verify end-to-end connectivity

---

## Network Topology

```
             Router (2911)
                  |
              G0/0 (Trunk)
                  |
             Switch (2960)
          /       |        \
      VLAN10   VLAN20    VLAN30
        PC0      PC1       PC2
```

---

## VLAN Configuration

| VLAN | Department | Network |
|------|------------|----------------|
|10|HR|192.168.10.0/24|
|20|Sales|192.168.20.0/24|
|30|IT|192.168.30.0/24|

---

## IP Addressing

| Device | IP Address | Gateway |
|---------|------------|------------|
|PC0|192.168.10.10|192.168.10.1|
|PC1|192.168.20.10|192.168.20.1|
|PC2|192.168.30.10|192.168.30.1|

---

## Technologies Used

- Cisco Packet Tracer
- Cisco 2911 Router
- Cisco 2960 Switch
- VLAN
- IEEE 802.1Q
- Router-on-a-Stick
- Static IP Addressing

---

## Verification

The following were successfully verified:

- VLAN Creation
- VLAN Assignment
- Trunk Configuration
- Router Subinterfaces
- Inter-VLAN Routing
- End-to-End Connectivity using ICMP

---

## Skills Demonstrated

- VLAN Configuration
- Access Port Configuration
- Trunk Configuration
- Router-on-a-Stick
- Static Routing Concepts
- Network Segmentation
- Layer 2 Switching
- Layer 3 Routing
- Network Troubleshooting

---

## Project Files

- Packet Tracer (.pkt)
- Switch Configuration
- Router Configuration
- Screenshots
- Documentation

---

## Author

**Divakar**

GitHub: https://github.com/divakar-45
