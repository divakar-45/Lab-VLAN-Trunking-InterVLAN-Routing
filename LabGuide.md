# Lab Guide

## Goal

Create three isolated VLANs and enable communication between them using Router-on-a-Stick.

---

## Step 1

Create VLANs

- VLAN 10 (HR)
- VLAN 20 (Sales)
- VLAN 30 (IT)

---

## Step 2

Assign Access Ports

Fa0/1 → VLAN10

Fa0/2 → VLAN20

Fa0/3 → VLAN30

---

## Step 3

Configure Trunk

Gi0/1

Mode: Trunk

Protocol: IEEE 802.1Q

---

## Step 4

Configure Router

Create Subinterfaces

G0/0.10

G0/0.20

G0/0.30

Assign Gateway IPs

---

## Step 5

Configure PCs

Assign Static IP Addresses

Configure Default Gateway

---

## Step 6

Verification Commands

show vlan brief

show interfaces trunk

show ip interface brief

ping
