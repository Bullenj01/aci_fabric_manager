# Examples and Use Cases

This collection provides a framework for deploying common Cisco ACI access topologies. It simplifies the creation of switch and interface profiles for both standalone switches and VPC pairs.

## Conceptual Framework
The framework assumes a standardized naming convention and sequential relationship for VPC pairs (typically odd-even numbering).

![ACI Fabric Access Policy Concept](../images/fabric_policies.JPG)

## Standard Deployment Example
The example below demonstrates a deployment for a leaf switch range of 101-106, including FEX (Fabric Extender) configurations on switches 101 and 103.

![Switch and Interface Profiles Example](../images/switch_profiles.JPG)

## Operational Usage
Once the base fabric access policies are deployed, operational tasks like adding a new server are streamlined. You can simply go to the corresponding Interface Profile and create a new Interface Selector.

![Interface Selector Configuration](../images/intSel.JPG)

## Usage with Playbooks
Refer to the main [README.md](../README.md) for detailed variable definitions and example playbook structure.