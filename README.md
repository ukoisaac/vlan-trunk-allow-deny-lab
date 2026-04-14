# VLAN Trunk Allow/Deny Lab

## Objective
To demonstrate how VLANs can be selectively allowed or denied across trunk links.

## Topology
Two switches connected via trunk link.

## VLANs
- VLAN 10 (IT)
- VLAN 20 (HR)
- VLAN 30 (ICT)

## Configuration
Trunk allows only VLAN 20 and 30.

## Result
- VLAN 20 & 30 communicate across switches
- VLAN 10 is blocked

## Skills Demonstrated
- VLAN creation
- Trunk configuration
- Traffic segmentation
