# KVM-Passthrough-TP-Link-Archer-T8E-AC1300-PCI-Express-Network-Card
KVM Passthrough of TP-Link Archer T8E AC1300 Dual-Band Wireless PCI Express Card

System specifications:
1. Intel core i7 7700K
2. Nvidia GTX 1070
3. TP-Link Archer T8E AC1300 Network card
4. Ubuntu 22.04

Tutorial:
1. Use ```lspci``` to find device
2. Bind PCI device in KVM
3. Use virtual network to install drivers in the operating system
4. Remove virtual network
5. The network card should work and be isolated to the virtual machine

Notes:
- I provided this tutorial to provide information that it is possible to passthrough network cards in kvm. I believe this will enhance security of the virtual machine. You can connect the VM to a VLAN that is isolated from the regular network.
