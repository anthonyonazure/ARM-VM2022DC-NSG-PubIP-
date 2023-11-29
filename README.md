# ARM-VM2022DC-NSG-PubIP-
This template includes:

A new resource group creation.
A virtual network and a subnet.
A network security group with an inbound rule to allow RDP (port 3389).
A public IP address for the VM.
A network interface connected to the subnet and the network security group.
A virtual machine with a system-assigned managed identity.
The VM is configured with a standard SSD OS disk of 127 GB.
The OS choice is between Windows Server 2022 Datacenter and Windows Server 2022 Datacenter Hotpatch, based on the parameter selection.
