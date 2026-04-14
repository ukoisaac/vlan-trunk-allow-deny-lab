<img width="1365" height="624" alt="vlan-trunk-allow-deny-lab" src="https://github.com/user-attachments/assets/22956f23-93c1-4824-865a-01b68dcaf1e7" />

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
<img width="1360" height="756" alt="VLAN  TRUNK ALLOW-DENY " src="https://github.com/user-attachments/assets/46fddc6d-d315-4f31-a300-2d32064fca9b" />

## Result
- VLAN 20 & 30 communicate across switches
- VLAN 10 is blocked

## Skills Demonstrated
- VLAN creation
- Trunk configuration
- Traffic segmentation
