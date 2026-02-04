# VLAN Basics – Concepts, Logic, and Troubleshooting

## Why VLANs Exist
A Layer 2 switch operates in a single broadcast domain by default.
VLANs allow logical segmentation of the network independent of physical location.

## Key Properties
- Each VLAN is a separate broadcast domain
- VLANs improve security and reduce unnecessary broadcast traffic
- Devices in different VLANs cannot communicate without Layer 3 routing

## Common Misconception
VLANs do not exist to pass traffic — they exist to **isolate** traffic.

Inter-VLAN communication requires a Layer 3 device such as:
- Router-on-a-stick
- Layer 3 switch using SVIs

## Verification Commands
- `show vlan brief`
- `show interfaces trunk`
- `show ip interface brief`

*(Lab exercises and troubleshooting scenarios will be added.)*

